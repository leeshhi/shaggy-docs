?> All commands here require `suggestion` to have been used and set in order to work.

<!--![Suggestions](_images/suggestions.png ':size=75%')-->

## Settings

?> `suggestion-limit` This option is optimal and turned off by default.
<!-- tabs:start -->
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | -----------------------------------------------------------------------------                      
**suggestion enable** [channel=suggestions]<br><span class="user-permissions">Administrator</span> | `/settings suggestion enable channel:#suggestions` | Sets a channel as the suggestions channel.
**suggestion limit** \<limit><br><span class="user-permissions">Administrator</span> | `/settings suggestion limit 5` | The amount of votes difference required to change the embed color to red/green.
**suggestion duration** \<limit><br><span class="user-permissions">Administrator</span> | `/settings suggestion duration 14d` | The length until a suggestion is automatically closed is 7 days by default.
**suggestion decisions** \<limit><br><span class="user-permissions">Administrator</span> | `/settings suggestion decisions aprove #suggest` | Lets you split the actions of a suggestion into various channels. [Suggestion Decisions](https://docs.joink.xyz/#/suggestions?id=suggestion-decisions)
**suggestion disable** \<limit><br><span class="user-permissions">Administrator</span> | `/settings suggestion disable` | Turns the entire suggestions system off.
<!-- tabs:end -->

## Making Suggestions
<!-- tabs:start -->                                                    
<!-- tab:Slash Commands -->
Anyone can use the `suggest` command to make suggestions.

Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**suggest** \<content> | `/suggest make vc`| Creates a suggestion.                                   
<!-- tabs:end -->

## Suggestion Decisions
<!-- tabs:start -->     
!> The default permissions for who can execute this command should be set independently in the server settings, note the bot welcome message!
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**suggestion approve** \<suggestionid> [reason] | `/suggestion approve 3` | Approves a suggestion.                    
**suggestion deny** \<suggestionid> [reason] | `/suggestion deny 4 spam` | Denies a suggestion.                       
**suggestion consider** \<suggestionid> [reason] | `/suggestion consider 5` | Marks a suggestion as being considered. 
**suggestion implemented** \<suggestionid> [reason] | `/suggestion implemented 1 Added` | Marks a suggestion as implemented.
<!-- tabs:end -->
