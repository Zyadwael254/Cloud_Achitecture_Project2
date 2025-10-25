# Cloud_Achitecture_Project2
Cloud_Achitecture_Project2
Design a solution for a two-tier web application for client on AWS. The solution must be highly available and fault tolerant within a single AWS region. The application tiers will be deployed using EC2 instances.

The database servers must not be accessible from the internet; however, they need to access the internet for updates and security patches.

Database administrators from the corporate network need SSH access to administer the Database EC2 instances. This access should only be allowed from the corporate data center.

Access to the database servers should be limited to the application tier and the administration traffic. Any other access should not be allowed.

Database servers will need to store data in S3. This traffic should not traverse the internet.
