### Ajaxload
---
http://www.ajaxload.info/

https://www.w3schools.com/jquery/jquery_ajax_load.asp

```js
$("button").click(function() {
  $("#div1").load("demo_test.txt", function(responseTxt, statusTxt, xhr){
    if(statusTxt == "success")
      alert("External content loaded successfully!");
    if(statusTxt == "error")
      alert("Error: " + xhr.status + ": " + xhr.statusText);
  });
});
```

```
```

```
```

