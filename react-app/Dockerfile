FROM node:alpine

# where want to save all files in docker container
WORKDIR /usr/app

COPY package.json .

RUN npm install

# copy everythings from working directory where docker file lies 

COPY . .

CMD ["npm", "run", "start"]