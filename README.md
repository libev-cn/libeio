# libeio —— Event-based fully asynchronous I/O library for C.

  From [here](http://software.schmorp.de/pkg/libeio.html)

## Blurb

  Libeio is a full-featured asynchronous I/O library for C, modelled in similar style and spirit as libev. Features include: asynchronous read, write, open, close, stat, unlink, fdatasync, mknod, readdir etc. (basically the full POSIX API). sendfile (native on solaris, linux, hp-ux, freebsd, emulated everywehere else), readahead (emulated where not available).

  It is fully event-library agnostic and can easily be integrated into any event-library (or used standalone, even in polling mode). It is very portable and relies only on POSIX threads.

  Its code, documentation, integration and portability quality is currently below that of libev, but should soon be ready for use in production environments.

## How To Build ?

  1. `./autogen.sh`

  2. `./configure`

  3. `make && make install`

## How To Use It ?

  Checkout `demo.c`.

## LICENSE

  [LICENSE](https://github.com/CandyMi/libeio/blob/master/LICENSE)