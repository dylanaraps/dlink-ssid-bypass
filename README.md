# dlink-ssid-bypass
Bypass SSID validation on D-Link DSL-2750B

## Instructions

On the pages that allow you to set the SSID, paste this into the console and click apply.

```javascript
encodeUrl = function() { SSID.value = "YOURVALUEHERE"; return SSID.value; }
```
