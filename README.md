## Steps to hack pylutron for now

Copy from this [raw file](https://raw.githubusercontent.com/awrede/pylutron/master/pylutron/__init__.py)
```
$ sudo docker exec -it home-assistant /bin/bash
$ cat <<EOF > input
$ rm __init.py__
$ mv input __init.py__
$ exit
```
