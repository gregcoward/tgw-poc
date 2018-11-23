# F5 WAF with AWS TGW POC


## Introduction

Weclome.  The above referenced CFT deploys a proof-of-concept environment as shown below.  Configuration values, (with the exception of a pre-existing SSH key pair) are hard set.
<img src="infra.png" alt="F5/AWS TGW POC">
**Important**: You may have to select the AWS region in which you want to deploy after clicking the Launch Stack button
<br><br>
**Lauch the POC Builder Template**
- *Existing Stack* which includes an external IP address (typical)
  - <a href="https://github.com/F5Networks/f5-aws-cloudformation/tree/master/supported/standalone/1nic/existing-stack/payg">**Hourly**</a>, which uses pay-as-you-go hourly billing 
    <a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=BigIp-1nic-PAYG&templateURL=https://s3.amazonaws.com/f5-cft/f5-existing-stack-payg-1nic-bigip.template">  
   <img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"/></a>
