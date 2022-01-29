# ✍ Guides

### Setting up Slash Commands

* Slash commands are disabled by default
* In the **config.js** set **SLASH = true** and **CONTEXT = true** and replace TEST\_GUILD\_ID with the guild ID where you want to initially test the commands. This will ensure that all the commands are registered immediately
* Once you are happy with the commands, set **GLOBAL = true** to register these interactions globally

{% hint style="warning" %}
_**Global slash commands** can take upto 1 hour to be shown across all guilds_
{% endhint %}
