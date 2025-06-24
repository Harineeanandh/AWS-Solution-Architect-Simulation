📌 AWS Solution Architect Simulation – Case Study

🧠 Overview
As part of the AWS APAC Solutions Architect virtual job simulation hosted on Forage, I stepped into the role of an AWS Solutions Architect to solve a real-world client challenge. The simulation was more than just a theoretical walkthrough — it involved critical thinking, cloud design decisions, cost analysis, and client-facing communication. It was one of the most engaging and hands-on cloud projects I’ve worked on to date.

📋 Client Scenario
Client: Lilly Sawyer, CTO at Fastier — a growing startup with a web application built using React (SPA frontend), Python Flask (backend), and PostgreSQL (database), all running on a single EC2 instance (t3.medium).
Pain Points:
    • Server crashes and memory overload during peak traffic
    • Slow response times
    • Downtime during deployments
    • No disaster recovery in place
    • Anticipated consistent linear growth

🧩 My Solution
I designed a scalable, resilient, and cost-aware AWS architecture tailored to Fastier’s needs. The solution centered around AWS Elastic Beanstalk to streamline infrastructure management, support auto-scaling, and facilitate zero-downtime deployments using blue/green deployment strategies.
🔧 Architecture Components:
    • Elastic Beanstalk: Orchestrated backend deployment using autoscaled EC2 instances.
    • EC2: Hosted the Python Flask application with load-based scaling.
    • RDS (PostgreSQL): Migrated their DB from a single EC2 to a fully managed and scalable RDS instance.
    • S3: Hosted the static frontend assets (HTML, CSS, JS), enabling global access with minimal latency.
    • Elastic Load Balancer: Distributed traffic across EC2 instances for fault tolerance and performance.
    • Route 53: Simplified DNS management and routing.
    • CodePipeline: Set up CI/CD pipelines to automate deployment of both frontend and backend applications.
🧑‍💻 I wrote a 700-word email proposal to the CTO, breaking down the architecture, cost variability, scalability benefits, and resilience improvements — using plain, client-friendly language.

📚 What I Learned Beyond the Simulation
While the core task required designing and explaining the Elastic Beanstalk-based setup, I took the opportunity to go much deeper:
🔍 Independent Exploration
    • Compared multiple compute solutions: Analyzed trade-offs between EC2, Lambda, Fargate, and Lightsail for different workloads and traffic patterns.
    • Explored multi-AZ vs single-AZ setups: Understood fault tolerance implications and the cost-benefit of regional redundancy.
    • Experimented with the AWS Pricing Calculator to understand how instance types, storage, and traffic affect monthly billing — an essential skill for cost optimization.
    • Dug into Blue/Green vs Rolling Deployments: Learned when to apply each based on application statefulness and downtime tolerance.
    • Reviewed VPC, Security Groups, and IAM roles to understand security best practices for a real production setup.

🛠️ Tools & Technologies Used
    • AWS Elastic Beanstalk
    • EC2, RDS, S3
    • Route 53, CodePipeline, Elastic Load Balancer
    • AWS Pricing Calculator
    • Python (Flask), React
    • Architecture Diagramming Tools (Draw.io, Lucidchart)

🎯 Why This Project Matters
This simulation sharpened my skills not only in designing scalable and resilient architectures but also in thinking like a consultant — balancing trade-offs between performance, cost, and complexity. It tested my ability to:
    • Explain technical decisions clearly to a non-technical client
    • Consider real-world deployment problems and scalability needs
    • Think proactively about disaster recovery and continuous delivery

🧾 Next Steps
I'm currently preparing for the AWS Certified Developer – Associate exam to deepen my expertise and validate my skills in real AWS environments, with a focus on:
    • Serverless deployment (Lambda, API Gateway)
    • Monitoring and logging (CloudWatch, X-Ray)
    • DynamoDB, IAM, Cognito
    • Application lifecycle and deployment strategies

✅ Summary
This simulation gave me real insight into what it's like to support a startup scaling their cloud infrastructure. It was both a technical challenge and a communication exercise — and reinforced my desire to work on backend architecture, DevOps pipelines, and cloud-native applications.
📎 View the detailed architecture diagram and proposal email here: https://github.com/Harineeanandh/AWS-Solution-Architect-Simulation

