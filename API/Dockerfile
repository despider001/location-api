FROM node:16
WORKDIR /usr
COPY . .
RUN npm install
RUN npm run build
EXPOSE 3000
CMD ["node","./dist/app.js"]