## Lando has tooling

### OMG WHYYYYY                                                                                                                   
`
docker exec -it mysite_appserver_1 /bin/sh -c "/path/to/my/php -e \"phpinfo();\""                                               
`
                                                                                                                                
### Hmm ok that's a bit better                                                                                                    
`
lando ssh -c "php -e \"phpinfo();\""                                                                                            
`
                                                                                                                                
### Oh so nice!                                                                                                                   
`
lando php -e "phpinfo();"                                                                                                       
`
* can build custom tooling commands and just run as `lando mycommand doit`, and can chain commands   

