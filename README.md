
- PHP 8.2
- Composer
- NodeJS
- NPM


Build the image:

```
docker build -t php-dev .
```

Run the container:

```
docker run -it php-dev
```

Run the container with a shared volume and port mapping:

```
docker run -it -v $(pwd):/app -p 8080:8000 php-dev
```
