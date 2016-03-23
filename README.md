# Concierge network

These are the bot files described in a [recent article]() posted on
our docs site. 

To get started, you'll need:

- Pandorabots user_key
- Pandorabots app_id

## Setup

You'll need to create 3 bots on your account (drakebot, mussiccat, personal).
Upload each set of bot files to the correct botname.

Once you've done this, you'll need to configure a property in the personal bot
so that it knows what comparison engine to use. Add the following property to
your bot properties file, replacing YOUR_APP_ID with your own credential:

```
["musiccat", "YOUR_APP_ID/musiccat"]
```

Compile all 3 bots, and you can begin talking to the personal bot to use the
network!
