# Blue Green Deployment PipeLine Plan for Test Website
- Pipeline 1
  1. Authenticate with AWS
  2. Create kubernetes cluster.
- Pipeline 2
  1. Lint HTML
  2. Build and Deploy Image
  3. Create Blue controller
  4. Create Green controller
  5. Send to Kubernetes
  6. Based on user feedback switch to Green/Blue.

- Following will be used:
Jenkins, NGINX, Docker, Kubernetes
