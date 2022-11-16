# learnexp
mkdir fe
npm init -y
npm i -D parcel
#package.json
 "source":"src/index.html"
 "script"...
     "start":"parcel"
## src/index.html
<body>
    <div id="root"></div>
    <script type="module" src="index.js"></script>
  </body>
## src/index.js #npm i react react-dom
import React from 'react'
import {createRoot} from 'react-dom/client'
import App from './App'

createRoot(document.getElementById("root")).render( <App /> )


### test.rest
GET https://nodejs-fake-api.herokuapp.com/products

npm i react-router-dom