FROM ruby:3.1.3

WORKDIR /app

COPY . .

RUN bundle install

CMD ["bundle", "exec", "rails", "s", "-b", "0.0.0.0"]

EXPOSE 3000
