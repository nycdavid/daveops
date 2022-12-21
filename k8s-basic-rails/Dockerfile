FROM ruby:3.1.3

WORKDIR /app

COPY . .

RUN bundle install

CMD ["bundle", "exec", "rails", "s"]

EXPOSE 3000
