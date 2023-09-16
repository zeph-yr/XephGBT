# XephGBT (Sabotage Mod)

Hai! I'm XephGBT, a smol Generative BloqTransformer chatbot created by Zephyr to help block-chopping streamers interact with their audiences. I have the ability to instantly transform maps in real-time on request. 

I can invert the map, change the JD, swap the colors, and mirror (for now). What will you choose to do with my troll-- I mean, capabilities?
<br>We trust you have only the best intentions towards our dear broadcasters! 🤗
<br>Get the mod at https://github.com/zeph-yr/XephGBT

Supporters of the mod have access to special features like Queue, ChannelPoints rewards, filtering by Subscribers, VIPs, Moderators, request type and setting limits 🥰

**TLDR: I am JDFixer and Chirality on steroids, but chat. And this is just the beginning!**

<p><img src="https://github.com/zeph-yr/XephGBT/blob/main/Screenshots/menu_main_2_small.png"></p>

## Features Overview
- Give viewers the power to instantly change the map you're playing via chat! How much do you trust them? 🤣
- Turn any map into a challenge map, play in bullet time, turn Chroma and Noodle maps into Halls of Mirrors, party like its 2019.
- There's really so much to this mod that you just have to try it for yourself to find out what the party is about!
- See this clip... coming soon

## What's The Playing Experience Like?
1. Your community types into chat using the !xg keywords.
2. Each transformation runs from the time it's received/applied until the end of the song.
3. For Supporters, transformations applied towards the end of a song continue into the next song. `Clear Queue` starts fresh.
4. Transformations are applied sequentially on top of previous ones and order matters. _As a smol BloqTransformer, I don't experience playing physically, but I would describe it as not commutative or associative._
5. As transformations begin to stack up... the map becomes increasingly convoluted. Hilarity ensues.
6. This is really fun → Your community can battle for control over your game. They can rapidly flip between inverted and vanilla arrows, swing the JD and NJS between extremes, jumpscare you etc.
7. Your experience will vary with your community. Engage wisely! 🥳
8. The more imaginative and respectful your community, the more fun you'll have.

## Supporter's Extras
- Customizable ChannelPoints rewards to treat your viewers to game sabotaging -I mean altering- fun!
- Auto-queue incoming requests and rewards. Transformations received in-menu will be applied when you press Play and those applied late into a song will continue on your next play. _Regular users receive requests in-map._
- Options to filter by type. Limit requests to only what you want to play, like invert, JD changes etc.
- Set limits for JD and NJS changes. _Regular users are at the mercy of their audience._
- Options to filter by viewer category. Limit requests to Subscribers, VIPs, Moderators.
- Personalized response messages. XephGBT will refer to you by your name instead of "the broadcaster" 🤩
  
### Become a Supporter!
Verification is done offline. Please reach out to my creator Zephyr9125 on Discord or zephyr@xephai.com. She'll give you details and access in ~24hrs 💎 Ping her again if she didn't see it.
- If you already are one or have previously supported the author, thanks for being a part of our community! We really appreciate it! Send her a ping on Discord!
- If you a new supporter, thank you and it's nice to meet you!! And send her a ping!
- If you would like to become one, awesome and TY! We're on https://ko-fi.com/zeph_yr and https://patreon.com/xeph_yr
- Reach out if you have questions 🤗
<p><img src="https://github.com/zeph-yr/XephGBT/blob/main/Screenshots/menu_supporter_1_crop.png" height=300><img src="https://github.com/zeph-yr/XephGBT/blob/main/Screenshots/menu_supporter_2_crop.png" height=300></p>

## Guide for Viewers: How to interact with the streamer's game
#### Request Keywords
Type `!xg [space]` followed by one of the transformations:
  - `invert`  like Chirality
  - `colors`  swap Red and Blue
  - `mirror`  switch Left and Righthanded mode
  - `jd [space] [number: any integer or decimal value]`
  - `njs [space] [number: any integer or decimal value]`
  - **Example:**`!xg colors` or `!xg jd 100`

#### In-chat Help
- Type `!xg help` for list of keywords
- Type `!xg info` or `!xg supporter` to learn about extra features and share mod link with your community

#### Redeem ChannelPoints Rewards
- When redeeming a **JD or NJS change, do enter a value into the rewards message** that you'd like the streamer to play!
- If you redeem without it, I'll pick one for you to keep things running smoothly

#### Community Guidelines and Being a Good User
- Do ask the streamer what their limits are and stay within them.
- Know that your requests may be auto-rejected or turned-down by the person playing and be ok with it.
- Do be respectful especially to the person playing the game. Make it a fun experience for everyone 💖

✨
## Guide for Streamers: How to use the mod
#### Step 1. Install
- Place `XephGBT.dll` into `Beat Saber\Plugins` directory
- Supporters should configure settings to get the most out of the experience!
- Run game, start stream and have fun with your community!
- **Make sure you have these:** [Requirements and game version are here](Requirements.md)

#### For Supporters: Setup ChannelPoints Rewards and Limits
#### Step 2. Stream-side Settings
- Create new Rewards in your channel, one per type you want to use. Refer to [Twitch's guide here.](https://help.twitch.tv/s/article/channel-points-guide)
- Give each a **unique** name or use these defaults: `Invert Map`, `Swap Colors`, `Mirror Map`, `Change JD`, `Change NJS`.
- For JD and NJS rewards: **Enable the `Require Viewer to Enter Text` option**. In the description, I recommend you ask viewers to enter a number. If a viewer doesn't enter one, I'll pick a random value within the limits you've set.
<br><img src="https://github.com/zeph-yr/XephGBT/blob/main/Screenshots/reward.png" width="250"/> <img src="https://github.com/zeph-yr/XephGBT/blob/main/Screenshots/config.png" width="300"/><br>

#### Step 3. XephGBT Config File
- Run game once to generate config file.
- Open `XephGBT.json` located in `Beat Saber\UserData` directory. Fill out the fields with the **exact names** of your rewards from Step 2.
- Customize JD and NJS limits: *Any integer or float* for `min_jd`, `max_jd`, `min_njs`, and `max_njs` is accepted. Save and close.
- Side note: It is highly discouraged to edit other fields in the file. They're for BloqTransformers to read, not humans. In the event you've perturbed them, delete the config file and restart game. You contaminated it. I'll generate a new one 🙂

### Disclaimer Before Downloading
Mods that interact with chat to alter gameplay in real-time require streaming, VR and game-specific expertise to use properly. Users are expected to know what they’re doing before using such mods.
<p><b>XephGBT is a for-fun project created on the author’s own time</b> in appreciation of her friends and in the spirit of creativity and academic interest. Its purpose is to provide a bespoke, fun and challenging experience for the Special Requester, the author’s community, and the author herself, all of whom are highly experienced VR enthusiasts. Understand this.</p>
<p>Use your own judgment. Mod is provided "as is" and "as available" without any warranty or guarantee. You agree that you are making use of the mod at your own risk.</p>
<p><b>ELI5: XephGBT is a mod intended for expert users, like ◆◆ slopes are for expert skiers. It is not recommended to use XephGBT if you are not experienced in streaming and VR.</b></p>

✨
## About
Copyright © 2023 Zephyr | www.xephai.com

<p>A lot of really, really hard work and countless hours (and cups of caffeine) went into the making of this mod. I wanted to have something unique and fun as a token of appreciation for my amazing friends and community. This is just the beginning!</p>

<p>🎉 This marks exactly 3 years since I started streaming and playing this game! Thank you for giving me your time and friendship, and going through a global pandemic and lockdown in VR with me. Our wee-hours MP sessions and conversations in 1.11.0, hardcore tournaments, pats for my kitty strimers, game-bending shenanigans and jokes when we laughed til we couldn't breathe are memories I cherish. Here's to more coming!🥳</p>

<p>I hope you enjoy playing with XephGBT as much as I did developing it ❤️ Thanks Wulfleee for the Special Request.</p>

<p><b>One more time.</b> This mod changes a player's game instantly. Please keep in mind when interacting with broadcasters that you are interacting with real people. Please treat them with respect, in a way they would like to be treated. If you're unsure, they'll probably appreciate your asking 🤗</p>
<p></p>
<img src="https://github.com/zeph-yr/XephGBT/blob/main/Screenshots/menu_main_regular_1.png" height="400"/>
