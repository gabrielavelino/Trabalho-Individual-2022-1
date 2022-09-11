FROM node:16

WORKDIR /app
ENV PATH=library_front/node_modules/.bin:$PATH
COPY package.json ./
COPY package-lock.json ./
COPY ./ ./

RUN npm install

EXPOSE 3000
CMD ["npm", "start"]