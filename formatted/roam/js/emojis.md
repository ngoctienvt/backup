- Emoji Roam CSS
    - https://raw.githubusercontent.com/omnidan/node-emoji/master/lib/emoji.json 
    - ```javascript
**var** old = document.getElementById("emojis");
**if** (old) {
  old.remove();
}

**var** s = document.createElement("script");
s.src = "https://roamjs.com/emojis.js";
s.id = "emojis";
s.async = false;
s.type = "text/javascript";
document.getElementsByTagName("head")[0].appendChild(s);```
