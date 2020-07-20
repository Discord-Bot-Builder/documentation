# Get Started

This is the official documentation of Discord Bot Builder with the help of the community.

---

### What is Discord Bot Builder?

Discord Bot Builder is a piece of software with which you can develop your own Discord bot using a GUI. You can buy it on Steam [here](https://store.steampowered.com/app/1119570/Discord_Bot_Builder/).

### What is the DBB Discord?

We offer support to the community and the oppotrunity to meet new people in our [Discord](https://discord.gg/PAzxTDw). Join it today!

---

## Let's go!

### Get Beta[^1]

Open Steam and go to your library. Right click on Discord Bot Builder and select Properties.

![](https://heroku.is-a-bad.host/i/qvwi.png)

In the new window, select the Betas tab at the top then in the dropdown menu, select the beta version. If you can't open the dropdown, make sure DBB is closed.

![](https://heroku.is-a-bad.host/i/47eh.png)

### Create Your First Project

Start DBB. You will be greeted with this screen:

![](https://heroku.is-a-bad.host/i/6cyb.png)

Click on Create New Project. You should now have this screen:

![](https://heroku.is-a-bad.host/i/j0aw.png)

The Bot Folder Name is the name of your project and the name of the folder that will contain your bot. The Bot Folder Path is the directory on your computer where the new folder containing your bot will be created. For example: 

![](https://heroku.is-a-bad.host/i/7b7i.png)

The bot will be saved on my desktop in the folder and with the project name 'My First Bot'.

### Create a New Bot Account and Set it Up in DBB

Go to the [Discord Developer Portal](https://discord.com/developers). If you've never made a bot before, you should be shown this screen:

![](https://heroku.is-a-bad.host/i/njjm.png)

Create a new application and give it a name.

![](https://heroku.is-a-bad.host/i/0k7v.png)

When you've clicked Create App, this should come up:

![](https://heroku.is-a-bad.host/i/z2u6.png)

Go to Bot on the side, and create the bot:

![](https://heroku.is-a-bad.host/i/w9rx.png)

You should now have this screen:

![](https://heroku.is-a-bad.host/i/h8mz.png)

If you want to make it so only you can invite the bot _(e.g. if it's a custom bot for your server)_, just click the slider under Public Bot:

![](https://heroku.is-a-bad.host/i/a55q.png)

Copy your bot's token. **MAKE SURE TO KEEP THE TOKEN SECRET AT ALL TIMES! IF SOMEBODY GETS THE BOT TOKEN, THEY CAN ACCESS AND ABUSE YOUR BOT!**[^2]

![](https://heroku.is-a-bad.host/i/njtf.png)

Input it into DBB. Do this by selecting the Bot menu in the toolbar at the top of the screen and selecting Set Bot Token. (you could also do the keyboard shortcut **Ctrl** + **Alt** + **T**.) Then paste the token and hit Enter or click OK.

![](https://heroku.is-a-bad.host/i/ahap.png)

Now you need to invite the bot to your server. Get an invite link by going to the Bot menu in the toolbar at the top of the screen and selecting Generate Invite. (you could also do the keyboard shortcut **Ctrl** + **G**.) 

![](https://heroku.is-a-bad.host/i/rotv.png)

Then go to your web browser and paste the invite link there. Choose which server you want to invite the bot to and click Continue.

![](https://heroku.is-a-bad.host/i/31l6.png)

On the next page, a huge list of permissions will come up. Change them as you wish[^3]. Scroll down to the bottom (there will be some information about your bot) and click Authorize.

![](https://heroku.is-a-bad.host/i/fjii.png)

Finally, complete the reCAPTCHA, click Verify, and this message should display: 

![](https://heroku.is-a-bad.host/i/fgcr.png)

That means you're all set and the bot's now in your server. 

![](https://heroku.is-a-bad.host/i/ww5x.png)

### Create a Command

To create a new command, click on the green + button next to the search bar at the top of the screen. 

![](https://heroku.is-a-bad.host/i/4d54.png)

#### Customising Your Workspace

Once you have clicked on the + icon, a new workspace will be created. 

![](https://heroku.is-a-bad.host/i/y4in.png)

You can customise the thumbnail, title and description.

##### Customising the Thumbnail

To customise the thumbnail of a workspace, hover over the empty grey space on the top right of the screen. Click on it, paste an image URL and hit enter or click OK. Boom! You're done. 

![](https://heroku.is-a-bad.host/i/8une.png)

Now your workspace looks nice and pretty.

![](https://heroku.is-a-bad.host/i/nobz.png)

##### Customising the Title

To customise the title of a workspace, click on My New Workspace and change it. Simple as. 

![](https://heroku.is-a-bad.host/i/j55a.png)

##### Customising the Description

To customise the description of a workspace, click anywhere on the empty space above the 3 buttons at the bottom. Then type whatever you want. Again, simple as. 

![](https://heroku.is-a-bad.host/i/utk1.png)

#### Adding Blocks

If you right-click on any empty spot in the workspace, the Blocks menu comes up. In the Events tab, there are some blocks so the bot can execute an action. In these docs, I will use the Message Sent Event block to execute an action whenever the bot receives a message (either in the server or its DMs). 

![](https://heroku.is-a-bad.host/i/b9gb.png)

This is the beginning of your command. The Message Sent Event block has an Action Output and a Message Output. If you don't know what this means, DBB is also well documented: whenever you hover over anything, it tells you what it is: 

![](https://heroku.is-a-bad.host/i/1duq.png)

??? "Good to know"

	Server = Guild

	User =/= Member

	A member is a user that is relevant to the guild only. You can execute actions to do with a specific server with a member.

	#### Good to know
	
#### Your turn!

Use these docs and the example workspace provided to you to make your own bot!

[^1]: We only support and document the beta version of DBB as it is the rewritten version.
[^2]: If a user somehow does get access to your bot's token, you can always hit the Regenerate button next to the Copy button. Make sure to replace the bot token in DBB after you've done this!
[^3]: You can use [this website](https://discordapi.com/permissions.html) to customise your bot's invite link.
