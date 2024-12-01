### 1
What does the 'Server Side Encryption' option on Amazon S3 provide?

- [x] It provides an encrypted virtual disk in the Cloud.
- [ ] It doesn't exist for Amazon S3, but only for Amazon EC2.
- [ ] It encrypts the files that you send to Amazon S3, on the server side.
- [ ] It allows to upload fi les using an SSL endpoint, for a secure transfer.

- - - - - -

### 2
What is a placement group?

- [ ] A collection of Auto Scaling groups in the same region.
- [x] A feature that enables EC2 instances to interact with each other via high bandwidth, low latency connections.
- [ ] A collection of authorized CloudFront edge locations for a distribution.
- [ ] A collection of Elastic Load Balancers in the same Region or Availability Zone.

- - - - - -

### 3
You are checking the workload on some of your General Purpose (SSD) and Provisioned IOPS (SSD) volumes and it seems that the I/O latency is higher than you require. You should probably check the [...] to make sure that your application is not trying to drive more IOPS than you have provisioned.

- [ ] amount of IOPS that are available.
- [ ] acknowledgement from the storage subsystem.
- [x] average queue length.
- [ ] time it takes for the I/O operation to complete.

- - - - - -

### 4
Within the IAM service a GROUP is regarded as a:

- [ ] A collection of AWS accounts.
- [ ] It's the group of EC2 machines that gain t he permissions specified in the GROUP.
- [ ] There's no GROUP in IAM, but only USERS and RESOURCES.
- [x] A collection of users.

- - - - - -

### 5
Doug has created a VPC with CIDR 10.201.0.0/16 in his AWS account. in this VPC he has created a public subnet with CIDR block 10.201.31.0/24. While launching a new EC2 from the console, he is not able to assign the private IP address 10.201.31.6 to this instance. Which is the most likely reason for this issue?

- [ ] Private IP address 10.201.31.6 is blocked via ACLs in Amazon infrastructure as a part of platform security.
- [x] Private address IP 10.201.31.6 is currently assigned to another interface.
- [ ] Private IP address 10.201.31.6 is not part of the associated subnet's IP address range.
- [ ] Private IP address 10.201.31.6 is reserved by Amazon for IP networking purposes.

- - - - - -

### 6
A user is planning to make a mobile game which can be played online or offline and will be hosted on EC2. The user wants to ensure that if someone breaks the highest score or they achieve some milestone they can inform all their colleagues through email. Which of the below mentioned AWS services helps achieve this goal?

- [ ] AWS Simple Workflow Service.
- [x] AWS Simple Email Service.
- [ ] Amazon Cognito.
- [ ] AWS Simple Queue Service.

- - - - - -

### 7
Is creating a Read Replica of another Read Replica supported?

- [ ] Only in VPC.
- [ ] Yes.
- [ ] Only in certain regions.
- [x] No.

- - - - - -

### 8
Which of the following is NOT a characteristic of Amazon Elastic Compute Cloud (Amazon EC2)?

- [ ] It can be used to launch as many or as few virtual servers as you need.
- [x] It increases the need to forecast traffic by providing dynamic IP addresses for static cloud computing.
- [ ] It eliminates your need to invest in hardware up front, so you can develop and deploy applications faster.
- [ ] It offers scalable computing capacity in the Amazon Web Services (AWS) cloud.

- - - - - -

### 9
A user has launched one EC2 instance in the US East region and one in the US West region. The user has launched an RDS instance in the US East region. How can the user configure access from both the EC2 instances to RDS?

- [ ] It is not possible to access RDS of the US East region from the US West region.
- [ ] Configure the US West region's security group to allow a request from the US East region's instance and configure the RDS security group's ingress rule for the US East EC2 group.
- [x] Configure the security group of the US East region to allow traffic from the US West region's instance and configure the RDS security group's ingress rule for the US East EC2 group.
- [ ] Configure the security group of both instances in the ingress rule of the RDS security group.

- - - - - -

### 10
What happens to the 1/0 operations while you take a database snapshot?

- [ ] 1/0 operations to the database are suspended for an hour while the backup is in progress.
- [ ] 1/0 operations to the database are sent to a Replica (if available) for a few minutes while the backup is in progress.
- [ ] 1/0 operations will be functioning normally.
- [x] 1/0 operations to the database are suspended for a few minutes while the backup is in progress.

- - - - - -

### 11
When an EC2 EBS-backed (EBS root) instance is stopped, what happens to the data on any ephemeral store volumes?

- [ ] Data is automatically saved in an EBS volume.
- [x] Data is unavailable until the instance is restarted.
- [ ] Data will be deleted and will no longer be accessible.
- [ ] Data is automatically saved as an EBS snapshot.

- - - - - -

### 12
[...] is a durable, block-level storage volume that you can attach to a single, running Amazon EC2 instance.

- [ ] Amazon S3.
- [x] Amazon EBS.
- [ ] None of these.
- [ ] All of these.

- - - - - -

### 13
A favored client needs you to quickly deploy a database that is a relational database service with minimal administration as he wants to spend the least amount of time administering it. Which database would be the best option?

- [ ] Amazon SimpleDB.
- [ ] Your choice of relational AMIs on Amazon EC2 and EB.
- [x] Amazon RDS.
- [ ] Amazon Redshift.

- - - - - -

### 14
You have a number of image files to encode. in an Amazon SQS worker queue, you create an Amazon SQS message for each file specifying the command (jpeg-encode) and the location of the file in Amazon S3. Which of the following statements best describes the functionality of Amazon SQS?

- [x] Amazon SQS is a distributed queuing system that is optimized for horizontal scalability, not for single-threaded sending or receiving speeds.
- [ ] Amazon SQS is for single-threaded sending or receiving speeds.
- [ ] Amazon SQS is a non-distributed queuing system.
- [ ] Amazon SQS is a distributed queuing system that is optimized for vertical scalability and for single-threaded sending or receiving speeds.

- - - - - -

### 15
While creating an Amazon RDS DB, your first task is to set up a DB [...] that controls what IP addresses or EC2 instances have access to your DB Instance.

- [ ] Security Pool.
- [ ] Secure Zone.
- [ ] Security Token Pool.
- [x] Security Group.

- - - - - -

### 16
After launching an instance that you intend to serve as a NAT (Network Address Translation) device in a public subnet you modify your route tables to have the NAT device be the target of internet bound traffic of your private subnet. When you try and make an outbound connection to the internet from an instance in the private subnet, you are not successful. Which of the following steps could resolve the issue?

- [x] Disabling the Source/Destination Check attribute on the NAT instance.
- [ ] Attaching an Elastic IP address to the instance in the private subnet.
- [ ] Attaching a second Elastic Network Interface (EN I) to the NAT instance, and placing it in the private subnet.
- [ ] Attaching a second Elastic Network Interface (ENI) to the instance in the private subnet, and placing it in the public subnet.

- - - - - -

### 17
Which of the following would you use to list your AWS Import/Export jobs?

- [ ] Amazon RDS.
- [ ] AWS Import/Export Web Service Tool.
- [x] Amazon S3 REST API.
- [ ] AWS Elastic Beanstalk.

- - - - - -

### 18
Company B is launching a new game app for mobile devices. Users will log into the game using their existing social media account to streamline data capture. Company B would like to directly save player data and scoring information from the mobile app to a DynamoDS table named Score Data. When a user saves their game the progress data will be stored to the Game state S3 bucket. What is the best approach for storing data to DynamoDB and S3?

- [ ] Use an EC2 Instance that is launched with an EC2 role providing access to the Score Data DynamoDB table and the GameState S3 bucket that communicates with the mobile app via web services.
- [x] Use temporary security credentials that assume a role providing access to the Score Data DynamoDB table and the Game State S3 bucket using web identity federation.
- [ ] Use Login with Amazon allowing users to sign in with an Amazon account providing the mobile app with access to the Score Data DynamoDB table and the Game State S3 bucket.
- [ ] Use an IAM user with access credentials assigned a role providing access to the Score Data DynamoDB table and the Game State S3 bucket for distribution with the mobile app.

- - - - - -

### 19
If your DB instance runs out of storage space or file system resources, its status will change to [...] and your DB Instance will no longer be available.

- [ ] storage-overflow.
- [x] storage-full.
- [ ] storage-exceed.
- [ ] storage-overage.

- - - - - -

### 20
Your application is using an ELB in front of an Auto Scaling group of web/application servers deployed across two AZs and a Multi-AZ RDS Instance for data persistence. The database CPU is often above 80% usage and 90% of 1/0 operations on the database are reads. To improve performance you recently added a single-node Memcached ElastiCache Cluster to cache frequent DB query results. in the next weeks the overall workload is expected to grow by 30%. Do you need to change anything in the architecture to maintain the high availability or the application with the anticipated additional load? Why?

- [x] Yes, you should deploy two Memcached ElastiCache Clusters in different AZs because the RDS instance will not be able to handle the load if the cache node fails.
- [ ] No, if the cache node fails you can always get the same data from the DB without having any availability impact.
- [ ] No, if the cache node fails the automated ElastiCache node recovery feature will prevent any availability impact.
- [ ] Yes, you should deploy the Memcached ElastiCache Cluster with two nodes in the same AZ as the RDS DB master instance to handle the load if one cache node fails.

- - - - - -

### 21
How many Elastic IP by default in Amazon Account?

- [ ] 1 Elastic IP.
- [ ] 3 Elastic IP.
- [ ] 5 Elastic IP.
- [x] 0 Elastic IP.

- - - - - -

### 22
What would be the best way to retrieve the public IP address of your EC2 instance using the CLI?

- [ ] Using tags.
- [ ] Using traceroute.
- [ ] Using ipconfig.
- [x] Using instance metadata.

- - - - - -

### 23
A company is building a two-tier web application to serve dynamic transaction-based content. The data tier is leveraging an Online Transactional Processing (OLTP) database. What services should you leverage to enable an elastic and scalable web tier?

- [x] Elastic Load Balancing, Amazon EC2, and Auto Scaling.
- [ ] Elastic Load Balancing, Amazon RDS with Multi-AZ, and Amazon S3.
- [ ] Amazon RDS with Multi-AZ and Auto Scaling.
- [ ] Amazon EC2, Amazon DynamoDB, and Amazon S3.

- - - - - -

### 24
You are designing a connectivity solution between on-premises infrastructure and Amazon VPC. Your server's on-premises will De communicating with your VPC instances. You will De establishing IPSec tunnels over the internet You will be using VPN gateways and terminating the IPsec tunnels on AWS supported customer gateways. Which of the following objectives would you achieve by implementing an IPSec tunnel as outlined above? (Choose 4 answers)

- [ ] End-to-end protection of data in transit.
- [ ] End-to-end Identity authentication.
- [x] Data encryption across the Internet.
- [x] Protection of data in transit over the Internet.
- [x] Peer identity authentication between VPN gateway and customer gateway.
- [x] Data integrity protection across the Internet.

- - - - - -

### 25
You have been storing massive amounts of data on Amazon Glacier for the past 2 years and now start to wonder if there are any limitations on this. What is the correct answer to your question?

- [ ] The total volume of data is limited but the number of archives you can store are unlimited.
- [ ] The total volume of data is unlimited but the number of archives you can store are limited.
- [x] The total volume of data and number of archives you can store are unlimited.
- [ ] The total volume of data is limited and the number of archives you can store are limited.

- - - - - -

### 26
How are the EBS snapshots saved on Amazon S3?

- [ ] Exponentially.
- [x] Incrementally.
- [ ] EBS snapshots are not stored in the Amazon S3.
- [ ] Decrementally.

- - - - - -

### 27
An online gaming site asked you if you can deploy a database that is a fast, highly scalable NoSQL database service in AWS for a new site that he wants to build. Which database should you recommend?

- [x] Amazon DynamoDB.
- [ ] Amazon RDS.
- [ ] Amazon Redshift.
- [ ] Amazon SimpleDB.

- - - - - -

### 28
You have three Amazon EC2 instances with Elastic IP addresses in the US East (Virginia) region, and you want to distribute requests across all three IPs evenly for users for whom US East (Virginia) is the appropriate region. How many EC2 instances would be sufficient to distribute requests in other regions?

- [ ] 3.
- [ ] 9.
- [ ] 2.
- [x] 1.

- - - - - -

### 29
You are the new IT architect in a company that operates a mobile sleep tracking application. When activated at night, the mobile app is sending collected data points of 1 kilobyte every 5 minutes to your backend. The backend takes care of authenticating the user and writing the data points into an Amazon DynamoDB table. Every morning, you scan the table to extract and aggregate last night's data on a per user basis, and store the results in Amazon S3. Users are notified via Amazon 5M5 mobile push notifications that new data is available, which is parsed and visualized by The mobile app Currently you have around lOOk users who are mostly based out of North America. You have been tasked to optimize the architecture of the backend system to lower cost what would you recommend? (Choose 2 answers)

- [x] Create a new Amazon DynamoDB able each day and drop the one for the previous day after its data is on Amazon S3.
- [ ] Have the mobile app access Amazon DynamoDB directly instead of J50N files stored on Amazon S3.
- [x] Introduce an Amazon SQS queue to buffer writes to the Amazon DynamoDB table and reduce provisioned write throughput.
- [ ] Introduce Amazon Elasticache to cache reads from the Amazon DynamoDB table and reduce provisioned read throughput.
- [ ] Write data directly into an Amazon Redshift cluster replacing both Amazon DynamoDB and Amazon S3.

- - - - - -

### 30
You are implementing a URL whitelisting system for a company that wants to restrict outbound HTTP'S connections to specific domains from their EC2-hosted applications you deploy a single EC2 instance running proxy software and configure It to accept traffic from all subnets and EC2 instances in the VPC. You configure the proxy to only pass through traffic to domains that you define in its whitelist configuration You have a nightly maintenance window or 10 minutes where all instances fetch new software updates. Each update Is about 200MB in size and there are 500 instances in theVPC that routinely fetch updates After a few days you notice that some machines are failing to successfully download some, but not all of their updates within the maintenance window. The download URLs used for these updates are correctly listed in the proxy's whitelist configuration and you are able to access them manually using a web browser on the instances. What might be happening? (Choose 2 answers)

- [x] You are running the proxy on an undersized EC2 instance type so network throughput is not sufficient for all instances to download their updates in time.
- [x] You are running the proxy on a sufficiently-sized EC2 instance in a private subnet and its network throughput is being throttled by a NAT running on an undersized EC2 instance.
- [ ] The route table for the subnets containing the affected EC2 instances is not configured to direct network traffic for the software update locations to the proxy.
- [ ] You have not allocated enough storage to t he EC2 instance running the proxy so the network buffer is filling up, causing some requests to fail.
- [ ] You are running the proxy in a public subnet but have not allocated enough EIPs to support the needed network throughput through the Internet Gateway (IGW).

- - - - - -

### 31
You are playing around with setting up stacks using JSON templates in CloudFormation to try and understand them a little better. You have set up about 5 or 6 but now start to wonder if you are being charged for these stacks. What is AWS's billing policy regarding stack resources?

- [ ] You are not charged for the stack resources if they are not taking any traffic.
- [x] You are charged for the stack resources for the time they were operating (even if you deleted the stack right away).
- [ ] You are charged for the stack resources for the time they were operating (but not if you deleted the stack within 60 minutes).
- [ ] You are charged for the stack resources for the time they were operating (but not if you deleted the stack within 30 minutes).

- - - - - -

### 32
What does Amazon Cloud Formation provide?

- [ ] The ability to setup Autoscaling for Amazon EC2 instances.
- [ ] None of these.
- [ ] A templated resource creation for Amazon Web Services.
- [x] A template to map network resources for Amazon Web Services.

- - - - - -

### 33
You are signed in as root user on your account but there is an Amazon S3 bucket under your account that you cannot access. What is a possible reason for this?

- [x] An IAM user assigned a bucket policy to an Amazon S3 bucket and didn't specify the root user as a principal
- [ ] The S3 bucket is full.
- [ ] The S3 bucket has reached the maximum number of objects allowed.
- [ ] You are in the wrong Availability Zone.

- - - - - -

### 34
When creation of an EBS snapshot is initiated, but not completed, the EBS volume?

- [ ] Can be used while the snapshot is in progress.
- [ ] Cannot be detached or attached to an EC2 instance until the snapshot completes.
- [ ] Can be used in read-only mode while the snapshot is in progress.
- [x] Cannot be used until the snapshot completes.

- - - - - -

### 35
What does Amazon SES stand for?

- [ ] Simple Elastic Server.
- [x] Simple Email Service.
- [ ] Software Email Solution.
- [ ] Software Enabled Server.

- - - - - -

### 36
You receive a bill from AWS but are confused because you see you are incurring different costs for the exact same storage size in different regions on Amazon S3. You ask AWS why this is so. What response would you expect to receive from AWS?

- [ ] We charge less in different time zones.
- [x] We charge less where our costs are less.
- [ ] This will balance out next bill.
- [ ] It must be a mistake.

- - - - - -

### 37
Disabling automated backups [...] disable the point-in-time recovery.

- [ ] if configured to can.
- [ ] will never.
- [x] will.

- - - - - -

### 38
A user has launched a large EBS backed EC2 instance in the US-East-1a region. The user wants to achieve Disaster Recovery (DR) for that instance by creating another small instance in Europe. How can the user achieve DR?

- [ ] Copy the instance from the US East region to the EU region.
- [ ] Use the 'Launch more like this' option to copy the instance from one region to another.
- [ ] Copy the running instance using the 'Instance Copy' command to the EU region.
- [x] Create an AMI of the instance and copy the AMI to the EU region. Then launch the instance from the EU AMI.

- - - - - -

### 39
How many relational database engines does RDS currently support?

- [x] Three: MySQL, Oracle and Microsoft SQL Server.
- [ ] Just two: MySQL and Oracle.
- [ ] Five: MySQL, PostgreSQL, MongoDB, Cassandra and SQLite.
- [ ] Just one: MySQL.

- - - - - -

### 40
Are you able to integrate a multi-factor token service with the AWS Platform?

- [ ] Yes, you can integrate private multi-factor token devices to authenticate users to the AWS platform.
- [ ] No, you cannot integrate multi-factor token devices with the AWS platform.
- [x] Yes, using the AWS multi-factor token devices to authenticate users on the AWS platform.

- - - - - -

### 41
What is the default maximum number of MFA devices in use per AWS account (at the root account level)?

- [x] 1.
- [ ] 5.
- [ ] 15.
- [ ] 10.

- - - - - -

### 42
Select the correct statement: Within Amazon EC2, when using Linux instances, the device name /dev/sda1 is [...].

- [ ] reserved for EBS volumes.
- [ ] recommended for EBS volumes.
- [ ] recommended for instance store volumes.
- [x] reserved for the root device.

- - - - - -

### 43
Does Amazon Route 53 support NS Records?

- [ ] Yes, it supports Name Service records.
- [ ] No.
- [ ] It supports only MX records.
- [x] Yes, it supports Name Server records.

- - - - - -

### 44
Your web application front end consists of multiple EC2 instances behind an Elastic Load Balancer. You configured ELB to perform health checks on these EC2 instances, if an instance fails to pass health checks, which statement will be true?

- [ ] The instance gets terminated automatically by the ELB.
- [ ] The instance gets quarantined by the ELB for root cause analysis.
- [ ] The instance is replaced automatically by the ELB.
- [x] The ELB stops sending traffic to the instance that failed its health check.

- - - - - -

### 45
George has launched three EC2 instances inside the US-East-1a zone with his AWS account. Ray has launched two EC2 instances in the US-East-1a zone with his AWS account. Which of the below mentioned statements will help George and Ray understand the Availability Zone (AZ) concept better?

- [ ] All the instances of George and Ray can communicate over a private IP with a minimal cost.
- [x] The US-East-1a region of George and Ray can be different Availability Zones.
- [ ] All the instances of George and Ray can communicate over a private IP without any cost.
- [ ] The instances of George and Ray will be running in the same data centre.

- - - - - -

### 46
Once again your customers are concerned about the security of their sensitive data and with their latest enquiry ask about what happens to old storage devices on AWS. What would be the best answer to this question?

- [ ] AWS reformats the disks and uses them again.
- [x] AWS uses the techniques detailed in DoD 5220.22-M to destroy data as part of the decommissioning process.
- [ ] AWS uses their own proprietary software to destroy data as part of the decommissioning process.
- [ ] AWS uses a 3rd party security organization to destroy data as part of the decommissioning process.

- - - - - -

### 47
Which of the following are characteristics of Amazon VPC subnets? (Choose 2 answers)

- [ ] Each subnet spans at least 2 Availability Zones to provide a high-availability environment.
- [x] Each subnet maps to a single Availability Zone.
- [ ] CIDR block mask of/25 is the smallest range supported.
- [ ] By default, all subnets can route between each other, whether they are private or public.
- [x] Instances in a private subnet can communicate with the Internet only if they have an Elastic IP.

- - - - - -

### 48
Which AWS instance address has the following characteristics? 'If you stop an instance, its Elastic IP address is unmapped, and you must remap it when you restart the instance.'

- [ ] Both A and B.
- [ ] None of these.
- [ ] VPC Addresses.
- [x] EC2 Addresses.

- - - - - -

### 49
You are designing a data leak prevention solution for your VPC environment. You want your VPC Instances to be able to access software depots and distributions on the Internet for product updates. The depots and distributions are accessible via third party CONs by their URLs. You want to explicitly deny any other outbound connections from your VPC instances to hosts on the internet. Which of the following options would you consider?

- [x] Configure a web proxy server in your VPC and enforce URL-based ru les for outbound access Remove default routes.
- [ ] Implement security groups and configure outbound rules to only permit traffic to software depots.
- [ ] Move all your instances into private VPC subnets remove default routes from all routing tables and add specific routes to the software depots and distributions only.
- [ ] Implement network access control lists to all specific destinations, with an Implicit deny as a rule.

- - - - - -

### 50
What is an isolated database environment running in the cloud (Amazon RDS) called?

- [x] DB Instance.
- [ ] DB Unit.
- [ ] DB Server.
- [ ] DB Volume.

- - - - - -
