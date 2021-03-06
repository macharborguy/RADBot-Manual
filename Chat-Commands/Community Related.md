# Community Commands



### Click2Tweet Command

- **Command :** `!ctt <optional hashtag>`  
- **Alias Commands:** `!tweet`  
- **Permissions :** Broadcaster, Mods  
- **Description :** Announce a Click2Tweet link in chat.  The optional #hashtag will be appended to the end.
   - **`<optional hashtag>`** may not be appended if the resulting CTT message would be longer than Twitter's maximum allowed characters per tweet.  

- **IMPORTANT 1 :** This command will NOT work if the stream is not live (confirmed via the TwitchAPI, so actual stream status may be delayed)  

### Links Command

- **Command :** `!links`  
- **Permissions :** Broadcaster, Mods  
- **Description :** Announce a list of Social Media, Donation and other R&D related links in chat.  These include Twitch, Twitter, Steam Group, WYKTV and others.  
- **IMPORTANT :** This command has a cooldown for Mods to prevent multiple uses of !links from going thru.  


### Add Regular Command

- **Command :** `!reg <twitch username>`  
- **Alias Commands :** `!addreg`, `!regadd`  
- **Permissions :** Broadcaster, Mods  
- **Description :** Assign "Regular" status to a twitch user.  



### Raid Command

- **Command :** `!raid <optional twitch username>`  
- **Alias Commands :** `!r`  
- **Permissions :** Broadcaster, Mods  
- **Description :** Announce a chat raid, the raiding channel's URL (if username is provided) and trigger the on-stream alert.  
- **IMPORTANT :** This command has a cooldown for Mods to prevent multiple uses of !raid from going thru.  


### Caster Command

- **Command :** `!caster <twitch username>`  
- **Alias Commands :** `!c`, `!s`, `!streamer`  
- **Permissions :** Broadcaster, Mods  
- **Description :** Announce another Broadcaster in chat.  Includes the Broadcaster's Twitch Channel URL and, if set on that Broadcaster's profile, the game they were last playing.  


### Points Command (SCIENCE!!!)

- **Command :** `!points`  
- **Alias Commands :** `!rank`, `!sciencepoints`  
- **Permissions :** Broadcaster, Mods  
- **Description :** Display the users current total Science Points.  