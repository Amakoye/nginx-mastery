# Nginx Mastery Series

## Nginx

- Open source software for

  - Web serving
  - Reverse proxying
  - Caching
  - Load balancing
  - Media streaming & many more

- Similar options: Apache, Google cloudfare, e.t.c.

## Basic Service Management

- service nginx start
- service nginx stop
- nginx Commands
  - h
  - v -V :
    -t -T : Checks syntax & tests the configuration file
    -s : Used to send a signal

### Building an image for deployment

```
docker build -t webserver .
```

### Running the image

```
docker run -it --rm -d -p 8080:80 --name web webserver
```
