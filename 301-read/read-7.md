# SuperAgent
SuperAgent is light-weight progressive ajax API crafted for flexibility, readability, and a low learning curve after being frustrated with many of the existing request APIs. It also works with Node.js!

Node.js is an open source server environment that allows you to run JavaScript on the server.

Request basics A request can be initiated by invoking the any method on the request object, then calling .then()

**Request types :**
DELETE (.del()), HEAD, PATCH, POST, PUT 

Setting header fields To pass data on Request :

` request .get('/search') .set('API-Key', 'foobar') .set('Accept', 'application/json') .then(callback); `


