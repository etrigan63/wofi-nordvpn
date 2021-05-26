# wofi-nordvpn
Port of rofi-nordvpn to wofi

I was looking for functionality offered by loiccoyle/rofi-nordvpn but for sway/waybar. 

I will add syntax here.

###waybar module
I wrote the following waybar module to use wofi-nordvpn.

```
"custom/vpn": {
        "format": " {}",
        "exec": "wofi-nordvpn -s",
        "interval": 10,
        "on-click": "wofi-nordvpn &"
},
```
