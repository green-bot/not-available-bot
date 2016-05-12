





  

```
#!/usr/bin/env ruby

```







# Not Available Bot

# Summary
This simple bot tells the person texting into it that there's no one here
to chat with. Good for service interrruptions, a place holder until
the real bot can show up, whatever.

# Configuration
None.

# Installation

## Command line
To create not available bots in a greenbot server, first add this
to the library by NPM installing it in the greenbot core:
`/usr/local/src/greenbot_core: npm install not-available-bot`

Then, go to the library in greenbot-admin, make a new bot with it,
and attach it to the network you would like.

## Portal
From the library page of greenbot-admin, manual install not-available-bot`









Greenbot.rb holds the bot library functionality, not that we need
much of it at all. Just tell, and we could have printed that out
to the screen.


  

```
require './lib/greenbot.rb'
tell "I'm sorry, but this bot is not currently available. "


```




