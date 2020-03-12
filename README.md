# ami

- The creation of AMI will be triggered through circleci after merging the code with the master.
- The environment variables are set directly in circleci
    - AWS REGION
    - ACCESS KEYS FOR DEV/PROD ACCOUNT
    - SUBNET ID
    - SOURCE AMI
    
The EC2 instance using the AMI-ID we wish to use for cloudformation creation
Connected to the ubuntu server EC2 instance and copied the application folder from ubuntu to ubuntu using the SCP command
Application is deployed on ubuntu and API calls a made for Bill application with EC2 instance public domain and IP address
Stopped EC2 instance when not needed by termination the stack created by cloudformation.
Trying to setup ami as something went wrong


