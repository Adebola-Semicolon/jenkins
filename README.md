# jenkins
Custom jenkins images with docker-compose,docker and all the plugins pre-installed

If you are using this on production, you may want to comment the passowrd setup on the jenkins file 

## Support on Beerpay
Hey dude! Help me out for a couple of :beers:!

[![Beerpay](https://beerpay.io/rubiin/jenkins/badge.svg?style=beer-square)](https://beerpay.io/rubiin/jenkins)  [![Beerpay](https://beerpay.io/rubiin/jenkins/make-wish.svg?style=flat-square)](https://beerpay.io/rubiin/jenkins?focus=wish)


  
docker build -t myjenk .

docker run -d -v /var/run/docker.sock:/var/run/docker.sock \
-v $(which docker):/usr/bin/docker -p 8080:8080 myjenk
