# scankeys

Scans Redis keys for statistics. Built for [EmailEngine](https://emailengine.app)

App uses the same Redis config options as EmailEngine.

## Usage

```
$ npm install -g scankeys
$ scankeys --dbs.redis="redis://127.0.0.1:6379/8" > output.csv
```

App scans keys in Redis and groups these by type.
