FROM node:16

# 작업 디렉토리 설정
WORKDIR /usr/src/app

# 패키지 파일 복사
COPY package*.json ./

# 패키지 설치
RUN npm install

# 애플리케이션 코드 복사
COPY . .

# 개발 서버 시작
CMD ["npm", "start"]
