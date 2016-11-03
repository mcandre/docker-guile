# docker-guile - a Docker container for Guile Scheme

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-guile/

# EXAMPLE

```
$ make
docker run --rm mcandre/docker-guile:latest guile --version
guile (GNU Guile) 2.0.9
Copyright (C) 2013 Free Software Foundation, Inc.

License LGPLv3+: GNU LGPL 3 or later <http://gnu.org/licenses/lgpl.html>.
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)
* [Node.js](https://nodejs.org/en/) (for dockerlint)
