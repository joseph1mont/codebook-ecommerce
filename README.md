![Codebook](src/assets/images/sc.jpg "Codebook-courses store")

We use JSON Server and Json Server Auth to work with our data,

- JSON SERVER
  $ npx json-server data/db.json
  // for search: fetch("...... products?name_like=react") in productList.js
  https://github.com/typicode/json-server/

- Json Server Auth
  JWT Token

Json Server Auth
https://github.com/jeremyben/json-server-auth
$ npx json-server data/db.json -m ./node_modules/json-server-auth --port 8000

# with json-server installed globally and json-server-auth installed locally

We use react-toastify to display the Error msgs
