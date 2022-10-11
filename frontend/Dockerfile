FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]

#Network
# docker create network goals

#Build Image
# docker build -t goals-frontend .

#docker run --name goals-frontend -v "/Users/xxxx/Documents/Visual Studio Code/Docker & Kubernetes /7. Multi-Container/frontend/src":/app/src --rm -d -p 3000:3000 -it goals-react