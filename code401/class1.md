# Node Ecosystem, TDD, CI/CD

**Describe (in plain English) what Array.map() does**

`array.map()` iterates over each element in an array (similar to a for loop), running a function on each element. It does not change or mutate the original array, rather it returns a new array that is the same length as the original array.

``` js
array.map((value,index) => {
  //some action goes here
});
```
**Describe (in plain English) what Array.reduce() does**

`array.reduce()` iterates over each element in an array and returns the accumulator. With each iteration, the accumulator is modified and returned. The last iteration returns the accumulator value. You can set the initial value that the accumulator starts at.

```js
arr.reduce( (accumulator,value,index) => {
  //some action goes here
  return accumulator;
}, initialvalue)
```

**Provide code snippets showing how to use superagent() to fetch data from a URL and log the result**


With normal Promise .then() syntax

```js
superagent.get('http://apiurlgoeshere')
  .then( data => {
    console.log(data.body);
  })
  .catch(error => console.error(error));
```

Again with async / await syntax

``` js
async function superAgentAsyncExample() {
  let apiDataResults = await superagent.get('http://apiurlgoeshere');
  console.log(apiDataResults.body);
}

superAgentAsyncExample();
```

**Explain promises as though you were mentoring a Code 301 level student**

A `promise` allows you to write code for a value not initially known. You don't have to worry about how long it will take to get the value, and you can essentially "move on". Instead of immediately returning a value, the function will return a promise to supply the value at some point. When the value has been retrieved, the code will give it to you and you can then handle it however you intended. Promises are one way to handle Asynchronous actions.

*Promises come in 3 states:*

**pending:** not fulfilled or rejected

**fulfilled:** the operation was completed successfully

**rejected:** the operation failed

**Are all callback functions considered to be Asynchronous? Why or Why Not?**

No. Callback functions can be synchronous. Simply put, a callback is a function passed as an argument in another function. For example `array.map()` and `array.forEach()` use callback functions that are synchronous. If you are dealing with an external API call, then your callback will be asynchronous.


[Back to Homepage](../README.md)