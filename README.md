# KTLG
KTLG (Keep The Lights Green) is a support product and arrangement to support GoSource clients (referred to as tenants).

# KTLG software installation
## Slack app
Ensure that you are logged in to Slack with **permissions to the workspace of interest**  

Dled: Default permissions seem to be members can install apps, recommend changing in workspace settings>permissions>apps and custom integrations>approved apps
- Go to the URL https://slack-integration.mitm.ktlg.io
- Click the **Add to Slack** button
- In the top right, select the workspace
- Client **Authorize**

## Github app
Ensure that you are logged in to Github with owner permissions to the workspace of interest
- Go to the URL https://github.com/apps/ktlg-integration
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
- If ktlg-int is not displayed there, click the **plus** symbol and select ktlg-integration
- Click on ktlg-int, just as if you were sending a direct message to a person
- type `help` to see a summary of the commands available to you
- type `help {command name}` to see a description of what the command does, where {command name} is from the list displayed from the above `help` command
