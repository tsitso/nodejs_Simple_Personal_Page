# NodeJs Personal Page & Simple Blog
**Personal Web & Simple Blog : NodeJs + Express +  MongoDB + (Stylus + Jade) + Bootstrap**

## <a name='TOC'>Table of Contents</a>

1. [Introduction](#intro)
1. [Technologies](#tech)
1. [Running](#run)
1. [Tips](#tips)
1. [Credit](#credit)
1. [License](#license)

## <a name='intro'>Introduction</a>

This is a simple project for develop a personal page and blog. The finality this is learn the basic concept for NodeJS + Express + MongoDB.

## <a name='tech'>Technologies</a>

- [NodeJs](http://nodejs.org/) - Event-driven I/O server-side JavaScript environment based on V8.
- [Express](http://expressjs.com/) - Framework MVC for NodeJs
- [MongoDB](http://www.mongodb.org/) - A scalable, high-performance, open source NoSQL database.
- [Jade](http://jade-lang.com/) - High performance template engine for NodeJs.
- [Stylus](http://learnboost.github.com/stylus/) - Expressive, dynamic, robust CSS for NodeJs.
- [Passport](http://passportjs.org/) - Simple, unobtrusive authentication for NodeJs.
- [Bootstrap](http://twitter.github.io/bootstrap/) - Sleek, intuitive, and powerful front-end framework for faster and easier web development.

## <a name='run'>Running</a>
**With nodeJs and MongoDB Server**
	
1. Install [node.js](http://nodejs.org/#download).
2. Install [MongoDB](http://www.mongodb.org/downloads).
3. Init MongoDB & Change default values in:
```
<path to nodeJs_Simple_Page directory>/application/config/config_db.js
```
4. Install dependencies using the node package manger (npm).
```
npm install
```
5. Start the Application demo server:
```
node app
```
6. Visit [http://localhost:5000](http://localhost:5000) in a web browser.
	
## <a name='tips'>Tips</a>

- **If you want the stylus automatically compiles**
	+ Add Stylus in `package.json`
	+ Uncomment the line **32** in `app.js`
	+ `app.use(require('stylus').middleware({ src: __dirname + '/application/public' }));`

- **If you want compress css styles use this command**
	+ Stylus Compress: `stylus -c index_page.styl` intro: 
	+ `<path to nodeJs_Simple_Page directory>/application/public/stylesheets/`

## <a name='credit'>Credit</a>

**Author: Mario Andrade** [@TheVansters](https://twitter.com/TheVansters)

## <a name='license'>License</a>

**Public Domain**
