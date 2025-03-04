# notification-server
work-portfolio(acti)

## 1. Project Objective
1. **Enable Push Notification Service**  
   - Set up a server to integrate with AWS SNS to send push notifications to users' mobile devices.  
   - The main goal is to ensure that the product can notify users of important events or alerts in real time, improving user experience and response speed.  

## 2. Work Content
1. **Server Setup**  
   Use Node.js to set up the server, which handles notification requests from the product and integrates with AWS SNS.  

2. **Database Management**  
   Use DynamoDB to store notification service-related data, ensuring fast access and high availability.  

3. **Push Notification Integration**  
   Implement API integration with AWS SNS so that the server can send push messages to users' mobile devices.  

## 3. Technologies Used
1. **Node.js**  
   Used as the server-side development language to handle HTTP requests and interactions with AWS SNS.  

2. **DynamoDB**  
   A high-performance NoSQL database for storing push notification data.  

3. **AWS SNS**  
   Amazon Simple Notification Service, used to manage push notifications and send them to various mobile devices.  

4. **Putty**  
   A tool used for remote server connection and operation.  

## 4. Project Challenges and Solutions
1. **Push Notification Delay**  
   Network fluctuations or device status may cause push notification delays. To solve this issue, retry mechanisms and scheduling management were implemented to ensure timely and reliable delivery of push messages.  

## 5. Project Architecture Diagram
![image](https://github.com/user-attachments/assets/51ed8c0c-128e-4951-b0b5-9f4799ef2c24)

