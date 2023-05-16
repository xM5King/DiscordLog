سكربت يسهل لك انشاء لوق في اي سكربت بسهولة
# DiscordLog for FiveM

## Description

DiscordLog is a basic resource for making send log to "Discord App"

## Usage

### Client Side

TriggerServerEvent("Smart-Logs:CreateLog", {
    name = "name",
    title = "title",
    color = "green",
    message = "message"
})

### Server Side

TriggerEvent("Smart-Logs:CreateLog", {
    name = "name",
    title = "title",
    color = "green",
    message = "message"
})
