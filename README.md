☁️ Cloud Monitoring and Alerting with AWS
This project demonstrates how to launch an EC2 instance, host a webpage, monitor the instance using AWS CloudWatch, and receive alerts via Amazon SNS when CPU usage crosses a defined threshold.

🔧 Tools and Services Used
Amazon EC2
Amazon CloudWatch
Amazon SNS (Simple Notification Service)
Microsoft Clipchamp (for video recording)
GitHub (for version control and documentation)
📌 Overview
Launched an EC2 instance in the Mumbai region.
Created a security group to allow:
SSH access (port 22)
HTTP traffic (port 80)
Deployed a simple custom HTML webpage with:
🌤️ Hello from the Cloud! Monitoring in progress!!

Styling includes:
Background image from Wallpaperflare
A square image overlaid using: Google Image
🖥️ EC2 Monitoring with CloudWatch
Enabled EC2 CPU Utilization monitoring.

Accessed metrics from: CloudWatch → Metrics → EC2 → Per-Instance Metrics

Created a visual dashboard to observe usage trends.

🚨 Alarm & Notification Setup
Alarm Name: High Alert-Alarm
Threshold: CPU Utilization > 70%
Duration: 2 consecutive evaluation periods
Notification via SNS Topic: cpu-alert-topic
Email Endpoint: rachanathunga@gmail.com
(Confirmation required via email before it becomes active)
📬 Sample Notification Description:

"High Alert: Your EC2 instance is experiencing high CPU usage. Please investigate immediately."
