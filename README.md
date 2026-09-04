# Risk-assessment
## AUDITING CLOUD ACTIVITY USING AWS CLOUDTRAIL
## Objective
To audit and monitor cloud activity in AWS using AWS CloudTrail by viewing and analyzing recorded AWS events and identifying important audit information such as:

1.User identity
2.Event name
3.Event time
4.AWS service
5.Region
6.Operation status
## 1. Requirements
1.AWS Account
2.Web Browser
3.Internet Connection
4.Amazon S3 Access
5.AWS CloudTrail
## PART A — ACCESS AWS CLOUDTRAIL
## Step 1: Login to AWS
1.Open the AWS Management Console.
2.Sign in using your AWS account.
3.In the AWS search bar, type CloudTrail.
4.Select AWS CloudTrail.
Screenshot 1: AWS CloudTrail Dashboard
<img width="1920" height="1020" alt="Screenshot 2026-09-03 161056" src="https://github.com/user-attachments/assets/da8a1431-012b-430c-9e12-6489cade2cbe" />
## Step 2: Open Event History
1.In the CloudTrail navigation menu, select Event history.
2.CloudTrail displays recent AWS activity.
3.Review the available events.
The Event History page may display information such as:

1.Event Time
2.Username
3.Event Name
4.Event Source
5.Resource Type
6.Resource Name
Screenshot 2: CloudTrail Event History
<img width="1920" height="1020" alt="Screenshot 2026-09-03 161219" src="https://github.com/user-attachments/assets/7d9266dc-8434-4db4-90b6-f8547fa3302c" />
## PART B — ANALYZE A CLOUDTRAIL EVENT
## Step 3: Select an Event
1.From the Event History list, select an S3-related event.
2.Click the event to open its details.
3.Examine the event information and the event record/JSON.
4.For this experiment, a CreateKeyPair event can be used.

## Step 4: Analyze the CreateKeyPair Event
The CreateKeyPair event indicates that an Amazon EC2 bucket creation operation occurred.

## CreateKeyPair Event Observation
## Meaning of Important Fields
Screenshot 3: CreateKeyPair Event Details
<img width="1920" height="1020" alt="Screenshot 2026-09-03 161636" src="https://github.com/user-attachments/assets/5600c39c-6bdd-41ce-b480-e31ff8d08828" />
## PART C — IDENTIFY ANOTHER CLOUDTRAIL EVENT
## Step 5: Select Another Event
1.Return to CloudTrail → Event history.
2.Select another event.
3.Open its details.
4.Record the important fields.
For example, an event such as:
~~~
s3.amazonaws.com
~~~
may be present.

This event is associated with Amazon S3.

## Step 6: Analyze the Second Event
Screenshot 4: Second CloudTrail Event Details
<img width="1920" height="1020" alt="Screenshot 2026-09-03 161759" src="https://github.com/user-attachments/assets/3ed148f8-7df1-4336-b127-16fed2755079" />

