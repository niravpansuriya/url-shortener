# url-shortener

- This API converts a long website links to short (like goo.gl,bit.ly).
 

### Prerequisites

- Node.js
- NPM
- Express


### Installation

- Clone the project
- Run given commands to the project directory

- This command will install all require packages
```
npm install
```
<p align="center">
  <img src="https://github.com/niravpansuriya/url-shortener/blob/master/npm_install.JPG" title="npm_install_command">
</p>

- This command will start server in localhost and deploy the API on it (basically will run app.js file).
```
node app
```
<p align="center">
  <img src="https://github.com/niravpansuriya/url-shortener/blob/master/node_app.JPG" title="npm_install_command">
</p>

### How to use

- Now API is running on localhost. One can call the API from anywhere, I am using CURL.
- User has to call the api with POST method at end-point **api/shorten** (call with JSON object, key name is **fullURL** and value is **Website's Long Link**
- It will return the  


### How to use?

- Send a post request to **/api/shorten** with **fullURL** as key and link as a value
- Send a get request to **/** end point with **shortenURL**


### Demo

- Watch a [quick demo](https://drive.google.com/file/d/1X4Jkzv1MU37NBFuVUGwuuBEZYH0ey0Q4/view?t=08m29s)
- Watch a [full demo](https://drive.google.com/file/d/1X4Jkzv1MU37NBFuVUGwuuBEZYH0ey0Q4/view)


## Authors

* **Nirav C. Pansuriya** 
