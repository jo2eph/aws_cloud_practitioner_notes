# MODULE 4: GOING GLOBAL

---

## Choosing AWS Regions

### Key considerations when choosing Regions

1. **Compliance**
2. **Proximity**
3. **Features**
4. **Pricing**

#### 1. Compliance

- Different geographical locations have varying regulatory requirements and data protection laws
- Example:
  - General Data Protection Regulation (GDPR) is designed to protect personal data and privacy of individuals within European Union (EU)
  - Online retail company operating in EU would be required to meet GDPR compliance, including obtaining proper consent for data collection and providing mechanisms for data access and deletion

#### 2. Proximity

- Consider how to achieve low latency for users
- Regions closer to user base minimize data travel time, reduces latency and enhance application responsiveness
- Regions farther away from customers could introduce delays, which might impact user satisfaction and system efficiency

#### 3. Feature availability

- Consider which specific features and services are available in each Region
- AWS is constantly expanding features and services to multiple locations
- But not all Regions contain all AWS offerings
- Example:
  - AWS GovCloud Regions are specifically designed to meet the compliance and security requirements of US government agencies and their contractors
  - These regions have stringent physical, operational, and personnel security controls in place
  - These controls are only available in specific Regions to meet certain governmental regulatory requirements

#### 4. Pricing

- Some Regions have lower operational costs than others
- These costs can impact overall expenses for hosting applications and services
- Tax laws and regulations can also play a role in costs
- Some Regions might offer tax incentives or have lower tax rates
- Data sovereignty law in certain Regions might require data to be stored locally, affecting both compliance and cost

---

## Diving Deeper into AWS Global Infrastructure

### Deploying multi-Region and multi-AZ resources

- **High availability:**
  - Capability of a system to operate continuously without failing
  - Applications can handle failure of individual components without significant downtime
- **Agility:**
  - Ability to quickly adapt to changing requirements or market conditions
  - With AWS infrastructure in place, you can modify and deploy services rapidly
- **Elasticity:**
  - Ability of a system to scale resources up or down automatically in response to changes in demand

### Edge locations

- AWS has global edge network that provides quicker content access to users outside of standard Regions
- Edge locations strategically placed in areas like Atlanta or Shanghai to provide low-latency access to AWS services and content delivery
- Edge locations offer multiple services to run closer to end users
- Includes AWS networking services like Amazon CloudFront
  - CloudFront: a Content Delivery Network (CDN) and caching system

---

## Infrastructure and Automation

### CloudFormation

- **CloudFormation:** Service that helps model and set up AWS resources
- Spend less time managing resources and more time focusing on applications
- Define your infrastructure as code
- Create template that describes all the AWS resources you want (e.g. EC2 instances), CloudFormation takes care of provisioning and configuring these resources

### Interacting with AWS resources

#### Programmatic Access

- AWS CLI, AWS SDKs
- Best suited for developers and those familiar with coding languages
- AWS CLI
  - Manage multiple AWS services directly from command line
  - Can automate tasks through scripts
- AWS SDKs
  - Integrate AWS services into applications by providing APIs for various programming languages
  - AWS provides documentation and sample code
- Use cases for AWS CLI actions and SDKs:
  - AWS CLI: Automate routine tasks
    - Example: Write a script to provide routine backups for service such as Amazon Elastic Block Store (EBS)
  - SDKs: Invoke APIs for one part of application process
    - Example: Use SDK to store user data in AWS storage service (e.g. S3)

#### AWS Management Console

- Web interface for managing AWS services
- Offer quick access to services, search functionality, simplified workflows
- Great option for those new to the cloud or users with minimal or no development experience
- Use cases for console:
  - Billing and cost optimization dashboards and visualizations
  - Services focused on graphical representations (e.g. Amazon QuickSight and Amazon Neptune)

#### Infrastructure as Code

- IaC tools such as CloudFormation
- Automate resource management across your organization with AWS service integrations offering efficient and repeatable resource creation and management
- Use cases for CloudFormation:
  - Managing infrastructure with DevOps such as continuous integration and delivery (CI/CD) pipelines
  - Scaling resources (e.g. EC2 instances) to multi-Region applications in consistent, repeatable way

---

Previous: [Module 3: Exploring Compute Services](https://github.com/jo2eph/aws_cloud_practitioner_notes/tree/main/03_Exploring_Compute_Services)

Next: [Module 5: Networking](https://github.com/jo2eph/aws_cloud_practitioner_notes/tree/main/05_Networking)
