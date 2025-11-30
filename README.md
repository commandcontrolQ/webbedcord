# WebbedCord
WebbedCord is a fork of [diskcord](https://github.com/kolejker/diskcord) that is actually still being hosted (and updated, kinda). <br>
Unlike diskcord, _WebbedCord will only really be targetting Blackberry OS devices_ (specifically the latest version of BBOS 10). <br>
As a result, please do not create issues unless the problem affects such devices.

## Instances
There is currently only one instance: https://kooper.online/misc/diskcord

## Information
- As of writing, it is not possible to log in using an email and password, likely due to a change in Discord's API. This is a known issue.
    - This likely won't be fixed (and I might even remove it altogether). Do not create issues about this.
- If you experience certificate errors while trying to access the main instance, there is a good chance you are still utilising the stock root certificates. **Please update the root certificates before creating issues on this!**
    - Up-to-date root certificates can be downloaded from https://tlsroot.litten.ca

## What might be added in the future?
- Sending files/images
- Replying to messages
- Sending emojis properly
    - Sending custom emojis
- Reactions (this likely won't happen)
- Direct messages (this likely won't happen, see the section below)

## What will never be added?
- Anything which usually results in accounts being suspended or "limited" for a period of time. This includes:
    - Server management (creating, joining or leaving servers)
    - Starting or closing direct messages (chatting in preexisting DMs should be fine)
