# Ultroid - UserBot
A stable pluggable Telegram userbot, based on Telethon.

<p align="center">
  <img src="https://telegra.ph/file/a47512bb109b1d161950e.jpg" alt="Teamdevil">
</p>

[![Stars](https://img.shields.io/github/stars/TeamUltroid/Ultroid?style=social)](https://github.com/TeamUltroid/Ultroid/stargazers)
[![Forks](https://img.shields.io/github/forks/TeamUltroid/Ultroid?style=social)](https://github.com/TeamUltroid/Ultroid/fork)
[![Python Version](https://img.shields.io/badge/Python-v3.9-blue)](https://www.python.org/)
[![Contributors](https://img.shields.io/github/contributors/TeamUltroid/Ultroid)](https://github.com/TeamUltroid/Ultroid/graphs/contributors)
[![License](https://img.shields.io/badge/License-AGPL-blue)](https://github.com/TeamUltroid/Ultroid/blob/main/LICENSE)
[![Size](https://img.shields.io/github/repo-size/TeamUltroid/Ultroid)](https://github.com/TeamUltroid/Ultroid/)

<details>
<summary>More Info</summary>
<br>
  Documentation soon..  <br />
</details>

# Deploy 
- [Heroku](https://github.com/Theshashankk/whitedevil-WC#Deploy-to-Heroku)
- [Local Machine](https://github.com/TeamUltroid/Ultroid#Deploy-Locally)

## Deploy to Heroku
- Get your `API_ID` and `API_HASH` from [here](https://my.telegram.org/) and click the below button!  <br />  

[![Deploy]https://heroku.com/deploy?template=https://github.com/theshashankk/whitedevil-WC/blob/master


## Deploy Locally
- Get your `API_ID` and `API_HASH` from [here](https://my.telegram.org/)
- Get your `REDIS_URI` and `REDIS_PASSWORD` from [here](https://redislabs.com), tutorial [here](./resources/extras/redistut.md).
- Clone the repository: <br />
`git clone https://github.com/TeamUltroid/Ultroid.git`
- Go to the cloned folder: <br />
`cd Ultroid`
- Create a virtual env:   <br />
`virtualenv -p /usr/bin/python3 venv`   
`. ./venv/bin/activate`
- Install the requirements:   <br />
`pip install -r requirements.txt`   
- Generate your `SESSION`:   
`bash sessiongen`
- Fill your details in a `.env` file, as given in [`.env.sample`](https://github.com/TeamUltroid/Ultroid/blob/main/.env.sample).    
(You can either edit and rename the file or make a new file.)
- Run the bot:   
`bash resources/startup/startup.sh`

Made with 💕 by [@TeamUltroid](https://t.me/TeamUltroid). <br />

# Credits
* [Lonami](https://github.com/LonamiWebs/) for [Telethon](https://github.com/LonamiWebs/Telethon)

