# Jira Clone
To run locally
```
docker-compose up -d
```

* -d, __detached__


## Setting up environment variables
rename __.env.template__ to __.env__
* MongoDB URL Local:
```
MONGO_URL=mongodb://localhost:27017/entriesdb
```

* Build
```
yarn install
yarn dev
```


## Fill DB with test data

use:
```
http://localhost:3000/api/seed
```