FROM node:25.3.0-alpine3.23


WORKDIR /app
COPY package.json /app/package.json
# COPY package-lock.json /code/package-lock.json

# RUN npm ci
COPY . /app

# ENV CI=true
ENV PORT=3000

CMD [ "npm", "start" ]
