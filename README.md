# New generation of deploy tools
## install
```
  npm i -g huyax
```

## configure
place `deploy` command in package.json like this
```json
  "scripts": {
    "deploy": "rsync ./public root@production.server:/var/www"
  }
```

## use
just run `huyax` in the package.json directory
