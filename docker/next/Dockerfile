FROM node:16.14

# コマンド実行
RUN apt-get update && \
    apt-get install git && \
    apt install -y default-jre && \
    yarn global add create-react-app

WORKDIR /workspace
COPY src/universe-frontend /workspace
RUN npm init -y
RUN npm install
# RUN npx create-react-app ./
# RUN yarn install
