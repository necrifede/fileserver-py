# fileserver-py

this is small fileserver written in python to upload files.

run this with command in server
```shell
$ python3 fserver.py
```

then, to upload files from a client host with `curl` command as follows.
```shell
$ curl -X POST -F "file=@{filename.zip} http://{ip}:8000
```

the file `filename.zip` should be stored on 'uploads' folder in server


## posible improvements

[ ] Add the posibility to see the upload files

