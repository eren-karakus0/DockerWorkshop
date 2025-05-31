# Multi-stage build
FROM node:18-alpine AS base
WORKDIR /app
COPY package.json yarn.lock ./
RUN yarn install --production && yarn cache clean

FROM node:18-alpine AS dev
WORKDIR /app
COPY package.json yarn.lock ./
RUN yarn install
COPY . .
CMD ["yarn", "run", "dev"]

FROM base AS production
COPY . .
USER node
CMD ["node", "src/index.js"]