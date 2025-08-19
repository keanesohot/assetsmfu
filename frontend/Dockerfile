FROM node:18

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

# build next.js
RUN npm run build

# expose port 3000 สำหรับ Next.js
EXPOSE 3000

CMD ["npm", "run", "start"]
