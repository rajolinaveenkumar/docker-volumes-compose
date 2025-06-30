FROM node:20-slim
RUN mkdir /app 
WORKDIR /app
COPY scripts/* .
RUN npm install
ENV DB_HOST="mysql-exp"
CMD ["node", "index.js"]