# Create a DevOps task
KTLG utilises slack commands to allow tenant/project team members to create DevOps tasks. This is done with 
the _create task_ command in the appropriate channel within slack. The syntax is 
`@ktlg create task {title} -body {multi-line body}`, for example
```
@ktlg create task Create a repo with a new django project with celery worker deploy units -body 
Relates to the epic in https://github.com/SomeTenant/productX/issues/537

At a high level, this service is:
- a web service
- a database
- an async worker
- a message queue

Required: A new repo for a new django project with celery worker deploy units and CICD to support a standalone device authentication service.

Base Name: SomeTenant/devauth
Features: 
- External interfaces (ELB)
- Message queue (SQS)
- Celery worker
- Postgres (RDS)
- Reuse the existing automation environment
```
Disecting this message:
The `Relates to the epic in https://github.com/SomeTenant/productX/issues/537` is optional, but we encourage it to link the 
DevOps task to the story or epic to which it relates.

Next is a summary of the context to give any needed understanding to the DevOps personnel actioning the task

Then a clear statement of what is required

Finally all necessary information for the configuration
