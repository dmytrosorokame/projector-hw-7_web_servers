# Projector HSA Home work #7: Web Servers

## To run the project:

```bash
$ docker-compose up
```

## To test cache functionality:

### 1. Open in browser:

- [http://localhost/image.png](http://localhost/image.png)

### 2. Check X-cache-status header:

For first two requests it should be `MISS`, for the third one and further it should be `HIT`.

### 3. For clearing cache open in browser:

- [http://localhost/purge?uri=/image.png](http://localhost/purge?uri=/image.png)

### 4. Check X-cache-status header:

For the next request it should be `MISS` again.
