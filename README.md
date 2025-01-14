# DSV
Discord Username's availability checker.

**For contribution and updates: <a href="https://discord.gg/Bww4DvKA4Z">Join the Discord</a>**<br>
**Support me: <a href="https://www.paypal.com/paypalme/suegdu">Paypal</a>**

---
- Checks for a specific list of usernames.
- Generates and checks for a specific given amount of usernames with a specific username length, (e.g 4 letters usernames.)
- Supports Multi-Tokens.
- Supports Webhooks.
- Completely customizable.
> - Hmm but what about proxies? Proxies **Does NOT** bypass the rate limit. Will add it soon though

 > Check <a href =#notes >notes</a> for a very important information before using this tool, and for some FAQ. And BEFORE opening an issue.

# How to use
- Have <a href="https://www.python.org/">Python</a> installed.
- First clone the repository or <a href="https://github.com/suegdu/DSV/archive/refs/heads/main.zip">download it as .zip</a>
- Install the required libraries, by running : ```pip install -r requirements.txt``` or `pip3 install -r requirements.txt` in your command line.
- Open `config.ini`
- Paste your account's token in front of the equal symbol `TOKEN`
- Configure DSV as how you'd like (`config.ini`)
- Run `dsv.py` 

> - For adding a specific list of usernames, create a file named `usernames.txt` in the same running directory as `dsv.py` and list your usernames there, separating them by a new line.
> - For adding multiple tokens, open `config.ini` and enable `MULTI-TOKEN` by making it `true` and paste your tokens inside `tokens.txt` separating them by a new line.

- #### Note: It will only work with accounts that didn't proceed to apply the name change and has the pop up to update(Eg: Create an alt.). Read <a href =#notes >Notes</a> to know why.

# Images
![](./images/img11.png)
![](./images/img22.png)
![](./images/img33.png)

# Notes
#### Disclaimer: I'm not responsible for/of any damage/results/returns/suspension made/resulted with/by this tool. It is your will to run, and once ran, it's your responsibility.


> ### Due to recent changes in Discord's API, Discord added CAPTCHA requirements. It will only work with an account that didn't proceed to apply the name change and has the pop up to update.
> - This repository is licensed under a **NON-COMMERCIAL USE.** <a href="https://github.com/suegdu/Discord-Username-Checker/blob/main/LICENSE">READ here.</a>

- I **demand** my credits to the code wherever it's used.
- Spamming Discord's API is against TOS, You may get your account suspended/rate limited and I am not responsible. For a further caution, use an alt's token and a longer delay.
- You need to get your Discord's account's authorization token and paste it inside the variable: `TOKEN` . On how to do that check these following steps: https://www.androidauthority.com/get-discord-token-3149920/
- Make sure to have a decent delay or you may get your account disabled. 



