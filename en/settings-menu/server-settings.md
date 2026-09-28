---
description: Server-specific system settings
---

# ⚙️ Server Settings

## Bot Language

Starbot is available in <mark style="color:$primary;">English</mark> & <mark style="color:$primary;">Japanese</mark>. This is the language that the bot will use for public messages within the server.

***

## Special Roles

<table><thead><tr><th width="161.20001220703125">Role</th><th>Usage</th></tr></thead><tbody><tr><td><mark style="color:$primary;">🤖 Bot Role</mark></td><td>Automatically assigned when a bot joins, necessary for bots to have correct permissions in Starbot temporary voice channels</td></tr><tr><td><mark style="color:$primary;">🌟 Entry Role</mark></td><td>Automatically assigned when a user joins, separate from Lv. 0 role</td></tr></tbody></table>

***

## Item Settings

### Item Effect Messages

Items that do not affect other users will not show public messages. Items that **do**, will by default show messages in the channel that the interaction was in.

By setting a specific channel, all inter-user item interaction messages will be sent to that channel.

### Troll Items

These are items that allow users to bypass certain permissions temporarily. For example, there is an item that allows the user to randomly disconnect one user in the voice channel. These are **disabled by default**.

{% hint style="warning" %}
Enabling this is not recommended for larger, public servers unless a little chaos is okay! Items must be obtained within Starbot's economy/item system in order to be used. <mark style="color:$primary;">Coins</mark> are **global**, while <mark style="color:$primary;">items</mark> are **per-server**.
{% endhint %}

