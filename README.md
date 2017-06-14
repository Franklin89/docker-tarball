# docker-tarball

Very simple docker image hosting a simple webpage that was packaged as a splitted tarball

## Build

```bash
docker build -t docker-tarball .
```

## Run

```bash
docker run -p 8080:80 -d docker-tarball
```

or take the image from docker hub.

```bash
docker run -p 8080:80 -d franklin89/docker-tarball
```

Then start up a browser and check that the Hello World page is displayed

### Sample web page that should be displayed

```html
<html>
<head>
    <title>Hello World</title>
</head>
<body>
    <h1>Hello World</h1>
</body>
</html>
```