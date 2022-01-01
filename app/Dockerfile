# Dev container 

FROM mhart/alpine-node:16.4
RUN apk update
RUN apk add git

RUN git clone https://github.com/revslaughter/pupdates.git

WORKDIR /pupdates/app
RUN npm ci

EXPOSE 3000
