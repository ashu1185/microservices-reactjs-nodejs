FROM node:8
WORKDIR /app
COPY . .        
RUN npm install
VOLUME ["/app/node_modules"]  # Mount a volume for npm cache
COPY . .
EXPOSE 8080
CMD ["npm", "start"]