FROM node:12

WORKDIR /app
RUN git clone https://github.com/OpenClassrooms-Student-Center/ghost-cms.git 
WORKDIR /app/ghost-cms
RUN npm install

EXPOSE 2368
VOLUME /app/logs

CMD npm run start
