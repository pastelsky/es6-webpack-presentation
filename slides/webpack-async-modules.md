<h2>Webpack Async modules</h2>

```javascript
// Listing.jsx

/**
* Compares two or more products
* from the same family
*/
openProductComparator() {

System.import("../product-comparer.js")
// dependency load succeeded
.then(compareProducts)
// dependency load failed
.catch(() => {
throw new Error("Product comparator load failed.")
})

//*
```
