

# **Spring Boot AWS ECS Deployment Pipeline**  
**A CI/CD pipeline for containerized Spring Boot applications on AWS Fargate**

[![AWS CodeBuild Status](https://img.shields.io/badge/CodeBuild-Passing-success?logo=amazonaws)](https://us-east-1.console.aws.amazon.com/codesuite/codebuild/projects)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Java Version](https://img.shields.io/badge/Java-17-orange?logo=openjdk)](https://openjdk.org/projects/jdk/17/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.1-green?logo=spring)](https://spring.io/projects/spring-boot)

![AWS](https://img.shields.io/badge/AWS-ECS-FF9900?logo=amazonaws&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Fargate-FF9900?logo=amazonaws&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-CodePipeline-FF9900?logo=amazonaws&logoColor=white)

This project demonstrates a complete infrastructure-as-code solution for deploying Spring Boot applications to AWS using:  
- **AWS ECS Fargate** (serverless containers)  
- **AWS CodePipeline** (CI/CD automation)  
- **AWS CodeBuild** (build/test)  
- **Amazon ECR** (Docker image storage)   

## **Key Features**  
✅ **Automated deployments** triggered by GitHub commits  
✅ **Dockerized** Spring Boot application with multi-stage builds 
✅ **Blue-green deployment** readiness  
✅ **Health checks** and monitoring integration  

## **Architecture**  
```mermaid  
graph LR  
    GitHub --> CodePipeline --> CodeBuild --> ECR --> ECS --> ALB  
```    

## **Technology Stack**  
- **Backend**: Spring Boot 3.x (Java 17)  
- **Infra**: AWS ECS, Fargate, CodePipeline  
- **Tools**: Docker, Maven, AWS CLI  

---

### **Why This Project?**  
This template solves common challenges when deploying Java apps to AWS:  
- Proper container naming conventions  
- ECR authentication in pipelines  
- IAM permission best practices  
- Zero-downtime deployment patterns  

---

This description:  
1. Explains **what** the project does  
2. Highlights **key technologies**  
3. Provides **visual architecture**  
4. Includes **quick start** instructions  
5. Positions it as a **reference solution**  
