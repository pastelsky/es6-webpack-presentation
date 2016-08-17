## Nested Callbacks

```javascript
$.get(url, function(data) {

    $.getJSON(url2, function(data) {

      $.post(url3, function(data) {

          doSomethingInteresting();

          $.get(url4, function(data) {
              // All done.
          });

      });

    });
    
});
```
