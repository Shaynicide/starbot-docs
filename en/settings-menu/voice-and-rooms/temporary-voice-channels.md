---
description: >-
  You can create channels that when joined, create a new temporary voice channel
  (room) and move the user to it. This room will automatically be deleted when
  there are no (human) users remaining.
---

# ⏳ Temporary Voice Channels

## Room Creation

### Room Owner

The person who created the room will be given channel editing permissions (they can change the channel name, user limit, etc.) and the ability to use `/room`. This command allows them to easily transfer room ownership, hide/show the room, invite others to a hidden room, or kick/block specific users from the room.

When the owner leaves, anyone in the room can claim ownership with `/room`.

### Blocked Users

Users that have been blocked by the the creator using `/block` will not be able to see the created room by default.

### Audio Quality

You can set the default audio quality to be used when a room is a created. This is limited by the server's <mark style="color:pink;">boost level</mark>.

### Room Names

Room names can use variables.

<table><thead><tr><th width="218.00006103515625">Variable</th><th>Result</th></tr></thead><tbody><tr><td><mark style="color:$primary;">!NUM!</mark></td><td>An incrementing room number</td></tr><tr><td><mark style="color:$primary;">!NUM2!</mark></td><td>The same as above, but with encircled numbers (28 → ②⑧)</td></tr><tr><td><mark style="color:$primary;">!ALPH!</mark></td><td>The same as above, but with alphabet (28 → AB)</td></tr><tr><td><mark style="color:$primary;">!NAME!</mark></td><td>The creator's display name</td></tr><tr><td><mark style="color:$primary;">!USER!</mark></td><td>The user's username</td></tr><tr><td><mark style="color:$primary;">!EMOJI!</mark></td><td>A random emoji</td></tr></tbody></table>

{% hint style="info" %}
When the previous character is full-width, the following room number will also be full-width.
{% endhint %}

***

## Member-Only Chat

Only the people inside the room can use the chat, and outsiders cannot see the chat history unless they are focused on the channel, and they are unable to see any messages from before they focused the channel.

***

## Fallback Channels

You can specify extra channels to be used **only** when Starbot is offline. If Starbot is online and functional, these channels will automatically kick users upon join.
