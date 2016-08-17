<h2>Webpack: Multiple entry points</h2>

``` javascript
{
    entry: {
        shopping: ["./homepage.js", "./product.js", "./listing.js"],
        login: ["./signup.js", "login.js"]
    },
    output: {
        path: path.join(__dirname, "dist"),
        filename: "[name].entry.js"
    }
}
```
