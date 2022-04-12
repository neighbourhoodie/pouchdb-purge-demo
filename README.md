# PouchDB purge Demo

Demo the new PouchDB purge funcitonality in your browser.

1. Build PouchDB on the [`feat/purge` branch](https://github.com/neighbourhoodie/pouchdb/tree/feat/purge) via `$ npm run build`
2. Symlink the dist files to the pouchdb build files via (e.g., assuming the PouchDB directory resides next to this repo)
   1. `pouchdb.js`: `$ ln -s ../pouchdb/packages/node_modules/pouchdb/dist/pouchdb.js`
   2. `pouchdb.indexeddb.js`: `$ ln -s ../pouchdb/packages/node_modules/pouchdb/dist/pouchdb.indexeddb.js`
   3. `pouchdb.find.js`: `$ ln -s ../pouchdb/packages/node_modules/pouchdb/dist/pouchdb.find.js`
3. Install dependencies via `$ npm install`
4. Run the local server via `$ npm run serve` and head to http://localhost:3000/

The website will tell you about the available commands that you can enter in your browser's console.
