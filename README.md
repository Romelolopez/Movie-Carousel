# Movie-Carousel
<div align="center">
  ![gif](https://user-images.githubusercontent.com/48486610/155921835-37d63964-8da4-4824-bda9-f73b114dedd9.gif)
  <p>Carousel made using HTML, CSS, JavaScript, JSON</p>
</div>



## Creat your own json-server

> **1st**: Clone this repository.

> **2nd**: Under this repo, run: npm install

> **3rd**: Start this json-server, run: npm start

### Run your json-server
Check the server port (default port should be 3000).

On browser, check json-server main page(http://localhost:3000 ) for our json-server.

Click “/posts”, check our posts data. (http://localhost:3000/movies)

# Try it:

```javascript
fetch('http://localhost:3000/mvoies')
  .then(response => response.json())
  .then(json => console.log(json))
