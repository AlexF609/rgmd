- Run: `$ npm install` then: `$ gulp copy-assets`

### Running
To work and compile your Sass files on the fly start:

- `$ gulp watch`

Or, to run with Browser-Sync:

- First change the browser-sync options to reflect your environment in the file `/gulpconfig.json` in the beginning of the file:
```javascript
  "browserSyncOptions" : {
    "proxy": "localhost/site/",
    "notify": false
  }
};
```
- then run: `$ gulp watch-bs`

