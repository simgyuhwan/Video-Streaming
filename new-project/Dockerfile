FROM node:12.18.1-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install --only=production
RUN export PORT=3000
COPY ./src ./src
COPY ./SampleVideo_1280x720_1mb.mp4 ./
CMD npm start