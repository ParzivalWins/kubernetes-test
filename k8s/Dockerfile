FROM ruby:2.3.1 
MAINTAINER Ben Morris

RUN gem install sinatra
RUN gem install redis
COPY ./hello-world.rb /app/hello-world.rb
WORKDIR /app/

EXPOSE 4567
CMD ["ruby", "./hello-world.rb"]
