FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=root

ENV MONGODB_PASSWORD=secret

CMD ["npm", "start"]

#Network
# docker create network goals

#Build Image
# docker build -t goals-frontend .

#Mongo DB
#Build
#docker build -t mongo .


#Run
#docker run --name mongodb --network goals -v data:/data/db --rm -d -e MONGO_INITDB_ROOT_USERNAME=mykeadam -e MONGO_INITDB_ROOT_PASSWORD=secret mongo

#Build Image
# docker build -t goals-backend .

#Run Container
#docker run --name goals-backend --network goals -v "/Users/xxxx/Documents/Visual Studio Code/Docker & Kubernetes /7. Multi-Container/backend":/app -v logs:/app/logs -v /app/node_modules -e MONGODB_USERNAME=mykeadam -d --rm -p 80:80 goals-node