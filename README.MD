# Nginx Mastery Series

### Building an image for deployment

```
docker build -t webserver .
```

### Running the image

```
docker run -it --rm -d -p 8080:80 --name web webserver
```
