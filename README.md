# JamesBot - Support
JamesBot allows you to manage your server and add content to it.

For support and feature requests join our discord server: https://discord.gg/RFsgJcN

[Add bot to your server](https://discord.com/api/oauth2/authorize?client_id=425377070525317120&permissions=306048080&scope=bot)

## Commands

The default prefix for JamesBot is `!!` you can customise it as desired. Later you will be able to @mention the bot to launch command instead of using his prefix.

This is a list of commands you can use. You can get more info about a specific command by using `!!help <command>` (e.g. `!!help leaderboard`)

Arguments are listed after the command. Bracket [] indicate an optional argument. (e.g. `[reason]` means the reason is optional)

### Configuration

**This section is specially to understand each config settings**


* `!!config -sysNotif` Make you able to enable/disable bot notification
* `!!config -modo @role` Make you able to set Moderator role *(Only 1 role per server right now)*
* `!!config -admin @role` Make you able to set Administrator role *(Only 1 role per server right now)*

### Moderation

* `!!clear amount` Clear an amount of messages
* `!!mku (-m) message|message_ID ` Put your message into an embed *(Use -m if you use a message ID instead of a string)*
* `!!prefix (-edit/-del) prefix` Set a new prefix for the bot on your server *(-del reset to default prefix)*
* `!!poll -amount_of_reaction text` Make a new poll with a custom amount of reaction
* `!!report -type @user reason` Report a user on the server. **This command can take several properties check them below**
```.env
# Command usable by all users
!!report -type @user reason

# Command usable by bot moderator or higher
!!report -show @user|report_Id 

# Command usable by bot Administrator or higher
!!report -del report_Id
```

### Social

* `!!bang @user` Wow ... That's nice to 🔫 your friends !
* `!!kiss @user` Mooooh so cute !
* `!!slap @use` Ouch that had to hurt
* `!!claim` Later you will be able to claim prizes

### Server

* `!!info` Gives you infos about the server
* `!!stats` Gives you some stats about the bot

### User

* `!!rank ((@user)` See your xp and your rank on the server
* `!!leaderboard (@user)` Get a clean and nice leaderboard of the 5 first users on this server and it gives you your rank
* `!!ping` Wow ... that's a revolution !!!
* `!!help (command)` A little bit of help

## More about the bot

Invite JamesBot to your guild band grant the necessary permissions. These permissions can change in the future while adding features to the bot. You will be notified in case of this append.

### Webpanel
The dashboard is being worked on. If you would like to get access to it, join the Discord Support server and get BETA access when this dashboard will be release.

### Get additional help

You can get more help on the official [github page](https://github.com/James-Bot-Freezlex/JamesBot-Support). You can also ask for a feature that you want to add on the bot also on this page, just open an issue and give the more detailed info about you idea if you are familiar with this or go on the official [discord server](https://discord.gg/RFsgJcN).

## **Please keep in mind than i'm a student and then i'm developing this bot on my free time**
