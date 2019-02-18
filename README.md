PHP 8 with experimental JIT support docker image 
===

This code is a helper to try out the PHP with experimental JIT support. It was written as a pet project inspired by
the [tweet](https://mobile.twitter.com/dr4goonis/status/806817526097346560) that states 54% performance improvement.

This image is based on experimental branch: https://github.com/zendtech/php-src/tree/jit-dynasm

You can read more about JIT support in internals mail list (https://externals.io/message/103903) or review changes in related pull request (https://github.com/php/php-src/pull/3792).

To get latest image you should run:
```bash
docker pull dmitrybalabka/php-jit:latest
```
Docker hub link: https://cloud.docker.com/u/dmitrybalabka/repository/docker/dmitrybalabka/php-jit

Code is a copy-paste of [docker/php](https://github.com/docker-library/php) builder with slight additions to be able to compile
git-based version of php.

Copyright (c) 2014-2016 Docker, Inc.
