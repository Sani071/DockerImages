# NodeJSAndRedisWithDocker

## Project Description
This project host a basic website on a nodeJS server and every time you visit the website the 'visit counter' is increased and stored in redis. Both redis and nodeJS server run in seperate containers.

## How to use
1. Clone the repo
2. Use the following command to run the nodeJS server and redis
```
docker-compose up --build 
```

## How to run
1. Open browser
2. go to localhost:8080
3. You should be able to see the rendered content of index.js
4. Referesh the page
5. The count should be increasing every time
