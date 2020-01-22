# AngularToAndroid-OR-ios

Requirements "android studio sdk", "gradle" 
If the Requirements are not installed it will not going to work install all the requirements for more refer cordova documentery.


#Steps

1) Install cordova (npm i -g cordova).
2) Create cordova project in that directory (type in terminal "cordova create 'name of Project'").
3) Copy all the folders and files of cordova Project to angular project directory except "package.json" file.
4) Now Type ng update in terminal.
5) Now create Platform for angular Project (type in terminal "cordova platform add 'android or ios or browser'").
6) In a Folder Named "www" there is an index.html file copy the only Script tag elements and paste it into the angular's index.html file.



#7) In angular's index.html file change href="/" to href="./" which is very importent.
8) In angular.json file change build src which is "dist" to "www".
9) Now type ng build in terminal.
10) last step is to build android app (type in terminal "cordova build").

#enjoy now your android app is ready.
#run android sdk manager and run any android emulator.

#Just type in terminal(cordova emulate android).
