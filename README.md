# Kubernetes

The repository maintains all the deployment files necessary for deploying the below mentioned microservices using docker and kebernetes on a local setup:
- User service
- Restaurant service
- Menu Service
- Order service
## File details
|File | Use |
|-----|------|
|deployments.yaml | Contains all the configurations for mentioned services|
|ingress.yaml |Contains all the configuration for port redirection and making services available on *.local|
|mongo-deployment.yaml|Contains configuration for the MongoDB setup|
|mysql-deployment.yaml|Contains configurations for MySQL setup|
