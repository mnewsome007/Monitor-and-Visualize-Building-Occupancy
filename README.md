<h1>Monitor and Visualize Building Occupancy</h1>


<h2>Description</h2>
Through this project, you will be able to monitor a buidlings occupancy using a Raspberry Pi along with a PIR sensor; connected to AWS IoT in oder to visualize the data with Amazon Quicksight.
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
- <b>Python SDK</b>




<h2>Monitor and Visualize Building Occupancy walk-through:</h2>

- <b>Connect and setup your PIR Sensore with your Raspberry Pi physically</b>
- <b>Within AWS IoT Core console, connect your Raspberry Pi to AWS IoT Core and register it as a "thing"; creating policy and certificates</b>
- <b>Name your "thing"</b>
- <b>Download your certificates to your Raspberry Pi using the SFTP route</b>
- <b>Install AWS IoT Python SDK in the terminal of your Raspberry Pi and create a 
.py" file for your PIR sensor</b>
- <b>Within the AWS IoT cosole,select "Interact: and copy the HTTPS endpoint into your "py" file</b>
- <b>Configure your credentials with the certificates created earlier</b>
- <b>Create a delivery stream with Amazon Kinesis "Pi-to-Kinesis"</b>
- <b>Within the AWS IoT consle,create a new AWS IoT rule and then test the reception of messages</b>
- <b>Within Amazon S3 the data can be extracted/downloaded</b>
- <b>Utilize AWS Glue console and create a table</b>
- <b>Configure Amazon Athena with Amazon QuickSight in order to analyze the date being observed</b>
- <b>Create a simple table in Amazon Athena</b>
- <b>Within Amazon QuickSight, open the console and create a "Neew analysis, New dataset" and choose Athena as a new data source</b>
- <b>Redseign your AmazonQuicksight visualization to your preferences</b>





<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
