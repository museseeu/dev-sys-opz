# dev sys opz


## Mac 

### quick tips

How to user command line display system file

    defaults write com.apple.finder AppleShowAllFiles TRUE;\killall Finder

How to hidden system file

    defaults write com.apple.finder AppleShowAllFiles FALSE;\killall Finder


How to change screenshot path

    defaults write com.apple.screencapture location ~/Pictures/
    
    killall SystemUIServer

How to change default screenshot name

    defaults write com.apple.screencapture name "Screenshot"

    killall SystemUIServer  


## Frontend Development Package

Support Basically frontend

    npm install express-generator@4 -g
    npm install vue-cli -g
    npm install gulp-cli -g
    npm install supervisor -g
    npm install pm2 -g
    npm install typescript -g 
