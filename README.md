

## Requirements

* [Node.js](http://nodejs.org/) Environment
* An account with [now.sh](https://zeit.co/now)

## Installation Steps

1. Clone repository
2. Run `npm install`
3. Start the server with `npm start` or `node server`
4. Visit [http://localhost:3000/](http://localhost:3000/)

HTTPS is required for remote cameras and remote microphone to work. Currently, there's no known method for creating SSL certificates for a private IP address. You can easily acquire a free SSL certificate for a public domain.

## Deployment Steps


1. Clone repository
2. Run `npm install`
3. Run `npm install -g now`
4. Deploy the server with `now --public`. Follow the printed out instructions
5. Visit the url provided
6. Enter room name and username, click 'Create Room'
7. Invite a friend or use another device with a front camera, visit the url. Give another name but provide the same room name
8. Remote videos should show up on both videos. You can also send chat which also works without video
