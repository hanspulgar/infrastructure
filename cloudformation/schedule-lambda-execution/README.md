# Schedule Lambda Execution

This templates deploys a rule to schedule a lambda execution. This matches perfectly with a lambda that turns on/off resources in order to avoid expending unnecesary compute time therefore money.

In example: you can combine this schedule with my lambda [start-stop-ec2](https://github.com/hanspulgar/infrastructure/tree/master/cloudformation/lambda/start-stop-ec2) to schedule the EC2 turning off after office hours or turn it on before starting to work.
