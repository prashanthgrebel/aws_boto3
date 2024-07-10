# # EBS

* list root devices
``` aws ec2 describe-instances --region=us-east-1 --query 'Reservations[*].Instances[*].[InstanceId,RootDeviceType,RootDeviceName]' --output table ```
