# DevOps

A collaborative approach that allows the following teams to collaborate to continuously deliver software:

- Business owners
- Development
- Operations
- Quality Assurance

Applies agile and lean thinking principles to all stakeholders, including customers, suppliers and partners

Improves productivity through:

- Accelerated feedback cycles
- Unified measurements and collaboration
- Reduced overhead, duplication and rework

## Benefits

- Devs can produce software in short iterations
- A continuous delivery of new features and bug fixes in rapid cycles
- Businesses can seize market opportunities
- Reduces time to include customer feedback in products

## Process

- Continuous Delivery - #CD
  - Small, well-designed, high-quality increments of software to the customers
  - Continuous delivery ensures that code changes are always in a state that can be released immediately. This state allows organizations to deploy software anytime with minimal manual intervention. Tools like #Jenkins and Bamboo facilitate the automation of build, test, and deployment processes.
- Continuous Integration - #CI
  - Creating packaged builds of the code changes released as immutable images
    - Immutable meaning when modifications are needed, the entire unit is replaced
    - Developers integrate their code changes into a shared repository frequently, ensuring early detection of integration issues. Version control systems like #Git and Subversion support this process.
- Continuous Deployment - #CDep
  - Progressing each new packaged build through the deployment cycle as rapidly as possible
  - Continuous deployment takes automation further, enabling organizations to automatically deploy software changes into production environments after passing the necessary tests.
- Continuous Monitoring - #CM
  - Help devs understand performance and availability of the applications, even before they are deployed to production
  - Continuous monitoring provides real-time insights into application and infrastructure performance, allowing organizations to detect issues promptly and take proactive measures. Tools like #Prometheus and ELK Stack are commonly used for monitoring in DevOps.
- Delivery Pipeline
  - Automated sequence of steps that involves the stages of:

![Delivery Pipeline Diagram](../assets/images/Delivery-Pipeline.svg)

## DevOps in the context of [[Cloud Computing]]

DevOps provides the following solutions to cloud's complexities:

- Automated provisioning and installation
  - Documented, repeatable, verifiable and traceable
- Continuous integration and deployment pipelines
- Define how people work together and collaborate
- Test in low-cost, production-like environments
- Recover from disasters by rebuilding systems quickly and reliably
- Scalability and Flexibility
  - Cloud platforms provide the scalability and flexibility required for DevOps workflows. Organizations can leverage cloud resources to scale infrastructure dynamically, accommodate varying workloads, and optimize resource utilization based on demand.
- Cloud services seamlessly integrate with popular DevOps tools, enabling continuous integration and delivery (CI/CD). This automation streamlines build, test, and deployment processes, reducing errors and facilitating faster, more reliable software releases.

## Use Cases on Cloud Platforms

### DevOps on Amazon Web Services (AWS)

Organizations leveraging DevOps on AWS can take advantage of services such as AWS CodePipeline for CI/CD pipelines, AWS Elastic Beanstalk for simplified application deployment, and AWS Lambda for serverless computing. This use case enables seamless scalability, efficient resource management, and rapid delivery of software solution

### DevOps on Microsoft Azure

DevOps on Azure empowers organizations with services like Azure DevOps for collaboration, Azure Kubernetes Service (AKS) for container orchestration, and Azure Functions for serverless computing. Organizations can achieve automated deployments, efficient scaling, and improved application performance by leveraging these services.

### DevOps on Google Cloud Platform (GCP)

DevOps on GCP offers services such as Cloud Build for CI/CD pipelines, Google Kubernetes Engine (GKE) for container management, and Cloud Functions for serverless computing. This use case enables organizations to automate infrastructure provisioning, manage complex containerized applications effectively and optimize resource utilization.

### DevOps on IBM Cloud

DevOps on IBM Cloud provides services like IBM Continuous Delivery for automated deployments, IBM Kubernetes Service (IKS) for container orchestration, and IBM Functions for serverless computing. These use cases allow organizations to achieve streamlined software delivery, efficient infrastructure management, and seamless scaling on the IBM Cloud platform.

When combined with cloud platforms, DevOps empowers organizations to streamline software delivery, enhance collaboration, and leverage scalable resources. By implementing DevOps on popular cloud providers such as AWS, Azure, GCP, and IBM Cloud, organizations can accelerate their software delivery cycles, reduce time-to-market, and adapt to changing business needs effectively. It is a winning combination that enables organizations to stay competitive in today's fast-paced digital landscape



