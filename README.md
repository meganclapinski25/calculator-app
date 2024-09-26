
# docker-flask

<!-- omit in toc -->
## Table of Contents

1. [Build the Image](#build-the-image)
1. [Run the Container](#build-the-container)
1. [Access via Browser](#access-via-browsers)

## Command Reference

### 1. Build the Image

```bash
docker build -t flask-image .
```

### 2. Run the Container

```bash
docker run -p 5005:5005 --rm --name calc-calculator flask-image
```

### 3. Access via Browser

http://localhost:5005
