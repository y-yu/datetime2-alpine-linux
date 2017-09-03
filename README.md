datetime2 in Alpine Linux
============================

## How to Use

```
$ docker pull yyupw/datetime2-alpine-linux

$ mkdir out

$ docker run -v `pwd`/out:/workdir/out -i -t yyupw/datetime2-alpine-linux "/bin/cp" "mwe.pdf" "./out"
```

In `out` directory, you can find `mwe.pdf`.
