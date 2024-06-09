# FileStore Bot


<div align="center">
<a href="https://graph.org/file"><img src="https://graph.org/file/f38cb080fd486ffa1134d.jpg" alt="1" border="100">
</a></div>


## Main Features
- **Rename Feature & On/Off Toggle**
- **Stream Feature On/Off Toggle**
- **URL Shortener On/Off Toggle**
- **Request to Join Force Subscribe**
- **Stream Feature with Multi-Player Support**
- **Save Restricted Content & On/Off Toggle**
- **Custom URL Shortener Support**

## Variables

### Required Variables
* **`BOT_TOKEN`**: Create a bot using [@BotFather](https://telegram.dog/BotFather) and get the Telegram API token.
* **`API_ID`**: Get this value from [telegram.org](https://my.telegram.org/apps)
* **`API_HASH`**: Get this value from [telegram.org](https://my.telegram.org/apps)
* **`CHANNELS`**: Username or ID of channel or group. Separate multiple IDs with a space.
* **`ADMINS`**: Username or ID of Admin. Separate multiple Admins with a space.
* **`DATABASE_URI`**: [MongoDB](https://www.mongodb.com) URI. Get this value from [MongoDB](https://www.mongodb.com). For more help, watch this [video](https://youtu.be/I36_OTWvT2w).
* **`DATABASE_NAME`**: Name of the database in [MongoDB](https://www.mongodb.com).
* **`FILE_STORE_CHANNEL`**: Channel from where file store links of posts should be made. Separate multiple IDs with a space.

---

## Deploy 

<details>
<summary><b>Deploy to Heroku</b></summary>
<p>
<a href="https://heroku.com/deploy?template=https://github.com/amitpatle/FileStore-Bot">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy to Heroku">
</a>
</p>
</details>



<details>
<summary><b>Deploy to Koyeb</b></summary>
<p>
<b>The fastest way to deploy the application is to click the Deploy to Koyeb button below.</b>
<br><br>
<a href="https://app.koyeb.com/deploy?type=git&repository=github.com/amitpatle/FileStore-Bot&branch=amitpatle&name=FileStore-Bot">
  <img src="https://www.koyeb.com/static/images/deploy/button.svg" alt="Deploy to Koyeb">
</a>
</p>
</details>



<details>
<summary><b>Deploy to Render</b></summary>
<p>
<b>Use these commands:</b>
<br><br>
• Build Command: <code>pip3 install -U -r requirements.txt</code>
<br><br>
• Start Command: <code>python3 bot.py</code>
<br><br>
Go to [UptimeRobot](https://uptimerobot.com/) and add a monitor to keep your bot alive.
<br><br>
Use these settings when adding a monitor:
<br><br>
<img src="https://telegra.ph/file/a79a156e44f43c9833b50.jpg" alt="UptimeRobot Settings">
<br><br>
<b>Click the button below to deploy directly to Render:</b>
<br><br>
<a href="https://render.com/deploy?repo=https://github.com/amitpatle/FileStore-Bot/tree/amitpatle">
  <img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
</a>
</p>
</details>



<details>
<summary><b>Deploy to VPS</b></summary>
<p>
Clone the repository:
<pre><code>git clone https://github.com/amitpatle/FileStore-Bot</code></pre>

Install the required packages:
<pre><code>pip3 install -U -r requirements.txt</code></pre>

Edit `info.py` with the required variables, then run the bot:
<pre><code>python3 bot.py</code></pre>
</p>
</details>

<hr>
