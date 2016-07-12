# New generation of deploy tools
## use
place `deploy` command in package.json like this
  
  "scripts": {
    "deploy": "rsync ./public root@production.server:/var/www"
  }
