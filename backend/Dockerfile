FROM node:18

# กำหนด working directory
WORKDIR /app

# copy package.json
COPY package*.json ./

# ติดตั้ง dependencies
RUN npm install

# copy source code ทั้งหมด
COPY . .

# expose port ของ backend (เช่น 4000)
EXPOSE 4000

CMD ["npm", "run", "start"]
