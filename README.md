# Doc - https://docs.aws.amazon.com/vpc/?icmpid=docs_homepage_featuredsvcs

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/3b5ba06b-1d70-474e-8000-7a6745c9afe7)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/88ead825-1e5e-4842-a8ff-4b06056b3849)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/f12c2041-51b0-45f2-9b05-12b7f665a138)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/706bb7d2-d3cd-4539-be63-fa1b27bb56c9)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/a1f15141-1f4f-4efe-83ba-eb7e4a1e4408)

Security Groups:
    Security Groups act as virtual firewalls for Amazon EC2 instances (virtual servers) at the instance level. They control inbound and outbound traffic by allowing or denying specific protocols, ports, and IP addresses.
    Each EC2 instance can be associated with one or more security groups, and each security group consists of inbound and outbound rules.
    Inbound rules determine the traffic that is allowed to reach the EC2 instance, whereas outbound rules control the traffic leaving the instance.
    Security Groups can be configured using IP addresses, CIDR blocks, security group IDs, or DNS names to specify the source or destination of the traffic.
    They operate at the instance level and evaluate the rules before allowing traffic to reach the instance.
    Security Groups are stateful, meaning that if an inbound rule allows traffic, the corresponding outbound traffic is automatically allowed, and vice versa.
    Changes made to security group rules take effect immediately.

Network Access Control Lists (NACLs):
    NACLs are an additional layer of security that operates at the subnet level. They act as stateless traffic filters for inbound and outbound traffic at the subnet boundary.
    Unlike Security Groups, NACLs are associated with subnets, and each subnet can have only one NACL. However, multiple subnets can share the same NACL.
    NACLs consist of a numbered list of rules (numbered in ascending order) that are evaluated in order from lowest to highest.
    Each rule in the NACL includes a rule number, protocol, rule action (allow or deny), source or destination IP address range, port range, and ICMP (Internet Control Message Protocol) type.
    NACL rules can be configured to allow or deny specific types of traffic based on the defined criteria.
    They are stateless, which means that if an inbound rule allows traffic, the corresponding outbound traffic must be explicitly allowed using a separate outbound rule.
    Changes made to NACL rules may take some time to propagate to all the resources using the associated subnet.


![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/811efab0-aec7-4d83-96d9-d7ecc177a027)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/9816aa41-a0be-4188-ad9c-4cb879de0c1d)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/3e70d46e-e2de-4ab4-bc33-fdbf87c18bc8)

# Go 2 aws console -- select VPC -- create VPC

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/b0768c75-01d2-448b-9683-eb49b8ae4163)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/dafdd3e8-0bdb-4df0-9690-e2ffbc15bbdb)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/e59d66c1-534b-44a7-a348-1e647ff3afac)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/4184c41e-5119-4d41-b9cf-8e9063fdf4fd)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/b9ea2376-f45e-4306-8a68-eaf26143df9e)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/6b2400c0-9590-48fd-8769-b9f6c82b206b)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/8484b1f6-fad8-4a7b-befc-2698e451d641)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/3991105e-cc56-4d6e-8420-38d305970c24)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/68c3b262-bdf1-4d51-95b9-cc227b80ce09)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/735846b9-466b-4de0-9181-5b169b9cc7ab)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/79dfc099-a486-4a54-bddb-027ea2acc3f5)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/303ef44f-77f0-41c5-ba85-740dbfa61e3b)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/8f6da820-1f45-4d36-bfff-3960f6532469)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/fbabc6bb-d58e-41a8-a76d-8c7c9043a772)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/e33e44d6-5d6e-4970-9ff8-47727dd1e2a7)

# Internet gateway activated

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/066ea01a-79fd-4448-95f7-ca858bb47d7f)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/3c845c9b-ec22-4796-aeaa-de1928d1915e)

# Now create VPC – EC2 instance with  network setting mapping to newly Created VPC(Custom- VPC)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/fe87ef82-5c03-4791-81bb-dda3fd2bae44)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/6adab7eb-0af2-4841-a508-953a06dac862)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/a3eb6119-457c-4039-85cd-0bd69982f618)

# Edit network do Changes  & select demo-vpc

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/f124fd17-6cf2-48fa-a53f-f33a5bb84494)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/694a9c35-5644-44a2-94e6-bfce82deb291)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/df6cb092-2cfa-46a3-bbcc-7119a87c1cf6)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/59259c30-d7e6-4540-a3a0-4d49aebdcb8b)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/0204010a-63fb-4aa5-beaa-758c3e22f160)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/4cdf089b-2139-4148-91fa-fde6e42ec2bb)

# Now Install Python Application run it on Port 8000

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/a00e1a27-9fa5-43b0-a12c-d1471b3558be)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/f418fcf5-0b65-48ec-b710-e4d535119471)

# Python

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/94c558b8-f19f-4f1c-b14e-19fb63d3c231)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/503eda1f-33d9-426e-a6af-5d0e9b386144)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/08345ce5-1190-40c0-a5cf-a1d3826049c5)

# https:// http://100.26.245.72:8000

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/fab11af1-eb9b-4da3-bdb1-f216f3dabfb9)


# no Access ---------------

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/c79743b5-96b7-4ad8-99a1-6e5e779988bc)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/3ee9a656-9881-496e-84e2-a5bc9de700dc)

# Security Group will allow only  port 22


# now check NACl Confirguration

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/745c8d8d-91b2-4468-b6b9-7950c944e6e7)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/92298c5d-9962-4b2e-8edd-3134d507b188)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/6fcefcae-ce8b-4bcc-ba5a-f36e606ed122)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/e2c552d9-c193-4a8b-957b-2ff5f00c6b2c)

# Go to SG Add one more Route- custom- TCP – Port 8000 enable

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/903f2d1d-c06d-44a6-aafe-232ddc12de6e)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/ac5d3502-c458-4224-9d49-8b8251e60b30)

http://publicaddress:8000

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/b73e3aef-401e-43ea-bf52-b9dbdda673dc)


# Now blocking

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/938d95b8-1afb-4629-9629-dcba78b7d03a)

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/3a1ae127-a42b-4920-82e7-30e69f7e4aa5)

# Copy same above # open Diff browser http://publicaddress:8000

![image](https://github.com/Siddhartha082/AWS_VPC_SSH_Port_Autrhentication_Security_Groups_NACL_Networks/assets/110781138/d836a84e-e49b-4faa-b276-a7b1532a80e8)


