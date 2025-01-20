## Giveaways
?> This feature is currently in open beta so expect frequent changes and updates.

<!-- tabs:start -->
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**giveaway create** \<duration> \<winners> \<prize> [host=none] [channel=current]<br><span class="user-permissions">Administrator</span> | `/giveaway create 10m 1 Nitro` | Creates a giveaway for the specified duration, number of winners, prize and optional channel which defaults to the channel that the command is used in.
**giveaway reroll** \<giveaway_id> [members...]<br><span class="user-permissions">Administrator</span> | `/giveaway reroll 23 @Shaggy` | Rerolls the giveaway with the specified giveaway id. Optionally, you can mention the members that should be excluded from the reroll.
**giveaway end** \<giveaway_id><br><span class="user-permissions">Administrator</span> | `/giveaway end 42` | Ends an ongoing giveaway prematurely. You will be asked if you want to announce winners or not.
**giveaway list** [choice=active]<br><span class="user-permissions">Administrator</span> | `/giveaway list inactive` | Shows the list of active/inactive giveaways.
**giveaway participants** \<giveaway_id><br><span class="user-permissions">Administrator</span> | `/giveaway participants 4` | Check the users that have participated in a particular giveaway.
<!-- tabs:end -->

### Giveaway Create Infos
These variables can be used in the giveaway create:
- `duration` - **Samples:** `10s` second(s), `1m` minute(s), `1h` hour(s), `1w` week(s)
- `winners` - How many people could win in this giveaway.
- `prize` - What can be won in this giveaway?
- `host` - Who hosts the giveaway? **Default: `NONE`** if you want a host to be shown, select a user accordingly.
- `channel` - By default the giveaway will be posted to the channel where the command is executed, if you want a specific channel without executing the command there, select this channel accordingly


## Polls
<!-- tabs:start -->
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**poll** \<question> [choices]<br><span class="user-permissions">Administrator</span>  | `/poll Is this nice?` | Creates a thumbs up-down poll where users vote with reactions. Use `\|` or `,` to separate the choices.
<!-- tabs:end -->

### Poll Create Infos
- `duration` - **Samples:** `10s` second(s), `1m` minute(s), `1h` hour(s), `1w` week(s)


## Verify
!> In order to use the Verify-system you have to set the verify role in settings!

<!-- tab:Prefix Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**m?verify** [channel=current]<br><span class="user-permissions">Administrator</span> | `m?verify` | Creates the Verifying captcha message.
