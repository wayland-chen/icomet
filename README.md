icomet
======

A C/C++ comet server built with libevent

## Usage

```shell
make
./icomet

curl -v "http://127.0.0.1:8100/sub?id=12"
# open another terminal
curl -v "http://127.0.0.1:8000/pub?id=12&content=hi"
```
