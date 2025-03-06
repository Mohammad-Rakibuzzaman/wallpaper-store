# wallpaper-store

## Project Installation KICKSTART WITH BACKEND PART

* To create package.json outside of folders so it would be easier when it comes to the deployment part:
```
npm init -y
```
* Next install all the dependencies

```
npm install express mongoose dotenv
```

* Now create a file called server.js inside of backend folder. Which will be the entry point for our api. 

* add **type** inside of package.json to use module or modern way to import export

* Now write server.js file": [server.js](https://prnt.sc/pLRCYHB_d1TX)

* Lets install nodemon so that when we update our server it will inform us update frequently: 
```
npm i nodemon -D
```
here -D means dev dependencies inside of package.json file and we can also add inside of scripts "type" : "nodemon backend/ server.js"