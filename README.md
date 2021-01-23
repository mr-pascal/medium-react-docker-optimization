# Medium React Docker Optimization


### Start React app

All commands need to be run inside `./my-app/` folder:

Install dependencies
```sh
yarn install
```

Start local development server (Chrome tab is automatically opened on http://localhost:3000/)
```sh
yarn start
```

### Docker
Build Docker image
```sh
docker build -t react-nginx .
```


Start Docker container

```sh
docker run -d -p 8080:80 react-nginx
```
