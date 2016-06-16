FROM node
RUN git clone https://github.com/aseemk/node-neo4j-template.git
WORKDIR /node-neo4j-template
RUN npm install
# ugly 20s sleep to wait for neo4j to initialize
CMD sleep 20s && node app.js
