# Kubernetes-project-using-an-EKS-cluster



1) Set up an EKS Cluster with Fargate: Launched an Amazon EKS cluster and configured it to use AWS Fargate for serverless compute power.

2) Configured CLI Access: Updated the kubeconfig file to enable CLI access to the EKS cluster, ensuring smooth interaction with Kubernetes resources.

3) Created Namespace and Fargate Profile: Set up the game-2048 namespace and linked it to the alb-sample-app Fargate profile, enabling efficient resource management.

4) Deployed the 2048 App: Deployed the classic 2048 game as a Kubernetes Pod, created a service for internal exposure, and configured an Ingress resource to handle traffic routing.

5) Installed Ingress Controller: Installed and configured the AWS Load Balancer Controller to automatically manage Application Load Balancers (ALB) for the Ingress resource.

6) Configured IAM OIDC Provider: Set up an IAM OIDC provider to grant the ALB Controller the necessary permissions to manage load    balancers.

7) Deployed ALB Controller Using Helm: Used Helm charts to deploy the ALB Controller, linking it with the appropriate service account for seamless AWS resource interaction.

8) Verified Application Deployment: Checked the deployment to ensure the 2048 application is running smoothly within the EKS environment, with traffic correctly routed via ALB.

