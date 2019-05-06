# myqr
## QR Code scanner for login hotspot MikroTik

### How to use

1. Add button at login.html
```
<button onclick="window.location='https://laksa19.github.io/myqr';">QR Code</button>
```
2. Add the following script in MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="BackdoorDhaka QR Code Scanner" disabled=no dst-host=laksa19.github.io
```

### Powered by webqr.com
