?> **Limits**<br>Non-Donor Shaggy servers are limited to subscribing to 15 Twitch channel notifications.<br>Donor Shaggy servers are unlimited to subscribing to how many Twitch channel notifications they want.

<!-- ![Twitch](_images/twitch.png ':size=100%')-->

<!-- tabs:start -->
## Settings
?> Twitch settings to setup twitch notifications.
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**settings twitch live** \[channel]<br><span class="user-permissions">Administrator</span> | `/settings twitch live #announcements` | Sets the default twitch notification channel.
**settings twitch clips** \[channel]<br><span class="user-permissions">Administrator</span> | `/settings twitch clips #announcements` | Sets the default twitch clips channel.
**settings twitch disable** <br><span class="user-permissions">Administrator</span> | `/settings twitch disable` | Turns off all twitch notifications.
<!-- tabs:end -->

<!-- tabs:start -->
## Commands
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**twitch user add** \<user><br><span class="user-permissions">Administrator</span> | `/twitch user add XYZ` | Turns on twitch notifications for user XYZ.
**twitch clips enable** \<user> [channel]<br><span class="user-permissions">Administrator</span> | `/twitch clips enable XYZ` | Turns on the clips for user XYZ.
**twitch clips disable** \<user> [channel]<br><span class="user-permissions">Administrator</span> | `/twitch clips disable XYZ` | Turns off the clips for user XYZ.
**twitch update message** \<user> <msg><br><span class="user-permissions">Administrator</span> | `/twitch update message XYZ message` | Lets you change the default live notification for user XYZ.
**twitch user add** \<user><br><span class="user-permissions">Administrator</span> | `/twitch user add XYZ` | Turns on twitch notifications for user XYZ.
**twitch list**<br><span class="user-permissions">Administrator</span>   | `/twitch list`    | Shows all the binded streamers and their live status.
**twitch online**<br><span class="user-permissions">Administrator</span> | `/twitch online`  | Shows all currently live streamers.
**twitch user remove** \<user><br><span class="user-permissions">Administrator</span> | `/twitch user remove shroud` | Unbinds a streamer's live alerts.
**twitch filter add** \<user> <type> <value><br><span class="user-permissions">Administrator</span> | `/twitch filter`  | Lets you apply certain filter functions to the clips.
**twitch filter remove** \<user> <type> <value><br><span class="user-permissions">Administrator</span> | `/twitch filter`  | Lets you remove certain filter functions to the clips.
<!-- tabs:end -->

### Extras
### Variables
These variables can be used in the message that is sent when a streamer goes live:
- `{link}` - Shows the stream link
- `{name}` - Shows the streamer's username
- `{game}` - SHows the Game being played
- `{here}` - Tags @here
- `{everyone}` - Tags @everyone
### Filters
?> If you don't want clips to be filtered, don't use filters, so all created clips will be posted.
These filters can be used to limit the clips that should be sent on Discord.
- `keyword` - Certain words must be included in the stream title.
- `user` - Clips from certain users are only posted.
- `category` - Only clips from certain categories will be posted.
- `length` - Minimum clip length, shorter clips will not be posted.
