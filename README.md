# Kubernetes Interview Questions and Answers

Kubernetes is Google’s open source system for managing Linux containers across private, public and hybrid cloud environments.

It is used to automate the deployment, scaling, maintenance, scheduling and operation of multiple application containers across clusters of nodes. It offers an excellent community and works brilliantly with all the cloud providers. So, we can say that Kubernetes is not a containerization platform, but it is a multi-container management solution.

> You could find all the answers here 👉 https://hackatrick.com/40-best-kubernetes-interview-questions-answers/.

![Kubernetes interview questions and answers](https://hackatrick.com/wp-content/uploads/2021/09/Kubernetes-interview-question-and-answer-1536x864.png)

### Q1: What is Kubernetes?

**Answer:**

The purpose of kubernetes is to manage a containerized application in various types of physical, virtual, and cloud environments. Google Kubernetes is a highly flexible container tool to deliver even complex applications, consistently. Applications run on clusters of hundreds to thousands of individual servers.


### Q2: Why do we need Kubernetes and what can it do?

**Answer:**
Kubernetes is the container that provides a good way to run and bundle your applications. We need to effectively manage the containers in the production environment that allows us to run applications. It also provides a framework to run distributed systems resiliently.

### Q3: How does Kubernetes relate to Docker?

**Answer:**
Kubernetes is a container for Docker which is more comprehensive than Docker Swarm and is designed to counter clusters of the nodes at a level in a well-defined manner. Whereas, Docker is the platform tool for building and running the Docker containers.

### Q4: What is a container?

**Answer:**
It always helps to know what is being deployed in your pod, because what’s deployment without knowing what you’re deploying in it? A container is a standard unit of software packages up code and all its dependencies.

**Two optional secondary answers I received and am OK with include:**

a) A slimmed-down image of an OS and

b) Application running in a limited OS environment.

Bonus points if you can name orchestration software that uses containers other than Docker, like your favourite Public cloud’s container service.

### Q5: How can you get a static IP for a Kubernetes load balancer?

**Answer:**
A static IP for the Kubernetes load balancer can be achieved by changing DNS records since the Kubernetes Master can assign a new static IP address.

### Q6: What do you understand about the term Kube-proxy?

**Answer:**
This is a network-proxy that runs on each and every node and also reflects as defined in the Kubernetes API. This proxy can also perform stream forwarding across a set of backends. It is one of the optional add-ons that provide the DNS cluster for the cluster APIs.

**The syntax to configure Proxy is:**

_kubectl [command] [TYPE] [NAME] [flags]_

### Q7: What are the features of Kubernetes?

**Answer:**
-   Self-Healing Capabilities
-   Automated rollouts & rollback
-   Horizontal Scaling & Load Balancing
-   Offers enterprise-ready features
-   Application-centric management
-   Auto-scalable infrastructure
-   You can create predictable infrastructure

### Q8: What is the difference between Kubernetes and Docker Swarm?

**Answer:**
-   Docker Swarm can’t do auto-scaling (as can Kubernetes); however, Docker scaling is five times faster than Kubernetes.

-   Docker Swarm does automatic load balancing of traffic between containers in a cluster, while Kubernetes requires manual intervention for load balancing such traffic.
-   Docker Swarm is Docker’s native, open-source container orchestration platform that is used to cluster and schedule Docker containers. Swarm differs from Kubernetes in the following ways:
-   Docker Swarm is more convenient to set up but doesn’t have a robust cluster, while Kubernetes is more complicated to set up but the benefit of having the assurance of a robust cluster
-   Docker Swarm doesn’t have a GUI; Kubernetes has a GUI in the form of a dashboard .
-   Docker requires third-party tools like ELK stack for logging and monitoring, while Kubernetes has integrated tools for the same
-   Docker Swarm can share storage volumes with any container easily, while Kubernetes can only share storage volumes with containers in the same pod
-   Docker can deploy rolling updates but can’t deploy automatic rollbacks; Kubernetes can deploy rolling updates as well as automatic rollbacks

### Q9: What is a node in Kubernetes?

**Answer:**
A node is the smallest fundamental unit of computing hardware. It represents a single machine in a cluster, which could be a physical machine in a data center or a virtual machine from a cloud provider. Each machine can substitute any other machine in a Kubernetes cluster. The master in Kubernetes controls the nodes that have containers..

### Q10: What are the tools that are used for container monitoring?

**Answer:**
-   In a Kubernetes cluster, Kubelet acts as a bridge between the master and the nodes.
-   Container Advisor (cAdvisor)
-   Kube-state-metrics.
-   Kubernetes Dashboard.
-   Weave Scope..

### Q11: What is a kubelet?

**Answer:**
The kubelet is a service agent that controls and maintains a set of pods by watching for pod specs through the Kubernetes API server. It preserves the pod lifecycle by ensuring that a given set of containers are all running as they should. The kubelet runs on each node and enables the communication between the master and slave nodes.

### Q12: What is Kubectl?

**Answer:**
Kubectl is a CLI (command-line interface) that is used to run commands against Kubernetes clusters. As such, it controls the Kubernetes cluster manager through different create and manage commands on the Kubernetes component.

### Q13: What is GKE?

**Answer:**
GKE is Google Kubernetes Engine that is used for managing and orchestrating systems for Docker containers. With the help of Google Public Cloud, we can also orchestrate the container cluster.

### Q14: What is Ingress Default Backend?

**Answer:**
It specifies what to do with an incoming request to the Kubernetes cluster that isn’t mapped to any backend i.e what to do when no rules being defined for the incoming HTTP request If the default backend service is not defined, it’s recommended to define it so that users still see some kind of message instead of an unclear error.\

### Q15: Define K8s?

**Answer:**
K8s is another term for Kubernetes.

### Q16: What are Kubernetes pods? ⭐⭐⭐

 See 👉 **[Answer](https://hackatrick.com/40-best-kubernetes-interview-questions-answers/)**


### Q17: Why use namespace in Kubernetes? ⭐⭐⭐

 See 👉 **[Answer](https://hackatrick.com/40-best-kubernetes-interview-questions-answers/)**


### Q18: What tasks are performed by Kubernetes?⭐⭐⭐

 See 👉 **[Answer](https://hackatrick.com/40-best-kubernetes-interview-questions-answers/)**


### Q19: What is ‘Heapster’ in Kubernetes? ⭐⭐⭐

 See 👉 **[Answer](https://hackatrick.com/40-best-kubernetes-interview-questions-answers/)**


### Q20: What are Kubernetes Minions? ⭐⭐⭐

 See 👉 **[Answer](https://hackatrick.com/40-best-kubernetes-interview-questions-answers/)**


### Q21: What are minions in the Kubernetes cluster?⭐⭐⭐

 See 👉 **[Answer](https://hackatrick.com/40-best-kubernetes-interview-questions-answers/)**


### Q22: What is ClusterIP? ⭐⭐⭐

 See 👉 **[Answer](https://hackatrick.com/40-best-kubernetes-interview-questions-answers/)**


### Q23: What is etcd? ⭐⭐⭐

 See 👉 **[Answer](https://hackatrick.com/40-best-kubernetes-interview-questions-answers/)**


### Q24: Give examples of recommended security measures for Kubernetes. ⭐⭐⭐

 See 👉 **[Answer](https://hackatrick.com/40-best-kubernetes-interview-questions-answers/)**


### Q25: Name the initial namespaces from which Kubernetes starts? ⭐⭐⭐

 See 👉 **[Answer](https://hackatrick.com/40-best-kubernetes-interview-questions-answers/)**

**Read all the 40+ questions along with answers here : [40+ Kubernetes interview questions and answers](https://hackatrick.com/40-best-kubernetes-interview-questions-answers/)**
