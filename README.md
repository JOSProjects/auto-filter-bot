# Auto Filter Bot #

Do Fork And Star The Repository If You Liked It.

<p align="center">
  <a href="https://github.com/tgbotsProject/Auto-Filter-Bot/fork">
    <img src="https://img.shields.io/github/forks/tgbotsProject/Auto-Filter-Bot?label=Fork&style=social">
    
  </a>
  <a href="https://github.com/tgbotsProject/Auto-Filter-Bot">
    <img src="https://img.shields.io/github/stars/tgbotsProject/Auto-Filter-Bot?style=social">
  </a>
</p>

- This Is Just An Simple Advance Auto Filter Bot.
- Just Sent Any Text As Query It Will Search For All Connected Chat's Files In Its MongoDB And Reply You With The Message Link As A Button.

## Commands

<details><summary>How to Use..!</summary>
<p>
<br>
• Add to any group and make admin.<br>
• Add to your channel as admin with full previlages

**Bot Commands (Works Only In Groups) :**


* `/add chat_id`<br>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
OR
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- To establish a connection of group with a channel (Bot should be admin with full previlages in both group and channel)<br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`/add @Username`


* `/del chat_id`<br>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
OR 
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- To delete a group's coneection with a channel (Use disable option from settigns pannel for disconnecting temporarily instead of deleteing)<br>
    &nbsp;&nbsp;&nbsp;&nbsp; `/del @Username`


* `/delall`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - To delete all connections of a group and deletes all its file from DB
* `/settings`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; -  To disaply a Settings Pannel Instance which can be used to tweek bot's settings accordingly

 * Channel - Button will show you all the connected chats with the group along with there index buttons correspnding to there order for furthur controls...
 * Filter Types - Button will show you the 3 filter types available in bot... Pressing each buttons will either enable or disable them and this will take into action as soon as you use them...without the need of a restart....
 * Configure - Button will help you to change no. of pages/ buttons per page/ total result without acutally editing the repo... Also it provide option to Enable/Disable  showing Invite Link in each results
 * Status - Button will show the stats of your current group
</a>
</p>
</details>

### Pre Requisites 
- `BOT_TOKEN` From [@BotFather](http://telegram.dog/BotFather)
- `APP_ID` And `API_HASH` From [Telegram](https://my.telegram.org) or [@UseTGzkBot](http://telegram.dog/UseTGzkBot)
- `USER_SESSION` String Obtained From [Repl.it](https://replit.com/@ZauteKm/GenerateStringSession)
- `DB_URL` Obtained From [Mongo DB](http://mongodb.com)
- How to Get MongoDB URL: [Click here](https://youtu.be/nj-lJfkgb6w)

## How to Deploy
Click the below button to watch the video tutorial on deploying

<a href="https://youtu.be/dbUNznxWxVA"><img src="https://img.shields.io/badge/How%20To%20Deploy-blue.svg?logo=Youtube"></a>
<a href="https://youtu.be/dbUNznxWxVA"><img src="https://img.shields.io/youtube/views/dbUNznxWxVA?style=social">

## Deploy Now
You can deploy this bot anywhere.

• **[Watch Deploying Tutorial](https://youtu.be/dbUNznxWxVA)**

<details><summary>Deploy to Heroku</summary>
<p>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/tgbotsProject/Auto-Filter-Bot/tree/master">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>
</details>

<details><summary>Deploy to VPS</summary>
<p>
<pre>
git clone https://github.com/tgbotsProject/Auto-Filter-Bot
cd Auto-Filter-Bot
pip3 install -r requirements.txt
# Change The Vars Of bot/__init__.py File Accordingly
python3 -m bot
</pre>
</p>
</details>

## Credits

- Thanks To Dan For His Awsome [Libary](https://github.com/pyrogram/pyrogram)
- Thanks to Official Repository [AlbertEinsteinTG/Adv-Auto-Filter-Bot-V2](https://github.com/AlbertEinsteinTG)
