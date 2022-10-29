# Extension-Requests

Firestore Extension Request data model

```
{
    requestId: <id>,
    taskId: string,
    title: string,
    assignee: string,
    oldEndsOn: string,
    newEndsOn: string,
    reason: string,
    status : `PENDING | APPROVED | DENIED`
}
```