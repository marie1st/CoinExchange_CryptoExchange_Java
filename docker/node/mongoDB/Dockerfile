FROM node:10.12.0-alpine

RUN git clone --depth 1 https://github.com/hagopj13/node-express-boilerplate.git \
&& cd node-express-boilerplate \
&& npx rimraf ./.git \
&& npm install \
&& cp .env.example .env