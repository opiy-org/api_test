Install
===

```
sudo -u postgres psql

CREATE DATABASE atest;
CREATE USER atest WITH password 'atest';
GRANT ALL ON DATABASE atest TO atest;

```


```
#sh ./isntall.sh
