## Deploying and Monitoring a Simple EC2 Web Application on AWS  

### Overview  
This project demonstrates how to deploy a simple web application on an AWS EC2 instance and configure Amazon CloudWatch to monitor key metrics such as CPU utilization, memory usage, and disk I/O. A CloudWatch dashboard is also created for real-time visualization of these metrics.  

### Features  
- Deploy a web application on an EC2 instance.  
- Set up a basic web server (Apache) to serve an HTML page.  
- Configure Amazon CloudWatch to monitor critical EC2 metrics.  
- Create a custom CloudWatch Dashboard to visualize metrics.  

### Steps to Implement  
1. **Launch an EC2 Instance**:  
   - Select the Amazon Machine Image (AMI) and instance type.  
   - Configure security groups to allow HTTP (port 80) and SSH (port 22).  

2. **Set Up a Web Server**:  
   - SSH into the EC2 instance.  
   - Install Apache and configure it to display a basic "Hello, World!" web page.  

3. **Configure CloudWatch Monitoring**:  
   - Install and configure the CloudWatch Agent to collect memory and disk space metrics.  
   - Enable default and custom metric monitoring.  

4. **Create a CloudWatch Dashboard**:  
   - Add widgets for CPU, memory, and disk metrics.  
   - Organize the dashboard for easy performance tracking.  

### Prerequisites  
- An AWS account with permissions to create EC2 instances and access CloudWatch.  
- Basic knowledge of SSH and AWS services.  


### Usage  
- View the application at the public IP address of your EC2 instance.  
- Monitor performance metrics in real-time using the CloudWatch dashboard.  

### Key Metrics Visualized  
- CPU utilization.  
- Memory usage.  
- Disk I/O operations (read/write).  
- Disk space utilization.  

