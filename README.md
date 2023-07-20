Project Title: Containerized Application Deployment on Amazon Linux-based EC2 with Kubernetes using kind

Description: 
In this project, I successfully deployed a containerized application on an Amazon Linux-based EC2 instance in the AWS environment. The objective was to host the application on a locally simulated single-node Kubernetes (K8s) cluster using the 'kind' tool. The application source code was obtained from the GitHub repository provided in Assignment 1, and I created Docker images for it, which were published in Amazon ECR in the previous assignment.

Key Accomplishments:

1. Infrastructure Setup:
   - Set up an Amazon Linux-based EC2 instance with sufficient capacity to run the Kubernetes cluster.
   - Installed all necessary prerequisites, including 'kind', 'kubectl', and 'docker' on the EC2 instance.

2. Kubernetes Cluster Creation:
   - Created a single-node Kubernetes cluster using 'kind' to simulate the K8s environment locally.

3. Application Deployment:
   - Deployed the containerized application using Kubernetes manifests for 'pod', 'replicaset', 'deployment', and 'service'.
   - Exposed the web application using a Kubernetes Service of type NodePort to allow external access.
   - Exposed MySQL using a Kubernetes Service of type ClusterIP.

4. Application Versioning:
   - Implemented application versioning, allowing both old and new versions to run simultaneously.
   - The new version of the application displayed a different message on the "add employee" screen.


Technologies and Tools Utilized:

- Amazon ECR: Securely stored container images for the application.
- Cloud 9 IDE: Utilized for application development and building container images.
- Amazon EC2: Hosted the Kubernetes cluster for application deployment.
- kind: Deployed the local Kubernetes cluster.
- kubectl: Interacted with the Kubernetes API Server to manage the cluster and application.
- Docker: Created and managed Docker images for the application.
- AWS IAM: Granted the EC2 instance access to the Amazon ECR repository.
- Terraform (Optional): Used to deploy infrastructure (if applicable).

This project demonstrated my proficiency in containerization, Kubernetes deployment, versioning, and application scaling. It also showcased my ability to work with AWS services and infrastructure management tools. The successful implementation of application versioning and Ingress configuration highlighted my skills in managing complex deployment scenarios.
