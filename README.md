# Ionic Geofence Application

Realtime location tracking using pusher

## Prerequisites

- [Ionic](https://ionicframework.com/getting-started)
- [Express](https://expressjs.com/)
- [Pusher](https://pusher.com)
- A [Pusher account](https://pusher.com/signup) and [Pusher app credentials](http://dashboard.pusher.com/)

## Getting started

- Clone the project and install dependencies:
- Create a file named `.env`. Update the `.env` file with the content below:

```
PUSHER_APP_ID=app-id
PUSHER_APP_KEY=app-key
PUSHER_APP_SECRET=app-secret
PUSHER_CLUSTER=cluster
```

> **Note**: ensure to replace the placeholder values with your pusher `appId`, `key`, `cluster` and `secret`.

- Clone the repo
- Enter the project folder
- Run `yarn` or `npm i`
- Start server by running `node server`
- Run `ionic serve` to start the application


## Built With

- [Ionic](https://ionicframework.com/getting-started)
- [Pusher](https://pusher.com)
- [Express](https://expressjs.com/)