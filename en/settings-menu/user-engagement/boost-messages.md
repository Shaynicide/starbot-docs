---
description: Send a message when a new booster boosts the server
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# 🚀 Boost Messages

When enabled, you can send a message to a specified channel when someone **newly** boosts the server. The message can use variables.

<table><thead><tr><th width="173.199951171875">Variable</th><th>Result</th></tr></thead><tbody><tr><td><mark style="color:$primary;">!USER!</mark></td><td>The user as a <mark style="color:$primary;">@mention</mark></td></tr><tr><td><mark style="color:$primary;">!SERVER!</mark></td><td>The server's name</td></tr><tr><td><mark style="color:$primary;">!COUNT!</mark></td><td>The server's current number of boosts</td></tr><tr><td><mark style="color:$primary;">!LEVEL!</mark></td><td>The server's current boost level</td></tr></tbody></table>

{% hint style="warning" %}
Boost messages will not be sent if the user was already boosting the server.
{% endhint %}
