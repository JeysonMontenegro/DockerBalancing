#imge version
FROM node:0.10.38
# make dir src
RUN mkdir /src
# install nodemon
RUN npm install -g nodemon

# Define working directory
WORKDIR /src
ADD index.js /src/index.js
ADD package.json /src/package.json
RUN npm install

# Expose port
EXPOSE  8080

# Run app using nodemon
CMD ["nodemon", "/src/index.js"]
