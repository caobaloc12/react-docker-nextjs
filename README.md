# A simple React(Next.js) app development on Docker
## Run app with scripts
Setup to run dev environment
```
yarn install 
// or npm install
```

Run the app on local machine by running the command: 
```
yarn run dev
// or npm run dev
```

## Build and run with Docker

Build Docker image: 
```
docker build -t awesome-react-docker-nextjs .
```
Check it in the list docker images with `docker images`

Run up Container
```
docker run -d -p 3000:3000 awesome-react-docker-nextjs:lastest
```
Check it with `docker ps` and test it by openning brower with the address: http://localhost:3000 

