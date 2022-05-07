FROM node:18.1.0 
WORKDIR /usr/src/coffebase/frontend
COPY ./server/ .
RUN npm install
EXPOSE 3000 
CMD ["npm", "run", "dev", "--host"]
