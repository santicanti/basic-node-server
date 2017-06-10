# basic-node-server-with-docker

Steps to run in docker:

docker build -t node-test .

docker run -ti -p 3000:3000 node-test

Test it by going to http://localhost:3000 and a 'hello world!' message should appear
