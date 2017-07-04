##nodejs
	###Installation:
		1st. install compiling tools
			$ sudo apt-get install g++ curl libssl-dev apache2-utils
			$ sudo apt-get install python
			$ sudo apt-get install build-essential
			$ sudo apt-get install gcc
			$ sudo apt-get install g++
			$ sudo apt-get install libkrb5-dev
		2nd. download node source files and install Nodejs
			wget https://nodejs.org/dist/v6.10.3/node-v6.10.3.tar.gz
			$ tar -zxf node-v6.10.3.tar.gz
			$ cd node-v6.10.3
			$ ./configure
			$ make
			$ sudo make install
	###Usage:
	$node --version
	$npm --version
	$npm init		--will create file of package.json file
	$npm install	--will install all package in package.json file.
  
##karma & jasmine
    ###install karma
        $ npm install karma --save-dev
        $ npm install karma-coverage --save-dev
        $ npm install karma-jasmine karma-chrome-launcher jasmine-core --save-dev
        $ sudo npm install -g karma-cli
        $ npm install jasmine --save-dev
	###Config:
		1:use "$karma init" to generate karma.conf.js
		2: edit this file.
	###Usage:	
        $ karma start		--start karma test in project dir by
    ###reference
        -link: http://karma-runner.github.io/1.0/intro/installation.html
