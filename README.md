# Smart layout app
App for automatically placing items on presentation slide the Miro board

`git clone https://github.com/Readix/smart-layout.git`

`cd smart-layout`

### How to use
1) Run `./npm_init.sh` (install npm and load all necessary dependencies)
2) Run `npm run ngrok`
3) Edit `src/config.js`:
    - Set BASE_URL from ngrok with https protocol extension
    - Set CLIENT_ID from the App settings
    - Set CLIENT_SECRET from the App settings
4) Run in another terminal:

`npm run init`

`npm run start`

5) Open app landing (url from ngrok, like https://--------.ngrok.io)
6) Configure web-plugin — set iframe url in App settings
7) Explore it    

### How it works

`app.js` is the entry point

`api.js` contains methods for work with API

`config.js` contains configs, edit this file before usage

`events.js` process webhook events
 
`db.js` is simple DataBase which works with file database.txt
