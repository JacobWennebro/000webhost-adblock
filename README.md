# 000webhost adblock
Super simple script for 000Webhost to get their advertisement off your site.

![Advertisement](https://i.imgur.com/9LeNT3X.png)

```javascript
document.querySelector('img[alt="www.000webhost.com"]').parentElement.parentElement.remove()
```
