
## **[AWS Summit London 2022](https://aws.amazon.com/events/summits/london/agenda/#Threat_detection_.26_remediation_in_the_Cloud)**


------------------------------------------------------------------------------------------------
### **Threat detection & remediation in the Cloud - Presentation**

This session provides an overview of the latest developments in AWS threat detection and remediation. We also provide an overview of the AWS services used to detect and remediate threats. You can downloawd the presentation [here](https://github.com/rferroni/aws-threat-detection-demo/blob/main/AWSSummitLondon-ThreatDetectionRemediation.pdf).

![aws-threat-detection-pic](https://github.com/rferroni/aws-threat-detection-demo/blob/main/aws-threat-detection-pic.jpeg)
**Speaker:** Rodrigo Ferroni, STAM - Security Specialist, AWS - [Linkedin](https://www.linkedin.com/in/rferroni/)

------------------------------------------------------------------------------------------------
### **Threat detection & remediation in the Cloud - Demo** 

For the demo we will:

- Create a new ECR repository with scanOnPush feature enable.
- Create a Docker image that contain (on purpuse) an old vulnerable package.
- Review how Amazon ECR integration with Amazon Inspector generate Findings.
- Create AWS Security Hub Custom Actions.
- Create EventBridge Rules for those Custom Actions with different Targets:
  - CloudWatch Log group
  - SNS Topic with Input Transformation
  - Lambda Function to modify image tags

