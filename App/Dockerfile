FROM node:slim
WORKDIR /app
COPY package.json parkings.json ./ 
RUN  npm install
COPY . ./
EXPOSE 3080
CMD ["node" , "index.js"]