# Yttrium Light+

Yttrium Light+ — Bedwars-focused build (games `6872265039` and `6872274481`) with a polished, glowing GUI.

## Execution
```lua
script_key = "KEY-HERE"; loadstring(game:HttpGet('https://raw.githubusercontent.com/Yer1Yah/YttriumLightPlus/main/init.lua'), 'init.lua')({})
```

## Setup
Hosted at github.com/Yer1Yah/YttriumLightPlus (must be a PUBLIC repo).

## GUI
Open **GUI settings** to tune the white glow outline: *Glow outline*, *Glow speed*, *Glow intensity*.

## Independence
Yttrium Light+ only downloads files from your own repo (`Yer1Yah/YttriumLightPlus`).
Removed: the public-configs server, the remote whitelist/command system, the IP-geolocation lookup,
and the Discord invite/RPC hooks. The only other endpoint is Roblox's own server-list API used by the server-hop features.
