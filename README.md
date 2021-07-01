# Botter

## Getting Started

- First clone this repository: ```git clone https://github.com/Ayush7614/Botter.git```

- Replace 'XXXXXXXXX' in `src/config.js` with your [Twitter API](https://developer.twitter.com/en/apps/) keys.

```javascript
module.exports = {
  consumer_key: 'XXXXXXXXXXXXXXXX',  
  consumer_secret: 'XXXXXXXXXXXXXXXX',
  access_token_key: 'XXXXXXXXXXXXXXXX',  
  access_token_secret: 'XXXXXXXXXXXXXXXX'
}
```

- To run this [Twitter bot](https://twitter.com/SayHiToQuotter), first install dependencies : ```npm install```

- Then run the below command : ```npm run build``` or ```npm run start```

**Note** - Tests are written using **[Mocha](https://mochajs.org/)** and can be run using `npm test`

## APIs Used

- [Twitter API](https://dev.twitter.com/apps)
- [Unsplash - Photos for Everyone](https://unsplash.com/)

## Dependencies Used

- [inspirational-quotes](https://vinitshahdeo.github.io/inspirational-quotes/)
- [node-base64-image](https://www.npmjs.com/package/node-base64-image)
- [twitter](https://www.npmjs.com/package/twitter)

## Getting [Twitter API](https://dev.twitter.com/apps) keys

> Click [here](https://dev.twitter.com/apps) to get **Twitter API** key.

### Step by Step Instructions

- Go to [this](https://dev.twitter.com/apps/new) and log in, if necessary.

- Enter your Application Name, Description and your website address. You can leave the callback URL empty.

- Accept the TOS, and solve the CAPTCHA.

- Submit the form by clicking the Create your Twitter Application.

- Copy the consumer key (API key) and consumer secret from the screen and replace in `src/config.js`

- Generate acess token and access secret token and replace in `src/config.js`


