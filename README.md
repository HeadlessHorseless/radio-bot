#### This is radio bot
#### a controllable micspam bot created by [Headless](https://steamcommunity.com/id/HeadlessHorselessHorseman/)
#### original concept came from the "Remote Controlled Bot" idea (a bot that you can control via chat commands, i never got to finishing the idea and got left with Radio Bot)

## to get started here are some commands:
- !play (yt url / title)  --can take a few minutes depending on how long the video is (Download speed is usually about 2MB/s but can drop to 0.1MB/s) (sometimes problems can occour on certain videos (sometimes its old videos sometimes its really random or sometimes the bot cant even find the video)) You also have the option to manually review a video by doing "!play (title) manual review" which tends to have slower results but its more accurate for title
- !stop                         --stops the bot from micspamming
- !skip                         --skips the previous play request
- !help                         --the bot explains this one for you
- !earrapeify                   --makes the current song become earrape (Joke feature)
- !partyleader                  --gives you party leader role (ONLY WORKS WHEN IN BOT'S PARTY)
- !votelogs                     --toggles the vote logging feature (basically shows you who votes yes or no) (default is on) (Only takes effect when in party)
- !db (59-107)                  --How loud or quiet the current song should be (can be used to reset the earrapeify command) (default is 86 (works best))
- !current                      --Displays the current song
- !spin (-30 - +30)             --how fast the bot spins (it is possible to go beyond that (up to 100) but default maximium is 30 EDIT: Due to a rewrite i cannot go over 30 anymore)
- !leave                        --Makes the bot leave
- !killbind                     --killbinds
- !queue (map name)             --makes the bot queue for a map (put no map for the bot to queue via preset (all maps)) (works best when in bot's party)
- !aa (settings)                --Changes the AA (SpinBot) (Overrides the !spin command) (leave blank for random)
- !kick (player)                --Need someone to kick a bot but you are on cooldown? Well we got the feature just for you!
- !class (classname)            --Tired of a spinning scout? maybe try a medic or a soldier. Changes the class of the bot
- !ping                         --If the bot is ignoring your requests do this command for the bot to respond, if no response wait a couple of minutes
- !medicbot                     --Makes the bot switch to medic and follow you (the bot can sometimes lock onto other teammates but the beam will stay on you) DISABLED FOR NOW DUE TO BUGS
- !dlspeed                      --checks the current download speed (Can be inaccurate)
- !ignoreme                     --sets you on the bot ignore list (useless if you are friend with bot) (due to the fact that headlessbots and lodders use the exact same cheat you can use this for free headlessbot and lodders immunity)
- !sniperbot                    --makes the bot switch to sniper and do bot things (might get the bot kicked) (Due to a rewrite this feature is rather broken and instead of using nav meshes it now uses followbot)
- !addfriend (name)             --The bot will automaticly add the given player as a friend (Useful if someone cannot add the bot) Alternatively you can send the command without a name and it will add you instead
- !partycrash                   --crashes everyone in the party (joke feature) (i genuinely cannot tell if this even works or not)
- !playlist (playlist name)     --plays either the entire bot playlist (requests and default) or a specific one (found here) (EDIT: Due to me moving every single sound file i had every playlist is diffrent now)
- !rejoin                       --makes the bot rejoin after someone uses !leave (requires a party member to be ingame)
- !name                         --changes the name of the bot !!!THIS IS PATCHED!!!
- !joinserver (server ip)       --makes the bot join a server (I'd like it if you keep the bot away from community servers 99% of the time (so the bot doesnt get banned, the bot will not accept !sniperbot/!medicbot requests on community servers) (prefix also changes to ? example: ?play))
- !chatspam (option)            --makes the bot spam chat from default presets (Accepted presets: lmaobox, cathook, fedoraware) (request)
- !avatar (image link)          --changes the pfp of the bot (use !avatar default to return to the default)
- !playback                     --This feature will cause the bot to play the entire current playlist from the current song (Disabling looping)
- !screenshot (upload?)         --another way to clog up my ssd! Makes a screenshot from the current pov of the bot (if it should be uploaded do "!screenshot upload")
- !followbot                    --Makes the bot follow someone (crashes quite a lot less than at first)
- !noisespam (noisemaker)  --Spams the selected noisemaker (Currently the bot only has the vuvuzela)
- .
-
- !!If you type a command that doesnt exist (example: !hlep , !db 48) the bot will instead send an error!!

## other stuff
- total amount of radio bots: 1 Active 2 Total (Second one is the original which is now known as LoD)
- once VAC Banned the bot(s) will use Doeshotter's VAC Bypass to get around the ban (The bot might get kicked midway through the match when VAC decides to wake up)
- The default song the bot plays upon joining is always That's Life
- The bot doesnt leave spawn unless it has to and will most likely start spinning just cause
- The bot can also call votekicks on other bots
- You are free to add the bot to your party whenever (if the bot does not respond at all to your invite it either means the bot has blacklisted you or its already in a party (the bot will keep on thinking its in a party when the bot gets removed))
- commands are also compatible in party chat but take longer to respond
- The bot will requeue once the match is considered "dead" (bot filled matches or empty matches)
- The bot saves every song you request straight to this repository's release section
- every song saved into this repository does not need to download them so switching is almost instant
- The bot's region is EU (specificly DE)
- If the bot is online and not seemingly doing anything it means either i logged into the bot to check on stuff or the bot is prepping to launch the game
- The bot will automaticly stop micspamming upon votekick to avoid needing voicetoggle to be run manually

## List of AA Settings
- Up
- Down
- Zero
- Random
- Fake Up
- Fake Down
- Right
- Left
- Backwards
- Spin
- Edge
- On Hurt
- !NEW Section!
- Custom Up/Down (-89 to +89)
- Jitter
- Half up
- Custom Yaw (-180 to +180)
- Invert

#### Presets:
- default
- hvh
- spin
- too much caffine
- UpSpin
- none
#### Playlists:
- Default
- helf lief (Includes a lot of additional crap)
- micspam (New version of my other bots micspam)
- lodbot (Includes Only Earrapey sounds)
- gamer (LoDDers Micspam Squad Playlist)
- forlodders (For LoDDers bots as the name implies)
- Oanitic Bot (Playlist made for Oanitic bots)
- Radio Bot V2 (new default)
- 
> if you want to either request a new feature or just want to talk to me my discord is Headless#4855
> the bot's base is NOT avalible for download anywhere.
> however all you need is an undetected cheat base, a p2p account and some programming (i had to make 2 versions of this for all 3 methods of communication to the bot such as steam chat (js) and party chat + ingame chat (c++))
