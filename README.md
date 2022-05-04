### Deploy a high-availability web app using CloudFormation



### How to run ?

```bash
# Ensure that the AWS CLI is configured before runniing the command below
# Create the network infrastructure
# Check the region in the create.sh file
./create.bat myFirstStack network.yml network-parameters.json
# Create servers
# Change the AMI ID and key-pair name in the servers.yml
# Check the region in the update.sh file
./update.bat mySecStack servers.yml server-parameters.json
```