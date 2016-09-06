# Utility Commands


### Broadcaster Command

   **Command :** !broadcaster <name>  
   **Description :** Sets who the current Broadcaster is on TheRobAndDanShow.  Assists with the !mods command.  


### Game Command

   **Command :** !game  
   **Description :** Announce the current game name.  Based on the Twitch API.  RADBot will auto-announce the game name when she detects a change.  


### Mods Command

   **Command :** !mods  
   **Alias Commands:** !modpack  
   **Description :** Announce a URL to the current mods (Google Doc URL).  Will use the currently set !broadcaster and game name to determine the proper URL.  URL is set via !savemod  


### SaveMod Command

   **Command :** !savemod <url to google doc for mod list>  
   **Alias Commands :** !savemods, !editmod, !editmods, !addmod, !addmods  
   **Description :** Saves/Edits the current Google Doc URL for the current mod list.  
   **IMPORTANT :** The game MUST be set in the Twitch API/Dashboard AND the !broadcaster who uses the mods must be set BEFORE using this command.  If the game name is being set, please allow RADBot to announce the game name change in chat before using this command.  API changes can take up to 2 minutes.  


### Uptime Command

   **Command :** !uptime  
   **Alias Commands :** !time  
   **Description :** Announce how long the stream has been live.  
   **IMPORTANT :** RADBot may at times, based on her current Mood rating, may output a trolly response, followed by the uptime.  

