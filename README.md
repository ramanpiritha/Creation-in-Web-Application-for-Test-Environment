# EX no-6-CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
 # Date: 20-11-24
 # Name: Piritharaman R
 # Reg no: 212223230148
  ## AIM
    To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
Creating a web application for a test environment is essential to provide developers and testers with a dedicated platform to simulate, test, and validate software functionalities. The challenge lies in building an easy-to-use, scalable, and efficient application that supports realistic testing scenarios, automates workflows, and ensures smooth collaboration while minimizing setup and maintenance efforts.
## ALGORITHM
```
Step 1:
Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
Step 2:
Connect to the instance using SSH and install a web server like Apache
Step 3:
Create a simple HTML file in the server's default directory with basic content for testing.
Step 4:
Access the instance's public IP in a browser to verify the HTML page is displayed.
 ```
## COMMANDS
# webserver
```
To install httpd:

yum install httpd -y
To enable and start httpd :

systemctl enable httpd
systemctl start httpd
Create a simple HTML page :

cd /var/www/html
test.php

<!DOCTYPE html>
<html lang="en">
<head>
    <title>MY FIRST PHP!</title>
</head>
</body>
</html>
```
## OUTPUT
TERMINAL
![image](https://github.com/user-attachments/assets/622c1bdc-bb41-4592-a3c8-4943498132f7)
![image](https://github.com/user-attachments/assets/0f239180-f8d8-46f0-851e-d6ae0c084716)
![image](https://github.com/user-attachments/assets/3079b854-8167-43b5-abcd-58a156bf24a0)
WEBPAGE
![image](https://github.com/user-attachments/assets/724606fe-eac0-4b19-8750-d43f0def6673)

## RESULT
Thus the web application for test environment has successfully been created and executed. 

  


