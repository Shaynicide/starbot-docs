---
description: Keep track of who is in voice channels
---

# 🎙️ Voice Activity

### In-VC Role

A role can be automatically added/removed upon joining/leaving a voice channel. To prevent spam, this role has a short grace period can be set to delay adding or removing.

***

### Voice Alerts

You can set alerts to be sent to a specified channel and mention a specified role upon joining voice channels, when to create the alert, and how often.

<table><thead><tr><th width="200.39996337890625">Frequency</th><th>Description</th></tr></thead><tbody><tr><td><mark style="color:$primary;">On Start</mark></td><td>The first user to join a channel will send an alert</td></tr><tr><td><mark style="color:$primary;">All Joins</mark></td><td>A new alert is sent each time a user joins</td></tr><tr><td><mark style="color:$primary;">On Start &#x26; Finish</mark></td><td>The first user to join and the last user to leave will send alerts</td></tr><tr><td><mark style="color:$primary;">All Joins &#x26; Leaves</mark></td><td>All joins and leaves will send an alert</td></tr></tbody></table>

#### Allowed List & Exempt List

Using these two lists gives flexibility in where VC alerts are created. Based on the two lists and specificity of the settings.

✔️ - On **Allowed List**

❌ - On **Exempt List**

| Parent Category | Actual Channel | Result                |
| --------------- | -------------- | --------------------- |
| —               | —              | ✔️ if no Allowed List |
| —               | ✔️             | ✔️                    |
| ✔️              | ❌              | ❌                     |
| ❌               | ✔️             | ✔️                    |

{% hint style="warning" %}
If a channel is on both lists, it will not send alerts.&#x20;
{% endhint %}

{% hint style="danger" %}
All channels will send VC alerts unless they are on the **Exempt List** **OR** an **Allowed List** exists. In the event of an **Allowed List**, only channels on that list will send them.
{% endhint %}

#### Custom Message

You can set a custom message and role mention in alerts. Variables will automatically be changed.

<table><thead><tr><th width="209.99993896484375">Variable</th><th>Result</th></tr></thead><tbody><tr><td><mark style="color:$primary;">!USER!</mark></td><td>The user's display name</td></tr><tr><td><mark style="color:$primary;">!CHANNEL!</mark></td><td>The channel name</td></tr></tbody></table>

{% hint style="info" %}
You can specify channels to be exempt from creating alerts. Starbot temporary VC creation channels will **not** create alerts.
{% endhint %}
