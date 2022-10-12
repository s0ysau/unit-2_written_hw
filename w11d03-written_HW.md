<h1>Third Homework w11d03</h1>
<h2>Explain what Index New, Create and Show Routes Do </h2>

Index - displays the list of elements like a table of contents or links to other parts of the website.
```js
app.get('/<name>', (req, res) => {
    // Finds and displays the data 
    nameOfElement.find({}, (err, findParameter)) => {
        if {
            // Message if there's a error
        } else {
            // Render Index page
        }
    }
})
```

New - displays a site or page where the visitor can create a new entry with some amount of information. 
```js
app.get('/<name>/new', (req, res) => {
    // Render a page that allows the visitor to create an entry
    res.render('<name/New')
})
```

Create - It's an action where the visitor creates a new entry.
```js
app.post('/<name>', (req, res) => {
    // req.body which contains all of our form Data we will get from the user
    nameOfElement.create(req.body, (err, createPrameter)) => {
    if {
        // Message if there's a error
    } else {
        // Render Index page
    }
    }
})
```

Show - displays the data that was either already there, created by the visitor or both.
```js
app.get('/<name>/:id', (req, res) => {
    // Finds specific element or object using findById and displays said element or object. 
        nameOfElement.findById(req.params.id, (err, parameter)) => {
        if {
            // Message if there's a error
        } else {
            // Render Show page
        }
    }
})
```