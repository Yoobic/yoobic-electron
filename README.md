# yoobic-electron
* This code in this repo is for the Nuts server that handles updating and distribution of our Mac and Windows dashboard applications
* The server is currently hosted at `https://yoobic-dashboard-distribution.herokuapp.com/`
* The server looks for releases on this repo to know when a new version of the dashboard has been released
* Releases should be made automatically by the electron release process in yo-ui-web
* In order to be picked up by the server, application files must be attached to the release
* Since it's a free dyno on my account right now, the server needs 30 seconds to 'wake up' before it's operational
* bin/web.js is the only thing in this repo that should be edited
* If you make changes to the server and want them to take effect, you need to `git push heroku`, which should be a remote at `https://git.heroku.com/yoobic-dashboard-distribution.git`
