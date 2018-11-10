# https://jp.vuejs.org/v2/cookbook/dockerize-vuejs-app.html

FROM node:9.11.1-alpine

# カレントワーキングディレクトリとして 'app' フォルダを指定する
WORKDIR /home/buchitaro1022/Project/incomelimit

# プロジェクトの依存ライブラリをインストールする
RUN npm install

# カレントワーキングディレクトリ(つまり 'app' フォルダ)にプロジェクトのファイルやフォルダをコピーする
COPY . .

# 本番向けに圧縮しながらアプリケーションをビルドする
RUN npm run build
