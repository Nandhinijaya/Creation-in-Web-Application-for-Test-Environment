 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
  ## AIM
       To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
    Explain about the Experiment.

## ALGORITHM
 ### Steps 1: 
 Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
 ### Steps 2: 
 Connect to the instance using SSH and install a web server like Apache
 ### Steps 3:
 Create a simple HTML file in the server's default directory with basic content for testing.
 ### Steps 4:
 Access the instance's public IP in a browser to verify the HTML page is displayed.
 
 
## COMMANDS
### To install httpd:
```
yum install httpd -y
```
### To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```
### Create a simple HTML page :
```
cd /var/www/html
sudo nano nandha.php
```

```php
<!Doctype html>
<html>
<body>
<h1>Hello Friends</h1>
<?php
echo "Hello World";
?>
</body>
</html>

```

## OUTPUT

### REG NUMBER:212222100030
### NAME:NANDHINI E

### Terminal:

![image](https://github.com/user-attachments/assets/68c5106c-cdee-4b60-80d5-fd7f3b35f008)

### Website:
![image](https://github.com/user-attachments/assets/17ae6dfb-05be-4b3c-8592-92e482d6d331)


## RESULT
 Thus the web application for test environment has successfully been created and executed.

  
