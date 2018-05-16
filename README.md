This is a fake data back-end for the gawati-portal-ui. 

To use it, git clone this repository. Then `npm install` .

After that run `npm start`. 

In `gawati-portal-ui` - set `proxy` in `package.json` to `http://localhost:9111` and `GAWATI_DOCUMENT_SERVER` in `public/index.html` to `http://localhost:9111` and then run `npm start` in portal-ui.