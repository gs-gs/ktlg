# KTLG
KTLG (Keep The Lights Green) is a support product and arrangement to support GoSource clients (referred to as tenants).

# KTLG software installation
## Slack app
Ensure that you are logged in to Slack with permissions to the workspace of interest  

- Go to the URL https://slack.mitm.ktlg.io
- Click the **Add to Slack** button
- In the top right, select the workspace
- Client **Authorize**

<details><summary><b>Extra permissions info</b></summary>
  
Default permissions in Slack allow any member of the workspace to install an app. We recommend changing this setting to only allow owners to install apps. 

**Note:** The application need only be installed into a workspace **once**, not once per user

To do this:
 - click on the **name of your workspace then workspace settings**. This opens a browser tab
 - Under the Permissions tab, scroll down to **Apps & Custom Integrations**, and select **Manage permissions for apps and integrations in the App Directory**
 - Turn on **Approved Apps**  

   This setting allows a workspace owner to select apps that Members are then able to install at will, as well as allowing owners to install any apps they wish 
</details>

## Github app
Ensure that you are logged in to Github with owner permissions to the organisation of interest
- Go to the URL https://github.com/apps/ktlg
- Click the **Install** button
- Select **Only select repositories**
- Select the appropriate repositories.  Note: typing a partial name in the textbox under **Only select repositories** will display the matching repositories below
- Click the **Install** button

# KTLG activation
For KTLG to be any use you need to invite the bot to monitor specific channels.
- Log into Slack
- In a channel you want monitored by KTLG type `/invite @ktlg-int`

# KTLG use
If you forget your options, you can always ask the bot.  
- Go to the Apps area on the left hand menu
- If ktlg is not displayed there, click the **plus** symbol and select ktlg
- Click on ktlg, just as if you were sending a direct message to a person
- type `help` to see a summary of the commands available to you
- type `help {command name}` to see a description of what the command does, where {command name} is from the list displayed from the above `help` command
## Initial Basic Set-up
Doing these should cover basic set-up:
 - Assign the workspace to yourself (and optionally a product or environment) using the assign workspace command
 - Assign github repos to your products and environments using the assign repo command
 - Set up channels for each of your products and environments (see below)
 - Set up a chat channel(s) to communicate without going through github (see below)
## Setting up a channel to be monitored
After installing the app:
 - Create a channel for the monitoring
 - Install and set up an app to monitor your service
 - Invite the ktlg bot to the channel using /invite @ktlg-int
 - To associate this channel with a particular product and/or environment, direct message the bot and use the assign channel command
## Setting up a chat channel
To facilitate two-way communication with the ktlg team directly through Slack:
 - Create a channel and invite the bot
 - Post a message in the channel requesting that the channel become a chat channel  
