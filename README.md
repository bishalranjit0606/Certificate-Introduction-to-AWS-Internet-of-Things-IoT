# AWS IoT Lab
This project demonstrates a simple IoT solution using several Amazon Web Services (AWS). It simulates an IoT device and connects it to the AWS cloud, where it can be monitored and controlled.

## Project Highlights

 ✅ IoT Device Simulation: An Amazon EC2 instance runs a simple Python script that simulates an IoT device, sending sensor data (temperature) to AWS IoT Core.

 ✅ Data Processing: An AWS IoT Rule is used to process the incoming data. Using SQL-like syntax, the rule checks if the temperature exceeds a defined threshold.

 ✅ Alerting: When the temperature threshold is met, the rule triggers a notification to an Amazon SNS topic. This sends an email alert to a subscribed user.

 ✅ Device Control: The project also shows how to update the device shadow to send a command back to the simulated device, instructing it to "turn on the air conditioning" to lower the temperature.

### This hands-on lab provided practical experience with core AWS services and fundamental concepts of cloud-based IoT architecture.







