<h1>Monitor and Visualize Building Occupancy</h1>


<h2>Description</h2>
Through this project, you will be able to deploy an EC2 instance in a VPC using Terraform on macOS.
<br />

<h2>AWS Cloud Map</h2>
<p align="center">
<img src="https://i.imgur.com/zTMlvkv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<h2>Services Used</h2>

- <b>AWS IoT Core</b> 
- <b>AWS IoT Rule</b>
- <b>Amazon Kinesis</b>
- <b>Amazon S3</b>
- <b>AWS Glue</b>
- <b>Amazon Athena</b>
- <b>Amazon QuickSight</b>


<h2>Environments Used </h2>

- <b>AWS Management Console</b>
- <b>Raspberry Pi</b>




<h2>Monitor and Visualize Building Occupancy walk-through:</h2>

- <b>Install Terraform using Homebrew inside your home directory</b>
- <b>Create a user under IAM service and attach required policies</b>
- <b>Create new directory and create three empty files within this directory. ("main.tf" , "outputs.tf" , "variables.tf")</b>
- <b>Add your codes into your "main.tf" file, prompting Terraform to configure an AWS provider and also create an AWS VPC</b>
- <b>Run "terraform init" in your terminal to initilize and download the AWS provider</b>
- <b>Review the execution plan and implement the plan by using the command "terraform apply"</b>
- <b>Create a new workspace by running "terraform workspace new dev" in order to create a VPC for your enviroments</b>
- <b>After setting up your remote state file, add the following resources utilizing Terraform:</b>
  - Internet Gateway
  - 3x Public subnet — one for each AZ ("variables.tf")
  - 3x Private subnet — one for each AZ ("variables.tf")
  - 3x Database subnet — one for each AZ ("variables.tf")
  - Public subnet route table ("main.tf")
  - Private subnet route table ("main.tf")
  - Database subnet route table ("main.tf")
  - EC2 Bastion Host ("variables.tf")
  - Elastic IP Address
  - NAT Gateway





<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
