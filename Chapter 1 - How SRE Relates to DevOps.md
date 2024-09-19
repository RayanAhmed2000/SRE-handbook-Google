# Terms
- Silos -> barriers between departments
- SRE = No more Silos

# Background on SRE
- SRE term was coined by coined by Ben Treynor Sloss, a VP of engineering at Google


# SRE vs DevOps
- DevOps and Site Reliability Engineering (SRE) share similarities in their goals of improving system reliability, scalability, and speed of delivery. However, there are distinctions in how they approach achieving these goals.
  
## Core Responsibilities of DevOps:
- Collaboration Between Teams: DevOps fosters collaboration between development (Dev) and operations (Ops) teams to streamline the software delivery pipeline.
- Automation: DevOps aims to automate repetitive tasks, including CI/CD pipelines, infrastructure provisioning, and monitoring.
- Continuous Integration & Continuous Delivery (CI/CD): DevOps focuses on creating a smooth flow of code from development to production, minimizing manual intervention.
- Infrastructure as Code (IaC): Automating infrastructure provisioning and management using tools like Terraform, Ansible, and CloudFormation.
- Monitoring & Incident Response: Implementing monitoring solutions to ensure system health and proactively address issues.
- Scalability and Security: Ensuring the infrastructure can scale and is secure through automated checks and updates.
- Cultural Transformation: Encouraging a mindset shift towards shared responsibility between development and operations.
## Core Responsibilities of SRE (According to Google):
- Service Reliability: SRE teams focus on maintaining system reliability through Service Level Indicators (SLIs) and Service Level Objectives (SLOs). The idea is **to ensure systems meet reliability standards while balancing new feature deployments.**
- Incident Management: SRE teams are responsible for **managing incidents, performing root cause analysis, and post-incident reviews (blameless postmortems).**
- Monitoring & Alerting: **Implementing robust monitoring and alerting systems,** making sure the right people are alerted during outages or issues.
- Automation: Like DevOps, SRE emphasizes automation, but with the focus of reducing toil—manual, repetitive work that doesn't contribute to long-term value.
- Capacity Planning: Ensuring systems are built with the right capacity in mind, ensuring scalability and performance under load.
- Error Budgets: A concept unique to SRE, error budgets define the acceptable level of downtime or failures in a system, allowing for controlled risks and innovation without compromising reliability.
- Production Engineering: Google SRE teams often build and operate the software engineering infrastructure that supports highly reliable systems.
## Main Difference Between DevOps and SRE (According to Google):
- Focus on Reliability vs. Speed: DevOps emphasizes continuous delivery and speed, promoting a balance between operations and development for faster delivery of features. SRE, on the other hand, is more focused on ensuring the reliability of the system, using methods like SLAs, SLOs, and error budgets.

# Concept of Toil
- SRE places a specific emphasis on reducing "toil," which is repetitive, manual tasks that don't contribute to long-term value. While DevOps seeks automation, SRE's focus on toil reduction is more structured.

# Ownership Model
In a DevOps model, development and operations teams often have shared ownership of code and infrastructure. In contrast, SRE teams usually have more defined boundaries, where developers focus on building features and SREs manage production reliability. **SREs often work closely with developers to ensure code is production-ready.**

- In summary, DevOps is more focused on collaboration and automation to improve software delivery, while SRE emphasizes reliability, with specific metrics and methods to minimize failures and improve system uptime.

 # Conclusion 
- If you think of DevOps as a philosophy and an approach to working, you can argue that SRE implements some of the philosophy that DevOps describes, and is somewhat closer to a concrete definition of a job or role than, say, “DevOps engineer.”8 So, in a way, class SRE implements interface DevOps.
- In simple words DevOps is a set of practices that tells WHAT needs to be done SRE impliments those practices and tells HOW it needs to be done.


