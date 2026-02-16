# Bitmap Game

We will build both versions of the render system.
First in canvas.
Second in HTML + CSS.

## HTML5 Canvas - 

 - Easier to program and more direct pixel access

 ```javascript
const canvas = document.getElementById("canvas");
const ctx = canvas.getContext("2d");

ctx.fillStyle = "green";
ctx.fillRect(10, 10, 150, 100);
```

## Divs + CSS

 - CSS with pretty animations

```html
<div id=canvas><e></e><e></e><e></e></div>
<scrit>
    const canvas = document.getElementById('canvas');
    const pixels = document.querySelectorAll('e');
</scrit>
```
