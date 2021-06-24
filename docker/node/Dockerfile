FROM node:lts-slim

# コンテナ上の作業ディレクトリ作成
WORKDIR /var/www/

RUN npm init -y

RUN apt update
RUN npm i -D eslint prettier
RUN npm i -D eslint-config-prettier