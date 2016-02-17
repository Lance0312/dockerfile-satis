Dockerfile for Satis
====================

### Pull the image
```bash
$ docker pull lancechen/satis
```

### Build a repository
```bash
$ docker run --rm -v $(pwd):/build lancechen/satis build satis.json /build/output
```
