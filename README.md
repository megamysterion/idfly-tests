# idfly-tests

##clone rep
cmd project_folder  -git clone git@github.com:megamysterion/idfly-tests.git

##install npm packages
cmd project_folder  -npm install

##init
cmd project_folder  -grunt

##test#1
./html/index1.html

##test#2
./html/index2.html

## projHelper
You can clean your obj localStorage =>
=> uncomment "delete $scope.storage.local.entriesCalls;" in "app/Controller.js" at once(then comment this line).