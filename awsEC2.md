ec2 = elasatic compute cloud 

rent virtual machines (EC2 Instances)
store data on virtual drives (EBS) 
distributing load across machines (ELB)
Scaling services using and auto-scaling group (ASG)

can choose linux, mac, windows ec2 virtual machine 
decide cpu 
decide RAM
decide storage space (EBS or EFS)
hardware instance store 
network Card (speed of the card) 
firewall rules: security group 
bootstrap script (ec2 User Data)

EC2 User Data scripts 
bootstrapping 
automated tasks at startup 

t2 micro free 750 hrs for free 

LAUNCHING an EC2 instance on linux 


---

INSTANCE TYPES

general purpose 
compute memory and networking good balance 
m for general 

compute optimized 
high performance processors 
ex: gaming server 
    batch processing 
    high performance 
    c for compute 

memory optimized 
fast performance for large data sets in memory 
    hp relational/ non relational databases 
    web scale caches 
    business intel 
    r for ram

storage optimized 
    storage intensive taskes large data sets on local storage 


SECURITY GROUPS
only contain allow groups 
firewall on ec2 instances 
regulate access to ports, authorised IP ranges, control of inbound, control of outbound 

not required for first exam but extremely important 
security groups can be added to multiple security groups 
locked to regions 
lives outside ec2 
good to maintain separate security group for ssh access 
if app is not accessible could be security group issue 
connection refused security worked 

classic ports to know 
ssh security shell 
port 22 log into on linux 
21 FTP file transfer protocol 
22 SFTP secure file transport protocol 
80 access unsecured websites 
443 https access secure websites 
3389 rdp remote desktop protocol
 