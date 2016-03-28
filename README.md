### Command history 

*This my command history on a mac from zero to an ionic webview wrapper Android app for the Firebase sample chat app*

sudo npm install -g ionic  

sudo npm install -g cordova 

ionic start firebasechat

ionic platform add android

//here is where I started messing with www/index.html - check out the code checked into this repo and use that, be sure to update the firebase identifier with your own

ionic serve //preview in browser

ionic run android // make sure you have an adb connected android device, I used genymotion instance

ionic plugin add https://github.com/apache/cordova-plugin-whitelist.git //fixes 404 issue
//reference: http://docs.ionic.io/docs/cordova-whitelist

