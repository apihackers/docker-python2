[![Docker Stars](https://img.shields.io/docker/stars/apihackers/python2.svg?style=flat-square)](https://hub.docker.com/r/apihackers/python2/)
[![Docker Pulls](https://img.shields.io/docker/pulls/apihackers/python2.svg?style=flat-square)](https://hub.docker.com/r/apihackers/python2/)

# Python 2 Alpine Docker image

This image is based on Alpine Linux image, which is only a 5MB image,
and contains [Python 2.7](https://www.python.org/).

## Usage Example

```bash
docker run --rm apihackers/python2 python2 -c 'print("Hello World")'
```

Once you have run this command you will get printed 'Hello World' from Python!

NOTE: `pip`/`pip3` is also available in this image.
