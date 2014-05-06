chat-chrome-app
===============

Simple chat application developed using Node.js, Socket.io and Bootstrap.

###Development:


Install Dependencies:

  - Server :
  	$ npm install 
  - Client :
   	$ bower install
  
Configure:

  - Server : 
    Change 'port' in 'server.js' if required (default '6789')
  
  - Client : 
    Change 'serverAddress' in 'scripts/chat.io.js' to 'ip:port' on which you intend to run the server (default '127.0.0.1:6789')
  
Run Server:
  
	$ node server.js
	
Build:

	- Web App : no build required
	- Chrome App : package the app using general packaging procedure (https://developer.chrome.com/extensions/packaging)
	
Usage:

	- Browser : http://server-ip:port/ (default http://127.0.0.1:6789/)
	- Chrome App (packaged app : build/client.crx)
	

We will be able to chat across machines (browser and chrome app) within a private network.

### Credits

This application is built using the following:

- https://github.com/uditalias/chat-nodejs
- Animate.css library - by Dan Eden: http://daneden.me/animate/
- Avgrung modal - by Hakim El Hattab: http://lab.hakim.se/avgrund/


### License

Copyright (c) 2014 theTechies

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a> and <a rel="license" href="http://opensource.org/licenses/MIT">MIT License</a>.



