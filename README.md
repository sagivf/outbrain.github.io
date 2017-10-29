<link rel="shortcut icon" type="image/x-icon" href="favicon.ico">
<style>
@media screen and (min-width: 64em) {
    .page-header {
        padding: 5rem 6rem;
        background-image: url(http://bumpsbitsnbytes.com/wp-content/uploads/2013/02/240283-1920x1080.jpg);
        background-size: cover;
    }
}

@media screen and (max-width: 64em) and (min-width: 42em)
    .page-header {
        padding: 4rem 6rem;
        background-image: url(http://bumpsbitsnbytes.com/wp-content/uploads/2013/02/240283-1920x1080.jpg);
        background-size: cover;
    }
}

</style>
<a href="https://github.com/sagivf">
    <image src="github.png"/>
</a>
<a href="https://twitter.com/sagivfr">
    <image src="twitter.png"/>
</a>

## Projects
* [RethinkDB Job Queue UI](/rjq-ui)
* [Leonardo](http://outbrain.github.io/Leonardo/)

### Awesome CLI
* [Npm Update](https://www.npmjs.com/package/npm-check-updates)
* [Command Line HTTP](https://httpie.org/)

### Awesome Education
* [My Education List](/Education)
* [CORS](https://medium.com/statuscode/cors-a-guided-tour-4e72230a8739)
* [Learn HTTP](https://egghead.io/lessons/tools-http-response-status-codes-2xx-success)

### Awesome Node
* [Nicer call stack](https://www.npmjs.com/package/callsite-record)

### Awesome Tools
* [Image placeholder](https://dummyimage.com/)
* [Image placeholder kittens](http://placekitten.com/)
* [QR Code](https://github.com/kciter/qart.js)
* [Load test](https://httpd.apache.org/docs/2.4/programs/ab.html)

### Awesome plugins
* [the typing effect with a pure HTML interface](http://steven.codes/typerjs/)
* [clipboard js](https://clipboardjs.com/)
* [Tilt DOM](http://gijsroge.github.io/tilt.js/)
* [Tooltip](https://atomiks.github.io/tippyjs/)

## Awesome Productivity
* [I done this](https://idonethis.com/customers)

# Squiggles

## CMD
- ps aux | grep node
- kill -9 16783

## Mongo
```
- 3.2.10 version
- sudo service mongod start

/lib/systemd/system/mongod.service 
in /etc/mongod.conf

https://docs.mongodb.com/v3.2/tutorial/install-mongodb-on-ubuntu/
/var/log/mongodb/mongod.log
```

## Pin a specific version of MongoDB
```
* echo "mongodb-org hold" | sudo dpkg --set-selections
* echo "mongodb-org-server hold" | sudo dpkg --set-selections
* echo "mongodb-org-shell hold" | sudo dpkg --set-selections
* echo "mongodb-org-mongos hold" | sudo dpkg --set-selections
* echo "mongodb-org-tools hold" | sudo dpkg --set-selections    
```

## Node
- nodemon --debug=3002 server.js

## NPM
- npm ls --depth 0
- ntl	
- npm run env
- npm run env | grep npm_

## Heroku
- heroku repo:purge_cache --app appName


## BackUP:
- sudo dd if=/dev/sda1 of=/media/sagivf/Miri/ddbackup/back.img
- sudo kill -USR1 PID; sleep 1; ## show progress - PID use top
- df -BG ## show sizes


## Ubuntu
* sudo apt-get update
* sudo apt-get upgrade
* sudo apt-get dist-upgrade


## GIT
* git config credential.helper store
* https://git-scm.com/docs/git-credential-store

ab -c200 -t10 http://localhost:8080/
benchmark


<image src="me.jpg" style="width: 100%"/>

