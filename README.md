# Deploy-a-high-availability-web-app-using-CloudFormation

#### This code creates and deploys the infrastructure and application for an Instagram-like app from the ground up. <br/> You will begin with deploying the networking components, followed by servers, security roles and software. 

> URL to the deployed site: _http://Udagr-WebAp-1G9XF70GI0RZV-473017731.us-west-2.elb.amazonaws.com_ ~(unavailable avoiding recurring charges!)~

## Files Description:

* Udagram Web App: Udagram App Code (Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function etc ...)
* create.sh: Cloudformation create stack script. 
* update.sh: Cloudformation update stack script.
* del.sh : Cloudformation delete stack script.
* servers.yml: Udagram Project's CloudFormation script.
* network.json: Udagram Project's CloudFormation script parameters.

### Infrastructure Diagram: 
<img src="./My%20Udagram%20Infrastucture.png" width=85% >

### Helpful resources
https://www.lucidchart.com/pages/<br/> 
https://docs.aws.amazon.com/cli/latest/reference/cloudformation/create-stack.html<br/> 
https://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/API_Parameter.html<br > 
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-anatomy.html<br/> 
https://docs.aws.amazon.com/codebuild/latest/userguide/cloudformation-vpc-template.html <br/> 
https://medium.com/faun/getting-hands-dirty-with-aws-cloudformation-c20e44ea994e
