# docker-curl-alpine

Docker image for curl based on alpine linux image, just over 5MB in size.

## Usage
- you can modify ~/.bashrc or ~/.bash_profile

```sh
alias curl="docker run -i --rm jiapantw/curl-alpine"

curl -v -X GET localhost
```

- or you also can directly to use:

```sh
docker run -it --rm jiapantw/curl-alpine -v -X GET localhost
```
