# Spotify Web API

> Consuming Spotify Web API

Built with a bunch of things, but to name a few:

- [Spotify Web API](https://developer.spotify.com/documentation/web-api/)
- [Create React App](https://github.com/facebook/create-react-app)
- [Express](https://expressjs.com/)
- [Reach Router](https://reach.tech/router)
- [Styled Components](https://www.styled-components.com/)

## Setup

1. [Spotify API credentials](https://developer.spotify.com/dashboard/applications) and add `http://localhost:3030` as a Redirect URI in the app settings
1. Create an `.env` file in the server root of the project based on `.env.example`
1. `nvm use`
1. `cd client` and npm i
1. `cd server` and npm i
1. `npm run all`

## Deploying to Netlify
const FORM1_LINK =
  "https://kf.kobotoolbox.org/api/v2/assets/aH7MAWHwKXEujgLPKDPLyy/data.json";
const FORM2_LINK =
  "https://kf.kobotoolbox.org/api/v2/assets/aTM2in7zRASCRZxSpQCgKR/data.json";

const TOKEN = "39443751935e85263c61fc060395825b3c354ba0";


const FORM1_UUID = "3b04a98f2c3f419bba5b632acd39f2d8";
const FORM2_UUID = "eb856c4a9fb743b080316f43e4db3d21";

module.exports = { FORM1_LINK, FORM2_LINK, TOKEN, FORM1_UUID, FORM2_UUID };
...
