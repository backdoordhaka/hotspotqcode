# myqr
## QR Code scanner for login hotspot MikroTik

### How to use

1. Add button at login.html
```
<button onclick="window.location='https://backdoordhaka.github.io/qcode';">QR Code</button>
```
2. Add the following script in MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="BackdoorDhaka QR Code Scanner" disabled=no dst-host=https://backdoordhaka.github.io
```

### Powered by KZ Tech Bangladesh
