
to run the application : 
    mvn spring-boot:run

to get the configuration of sbcpc-config-consumer for default profile :
    http://localhost:3876/sbcpc-config-consumer/default
    
    
to get the configuration of sbcpc-config-consumer for production profile :
    http://localhost:3876/sbcpc-config-consumer/production
    
we can try :

1 /{application}/{profile}[/{label}]
2 /{application}-{profile}.yml
3 /{label}/{application}-{profile}.yml
4 /{application}-{profile}.properties
5 /{label}/{application}-{profile}.properties
    
    
if the git content change, then a pull is executed and the configuration is refreshed

