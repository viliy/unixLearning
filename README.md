# learning

## install

```shell
wget http://www.apuebook.com/src.3e.tar.gz

tar zxvf src.3e.tar.gz

cd apue.3e && make

```

## example

```

cp include/apue.h path/unixLearning/vendor
cp lib/libapue.a path/c/unixLearning/vendor

gcc myls.c -o myls -I../vendor -L../vendor -lapue

```
