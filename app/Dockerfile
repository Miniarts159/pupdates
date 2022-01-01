# Dev container 

FROM mhart/alpine-node:16.4
RUN apk update
RUN apk add git

WORKDIR /app
COPY package.json package-lock.json ./
RUN npm ci

COPY . .

EXPOSE 3000

CMD ["npm", "run", "dev", "--", "--host"]