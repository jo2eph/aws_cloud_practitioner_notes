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

---

## Infrastructure and Automation

---

Previous: [Module 3: Exploring Compute Services](https://github.com/jo2eph/aws_cloud_practitioner_notes/tree/main/03_Exploring_Compute_Services)

Next: [Module 5: Networking](https://github.com/jo2eph/aws_cloud_practitioner_notes/tree/main/05_Networking)
