FROM golang:1.5.2
MAINTAINER Francois Hill <francoishill11@gmail.com>
LABEL Description="A golang container with nodejs + gulp + jspm"

RUN curl -sL https://deb.nodesource.com/setup_5.x | bash - \
   && apt-get install --yes nodejs \
   && npm install -g gulp \
   && npm install -g jspm
