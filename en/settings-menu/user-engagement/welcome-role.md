---
description: A dynamic role used to mark new members
---

# 🔰 Welcome Role

A welcome role is used to differentiate newer members from regular server users. The role is automatically removed upon meeting any of the following criteria (values can be changed).

<table><thead><tr><th width="177.20001220703125"></th><th></th></tr></thead><tbody><tr><td><mark style="color:$primary;">Message Count</mark></td><td>Removed when a user has sent <mark style="color:$success;">X messages</mark></td></tr><tr><td><mark style="color:$primary;">Time in VC</mark></td><td>Removed when a user has participated in VC for <mark style="color:$success;">X hours</mark></td></tr><tr><td><mark style="color:$primary;">Time Since Join</mark></td><td>Removed when a user has been in the server for <mark style="color:$success;">X days</mark></td></tr></tbody></table>

{% hint style="info" %}
The criteria can be bypassed completely by using **Toggle Welcome Bypass** on a user.
{% endhint %}

***

### Member Pruning

You can specify a <mark style="color:$warning;">pruning period</mark> (in days), and when the **Prune Members** button is pressed, any members who still have the role after being in the server for the specified <mark style="color:$warning;">pruning period</mark> will be automatically <mark style="color:red;">kicked</mark> from the server.
