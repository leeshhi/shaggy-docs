?> After you make a Starboard channel, your members can react to any message with a ⭐ `:star:` which counts as a vote to display that message as a post on the Starboard. Once the message gets enough reactions *(default are 6)*, Shaggy posts it onto the Starboard. By default, a user's reaction on their own post doesn't count.

<!-- ![Starboard Settings](_images/starboard_settings.png ':size=75%')-->

<!-- tabs:start -->                                   
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**stars setup** [channel=starboard]<br><span class="user-permissions">Manage Server</span> | `/settings stars setup #stars` | Sets up the Starboard for the server. Defaults to creating new channel named `#starboard`.
**stars limit** \<limit><br><span class="user-permissions">Manage Server</span> | `/settings stars limit 3` | Sets the amount of reactions required for a post to get posted on the Starboard.
**stars nsfw**<br><span class="user-permissions">Manage Server</span>    | `/settings stars nsfw`     | Toggles embedding images from starred messages in NSFW channels.
**stars self**<br><span class="user-permissions">Manage Server</span>    | `/settings stars self`     | Toggles being able to star your own posts.
**stars blacklist** \<channels><br><span class="user-permissions">Manage Server</span> | `/settings stars blacklist #staff` | Blocks channels from having their messages starred.
**stars unblacklist** \<channels><br><span class="user-permissions">Manage Server</span> | `/settings stars unblacklist #staff` | Unblocks channels from having their messages starred.
**stars config**<br><span class="user-permissions">Manage Server</span>  | `/settings stars config`   | View Starboard configuration for server.
**stars lock**<br><span class="user-permissions">Manage Server</span>    | `/settings stars lock`     | Locks the Starboard making it completely uninteractive.
**stars disable**<br><span class="user-permissions">Manage Server</span>  | `/settings stars disable`   | Removes a channel as starboard.

<!-- tabs:end -->
