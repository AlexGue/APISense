<p align="center">
    <img src="https://i.imgur.com/yeM70JU.png">
    <h2>The Express middleware for microservice tracing</h2>
     <h2>The Express middleware for microservice tracing</h2>
</p>

<p>
  APISense is a Express middleware, that help you to track all the requests and the data that is being sent all over your microservices.
  
  It allow you to see all the system logs, the new requests sent, and the responses, generated by a incoming request in your service.
</p>
<br>

<h2>1. How to implement APISense?</h2>
Add the middleware in all the services you want to trace:
```javascript
//app.use(require('@alexgue/apisense')())
```



<br>
<h2>2. How to use APISense?</h2>
APISense deploy a new interface in every service deployed. You can access the APISense interface from the service URL + "/apisense".
Example:
localhost:8000/apisense
 
