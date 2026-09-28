---
description: Keep your server protected against spam
---

# ⚔️ Anti-Spam

{% hint style="danger" %}
These features are disabled by default and must be manually set up!
{% endhint %}

## Detection & Response Levels

<mark style="color:$primary;">**Detection**</mark> <mark style="color:$primary;">**Level**</mark> - determines at what point to trigger a response.\
<mark style="color:$primary;">**Response Level**</mark> - determines length of timeout to give on trigger.

Once the threshold is met and spam is detected, the user's messages will be deleted and the user will be timed out based on the <mark style="color:$primary;">response level</mark>.

{% hint style="info" %}
Both can be set from levels <mark style="color:pink;">1 to 5</mark> - 1 being _very lenient_ and 5 being _very strict_.
{% endhint %}

If a log channel is set, it well be sent as a <mark style="color:$primary;">system log</mark>. You can also set a channel to send reports of each deleted message.

***

## Trap Role & Channel

When set up, any users that add the role or post in the channel will be automatically <mark style="color:$warning;">timed out</mark>, <mark style="color:red;">kicked</mark>, or <mark style="color:$danger;">banned</mark> from the server. This is useful for reducing spambots that join the server.
