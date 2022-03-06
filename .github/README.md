<h1 align="center">⚙️ DEPLOYING ⚙️</h1>



    


<a href="https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2Fkaal0408%2FMusicplayer3&template=https%3A%2F%2Fgithub.com%2Fkaal0408%2FMusicplayer3" rel="nofollow" style="background-color: initial; box-sizing: border-box; color: #0366d6; text-decoration-line: none;"><img alt="Deploy" data-canonical-src="https://www.herokucdn.com/deploy/button.svg" src="https://camo.githubusercontent.com/83b0e95b38892b49184e07ad572c94c8038323fb/68747470733a2f2f7777772e6865726f6b7563646e2e636f6d2f6465706c6f792f627574746f6e2e737667" style="border-style: none; box-sizing: initial; max-width: 100%;" /></a></div>
</a>


<img src="https://telegra.ph/file/c0e014ff34f34d1056627.png" align="right" width="200" height="200"/>

# Yukki Music Bot <img src="https://img.shields.io/github/v/release/TeamYukki/YukkiMusicBot?color=black&logo=github&logoColor=black&style=social" alt="LICENSE">

[Yukki Music Bot](https://github.com/TeamYukki/YukkiMusicBot) is a Powerful Telegram Music+Video Bot written in Python using Pyrogram and Py-Tgcalls by which you can stream songs, video and even live streams in your group calls via various sources.

* Youtube, Soundcloud, Apple Music, Spotify, Resso and Telegram Audios & Videos support.
* Written from scratch, making it stable and less crashes.
* Attractive thumbnails, fonts and images,  making experience more user-friendly and interactive.
* Loop, Shuffle, Specific Skip, Playlists etc support
* Global, Users, Chats Top 10 played tracks stats
* Multi-Language support


# 🔗 An Overview

Here's a brief high-level overview of the Yukki Music Bot:

This project is based on [Pyrogram](https://github.com/pyrogram) and [Py-Tgcalls](https://github.com/pytgcalls/pytgcalls) . Pyrogram is a modern, elegant and asynchronous MTProto API framework.

* For database, Yukki uses the MongoDB to store data and keys. [MongoDB](https://www.mongodb.com/) is a document database with the scalability and flexibility that you want with the querying and indexing that you need.
* Project uses the bs4 web scrapping for getting many platform details. [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) is a Python library for pulling data out of HTML and XML files.
* The project uses the font [`Poppins`](../assets/font.ttf) as its main font for the thumbnails.
* The projects uses attractive images and icons which you can get in [assets](../assets/) directory.

For more information on the technologies that power the Yukki Music Bot, check out the [Docs](https://notreallyshikhar.gitbook.io/yukkimusicbot/).



# ⚡️ Getting Started

### Before deploying Yukki Music Bot , please have a look towards [all available config vars](../config/README.md) , also please check [all available commands](../strings/command.yml) of the project.

> If you want to start working with Yukki Music Bot you can either fork or import repo .
> The official [documentation site](https://notreallyshikhar.gitbook.io/yukkimusicbot/) contains a lot of information. The best place to start is from the deployment section.
> If you'd like to talk to us, join us on our [Telegram Group](https://t.me/YukkiSupport)


## 🖇 Prerequisites

> In order to avoid conflicts in your project, you must have/installed

- [Python3.9](https://www.python.org/downloads/release/python-390/)
- [Telegram API Key](https://docs.pyrogram.org/intro/setup#api-keys)
- [Telegram Bot Token](https://t.me/botfather)
- [MongoDB URI](https://telegra.ph/How-To-get-Mongodb-URI-04-06)
- [Pyrogram String Session](https://notreallyshikhar.gitbook.io/yukkimusicbot/deployment/string-session)


## 🖇 Generating Pyrogram String Session

- Generate a Pyrogram String Session via [Replit](https://replit.com/@NotReallyShikhar/Yukki-Music-String-Gen)

- Generate a Pyrogram String Session via [Telegram String Generation Bot](https://t.me/YukkiStringBot)

<h1 align="center">⚙️ DEPLOYING ⚙️</h1>



    


<a href="https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2Fkaal0408%2FMusicplayer3&template=https%3A%2F%2Fgithub.com%2Fkaal0408%2FMusicplayer3" rel="nofollow" style="background-color: initial; box-sizing: border-box; color: #0366d6; text-decoration-line: none;"><img alt="Deploy" data-canonical-src="https://www.herokucdn.com/deploy/button.svg" src="https://camo.githubusercontent.com/83b0e95b38892b49184e07ad572c94c8038323fb/68747470733a2f2f7777772e6865726f6b7563646e2e636f6d2f6465706c6f792f627574746f6e2e737667" style="border-style: none; box-sizing: initial; max-width: 100%;" /></a></div>
</a>

## 🖇 Heroku Deployment

<h4>Click the button below to deploy Yukki on Heroku!</h4>    
<a href="https://yukki.tech/deploy/"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a>

> Click on buttons below to expand and  detailed explanation process. !


<details>
    <summary><b> Detailed Heroku Depoyment Process » </b></summary>

<img src="https://telegra.ph/file/672efa7b8160ed39c6e86.jpg" align="right" width="350" height="700"/>

### 🚀 Deploy Process
- Click on the deploy button above and login to your [heroku account](https://heroku.com/login) .
- Fill your values there.
- If you don't know how to get config vars : [Please refer here](../config/README.md)
- Make sure you fill correct values.
- Click on **Deploy** button.
- Please wait till the app gets deployed on heroku. Deploying can take upto **2-3 mins**..
- When your app is successfully deployed, click on **Manage App** button.


### 🚀 Booting Process
- Search for **Resources** Tab inside your app. ( Check Image for more details)
- Click on the **Pencil Icon** under resources section.
- Turn **on** the **switch** present there near pencil icon.
- Congrats your Music Bot is now **Booting**.


### 🚀 Checking Logs
- After Turning on your booting .
- Click on the **More Button** present at top right corner .
- Click on the **View Logs** button from the drop down menu.
- You check your logs there!
- Click on save button there at bottom to save your logs and forward it to us on [@YukkiSupport](https://t.me/YukkiSupport) if you face any problem

</details>

## 🖇 VPS Deployment

> Checkout [Docs](https://notreallyshikhar.gitbook.io/yukkimusicbot/deployment/local-hosting-or-vps) for Detailed Explanation on VPS Deploy


```console
shikhar@MacBook~ $ git clone https://github.com/notreallyshikhar/YukkiMusicBot
shikhar@MacBook~ $ cd YukkiMusicBot
shikhar@MacBook~ $ sudo bash setup
```
> Setup will install each and every requirement, nodejs and pip packages automatically. After successfull installation of requirements , setup will ask you to input your vars.
> Please input your vars correctly.

```console
shikhar@MacBook~ $ bash start
```

> Not Getting VPS Method? [Watch Tutorial](https://t.me/TheYukki/2275)


<img src="https://telegra.ph/file/6b75b57da50ef1183fcdc.jpg" align="center">


## 🏷 Support

Reach out to the maintainer at one of the following places:

- [GitHub Issues](https://github.com/TeamYukki/yukkimusicbot/issues/new?assignees=&labels=question&template=SUPPORT_QUESTION.md&title=support%3A+)
- Contact options listed on [this GitHub profile](https://github.com/TeamYukki)
- [Telegram Support](https://t.me/YukkiSupport)

## 🎗 Project assistance

If you want to say **thank you** or/and support active development of YukkiMusicBot:

- Add a [GitHub Star](https://github.com/TeamYukki/YukkiMusicBot) to the project.
- Fork the Repo :)
- Write interesting articles about the project on [Dev.to](https://dev.to/), [Medium](https://medium.com/) or your personal blog.

PS: You can buy me a coffee too :)
<p><a href="https://www.buymeacoffee.com/notreallysy" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 35px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a></p>

Together, we can make YukkiMusicBot **better**!

## ✍🏻 Contributing

First off, thanks for taking the time to contribute! Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make will benefit everybody else and are **greatly appreciated**.

Please read [our contribution guidelines](CONTRIBUTING.md), and thank you for being involved!

## 👨🏻‍💻 Authors & contributors

The original setup of this repository is by [Team Yukki](https://github.com/TeamYukki).

For a full list of all authors and contributors, see [the contributors page](https://github.com/TeamYukki/YukkiMusicBot/contributors).

## ⚠️ Security

YukkiMusicBot follows good practices of security, but 100% security cannot be assured. YukkiMusicBot is provided **"as is"** without any **warranty**. Use at your own risk.

For more information and to report security issues, please refer to our [`SECURITY.md`](SECURITY.md)


## 🗂 License

This project is licensed under the **GNU General Public License v3**. All designs were created by [@NotReallyShikhar](https://github.com/NotReallyShikhar) .

See [LICENSE](../LICENSE) for more information.

## 📑 Acknowledgements

Special thanks to these amazing projects/people which/who help power Yukki Music Bot:

- [Pyrogram](https://github.com/pyrogram/pyrogram)
- [Py-Tgcalls](https://github.com/pytgcalls/pytgcalls)
- [CallsMusic Team](https://github.com/Callsmusic)
- [TheHamkerCat](https://github.com/TheHamkerCat)
- [Charon Baglari](https://github.com/XCBv021)





Reminder that you are great, you are enough, and your presence is valued. If you are struggling with your mental health, please reach out to someone you love and consult a professional.
