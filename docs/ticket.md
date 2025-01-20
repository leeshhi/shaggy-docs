?> This feature is currently in open beta so expect frequent changes and updates.<br>Check booth command types below.

## Settings
<!-- tabs:start -->

<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**ticket setup** <br><span class="user-permissions">Administrator</span> | `/settings ticket setup #tickets` | Sets the category for new tickets.
**ticket limit** <br><span class="user-permissions">Administrator</span> | `/settings ticket limit 5` | Sets the max open ticket amount per user.
**ticket disable** <br><span class="user-permissions">Administrator</span> | `/settings disable` | Disables the ticket-system.
<!-- tabs:end -->


## Ticket Controls

<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**ticket add** <br><span class="user-permissions">Administrator</span> | `/ticket add @Shaggy` | Allows you to add users and/or roles in a ticket.
**ticket remove** <br><span class="user-permissions">Administrator</span> | `/ticket remove @Shaggy` | Allows you to remove users and/or roles in a ticket.
<!-- tabs:end -->


## Create Ticket
<!-- tabs:start -->

<!-- tab:Prefix Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | ----------------------------------------------------------------------------- 
**m?ticket** [channel=current]<br><span class="user-permissions">Administrator</span> | `m?ticket` | Creates the ticket in the channel you are sending the message to.
