# Twitter-Bot

Tweets a random inspirational quote every 5 minutes.

## Getting Started

You will need to go to [Twitter Apps](http://www.apps.twitter.com) and create a twitter bot. You will then need to input your values for:

```
    consumer_key:         '',
    consumer_secret:      '',
    access_token:         '',
    access_token_secret:  ''
```


### Prerequisites

Install Node and NPM [Node](https://docs.npmjs.com/getting-started/installing-node)

```
  node -v
  npm install npm@latest -g
```

### Installing

Install the Twit Package via NPM [Twit](https://www.npmjs.com/package/twit)

```
npm install twit
```

Install the Twit Package via NPM [Node Schedule](https://www.npmjs.com/package/node-schedule)

```
npm install node-schedule
```

## Package.json 

Your Package.json should look like

```
{
  "name": "twitter-bot",
  "version": "",
  "dependencies": {
    "node-schedule": "^1.2.5",
    "request": "^2.83.0",
    "twit": "^2.2.9"
  },
  "scripts": {
    "start": "node index.js"
  }
}
```

### Running

Then simply run with either

```
node index.js
```
OR

```
npm start
```
