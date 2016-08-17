## Nested Callbacks

```javascript

spree.auth.signup(function () {
    spree.auth.login(function() {
        //handle success
        redirect();
    },  function() {
          // handle failure
          showError();
        })
    },
    function() {
        // handle failure
        showError();
})
```
