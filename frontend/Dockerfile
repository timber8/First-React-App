FROM node:10.9.0-alpine
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
RUN npm install -g nodemon --quiet
COPY ./ /usr/src/app/
RUN npm install
EXPOSE 3000
CMD ["npm", "start"]