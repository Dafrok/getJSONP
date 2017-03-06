# getJSONP
A simpler helper function to get JSON data from another server.

[Download getJSONP](https://github.com/cferdinandi/getJSONP/archive/master.zip)


## Getting Started

### 1. Include getJSONP on your site.

Include the code in your script, or load it as an external file.

```js
var getJSONP = function ( url, callback ) {
	...
};
```

### 2. Fetch your JSON data.

Pass in the URL to fetch data from, as well as the name of a callback function to pass the data to.

```js
// Callback function
var logAPI = function ( data ) {
    console.log( data );
};

// Get JSON
getJSONP( 'https://jsonplaceholder.typicode.com/posts/10', 'logAPI' );
```



## Browser Compatibility

scrollStop works in all modern browsers, and IE 6 and above.



## How to Contribute

Please review the [contributing guidelines](CONTRIBUTING.md).



## License

The code is available under the [MIT License](LICENSE.md).
