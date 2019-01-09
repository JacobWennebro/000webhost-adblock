# 000webhost adblock
Super simple script for 000Webhost to get their advertisement off your site.

![Advertisement](https://i.gyazo.com/36c65c10daa76b7d15726cf910a06f85.gif)

```javascript
document.querySelector('img[alt="www.000webhost.com"]').parentElement.parentElement.remove()
```
