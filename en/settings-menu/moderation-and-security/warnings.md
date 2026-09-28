---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
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

# ⚠️ Warnings

Users can be given warnings via Starbot. You can control what actions are taken at certain levels. More than one warning can be given at a time - this is useful for more severe infractions.

***

## Actions

Users can be automatically <mark style="color:$warning;">timed out</mark>, <mark style="color:$primary;">given a role</mark>, or <mark style="color:$danger;">banned</mark> upon reaching each threshold specified in the settings. For example:

| Warning Level | Code | Action           |
| ------------- | ---- | ---------------- |
| 2             | role | Role Given       |
| 4             | t-3  | Timeout (3 Days) |
| 7             | t-7  | Timeout (7 Days) |
| 10            | ban  | Ban              |

{% hint style="info" %}
When warning someone who will reach a specified threshold, it will appear in the warning confirmation screen.
{% endhint %}

***

## Warning Regression

You can optionally set warnings to <mark style="color:$success;">decrease by 1</mark> every **X** number of days without incident. If a user receives a warning before X number of days have passed, the countdown resets.

{% hint style="info" %}
This can be set to 0 to disable it.
{% endhint %}
