---
description: Settings for managing excessive alerts and pings
---

# 🔔 Ping Control

{% hint style="danger" %}
These features are disabled by default and must be manually set up!
{% endhint %}

## @everyone Control

When enabled and an **`@everyone`** mention is detected, the mention will be removed and the user will receive a <mark style="color:$warning;">timeout</mark>. The length can be adjusted from <mark style="color:$primary;">30 minutes</mark> to <mark style="color:$primary;">1 week</mark>.

{% hint style="info" %}
You can specify whitelisted roles.
{% endhint %}

{% hint style="warning" %}
Anti-spam measures (such as timeout) will take priority!
{% endhint %}

***

## Ghost Ping Alerts

Can be enabled to send an alert in-channel when someone sends a mention (ping) and deletes it. Applicable mentions types can be toggled individually.

<table><thead><tr><th width="217.20001220703125">Type</th><th></th></tr></thead><tbody><tr><td>@everyone / @here</td><td>Self-explanatory</td></tr><tr><td>Role Mentions</td><td>When a role is mentioned</td></tr><tr><td>User Mentions</td><td>When an individual is mentioned</td></tr></tbody></table>

{% hint style="info" %}
You can specify the detection length, a custom message, and whitelisted roles.
{% endhint %}

***

## Ghost Message Logs

When enabled, sends a log to the specified channel when someone sends a message and erases it within the specified timeframe.

{% hint style="info" %}
You can specify the detection length, the log channel, and whitelisted roles.
{% endhint %}
