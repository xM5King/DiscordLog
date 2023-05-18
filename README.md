# DiscordLog for FiveM

## Description

DiscordLog is a basic resource for making send log to "Discord App"

### Description of the script
https://youtu.be/Y2ija7_yhls

## Usage

### Client Side
```lua
TriggerServerEvent("Smart-Logs:CreateLog", {
    name = "name",
    title = "title",
    color = "green",
    message = "message"
})
```
### Server Side
```lua
TriggerEvent("Smart-Logs:CreateLog", {
    name = "name",
    title = "title",
    color = "green",
    message = "message"
})
```

## Created By
```
Name: Mohammed
Discord: M5#0009
Discord Link: https://discord.gg/yBE3635T4p
```
