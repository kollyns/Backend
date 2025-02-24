# DevOps Tools and Git Commands

## Favorite DevOps Tools

### 1. **Docker**
Docker is an open-source platform used to automate the deployment, scaling, and management of applications in lightweight containers.

- **Benefits**: Portability, Scalability, Version control for containers
- **Common Commands**:
    - `docker build`: Build an image from a Dockerfile.
    - `docker run`: Run a container.
    - `docker ps`: List running containers.
    - `docker images`: List Docker images.

### 2. **Kubernetes**
Kubernetes is a container orchestration platform that automates the deployment, scaling, and management of containerized applications.

- **Benefits**: Automated scaling, self-healing, rolling updates.
- **Common Commands**:
    - `kubectl get pods`: List all pods.
    - `kubectl apply -f deployment.yaml`: Deploy application from a YAML file.
    - `kubectl logs <pod-name>`: View logs of a pod.

### 3. **Jenkins**
Jenkins is an open-source automation server for continuous integration and continuous delivery (CI/CD).

- **Benefits**: Automates build and deployment pipelines, supports plugins.
- **Common Commands**:
    - `jenkins-cli build <job-name>`: Trigger a job build.
    - `jenkins-cli get-job <job-name>`: View a Jenkins job configuration.

---

## Git Commands

### 1. **git clone**
Clone a remote repository to your local machine.
```bash
git clone <repository-url>
