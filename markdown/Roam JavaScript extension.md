- {{[[roam/js]]}}
    - ```javascript
var old = document.getElementById("sort-references");
if (old) {
  old.remove();
}

var s = document.createElement("script");
s.src = "https://roamjs.com/sort-references.js";
s.id = "sort-references";
s.async = false;
s.type = "text/javascript";
document.getElementsByTagName("head")[0].appendChild(s);```
