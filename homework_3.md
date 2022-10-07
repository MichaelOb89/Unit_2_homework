# Third written homework w11d01
## Index Route
Index route will display the complete list of items in a database. Index route only reads data and therefore uses get.
```js
app.get("/index", (req, res)=>{
    //code to display/render HTML here
})
```

## New Route
New route will display the form to create a new item in the database. New route also uses get, because it only diplays the form information
```js
app.get("/index/new", (req, res)=>{
    //code to display/render HTML here
})
```

## Create Route
Create route will take the data from the form in the new route,  and create a new item in the database. To do this, the create route uses post.
```js
app.post("/index", (req, res)){
    //code to post new item
}
```
## Show Route
Show route will display in detail one of the items from the database that appear in the index route.  Show route is read only and uses get
```js
app.get("/index/item._id", (req, res)=>{
    //code to display/render HTML for show route
})
```