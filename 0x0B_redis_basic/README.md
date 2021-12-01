# 0x0B. Redis basic

## Requirements

+ All of your files will be interpreted/compiled on `Ubuntu 18.04 LTS` using python3 (version 3.7)
+ All of your files should end with a new line
+ A `README.md` file, at the root of the folder of the project, is mandatory
+ The first line of all your files should be exactly `#!/usr/bin/env python3`
+ Your code should use the `pycodestyle` style (version 2.5)

### Install Redis on Ubuntu 18.04

```bash
$ sudo apt-get -y install redis-server
$ pip3 install redis
sed -i "s/bind .*/bind 127.0.0.1/g" /etc/redis/redis.conf
```

### Tasks

0. Writing strings to Redis
1. Reading from Redis and recovering original type
2. Incrementing values
3. Storing lists
4. Retrieving lists
5. Implementing an expiring web cache and tracker

## AUTHOR

### JACKSON MORENO
