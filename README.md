# Project 4.0 - RideOnTrack

As part of a team project, our group was tasked with developing a full-fledged solution for RideOnTrack, a company that needed a secure, scalable, and innovative infrastructure for their business operations. The project covered four major domains: application development, artificial intelligence (AI), cloud infrastructure, and cybersecurity. My role, along with another student, focused on the cloud and cybersecurity aspects, ensuring that the system was not only robust and efficient but also fully compliant with industry regulations like ISO 27001.

**Video:** [YouTube](https://youtu.be/UOerbUoQf3A?si=1c1w2_q45qiMm5zU)

**Completed:** January 2023

## Project 4.0 - RideOnTrack

#### Application Development
The app team developed an intuitive and user-friendly platform designed to streamline internal operations at RideOnTrack. This platform was tailored to meet the specific requirements of the company's business model, offering seamless integration with existing systems. It contained various functionalities, such as actively following trains and showing deviations on the train tracks.

#### Artificial Intelligence (AI)
Our AI team integrated machine learning capabilities into the project to recognize anomalies on the track. And also to recognize traffic signs.

### My Contribution: Cloud Infrastructure and Cybersecurity
In collaboration with another student, I was responsible for both the cloud infrastructure and cybersecurity elements of the project. These components were critical for ensuring the platform's reliability, scalability, and security in a cloud-based environment.

#### Cloud Infrastructure
We designed and implemented the cloud infrastructure using AWS, leveraging Infrastructure as Code (IaC) principles with Terraform to automate and simplify resource deployments. Our goal was to ensure scalability, maintainability, and efficient resource management for RideOnTrack's business operations.

The core tasks included:
- **Network Segmentation**: The network was divided into multiple subnets, each catering to different departments within the organization. For instance, VLANs were set up for the finance, sales, and R&D teams, ensuring that sensitive data remained secure while maintaining optimal performance across the network.
- **Virtual Network Deployment**: Utilizing Terraform, we automated the deployment of critical resources like Virtual Networks (VNets) and subnets within Azure. This allowed for rapid provisioning and easy management, ensuring the company's cloud environment was both flexible and resilient.
- **High Availability and Redundancy**: To minimize downtime, we implemented redundant links and failover mechanisms. This ensured the system would remain operational even in the event of component failures, providing the organization with a highly reliable infrastructure.
- **Resource Automation**: Through the use of Terraform modules, we simplified the deployment of various cloud services, making it easy to replicate environments as needed. The infrastructure was designed to be scalable and adaptable, meeting both current and future needs.

The infrastructure component of the project was crucial for providing RideOnTrack with a scalable and secure environment, ensuring their cloud operations were efficient and future-proof.

#### Cybersecurity
For the cybersecurity part of the project, we worked closely to ensure that RideOnTrack’s cloud and network infrastructure adhered to best practices and industry regulations, specifically ISO 27001 standards. We not only implemented technical security controls but also developed a comprehensive manual to help the company maintain compliance.

The key aspects of our work included:
- **ISO 27001 Compliance**: A large portion of our work involved creating a manual to help RideOnTrack comply with ISO 27001 regulations. This manual covered guidelines on how to secure critical assets, manage risk, and respond to security incidents, aligning the company's operations with international standards.
- **Network Security**: We set up a secure network environment by implementing firewalls, Access Control Lists (ACLs), and robust password policies. These measures ensured that sensitive data was protected from unauthorized access and that traffic between different departments (via subnets and VLANs) was tightly controlled.
- **Penetration Testing**: As part of our security efforts, we conducted a comprehensive penetration test on the company's edge platform. This test was aimed at identifying vulnerabilities and assessing the platform’s resilience to external threats. The findings from this test allowed us to implement additional security controls and fine-tune the network's defenses.
- **Access Control and Encryption**: We implemented strict access control measures, including multi-factor authentication (MFA) for critical systems, ensuring that only authorized users could access sensitive data. Additionally, we enforced secure encryption standards for data both at rest and in transit, reducing the risk of data breaches.
- **Office 365 Security**: We also worked on securing the company's Office 365 environment by enforcing MFA, setting up data loss prevention (DLP) policies, and configuring conditional access rules to control access based on user behavior and location. This ensured that even the company's collaboration tools adhered to strict security policies.
- **Password Policies**: To enhance overall access security, we established strong password policies, requiring complex, regularly updated passwords for all employees. This was supplemented with a password manager, helping users generate and securely store complex passwords.
- **Incident Response Plan**: We also helped the company craft an incident response plan, outlining procedures for detecting, containing, and mitigating security breaches. This proactive approach ensures the organization can quickly respond to cybersecurity incidents while minimizing the impact on operations.

By implementing these cybersecurity measures, we ensured that RideOnTrack’s network and cloud infrastructure were not only compliant with industry regulations but also resilient against modern cyber threats.

### Conclusion
This project was a rewarding experience where we were able to combine our cloud and cybersecurity skills with the expertise of our teammates in app development and AI. The result was a comprehensive, secure, and scalable solution for RideOnTrack that addressed their operational and security needs, allowing them to operate more efficiently while safeguarding their sensitive information.
