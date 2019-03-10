# easyswoole-docker
easyswoole docker image

swoole     => v4.3.0  
easyswoole => v3.1.17  
yaconf     => config dir `/var/www/easyswoole/config`


# usage
docker run -d -p 9501:9501 -v /you/workspace:/var/www/easyswoole ctwj/easyswoole 
