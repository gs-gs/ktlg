# Incident Lifecycle
Through proactive monitoring, KTLG endeavors to know about potential incidents before you do. However no monitoring is 
perfect so we encourage you to notify us of any potential incident you discover. This has the added benefit of identifying
interested parties to notify when the incident is resolved.

An incident progresses through a lifecycle of
* Report of a potental incident (either automated monitor or manually initiated)
* Evaluation of a potential incident by KTLG personnel
* Resolution at point of first contact for procedural issues (eg not prefixing an in-channel command with @ktlg)
* Creation of a new incident or joining to an existing incident (github ticket). Note a KTLG github ticket will be replicated to the assigned tenant/product/environment repo
* Assigning github ticket to appropriate DevOps resource
* Work will be done to identify and rectify the incident
* Once resolved the github ticket will be closed with a closure comment summarising the rectification
* All interested parties will receive a closure notification as a reply to the initiating message
* If the incident was a major incident, a Post Incident Review will be performed and sent to the Tenant contact for that product.

Out of process activities include:
* Adding comments to an incident
   * This can be through the _add comment_ slack command; or 
   * Directly into your (appropriate) github repo on the replicated ticket, which will then replicate the comment to the KTLG github ticket

