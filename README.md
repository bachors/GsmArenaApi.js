# GsmArenaApi.js
Hybrid

<pre>// searching
var data = {
    param: 'search',
    query: 'keyword'
}

// get informations
var data = {
    param: 'detail',
    query: 'slug'
}

// result
GsmArenaApi(data, function(result) {
    console.log(result);
});</pre>
