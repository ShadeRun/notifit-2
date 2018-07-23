# notifit-2
notifIt version 2 (https://github.com/naoxink/notifIt)

# Why notifit 2?
- [x] No dependencies
- [x] Simple
- [x] Quick setup
- [x] Customizable
- [x] Size less than 4kb

> Note: `notif_prompt` and `notif_confirm` are not included yet.

# How do I use it?
It's quite simple, you only have to include the `.js` and `.css` files in your HTML.
```html
<link rel="stylesheet" href="notifit.min.css">
```
and
```html
<script src="notifit.min.js"></script>
```
```javascript
var myNotification = notif({
  'type': 'success',
  'msg': 'Hello world! This is notifit 2!'
})
```

# Available options
Key|Value type|Required|Options|Description
---|---|---|---|---
type|`string`|No|success, error, info, warning|Notification type (color)
msg|`string`|No||Message you want to display
position|`string`|No|left, center, right|Position in the top of the document
opacity|`number`|No||Notification opacity
zindex|`number`|No||Personal z-index
callback|`function`|No||Function that is executed when notification get dismissed
clickable|`boolean`|No|true, false|Allows to click the notification without dismiss it
