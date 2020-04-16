# cloudformation-playground
These scripts automate deployment of a high-availability web-app using AWS CloudFormation.

## run it
Follow these steps to deploy the sample web-app "Udagram" (Apache Web Server).
- Install the aws cli, authenticate and connect your project
- `sh create-network-stack.sh`
- Check the cloudformation console and wait for the stack to be created
- `sh create-stack.sh`
- In the cloudformation console open UdagramCFStack > Outputs: Confirm the shown public DNS of your Load Balancer servers your sample application
