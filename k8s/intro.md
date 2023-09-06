# K8S Interview Prep Basic Road Map

### 1. **Understand the Basics of Containerization**:
- **Why Containers?**
  - **Resources**: 
    - [Docker's Why Containers?](https://www.docker.com/why-docker)
    - [Difference Between VMs and Containers](https://www.nakivo.com/blog/docker-containers-vs-virtual-machines/)
  - **Explanation**: Containers offer a lightweight means of virtualization, allowing for more efficient resource use than traditional VMs. They encapsulate an application's code, runtime, system tools, and libraries into a single unit, ensuring consistency across different environments.
  
- **Docker**:
  - **Resources**: 
    - [Docker's Get Started Guide](https://docs.docker.com/get-started/)
    - [Docker CLI Reference](https://docs.docker.com/engine/reference/commandline/cli/)
  - **Explanation**: Docker is a platform for developing, shipping, and running applications in containers. With Docker, you define an application's environment in a Dockerfile, producing a consistent and reproducible environment.

### 2. **Introduction to Kubernetes**:
- **Concepts**:
  - **Resources**: 
    - [Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)
    - [Kubernetes Concepts](https://kubernetes.io/docs/concepts/)
  - **Explanation**: Kubernetes (K8s) is an open-source system for automating deployment, scaling, and managing containerized applications. It groups containers into "pods" and manages these pods through constructs like "services" and "deployments".
  
- **Installation & Setup**:
  - **Resources**: 
    - [Setting up Minikube](https://kubernetes.io/docs/tasks/tools/install-minikube/)
    - [Installing kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
  - **Explanation**: `Minikube` is a tool that lets you run Kubernetes locally. `kubectl` is the CLI tool for managing Kubernetes clusters.

### 3. **K8s Deep Dive**:
- **Pods**: 
  - **Resources**: 
    - [Pods in Kubernetes](https://kubernetes.io/docs/concepts/workloads/pods/)
    - [Life of a Pod](https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle/)
  - **Explanation**: A Pod can host multiple containers that form a unit of deployment. They share storage and network IP.
  
- **Services & Networking**:
  - **Resources**: 
    - [K8s Services](https://kubernetes.io/docs/concepts/services-networking/service/)
    - [K8s Networking](https://kubernetes.io/docs/concepts/services-networking/)
  - **Explanation**: Services define rules for accessing pods. Networking in Kubernetes is designed so that each pod has a unique IP.
  
- **Storage**:
  - **Resources**: 
    - [Persistent Storage in K8s](https://kubernetes.io/docs/concepts/storage/persistent-volumes/)
    - [Dynamic Volume Provisioning](https://kubernetes.io/docs/concepts/storage/dynamic-provisioning/)
  - **Explanation**: Kubernetes supports persistent storage, allowing storage resources to persist across pod restarts. Storage can be provisioned either statically or dynamically.

- **Configuration & Secrets**:
  - **Resources**: 
    - [ConfigMaps](https://kubernetes.io/docs/concepts/configuration/configmap/)
    - [Secrets](https://kubernetes.io/docs/concepts/configuration/secret/)
  - **Explanation**: ConfigMaps allow you to decouple configuration from application images, while Secrets let you store sensitive information, like passwords.

- **Deployments & Rollouts**:
  - **Resources**: 
    - [Deployments in K8s](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)
    - [Rolling Updates and Rollbacks](https://kubernetes.io/docs/tutorials/kubernetes-basics/update/update-intro/)
  - **Explanation**: Deployments describe the desired state for your apps and can update them using rolling updates. They also support rollback to previous versions.

- **Scaling & Autoscaling**:
  - **Resources**: 
    - [Scaling Deployments](https://kubernetes.io/docs/tutorials/kubernetes-basics/scale/scale-intro/)
    - [Horizontal Pod Autoscaling](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/)
  - **Explanation**: Kubernetes allows manual scaling of pods and can automatically scale them based on CPU utilization or other select metrics.

### 4. **Advanced Topics**:
- **StatefulSets, DaemonSets, Jobs, CronJobs**:
  - **Resources**: 
    - [StatefulSets](https://kubernetes.io/docs/concepts/workloads/controllers/statefulset/)
    - [DaemonSets](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/)
    - [Jobs](https://kubernetes.io/docs/concepts/workloads/controllers/job/)
    - [CronJobs](https://kubernetes.io/docs/concepts/workloads/controllers/cron-jobs/)
  - **Explanation**: StatefulSets are for stateful applications. DaemonSets ensure all nodes run a copy of a pod. Jobs run tasks once, and CronJobs schedule tasks at fixed times or intervals.

- **RBAC and Helm**:
  - **Resources**: 
    - [RBAC Authorization](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)
    - [Introduction to Helm](https://helm.sh/docs/intro/)
  - **Explanation**: RBAC lets you define access permissions and roles for your cluster. Helm is a package manager for Kubernetes, allowing you to define, install, and upgrade complex Kubernetes applications.

### 5. **Practice Hands-On**:
- **Resources**: 
  - [Katacoda Kubernetes Scenarios](https://www.katacoda.com/courses/kubernetes)
  - [Play with Kubernetes](https://labs.play-with-k8s.com/)
- **Explanation**: Engage in hands-on scenarios, challenges, and simulations. Practical experience is vital.

### 6. **Mock Interviews & Scenarios**:
- **Resources**: 
  - [Pramp](https://www.pramp.com/)
  - [Interviewing.io](https://interviewing.io/)
  - [Common Kubernetes Interview Questions](https://www.simplilearn.com/tutorials/kubernetes-tutorial/kubernetes-interview-questions)
- **Explanation**: Simulate real interview conditions, practice answering questions, and work on Kubernetes tasks/scenarios to prepare for actual interviews.

### 7. **Stay Updated**:
- **Resources**: 
  - [Kubernetes Blog](https://kubernetes.io/blog/)
  - [Kubernetes GitHub Repository](https://github.com/kubernetes/kubernetes)
- **Explanation**: Given the rapid evolution of Kubernetes and related technologies, staying updated with the latest releases, features, and best practices is essential.

The detailed roadmap provides a structured approach, but it's essential to practice hands-on and dive deep into each topic for a profound understanding.