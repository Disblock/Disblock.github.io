# Blocks

## How to use blocks

Blocks are used to describe what needs to be done when an event is triggered. Some can get an information, others can do something in your Discord server.

### Values blocks

These blocks are used to get an information from your Discord server, like "what's the username of this user ?" or "Does this user has this role ?". You can use the result of these blocks in others blocks.&#x20;

Here is an example :

<figure><img src="../.gitbook/assets/ValueBlocks.PNG" alt=""><figcaption><p>A simple action flow that show how to use some value blocks.</p></figcaption></figure>

When a message is sent, we check if the user has the _Manage server_ permission. The "Does user has permission" block return a **Boolean** to the "If" block. If the user has the permission, we continue, else, we can stop here since there isn't any "else" statement.

#### Values blocks types

When using values blocks with others blocks, you must be careful of the type returned by the value block, and the type needed by the used input. Some values blocks will return an User, some return a TextChannel, ...

Here is a list of available types in DIsblock :

| Variable type | Explanations                                                               |
| ------------- | -------------------------------------------------------------------------- |
| String        | A text - Can be a word, a sentence, ...                                    |
| Number        | Also called Integer, that represent a number.                              |
| List          | Can contain any type of elements.                                          |
| Color         | A color.                                                                   |
| Boolean       | Can be **True** or **False**, generally used with If/Else blocs.           |
| User          | Someone in your Discord server.                                            |
| TextChannel   | A text channel within your server.                                         |
| VoiceChannel  | A voice channel within your server.                                        |
| ThreadChannel | A Thread channel within a text channel.                                    |
| Message       | A message sent by an user.                                                 |
| EmbedMessage  | An embed message, to send somewhere on your server.                        |
| Rank          | Also called Role.                                                          |
| Emoji         | An emoji from Discord ( globally available ), or from your DIscord server. |

### Action blocks

Action blocks are used to interact with your Discord server. These blocks must be used inside events blocks to be enabled, and are executed one by one.
