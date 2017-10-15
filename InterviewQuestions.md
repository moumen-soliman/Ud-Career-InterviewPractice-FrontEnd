
## 1. What is the most influential book or blog post you’ve read regarding front-end development?

## 2. If you could master one technology this year, what would it be and why?


## 3. Describe any front-end web application framework (preferably one that you use). How does it work? What are the upsides and downsides?

## 4. Write a JavaScript function that takes only one argument——another function——and returns a "memoized" version of that function. A "memoized" version of a function caches and returns the results of its call so that when it is called again with the same input, it doesn’t run its computation but instead returns the results from cache. Note that previous results should be retrievable in any order without re-computation.

Feel free to include your own example use, input, and output (like what is seen below).
```javascript
foo = function (x) {
console.log("calculating!");
return x + 5;
}

var memoizedFoo = memoize(foo);

memoizedFoo(5);
// calculating!
// 10

memoizedFoo(5);
// 10 (notice how 'calculating!' is not printed this time)

memoizedFoo(10);
// calculating!
// 15
```
## 5. Create a simple webpage that has a cow image in the middle (centered horizontally on the page) and a counter label below it. Add the necessary code so that every time you click the cow image, the counter is incremented by 1. The counter should start with a value of 0. You should include a brief explanation of your code. Also, here is a URL for a cow image, https://upload.wikimedia.org/wikipedia/commons/2/21/Cow_cartoon_04.svg, if you would like to include it in your answer.

## 6. If you were to start your front-end position today, what would be your goals a year from now?
