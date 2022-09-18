# Embeds blocks

Sometimes, you way want something better than simple text messages, and to replace them, you can use some Embed Messages. Let's see how to use them !

Here is the minimal action flow to create and send an Embed message :

<figure><img src="../.gitbook/assets/EmbedMessageMinimal.JPG" alt=""><figcaption><p>The minimal Action flow to send an Embed message</p></figcaption></figure>

<figure><img src="../.gitbook/assets/EmbedMessageMinimalResult.JPG" alt=""><figcaption><p>The result of the created embed</p></figcaption></figure>

{% hint style="info" %}
When creating an Embed Message, you will probably want to send it. That can be done with the _Send embed message_ Block.
{% endhint %}

For now, that's only a very simple Embed message, but by adding few options to our _Create an embed message_ block, we can create way more complexes messages, like this one :&#x20;

<figure><img src="../.gitbook/assets/EmbedMessagesComplete.JPG" alt=""><figcaption><p>An embed message, using all the possibles options.</p></figcaption></figure>

## Embed messages options

Let's see what are the available options :

### Define Embed Image

Probably one of the most used, this option will add an image to your Embed :

<figure><img src="../.gitbook/assets/EmbedMessagesOptionImage.JPG" alt=""><figcaption><p>The block <em>Define Embed Image</em> was added in the customization input of the <em>Create embed</em> block</p></figcaption></figure>

<figure><img src="../.gitbook/assets/EmbedMessagesOptionImageResult.JPG" alt=""><figcaption><p>An image was added to the embed. ( <a href="https://pixabay.com/fr/photos/cat-jeune-animal-chaton-chat-gris-2083492/">Source</a> )</p></figcaption></figure>

### Define Embed Thumbnail

This option will add a thumbnail to your embed, always at the right top of the message :

<figure><img src="../.gitbook/assets/EmbedMessagesOptionThumbnail.JPG" alt=""><figcaption><p>This time, the <em>Define Embed Thumbnail</em> block is used in the customization input</p></figcaption></figure>

<figure><img src="../.gitbook/assets/EmbedMessagesOptionThumbnailResult.JPG" alt=""><figcaption><p>The thumbnail was added to the Embed message ( <a href="https://pixabay.com/fr/photos/cat-animal-de-compagnie-animal-300572/">Source </a>)</p></figcaption></figure>

### Add a field

Fields can be used to add more informations or details to the message. Each field have a maximum length of 512 characters.

<figure><img src="../.gitbook/assets/EmbedMessagesOptionFieldInline.JPG" alt=""><figcaption><p>Three fields are added in the customization input</p></figcaption></figure>

<figure><img src="../.gitbook/assets/EmbedMessagesOptionFieldInlineResult.JPG" alt=""><figcaption><p>The embed created by the above action flow</p></figcaption></figure>

<figure><img src="../.gitbook/assets/EmbedMessagesOptionFieldResult.JPG" alt=""><figcaption><p>The same embed, but if the <em>inline</em> option isn't checked</p></figcaption></figure>

### Set Embed's author

You can show who created this embed, and even add a link to a website and a picture :

<figure><img src="../.gitbook/assets/EmbedMessagesAuthor.JPG" alt=""><figcaption><p>The <em>set author</em> block was added. You must specify the author's name, but you don't need to give an URL or an image.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/EmbedMessagesAuthorResult.JPG" alt=""><figcaption><p>The created embed, "LJ5O" is a link to https://disblock.xyz ( <a href="https://pixabay.com/fr/photos/cat-chaton-animal-de-compagnie-551554/">Source </a>)</p></figcaption></figure>

### Add a footer

It is possible to add a small text and a picture at the end of your embed, with the _Add Footer_ block :

<figure><img src="../.gitbook/assets/EmbedMessagesFooter.JPG" alt=""><figcaption><p>This time, we added the <em>add footer</em> block. You don't need to specify an image for it to work.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/EmbedMessagesFooterResult.JPG" alt=""><figcaption><p>The created embed, with the footer. ( <a href="https://pixabay.com/fr/photos/cat-chaton-animal-de-compagnie-551554/">Source </a>)</p></figcaption></figure>

### Add timestamp

If you need to show when the embed was sent, you can use the _Add Timestamp_ block :

<figure><img src="../.gitbook/assets/EmbedMessagesTimestamp.JPG" alt=""><figcaption><p>The <em>Add Timestamp</em> block was added in the customization input</p></figcaption></figure>

<figure><img src="../.gitbook/assets/EmbedMessagesTimestampResult.JPG" alt=""><figcaption><p>The timestamp is visible at the end of the embed message.</p></figcaption></figure>
