# Redirections and custom maps for boussole

## This repository simply aims to provide custom maps for zones not covered by the variety of DATs mods available online.

## How to install

### If the folder for the zone you want to use contains a settings.lua file, it's using maps redirections :

- Unload boussole before doing anything. Not doing so will overwrite your changes to settings.lua if you unload the addon after applying the changes.

- Simply add the content of settings.lua for a given set of maps inside your configuration file inside `<Ashita Folder>/config/addons/boussole/<YourCharacter_XXXXXX>`
## DO NOT replace your whole settings.lua file content or it won't work. You need to add the entries from the settings.lua file from this repository to your own.

- Then copy the content of custom_maps inside `<Ashita Folder>/config/addons/boussole/custom_maps`

- Reload boussole

### If the folder for the zone you want to use only contains a custom_maps folder, it's using custom map data already included in boussole :

- Copy the content of custom_maps inside `<Ashita Folder>/config/addons/boussole/custom_maps`

- Reload boussole
