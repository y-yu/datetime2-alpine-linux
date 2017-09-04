datetime2 in Alpine Linux
============================

## How to Use

```
$ docker pull yyupw/datetime2-alpine-linux
$ mkdir out
```

or

```
$ git clone https://github.com/y-yu/datetime2-alpine-linux.git
$ cd datetime2-alpine-linux
$ docker build .
```

then


```
$ docker run -v `pwd`/out:/workdir/out -i -t yyupw/datetime2-alpine-linux "/bin/cp" "-r" "*.pdf" "./out"
```

In `out` directory, you can find `dtmnow.pdf` and `mwe.pdf`.
