**Promises:**

Promises in javascript is like promises in real life. If the promise is complete than do something otherwise the promise is break.
In javascript promise gives two params, first one if the promise is reslove and the second one if promise is not fullfiled.

**Example:**
```
let IsWorkComplete = new Promise(function(resolve,reject){
 let isWork=false;
 if(isWork){resolve('complete')}
 else{reject('incomplete')}
});

IsWorkComplete.then(function(fromResolve){
console.log('Play');
}).catch(function(fromReject){
console.log('Not play.');
})

```
[jsfiddle](https://jsfiddle.net/helloaliimran/ohxn823b/latest/)

***Explaination***
Promise has two parts:
1. promise condition.
2. check promise is full fill or not.
