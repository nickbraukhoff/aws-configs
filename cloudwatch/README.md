#How to apply Cloudwatch Configs Using EC2 RunCommand

###Cloudwatch Configuration Documentation
* [Cloudwatch Logs] (http://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html?shortFooter=true)
* [AWS:Cloudwatch] (http://docs.aws.amazon.com/ssm/latest/APIReference/aws-cloudWatch.html)
* [Cloudwatch Configuration Using EC2 RunCommand] (http://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/remote-commands-cloudwatch.html)

###Steps to Upload Configuration to EC2 Instance
1. Log into AWS and select the EC2 Service
2. Select **Run Command** from the **SYSTEMS MANAGER SERVICES** menu
3. Click **Run a Command** button located at the top of the page
4. In the **Command document** select **AWS-ConfigureCloudWatch**
5. Select **Target Instance** 
6. Copy and Paste the json config file into the **Properties** text field
7. Click **Run** found at the bottom right of the webpage
