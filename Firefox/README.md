Place this userChrome.css file in this directory
```
C:\Users\THARUN\AppData\Roaming\Mozilla\Firefox\Profiles\d9ssq99a.default-release\chrome
```

then to remove the youtube fullscreen dialog box warning, and delay
Go to,
1. about:config
then change these settings
```
full-screen-api.transition-duration.enter	0 0	
full-screen-api.transition-duration.leave	0 0 	
full-screen-api.warning.timeout	0
```
