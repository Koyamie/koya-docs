---
description: Here are the info moderation commands.
---

# Moderation

{% hint style="warning" %}
You must have a Moderator role defined by Koya to use these commands.
{% endhint %}

## ^^ban

{% hint style="info" %}
**Cooldown** : 3 seconds
{% endhint %}

{% hint style="warning" %}
The ban duration is in minutes by default but can be applied with time indicators such as `d, h, m, s`

Example: `^^ban @user 2d spam` returns to ban the user for 2 days with spam as reason.
{% endhint %}

| Description | Usage |
| :--- | :--- |
| Ban an user with an optional duration and optional reason. | ^^ban \[UserResolvable\] \[duration\] \[reason\] |

### ^^ban check

| Description | Usage |
| :--- | :--- |
| Check if a user is banned. | ^^ban check \[UserResolvable\] |

### ^^ban list

| Description | Usage |
| :--- | :--- |
| Displays the ban list. | ^^ban list |

## ^^bot\_nick

{% hint style="info" %}
**Cooldown** : 3 seconds.  
**Aliases** : ^^botnick
{% endhint %}

| Description | Usage |
| :--- | :--- |
| Edit or reset the bot nickname. | ^^bot\_nick \[nickname \| reset\] |

## ^^clean

| Description | Usage |
| :--- | :--- |
| Clean bot messages. | ^^clean |

## ^^clearwarns

{% hint style="info" %}
**Cooldown** : 3 seconds.  
**Aliases** : ^^cw
{% endhint %}

| Description |  |
| :--- | :--- |
| Clear user or server warns. | ^^clearwarns \[UserResolvable \| all\] |

## ^^custom\_commands

{% hint style="info" %}
**Cooldown** : 3 seconds  
**Aliases** : ^^cc
{% endhint %}

### ^^custom\_commands blacklist

| Description | Usage |
| :--- | :--- |
|  | ^^custom\_commands blacklist \[command name \| list\] |

### ^^custom\_commands list

| Description | Usage |
| :--- | :--- |
|  | ^^custom\_commands list |

### ^^custom\_commands remove

| Description | Usage |
| :--- | :--- |
|  | ^^custom\_commands remove \[command name\] |

### ^^custom\_command set

| Description | Usage |
| :--- | :--- |
|  | ^^custom\_commands set \[command name\] \[command answer\] |

## ^^kick

{% hint style="info" %}
**Cooldown** : 3 seconds
{% endhint %}

| Description | Usage |
| :--- | :--- |
| Kick a user | ^^kick UserResolvable \[reason\] |

## ^^massban

{% hint style="info" %}
**Cooldown** : 20 seconds.
{% endhint %}

| Description | Usage |
| :--- | :--- |
| Ban multiple users at once. | ^^massban \[UserResolvable1\] \[UserResolvable2\] \[UserResolvableN\] |

## ^^moderations

{% hint style="info" %}
**Cooldown** : 5 seconds.
{% endhint %}

| Description | Usage |
| :--- | :--- |
| Show server moderations. | ^^moderations |

## ^^modlogs

| Description | Usage |
| :--- | :--- |
| Retrieve the list of mod logs for an user. | ^^modlogs UserResolvable |

## ^^move

{% hint style="info" %}
**Cooldown** : 3 seconds.
{% endhint %}

| Description | Usage |
| :--- | :--- |
| Move a user in a voice channel. | ^^move UserResolvable ChannelResolvable |

## ^^mute

{% hint style="info" %}
**Cooldown** : 3 seconds.
{% endhint %}

{% hint style="warning" %}
The mute duration is in minutes by default but can be applied with time indicators such as `d, h, m, s`  
Example: `^^mute @user 2d spam` returns to mute the user for 2 days with spam as reason.  
  
Muting a member will automatically create a role if none exists.
{% endhint %}

| Description | Usage |
| :--- | :--- |
| Mute an user with an optional duration and optional reason. | ^^mute UserResolvable \[duration\] \[reason\] |
|  | ^^mute list |

## ^^purge

{% hint style="info" %}
**Cooldown** : 10 seconds.  
**Aliases** : ^^clear \| ^^prune
{% endhint %}

| Description | Usage |
| :--- | :--- |
| Allows to purge/clean the channel with specific content. | ^^purge \[UserResolvable\] \[number\] |

### ^^purge bots

...

### ^^purge commands

### ^^purge embeds

### ^^purge emojis

### ^^purge endswith

### ^^purge images

### ^^purge invites

## ^^reason

| Description | Usage |
| :--- | :--- |
| Add or edit the reason of a mod log Case. | ^^reason case \[Case number\] |







