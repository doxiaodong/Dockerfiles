## static-server
https://github.com/zeit/serve

## Usage

```
docker run --name static-server \
  -p 80:8080 \
  -v /path/to/resources:/resources \
  -d \
  -t duxiaodong/static-server
```
