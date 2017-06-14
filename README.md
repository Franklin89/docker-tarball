# docker-tarball

Very simple way to integrate a splitted tarball in a image. The splitted tarball in this project is a ver simple hello world webpage.

## Build

```bash
docker build -t docker-tarball .
```

## Run

```bash
docker run -p 8080:80 -d docker-tarball
```

Then start up a browser and check that the Hello World page is displayed

### Sample

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