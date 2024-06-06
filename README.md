# Setup-Simple-AD-in-the-Directory-Service
Setup Simple AD in the Directory Service

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/83b6cfb8-81bf-40ae-8b30-adafabb2d8a9)

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/9dacc2a8-d133-41a4-acb8-d002f19d3c6e)

click next

Select VPC and subnet
![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/6d7fdb08-2c9d-4f60-a3a8-17472bd80ab6)

Review and click create directory 

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/106ee798-12d9-4563-bb17-bc07d1b92588)

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/894c6277-69e6-48c0-a105-60b37d47be4a)




Launch an windows EC2 instance

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/ebe5a84f-f56e-4cfd-a5d2-299ac5288c5b)

add neccessary IAM policy AmazonEC2ReadOnlyAccess and AmazonSSMFullAccess

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/e606e660-0086-4d78-854d-f0f3f8e9062e)

connect to instance using RDP form remote use RPD client in EC2 console to generate password for your instance

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/c83f1f84-d207-426b-b7ec-fb83e64ea3f5)

connect to EC2
![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/4d092d99-9840-4655-a906-1b65658d44fd)

Join the Instance to the Simple AD Domain:

Open Server Manager.
Click on Local Server on the left panel.
Next to WORKGROUP, click on the existing workgroup name.
In the System Properties window, click on Change.
Select Domain, then enter the domain name of your Simple AD.
Click OK. 
![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/0f69b092-f596-44cb-9ed6-93e29ae9ae17)

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/a2453034-3145-41e7-988e-e4f890187825)


Troubleshoot

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/19ecd60f-4050-476f-bd34-bbc995ccfd19)

right click properties
![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/7ee2111b-ce8f-47f8-acf1-c0f60f4c6ceb)

select TCP/IPv4 and click on properties and add DNS server IP address of your active directory

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/06c62790-e0c3-46ff-8e6a-e593cf62afce)
![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/7e35a1c2-437c-461c-a4a1-270a59819087)

restart and do ping the DNS name
![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/8f32b561-9559-47fa-a78c-8751c313ecbe)


Right-click on This PC or Computer on the desktop or in File Explorer, and select Properties.
Click Advanced system settings on the left.
In the System Properties window, click the Computer Name tab and then click Change.
Join the Domain:

Select Domain and enter DemoDirectory.com (replace this with your actual domain name).
Click OK.
When prompted, enter the domain administrator credentials. Based on your setup, this should be:
Username: DEMO\Admin (if DEMO is your NetBIOS name and Admin is the default admin username)
Password: The password you set for the domain admin
Welcome to the DemoDirectory.com domanin

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/02d01988-0aba-4632-95b2-88418ae0da0a)

Restart instance after it

-------------------
Steps 

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/2838acbb-8868-4e70-b891-c1bf638f4a97)

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/b0f54f71-75cf-4b76-ba99-2c6b88e51da2)

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/0623075e-15ec-4675-a1b5-90c129b04fce)

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/9f351ea3-aaab-4f5e-8ee9-8e2269a8794b)

---------------------------------------



search Active Directory Users and Computer in search bar and click ok

![image](https://github.com/Ayyappa231096/Setup-Simple-AD-in-the-Directory-Service/assets/96643324/1ed71ba8-5ff3-4e1f-b35b-8a1c707f5a7f)









