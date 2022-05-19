# Start/Stop EC2 Cloudformation Template

This templates deploys two resources:

- Lambda Function
- Role to execute Lambda Function

This lambda starts or stops a list of EC2 instances, it recieves an input in JSON and performs the defined action to the EC2 IDs list.

Here is an example of JSON input:

```
{
  "ACTION": "start",
  "REGION": "us-east-1",
  "INSTANCES_ID": [
    "i-xxxxxxxxxxxxxxxx1",
    "i-xxxxxxxxxxxxxxxx2",
    "i-xxxxxxxxxxxxxxxx3",
    "i-xxxxxxxxxxxxxxxx4"
  ]
}
``` 
