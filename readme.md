# Shop-Catalog
## Includes
  - Simple PHP Backend
  - Simple API
  - Modules: Logger, Page
  - Components: Cart, Catalog
  - Services: Terminal


## Build-With
  - jQuery
  - ES6
  - Babel
  - Webpack

# Code
Editor: vscode
## Rules:
### Code Access
| Type | Modules | Services | Library
| ------ | ------ | ------ | ------ |
| Modules | Yes | No | No
| Services | Yes | Yes | Yes
| Library | No | No | Yes

# demo
### preview
![alt text](https://i.ibb.co/JFQ9Wm1/1.png)
![alt text](https://i.ibb.co/KGgyCx1/2.png)
![alt text](https://i.ibb.co/gygZSBb/3.png)
![alt text](https://i.ibb.co/cYV4d2G/image.png)
![alt text](https://i.ibb.co/kHsq0dq/image.png)

### Live
http://138.201.155.5/leo123/shop-catalog/

# frontend:
### es6 plain js: index.html (no extrernal libraries or freamworks except jQuery)
### babel with webpack: index_babel.html

# backend:
### folder: api

## to start the backend
```
mysql <your mysql info>
mysql> create database market
$ mysql -u <your user> market < market.sql
$ vim api/config/database.php
$ php -S localhost:8080
````
## es6 http://localhost:8080/
## babel http://localhost:8080/babel-index.html

## build for babel with the command 
````
$ npm install
$ npm run webpack
````
