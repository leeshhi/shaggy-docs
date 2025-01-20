?> All commands here require `suggestion` to have been used and set in order to work.

<!--![Suggestions](_images/suggestions.png ':size=75%')-->

## Settings
?> `suggestion-limit` This option is optimal and turned off by default.
<!-- tabs:start -->
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | -----------------------------------------------------------------------------                      
**suggestion enable** \[channel]<br><span class="user-permissions">Administrator</span> | `/settings suggestion enable #suggestions` | Sets a channel as the suggestions channel.
**suggestion limit** \<amount><br><span class="user-permissions">Administrator</span> | `/settings suggestion limit 5` | The amount of votes difference required to change the embed color to red/green.
**suggestion duration** \<duration><br><span class="user-permissions">Administrator</span> | `/settings suggestion duration 14d` | The length until a suggestion is automatically closed is 7 days by default.
**suggestion decisions** \<type> [channel]<br><span class="user-permissions">Administrator</span> | `/settings suggestion decisions aprove #suggest` | Lets you split the actions of a suggestion into various channels. [Suggestion Decisions](https://docs.shag.gg/#/suggestions?id=suggestion-decisions)
**suggestion disable** <br><span class="user-permissions">Administrator</span> | `/settings suggestion disable` | Turns the entire suggestions system off.
<!-- tabs:end -->

## Making Suggestions
?> Should be public, but can be limited to a certain channel.
<!-- tabs:start -->                                                    
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**suggest** \<content> | `/suggest make vc`| Creates a suggestion.                                   
<!-- tabs:end -->

## Suggestion Decisions
!> The default permissions for who can execute this command should be set independently in the server settings, note the bot welcome message!
<!-- tabs:start -->     
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**suggestion approve** \<id> <reason> | `/suggestion approve 1 aproved` | Approves a suggestion.                    
**suggestion deny** \<id> <reason> | `/suggestion deny 4 spam` | Denies a suggestion.                       
**suggestion consider** \<id> <reason> | `/suggestion consider 5 consider` | Marks a suggestion as being considered. 
**suggestion implemented** \<id> <reason> | `/suggestion implemented 1 Added` | Marks a suggestion as implemented.
<!-- tabs:end -->
