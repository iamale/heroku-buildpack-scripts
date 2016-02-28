heroku-buildpack-scripts
=========================

```
$ heroku buildpacks:set https://github.com/ddollar/heroku-buildpack-multi.git
$ cat .buildbacks
https://github.com/iamale/heroku-buildpack-scripts.git
https://github.com/heroku/heroku-buildpack-python.git
$ cat .heroku_compile
#!/usr/bin/env bash
echo "Hello, world!"
$ git push heroku
       ...
-----> Hello, world!
       ...
```
