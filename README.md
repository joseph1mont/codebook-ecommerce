E-Commerce web-application built with React, Tailwind CSS, JSON Server, JWTAuth, Context API and deployed on Netlify/Render

this is a proper full fledged e-commerce project with search, with proper fake seperate backend

order history, proper login, proper registration, proper JWT, as well as your theme controller,

lot of stuff

We can access the JSON server and JSON server Auth locally on port 8000, in 2 different ways

1- start them on new bash:
$
npx json-server data/db.json -m ./node_modules/json-server-auth --port 8000

2- or, using "node" from backend project (codebook Mock Server) using:
$
npm start

![Codebook](src/assets/images/sc.jpg "Codebook-courses store")

We use JSON Server and Json Server Auth to work with our data,

- JSON SERVER
  $
  npx json-server data/db.json

  // for search: fetch("...... products?name_like=react") in productList.js
  https://github.com/typicode/json-server/

- Json Server Auth
  JWT Token

Json Server Auth
https://github.com/jeremyben/json-server-auth

To test locally:
$
npx json-server data/db.json -m ./node_modules/json-server-auth --port 8000

# with json-server installed globally and json-server-auth installed locally

We use react-toastify to display the Error msgs
