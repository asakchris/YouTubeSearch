# YouTube Search Using React JS

Simple react project to search youtube videos

### Getting Started

1. Clone this repository
1. Follow below steps to create YouTube API key:
   - Go to [this](https://console.cloud.google.com/) link
   - Singin using your Google crdentials
   - create new project
   - Select `API & Services`
   - Go to `Enabled APIs & services`
   - Search for `YouTube Data API v3` and select it
   - Enable it
   - Go to `Credentials` on left panel
   - Click `Create Credentials`
   - Select `API key`
   - Save the key
1. Update `API_KEY` in (index.js)[./src/index.js] with the key generated in previous step
1. Use any editor/command line tool and run `npm install` from root directory to download all dependencies
1. Disable SSL using `npm config set strict-ssl false` command if any issues downloading dependencies
1. Start the application using `npm start` comand
1. Access application using [this](http://localhost:8080/) link
