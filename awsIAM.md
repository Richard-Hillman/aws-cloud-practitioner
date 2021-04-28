Identity and Access Management 
------------------------------
root account not used or shared 



users are people in your org. you can group them 

allow them to use our accounts with permissions 

assign policies 



least privelege principle - users get the least amount of privelages that they need 



tags are a way to categorize your user (engineering, supply chain, accounting

Security- use both these for iam and mfa 
---------
Password policies
Multi Factor Authentication MFA - password you know, device you own 

-virtual mfa device (google auth, authy(multiple device support)) support for multiple tokens on a single device

-universal 2nd factor U2F security key (yubikey-security device)
hardware key fob mfa device 

-hardware key fob mfa device for aws govcloud US 


IAM Roles for Services 
-------------------------
you need to assign IAM roles and permissions to those roles.

EC2 is a virtual server 
may want to perform an action on aws so you need to give permissions to the IAM role that uses the ec2 to access AWS 


IAM Security tools
--------------------
IAM credential report 
report of users and credentials 

IAM access advisor
SHows credentials to a user and when they were last used. 


IAM guiedlines and best practices 
---------------------------------
Dont use root account 
one user = one physical person 
strong password and mfa
use groups for high level permissions 
use roles for giving permissions to services 
use access keys for programmtic acess
audit permissions 
never share keys or passwords 


