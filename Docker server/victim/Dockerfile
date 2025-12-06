FROM node:20-alpine

WORKDIR /app

# package.json 복사
COPY package.json ./

# 의존성 설치
RUN npm install

# 앱 코드 복사
COPY app.js ./

EXPOSE 5000

CMD ["npm", "start"]
