# Task Lifecycle
Through a monitored slack channel, you **[create a DevOps task](CreateTask.md)**. THe key difference between an incident and a task is that a task is proactive and scheduled, while an incident is reactive.

A task progresses through a lifecycle of
* Task is created (either by tenant/project team or KTLG personnel) which will create the new task (github ticket). Note a KTLG github ticket will be replicated to the assigned tenant/product/environment repo
* Assigning github ticket to appropriate DevOps resource. This may be performed in either the tenant/product/environment repo for project changes or in the KTLG repo for support issues.
* Work will be done to complete the task
* Once complete the github ticket will be closed with a closure comment summarising the completion.
* All interested parties will receive a closure notification as a reply to the initiating message

Out of process activities include:
* Adding comments to a task
   * This can be through the _add comment_ slack command; or 
   * Directly into your (appropriate) github repo on the replicated ticket, which will then replicate the comment to the KTLG github ticket

