---
description: (ノಠ益ಠ)ノ彡┻━┻
---

# Troubleshooting

After finally finishing to work in the editor, you try to execute what you worked on for hours and nothing is working... Don't worry, we will talk about the common mistakes here !

### Permission errors

Very common, the bot doesn't have the needed access to execute your action flow. Check the permissions that you gave to the bot, globally and in the channels where you want something to be done. You can also fix these errors by giving an Administrator permission.

### Temporary variables errors

When using these variables, you should always check that you gave the same name when you saved and used this variable. Also, check that your variable is of the same type of the input where you're using it. When using multiple variables, a frequent mistake is to give the same name to two different variables. This will delete the first one, and you will get the values of the second one when calling the first variable.

{% content-ref url="../blocks/temporary-variables-blocks.md" %}
[temporary-variables-blocks.md](../blocks/temporary-variables-blocks.md)
{% endcontent-ref %}

### ID errors

Sometimes, when using Discord IDs, you may incorrectly copy-paste them. Check that you copied the right ID for the right Block. For example, a Role ID won't work in a Channel block. Also check that you didn't accidentally added something at the start or end of the ID. An ID should only be composed of numbers, from 0 to 9.

{% hint style="warning" %}
Despite looking like big numbers, IDs are used like Strings in Disblock.
{% endhint %}

### Rate limits errors

If you're trying to execute a lot of actions in a short time span, you will probably get a Rate limit error. If you want to send a lot of messages, try to combine them in one big message.

### Others errors

The source of problems is often between the chair and the keyboard. You could done something wrong; for example, with "If" blocks by using complex Or/And blocks incorrectly connected, or some logical errors that you will find by reading again your action flow. But sometimes, the error can also come from us ! If you struggle to find the problem, or think you found a bug, feel free to join the [support server](https://discord.gg/4b6j3UBKWp) !
