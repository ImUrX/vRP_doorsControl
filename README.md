# vRP_doorsControl
Door control system. The doors are fully synchronized between the players and also retain their position until the resource reboots, this fork is just less russian
# Install
1. clone the repo with `git clone <link>` (the link is on the the big green button that says **Clone or download**)
2. add in server.cfg "start doors"
3. **CRASH YOUR SERVER??**
# Updating
Just `git pull` inside the plugin folder
# Keys
You can use group permissions or items (Keys) for access to doors control. Key on keyboard for control on default NUM4<hr/>
Default items (add in vrp/cfg/items.lua)<br/>
```lua
  ["key_pd_boss"] = {"🔑 Captain room", "", nil, 0.01},
  ["key_lspd"] = {"🔑 LSPD", "", nil, 0.01},
```

