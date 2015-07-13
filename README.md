json-server
============

A simple example of a JSON Server Gulp task

---

### Getting up and running

1. Clone this repo from `https://github.com/emb0624/json-server.git`
2. Run `npm install` from the root directory
3. Run `gulp` (may require installing Gulp globally `npm install gulp -g`)
4. Your browser will automatically be opened and directed to the browser-sync proxy address
5. Change URL to http://localhost:3002/ it will open a simple UI for inspecting the JSON object.

Now that `gulp` is running, the server is up as well and serving files from the `/build` directory. Any changes in the `/src` directory will be automatically processed by Gulp and the changes will be injected to any open browsers pointed at the proxy address.

---
