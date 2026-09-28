---
description: Send a message to a specified channel when a user enters or exits the server
---

# 👋 Enter & Exit Messages

## Styles

There are 3 different styles to choose from.

<table><thead><tr><th width="128.20001220703125" valign="top">Style</th><th width="279.4000244140625" valign="top">Description</th><th>Example</th></tr></thead><tbody><tr><td valign="top"><mark style="color:$primary;">Text</mark></td><td valign="top">A straightforward text message</td><td><img src="../../.gitbook/assets/image_2024-03-15_191454925.png" alt="&#x22;Text&#x22; Style" data-size="original"></td></tr><tr><td valign="top"><mark style="color:$primary;">Card</mark></td><td valign="top">An simple embed-style card</td><td><img src="../../.gitbook/assets/image (15).png" alt="&#x22;Card&#x22; Style" data-size="original"></td></tr><tr><td valign="top"><mark style="color:$primary;">Image</mark></td><td valign="top">A custom-generated image</td><td><img src="../../.gitbook/assets/image (16).png" alt="&#x22;Image&#x22; Style" data-size="original"></td></tr></tbody></table>

***

## Message

You can customize the message to be displayed. If no message is specified, a default message will be sent. The following variables can be used.

<table><thead><tr><th width="182.5999755859375">Variable</th><th>Result</th></tr></thead><tbody><tr><td><mark style="color:$primary;">!SERVER!</mark></td><td>The name of the server</td></tr><tr><td><mark style="color:$primary;">!USER!</mark></td><td>The user as a <mark style="color:$primary;">@mention</mark></td></tr><tr><td><mark style="color:$primary;">!NAME!</mark></td><td>The user's username</td></tr><tr><td><mark style="color:$primary;">!MEMBERS!</mark></td><td>The server's member count (including the user)</td></tr><tr><td><mark style="color:$primary;">!RANDOM!</mark></td><td>Replaces the <strong>ENTIRE</strong> message with a random one</td></tr></tbody></table>

{% hint style="info" %}
Click the **Show Examples** button to generate an example for both the enter & exit messages based on the current settings.
{% endhint %}
