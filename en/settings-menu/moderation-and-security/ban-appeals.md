---
description: Allow users to appeal their bans
---

# 📝 Ban Appeals

{% hint style="danger" %}
This feature is disabled by default and must be manually set up!
{% endhint %}

## Overview

This can be enabled (or disabled) by setting (or removing) an appeal channel.

If enabled, users that have been banned from the server will be given the option to use the command  `/banappeal` to write an appeal that will be sent to a channel specified in these settings.

Users cannot unsend, modify, or resend an appeal until the original appeal has been responded to. (In case of accidental appeal deletion, they will be able to send a new appeal.

{% hint style="warning" %}
Enabling this feature will cause Starbot to automatically DM the user an appeal button upon ban.
{% endhint %}

***

## Settings

Moderators can set <mark style="color:$primary;">the channel to send the appeals to</mark> (appeals will be rejected if a proper channel with the correct permissions is not set) and a <mark style="color:$primary;">cooldown</mark> (the default setting is no cooldown) for how long after the last appeal until a user can appeal again.

***

## Process

The user will be shown the reason for their ban (via audit log) and be able to make an appeal by filling in a form provided by the bot. The appeal information is sent to a specified channel with the original <mark style="color:$primary;">ban reason, their appeal content, and the option to approve or reject the appeal</mark>.

For both cases, a moderator must write a response which will be sent via DM to the user.&#x20;

In case of <mark style="color:$success;">approval</mark>, the ban will be automatically removed.
