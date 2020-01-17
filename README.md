# vue-ssr-pro-with-express

## desc

vue app production with  express (ssr mode)

## project diretory constructor

get detail [here](./note/dir-construtor.md)

## some important deps for csr production

- express (use express framework)
- express.router (use route help you?)
- serve-static (use static file serve)
- serve-favicon (to quickly use favicon)
- morgan (use log for serve?)
- compression (use zlip to compress)
- lru-cache (mirco cache sth.)
- connect-multiparty (support multi middleware?)
- cookie-parser (parse cookie header and bind to req.cookies ?)
- body-parser (parse req body for json , urlencoded ?)
- moment (date library for parsing, validating, manipulating, and formatting dates?)


## some config

`config/server.config.js`

01.where the host is? [config](./config/server.config.js#L8)

02.which port will use?  [config](./config/server.config.js#L10)

03.where the html file to serve?  [config](./config/server.config.js#L12)

04.what is the name of html files?   [config](./config/server.config.js#L14)

05.where the static file to serve?   [config](./config/server.config.js#L16)

## some command

``` bash
# install dependencies
npm install # or yarn install

# serve in production mode
npm start
```

## author

yemiancheng <ymc-github@gmail.com>

## contributor

eteplus <eterplus@gmail.com>

## License
MIT
