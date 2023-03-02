
### Run Chrome browser without CORS by disabling web security
We can run the chrome browser in a security disabled mode, this is very helpful while developing a application.

### OSX
`open -n -a /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --args --user-data-dir="<path>" --disable-web-security`

<path> should be absolute path of the folder (eg) /users/username/folder1

### Windows
Just do follow steps:

Right click on desktop, add new shortcut

Add the target as ` "[PATH_TO_CHROME]\chrome.exe" --disable-web-security --disable-gpu --user-data-dir=~/chromeTemp`

Click OK.

### Linux
`google-chrome --disable-web-security`
