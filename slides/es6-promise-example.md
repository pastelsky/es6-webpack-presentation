<h2>Promises</h2>

 ```javascript
  spree.auth
        // signup user
        .signup()
        // then, sign him in
        .then(spree.auth.login)
        // take him back where he came from
        .then(redirectToHome)
        // hooray!
        .then(celebrate)
        // oops.
        .catch(showError)
 ```
