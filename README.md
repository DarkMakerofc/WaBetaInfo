<h2 align="center">🪀 WaBetaInfo 🪀</h2>

<h6 align="center">
This is Unofficial Scraper & NPM package , Created by Mr nima. </h6>

* How To install Package
* How To Require
* Get All News
* Get News Using Link
* Get Latest News



#### ⬇️ Install Package 
```
yarn add nima-wabeta-info
```


#### 📡 Require Package 
```
const betainfo = require("nima-wabeta-info")
```



#### 🔍 Get All Results  
```
betainfo.getAll().then((result) => {

console.log(result)

}).catch(error => console.log(error)
```


#### 🔍 Get Latest Result 
```
betainfo.getLatest().then((result) => {

console.log(result)

}).catch(error => console.log(error)
```


#### 🔍 Get Result From Link
```
var link = "https://wabetainfo.com/whatsapp-beta-for-ios-23-15-1-76-whats-new/"

betainfo.getFromLink(link).then((result) => {

console.log(result)

}).catch(error => console.log(error)
```

