This is a fake data back-end for the gawati-portal-ui. 

To use it, git clone this repository. Then `npm install` .

After that run `npm start`, it will start on port 9111. 

In `gawati-portal-ui`: 
  1. Set `proxy` in `package.json` to `http://localhost:9111` and ;
  1. Set `GAWATI_DOCUMENT_SERVER` in `public/index.html` to `http://localhost:9111` and ;
  1. Set `auth` to `false` in `configs/dev.json` in the portal-ui ;
  1. Now run `npm start`; the portal-ui will start on `localhost:3000`

