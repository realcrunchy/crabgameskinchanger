<h1 align="center">Crab Game Skin Changer 👋</h1>

Crab Game Skin Changer for version 1.362 of the game!

![ScreenShot2](https://cdn.discordapp.com/attachments/1036859677151072339/1038337400356749322/Screenshot_126.png)
![ScreenShot](https://cdn.discordapp.com/attachments/1038007561431031818/1038067285446901800/Screenshot_120.png) 

## Setup
Move these files into Crab Game_Data\Plugins\x86_64 and launch the game normally over Steam or the .exe
If Windows asks you to replace steam_api64_net.dll you agree with "yes"
Basically you just replace steam_api64_net.dll and add the steam_setting
folder to the 86x_64 Folder.
[!] By default in the custom broadcast text file are already the steam connections filled in but you need to activate them manually ingame. If you activate them you know you are breaking ToS of Steam rn. I have nothing to do with your illegal activaty [!]

## Config

- ~~Change your Username in \Plugins\x86_64\steam_settings\force_account_name.txt~~
- Change your Username ingame by pressing Shift + TAB | **THIS ONLY WORKS IF YOU DONT RUN THE GAME FROM STEAM!**
- Add your own items in items.json
- Edit item quantity in default_items.json

The items.json syntax is simple, you SHOULD validate your .json file before trying to run your game or you won't have any item in your inventory. Just look for "online json validator" on your web brower to valide your file.
You can use https://steamdb.info/app/1782210/items/ to list items and attributes they have and put them into your .json.
Keep in mind that some item are not valid to have in your inventory. For example, in Crab Game all items over item_id 50000 will make your game crash.
items.json should contain all the item definitions for the game, default_items.json is the quantity of each item that you want a user to have initially in their inventory. By default the user will have the items that are on the screenshot above.


## What's working ?

Everything! It now connects to real Steam Servers with your cheated inventory have fun! :D


## ToDo

- Open Crates
- Profile Pictures
- Adding custom colors
- Adding Shinys



#### Need help or you can help? Join [our Discord support server](https://discord.gg/RJSVxe9MP9)




## Authors

👤 **Raphael** (main developer)

* Github: [@raphaelreal](https://github.com/raphaelreal)
* Discord: raphael#0999

Special thanks to:
- Goldberg

## Show your support

Give a ⭐️ if this project helped you!

## Updates

## V1.2
05.11.2022 05:34:
- Added steam_appid.txt to steam_settings
- Added Ingame Name Changer
- Removed FORCE Text files because we dont need them anymore

## V1.21
05.11.2022 07:20
- Added all hairs to `items.json` and `default_items.json` in default color
- All informations in `items.json` and `default_items.json` are sorted in correct order from now on

## V1.22
12.11.2022 13:39
- Added custom_broadcast with Steam Servers so you can join real crab game lobby with cheated items
