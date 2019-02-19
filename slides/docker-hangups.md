##  Docker hangups

Docker is not perfect either. Requires a lot of Dockerfile magic and manual configuration to get networking running across all containers. Also not very easy to run commands in containers:

`
docker exec -it mysite_appserver_1 /bin/sh -c "/path/to/my/php -e \"phpinfo();\""                                               
`
                                                                                                                                
