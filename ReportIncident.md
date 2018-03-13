# Report an incident
KTLG utilises slack commands to allow tenant/project team members to report a potential incident. Because we make 
such significant use of automated monitoring, it is highly likely that the issue you are reporting is already under 
investigation. For this reason the creation of the incident is done by KTLG personnel based on your report.

In either a monitored channel or a chat channel you can make your report in normal text. Please include as much 
information as you can in order to identify the fault. For example
```
ProductX Preproduction is not processing new requests. For example request xx-12345-a
```

The KTLG personnel will review this and check against existing issues and you will receive a reply to your message 
in one of two forms

When the incident is already under investigation
```
Report actioned. Joined to https://github.com/ktlg/tickets/issues/232
```

Or when you have reported a new incident
```
Report actioned. Created an incident https://github.com/ktlg/tickets/issues/249
```

Regardless of which type of report, when the incident is resolved you will receive a reply like the following
```
Ticket closed. https://github.com/ktlg/tickets/issues/256 has been completed with the closure notes of:

Some explanation of the closure
```
