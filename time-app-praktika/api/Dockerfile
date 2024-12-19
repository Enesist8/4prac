FROM node:18-alpine

WORKDIR /time-app

# API
COPY package*.json .  
RUN npm install
COPY . .

# Определяем порты для  API  и  Frontend
EXPOSE 5000 
# Запускаем API и Frontend
CMD ["npm", "run", "dev"]