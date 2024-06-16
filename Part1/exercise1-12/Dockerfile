FROM node:16

EXPOSE 5000

WORKDIR /usr/src/app

#Install dependencies
COPY /material-applications/example-frontend/package.json ./
COPY /material-applications/example-frontend/package-lock.json ./
RUN npm install

COPY /material-applications/example-frontend . 

# Build the application
RUN npm run build
# Install 'serve' to serve the application
RUN npm install -g serve

CMD ["serve", "-s", "-l", "5000", "build"]
