# Projects
### Ares (2016-2019)
Ares was a level 7 (now known as level 6) Vanilla Lua to Roblox Lua Wrapper. I was able to achieve this by reverse engineering Roblox to find rLua C functions locations in memory and calling them from C++, hooking onto lua_gettop to grab the LuaState thread from Roblox. From there, as always, I had to bypass a few checks which was pretty much just turning the return check jz into a jmp, and then putting it back after thee function was properly called to avoid getting caught by memory check. From there, I developed Ares to wrap Vanilla Lua to Roblox Lua so that users could execute foreign lua scripts into Roblox's environment however they pleased. Ares had over 1,000 clients when development stopped. Here's a video of Ares being used in mid-2018: [https://www.youtube.com/watch?v=lubaIQWLIFw](https://www.youtube.com/watch?v=lubaIQWLIFw){:target="_blank"}
### Isabelle - The Discord Bot (2019-present)
Isabelle is a multi-purpose discord bot that's main purpose is to bring you all the tools you need for your Discord server, in one simple invite. Isabelle uses the Discord.JS library for functionality, and uses Lavalink to pump music to your voice channels. Visit Isabelle's website here: [https://isabelle.gg/](https://isabelle.gg){:target="_blank"}
### Isabelle - The Roblox Exploit (2019-present, still under development)
After Ares discontinued, I continued to research more efficient ways to exploit Roblox's environment, and bring clients to best user experience possible. Isabelle isn't done yet, but I've been continuously working on it for over a year to release a stable, powerful exploit to the market. For more information regarding development progress, join the discord: [https://isabelle.gg/support](https://isabelle.gg/support){:target="_blank"}
# Get in touch
via Email: azurilex@isabelle.gg\
via Discord Azurilex#0001\
via Twitter: @azurilex
