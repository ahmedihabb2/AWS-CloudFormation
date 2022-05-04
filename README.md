### Deploy a high-availability web app using CloudFormation


![Udagram](https://user-images.githubusercontent.com/57008633/166841484-ce2dd015-2bda-46b0-bc1d-cbc9c271746d.png)

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
