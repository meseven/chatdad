# TheChatFather
![the chat father](http://oi67.tinypic.com/10p5yy9.jpg)

# How to install
## Clone repo and install dependencies
`git clone https://github.com/meseven/thechatfather.git`

`cd thechatfather`

`npm install`

## Enviroment variables
Create a file named ".env" in the root directory and fill its contents as follows.

```ruby
DB_STRING = XXX

GOOGLE_LOGIN_CLIENT_ID = XXX
GOOGLE_LOGIN_SECRET_ID = XXX
GOOGLE_LOGIN_CALLBACK_URL = XXX

SESSION_SECRET_KEY = XXX

REDIS_URI = XXX
REDIS_PORT = XXX
REDIS_PASS = XXX
```

## Run the app
`npm run start:dev` // for locally
