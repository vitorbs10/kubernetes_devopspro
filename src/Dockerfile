FROM node:18-alpine

WORKDIR /app

RUN npm config set cache /app/.npm
RUN npm cache clean --force  # <--- Limpa o cache do npm

COPY package.json package-lock.json ./

RUN npm install --legacy-peer-deps --no-audit --prefer-offline

COPY . .

EXPOSE 8080

CMD ["node", "server.js"]
