# Administration

#### ^^admin\_role 

| Description | Usage |
| :--- | :--- |
| Add or remove an admin role | ^^admin\_role add RoleResolvable  |
|  | ^^admin\_role remove RoleResolvable  |
|  | ^^admin\_role list |

Aliases :                  ^^adminrole  
Cooldown :             3 seconds

## 

#### ^^announce\_channel

| Description  | Usage |
| :--- | :--- |
| Edit the Announce Channel for joins, leaves and bans. | ^^announce\_channel \[channel name or channel id\] |
|  | ^^announce\_channel remove |

Aliases :                   ^^announcechannel  and  ^^ac  
Cooldown :              3 seconds

## 

#### ^^auto\_nick

| Description | Usage |
| :--- | :--- |
| Edit or disable Auto Nick | ^^auto\_nick \[KOYA\] {username} |
|  | ^^auto\_nick \[nickname\] |
|  | ^^auto\_nick remove |

Note: Tag {username} is replaced by the username of the member who join when setting nickname.  
  
Aliases :                   ^^autonick  
Cooldown :              3 seconds

## 

#### ^^auto\_role

| Description | Usage |
| :--- | :--- |
| Edit or disable Auto Role | ^^auto\_role RoleResolvable |
|  | ^^auto\_role remove |

Aliases :                   ^^autorole  
Cooldown :              3 seconds

## 

#### ^^ban\_message

| Description | Usage |
| :--- | :--- |
| Manage ban message. | ^^ban\_message \[new message\] |
|  | ^^ban\_message off |
|  | ^^ban\_message on |
|  | ^^ban\_message test |

Availables tags : {user} - mention the user. \(Not recommended in the Join or Leave Image\) {username} - show the username. {server} - tells the server name. {membercount} - show the member count of the server. Example: {user} joined ! We are now {membercount} in the server. {dm} - Sends the announcement in dm \(Only available for the Join Message\).  
  
Aliases :                   ^^banmsg and ^^ban\_msg  
Cooldown :              3 seconds

## 

#### ^^channels

| Description | Usage  |
| :--- | :--- |
| Server channels management | ^^channels add \[text or voice or category\] ChannelResolvable |
|  | ^^channels remove ChannelResolvable |
|  | ^^channels list \[text or voice or category\] |
|  | ^^channels rename \[current name\] |

Cooldown :              5 seconds

## 

#### ^^command\_rule

| Description | Usage |
| :--- | :--- |
| Commands rules usage, add, list and remove command rules for your server, an user, a role or a channel. | ^^command\_rule add \[command or category+\] \[true or false\] \[server or channel or role or user\] \[channel or role or user name\] |
|  | ^^command\_rule clear |
|  | ^^command\_rule list \[server or channel or role or user\] \[channel or role or user name\] |
|  | ^^command\_rule remove \[command or category+\] \[server or channel or role or user\] \[channel or role or user name\] |

Aliases :                   ^^cmd\_rule / ^^crule / ^^cr  
Cooldown :              3 seconds

## 

#### ^^ignore\_channel

| Description | Usage |
| :--- | :--- |
| Add or remove channels from the ignored list. \(Except admins and mods\) | ^^ignore\_channel add \#channel1 \#channel2 ... |
|  | ^^ignore\_channel add all |
|  | ^^ignore\_channel list |
|  | ^^ignore\_channel remove \#channel1 channel2 ... |
|  | ^^ignore\_channel remove all |

Example :                ^^ignore\_channel add \#general  
Aliases :                   ^^ignorechannel and ^^ic  
Cooldown :              3 seconds

## 

#### ^^ignore\_role

| Description | Usage |
| :--- | :--- |
| Add or remove roles from the ignored list. \(Except admins and mods\) | ^^ignore\_role add @role |
|  | ^^ignore\_role remove @role |
|  | ^^ignore\_role list |

Example :                ^^ignore\_role add @Spammers  
Aliases :                   ^^ignorerole and ^^ir  
Cooldown :              3 seconds

## 

#### ^^ignore\_user

| Description | Usage |
| :--- | :--- |
| Add or remove users from the ignored list. \(Except admins and mods\) | ^^ignore\_user add @user |
|  | ^^ignore\_user remove @user |
|  | ^^ignore\_user list |

Example :                ^^ignore\_user add @Koyamie\#1050  
Aliases :                  ^^ignoreuser and ^^iu  
Cooldown :              3 seconds

## 

#### ^^image\_channel

| Description | Usage |
| :--- | :--- |
| Add or remove channels from the image channels list. \(Image channels are channels where only images can be sent\) | ^^image\_channel add \#channel1 \#channel2 ... |
|  | ^^image\_channel list |
|  | ^^image\_channel remove \#channel1 \#channel2 ... |
|  | ^^image\_channel remove all |

Example :                ^^image\_channel add \#images  
Aliases :                  ^^imagechannel and ^^imagec  
Cooldown :              3 seconds

## 

#### ^^join\_image

| Description | Usage |
| :--- | :--- |
| Manage join image | ^^join\_image \[new message\] |
|  | ^^join\_image background \[image or remove\] |
|  | ^^join\_image color \[circle or welcome or username or message\] \[\#hexadecimal color\] |
|  | ^^join\_image off |
|  | ^^join\_image on |

Availables tags : {user} - mention the user. {username} - show the username. {server} - tells the server name. {membercount} - show the member count of the server. Example: {user} joined ! We are now {membercount} in the server. {dm} - Sends the announcement in dm \(Only available for the Join Message\).  
  
Aliases :                  ^^joinimg and ^^join\_img  
Cooldown :              3 seconds

## 

#### ^^join\_message

| Description | Usage |
| :--- | :--- |
| Manage join message. | ^^join\_message \[new message\] |
|  | ^^join\_message off |
|  | ^^join\_message on |
|  | ^^join\_message test |

Availables tags : {user} - mention the user. \(Not recommended in the Join or Leave Image\) {username} - show the username. {server} - tells the server name. {membercount} - show the member count of the server. Example: {user} joined ! We are now {membercount} in the server. {dm} - Sends the announcement in dm \(Only available for the Join Message\).  
  
Aliases :                  ^^joinmsg  
Cooldown :              3 seconds

## 

#### ^^leave\_image

| Description | Usage |
| :--- | :--- |
| Manage leave image | ^^leave\_image \[new message\] |
|  | ^^leave\_image background \[image or remove\] |
|  | ^^leave\_image color \[circle or welcome or username or message\] \[\#hexadecimal color\] |
|  | ^^leave\_image off |
|  | ^^leave\_image on |

Aliases :                   ^^leaveimg and ^^leave\_img  
Cooldown :              3 seconds

## 

#### ^^leave\_message

| Description | Usage |
| :--- | :--- |
| Manage leave message | ^^leave\_message \[new message\] |
|  | ^^leave\_message off |
|  | ^^leave\_message on |
|  | ^^leave\_message test |

Availables tags : {user} - mention the user. \(Not recommended in the Join or Leave Image\) {username} - show the username. {server} - tells the server name. {membercount} - show the member count of the server. Example: {user} joined ! We are now {membercount} in the server. {dm} - Sends the announcement in dm \(Only available for the Join Message\).  
  
Aliases :                   ^^leavemsg  
Cooldown :              3 seconds

## 

#### ^^logs

| Description | Usage |
| :--- | :--- |
| Logs usage | ^^logs channel ChannelResolvable |
|  | ^^logs list |
|  | ^^logs all |
|  | ^^logs \[log name\] |

Example :                ^^logs ban unban  
Aliases :                   ^^log  
Cooldown :              3 seconds

## 

#### ^^mod\_role

| Description | Usage |
| :--- | :--- |
| Add or remove a Mod role | ^^mod\_role add RoleResolvable |
|  | ^^mod\_role remove RoleResolvable |
|  | ^^mod\_role list |

Aliases :                   ^^modrole  
Cooldown :              3 seconds

## 

#### ^^modlog

| Description | Usage |
| :--- | :--- |
| Mod logs configuration | ^^modlog channel ChannelResolvable |
|  | ^^modlog disable |
|  | ^^modlog enable |

Aliases :                   ^^ml  
Cooldown :              3 seconds

## 

#### ^^mute\_role

| Description | Usage |
| :--- | :--- |
| Edit or remove the mute role. | ^^mute\_role RoleResolvable |
|  | ^^mute\_role remove |

Example :                ^^mute\_role Muted  
Aliases :                   ^^muterole  
Cooldown :              3 seconds

## 

#### ^^prefix

| Description | Usage |
| :--- | :--- |
| Show or change bot prefix | ^^prefix \[new prefix\] |

Aliases :                   ^^prfx  
Cooldown :              3 seconds

## 

#### ^^reddit

| Description | Usage |
| :--- | :--- |
| Reddit feature usage | ^^reddit add \[subreddit name\] |
|  | ^^reddit list \[number\] |
|  | ^^reddit remove \[number\] |
|  | ^^reddit test \[number\] |

Example :                 ^^reddit add OnePiece  
Cooldown :              10 seconds

## 

#### ^^roles

| Description | Usage |
| :--- | :--- |
| Manage roles in the server, create, delete, or edit roles | ^^roles list |
|  | ^^roles add RoleResolvable \[hex color\] \[hoist on or off\] |
|  | ^^roles remove RoleResolvable |
|  | ^^roles color RoleResolvable \[new hex color\] |

Cooldown :              3 seconds

## 

#### ^^rss

| Description | Usage |
| :--- | :--- |
| RSS feature usage | ^^rss add \[rss link\] |
|  | ^^rss channel \[number\] \[new channel\] |
|  | ^^rss filters \[number\] \[new filters\] |
|  | ^^rss list \[number\] |
|  | ^^rss mention \[number\] \[on or off\] |
|  | ^^rss message \[number\] \[new message\] |
|  | ^^rss remove \[number\] |
|  | ^^rss test \[number\] |

Example :                ^^rss add [https://www.youtube.com/feeds/videos.xml?channel\_id=UCE7Om8-jVQXYhdr2gZ6Yi\_g](https://www.youtube.com/feeds/videos.xml?channel_id=UCE7Om8-jVQXYhdr2gZ6Yi_g)  
Aliases :                  ^^feed  
Cooldown :              10 seconds

