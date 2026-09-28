---
description: Useful for lotteries and giveaways
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

# 🎉 Lotteries

Create custom lotteries/giveaways that users can opt-in to join. When the lottery is finished, the specified number of users will automatically be selected at random and notified in the specified channel.

### Number of Winners

The number of winners for a single lottery can be set anywhere from <mark style="color:$primary;">1-25 users</mark>.

### Allowed Roles

Who is allowed to participate can be specified upon creation.

<table><thead><tr><th width="183.60003662109375"></th><th></th></tr></thead><tbody><tr><td><mark style="color:$primary;">Allow All Roles</mark></td><td>Anyone can participate</td></tr><tr><td><mark style="color:$primary;">Create Whitelist</mark></td><td>Only members who have a role on the specified list may join</td></tr><tr><td><mark style="color:$primary;">Create Blacklist</mark></td><td>Members on the specified list may <strong>not</strong> join</td></tr></tbody></table>

{% hint style="info" %}
Users who are not in the server upon the lottery ending will not be chosen.
{% endhint %}

### Title & Message(s)

A title and message for the description message of the lottery (the one used to join) can be set. Another custom message can also be set for the winner announcement message.

### Rerolls

A survey can be rerolled by the person who created it after the lottery has finished. This will send a new result notification as well.
