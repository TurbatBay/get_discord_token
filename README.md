# get_discord_token
get discord token using browser console

// COPY PASTE THIS TO BROWSER CONSOLE SO YOU CAN GET DISCORD TOKEN IN CONSOLE 
// THIS CODE IS FROM https://stackoverflow.com/questions/67348339/any-way-to-get-my-discord-token-from-browser-dev-console 

```
(
    webpackChunkdiscord_app.push(
        [
            [''],
            {},
            e => {
                m=[];
                for(let c in e.c)
                    m.push(e.c[c])
            }
        ]
    ),
    m
).find(
    m => m?.exports?.default?.getToken !== void 0
).exports.default.getToken()
```
