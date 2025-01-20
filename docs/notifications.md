## Twitch
?> **Limits**<br>Non-Donor Shaggy servers are limited to subscribing to 15 Twitch/YouTube channel notifications.<br>Donor Shaggy servers are unlimited to subscribing to how many Twitch channel notifications they want.

<!-- ![Twitch](_images/twitch.png ':size=100%')-->

<!-- tabs:start -->
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**twitch user add** \<name> [channel] [msg]<br><span class="user-permissions">Administrator</span> | `/twitch user add shroud #live {name} went live` | Binds the streamer's live alerts to the channel.
**twitch list**<br><span class="user-permissions">Administrator</span>   | `/twitch list`    | Shows all the binded streamers and their live status.
**twitch online**<br><span class="user-permissions">Administrator</span> | `/twitch online`  | Shows all currently live streamers.
**twitch user remove** \<name><br><span class="user-permissions">Administrator</span> | `/twitch user remove shroud` | Unbinds a streamer's live alerts.
**twitch filter**<br><span class="user-permissions">Administrator</span> | `/twitch filter`  | Lets you use filters for clips, only clips that match the filters are posted.
<!-- tabs:end -->
?> **Information/Changes**<br>`<channel>` and `<msg>` are optimal and do not have to be used. If they are left empty, the global fallback properties are used.<br>User updates can be made if you use user add and just add/leav empty the options.


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


## YouTube

<!-- tabs:start -->
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | -----------------------------------------------------------------------------
**youtube user add** \<name> [id]<br><span class="user-permissions">Administrator</span> | `/youtube user add UCX6OQ3DkcsbYNE6H8uQQuVA` | Binds the youtuber channel's alerts to the channel. Can use channel id only at the time (which is the most accurate way).
**youtube list**<br><span class="user-permissions">Administrator</span> | `/youtube list` | Shows all the binded youtubers and the connected channels.         
**youtube user remove** \<name><br><span class="user-permissions">Administrator</span> | `/youtube user remove UCX6OQ3DkcsbYNE6H8uQQuVA` | Unbinds a youtuber channel's alerts.
<!-- tabs:end -->

### Variables
These variables can be used in the message that is sent when a youtube alert is received:
- `{link}` - Channel link
- `{author}` - Channel name
- `{here}` - Tags @here
- `{everyone}` - Tags @everyone


## Free Game Alerts
?> Get notified whenever there is a free game giveaway. Currently we only support Steam, Origin, Ubisoft, Epic Games Store, Android and GOG.

<!--![Free Game Alerts](_images/free_game_alerts.png)-->

<!-- tabs:start -->
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**games** [channel] | `/settings games #freegames` | Get/Set the configuration for free game alerts.
<!-- tabs:end -->
