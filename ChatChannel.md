# Ask a DevOp a question
KTLG utilises a chat channel to allow tenant/project team members to ask questions of the oncall DevOps resource(s).
By convention this is named devops in your workspace, but your administrator may have changed its name. You can treat
conversations in this channel just like a conversation in any other channel with one specific difference. When you want
to mention a specific user (eg @ken9ross) in a message this will only mention a local user. As most of the DevOps will 
not be a local user, you will need to use the remote mention syntax (eg [=ken.ross]). Please note it is the userId after 
the equals sign. This can be gathered from the replication header of any message from that person.

A message that has been replicated will look like the below
```
From ktlg-production/SomeTenant-devops ken.ross

The DevOps chat channel is now active
```
From this you can see the user posting this message is ken.ross. If you want to mention him in the remote channel you 
would use the following
```
Thanks [=ken.ross]
```

