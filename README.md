# easyswoole-docker
easyswoole docker image
```
swoole     => v4.3.1    
easyswoole => v3.1.18   
yaconf     => config dir `/var/www/easyswoole/config` 
```

# usage
```
docker run -d -p 9501:9501 -v /you/workspace:/var/www/easyswoole ctwj/easyswoole 
```
# how to start you project

1. install you library  
```
 docker run --rm -v /you/project/dir:/var/www/easyswoole ctwj/easyswoole composer install
 ```
2. run project  
```
 docker run -d -p 9501:9501 -v /you/project/dir:/var/www/easyswoole ctwj/easyswoole
```

# change log

2019-08-21 Add sockets extends

2019-04-10 Add mongodb library
