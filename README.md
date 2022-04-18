# nordvpn-polybar

A polybar extension for nordvpn users


# How to install

Install python module
```
pip install nordvpn-polybar
```


Add to polybar config
```
[module/vpn]
type = custom/script
exec = python3 -m nordvpn_polybar.main "{status} {city} {transfer}"
interval = 1
format-underline = #2196f3
click-left = nordvpn connect
click-right = nordvpn disconnect
```

# How to use

Left click the polybar item to connect to VPN
Right click the polybar item to disconnect