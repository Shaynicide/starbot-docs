---
description: Keep track of moderation actions in your server
---

# 📜 Moderation Logs

{% hint style="danger" %}
These features are disabled by default and must be manually set up!
{% endhint %}

## Log Types

Each log type can be sent to its own specific channel as a message.

<table><thead><tr><th width="186.79998779296875">Type</th><th></th></tr></thead><tbody><tr><td><mark style="color:yellow;">Warning</mark></td><td>Raising or lowering a user's warning level</td></tr><tr><td><mark style="color:$warning;">Timeout</mark></td><td>Timing out a user or removing their time</td></tr><tr><td><mark style="color:$danger;">Kick/Ban</mark></td><td>Kicking or banning a user</td></tr><tr><td><mark style="color:pink;">System</mark></td><td>Bot actions (such as anti-spam, XP resets, etc.)</td></tr></tbody></table>

***

## Master Log

You can specify a master log channel - when this is set, you can send a copy of each log (what to log can also be specified) to a single channel.

{% hint style="info" %}
When the above are specified, they will send a message. However, you can view the master log from the settings menu and filter by **user**, **mod,** or **action type**.
{% endhint %}
