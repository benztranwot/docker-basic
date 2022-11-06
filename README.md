# Benz Blog

A simple app where I learned how to integrate Docker with.

- Backend: Express.js
- Frontend: React.js

# How to run this app

- I'll assume that you already have Docker installed on your machine and WSL 2 too if you're using Windows.

### Open terminal in the root directory where the `docker-compose.yaml` is located and type:

```
docker-compose up
```

- And then open your browser in `http://localhost:3000/` to view the app.
- You can also visit `http://localhost:4000/` to view the JSON data returned by the API.

### After done playing, open another terminal and type the following command to stop Docker:

```
docker-compose down --rmi all -v
```

## Show your support

Give a ⭐️ if you like this project!

## License

[MIT](LICENSE)
