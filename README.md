Here's a challenge for you!

Technologies:

Container Orchestration - Kubernetes
Load Balancing - Nginx Ingress Controller
Containers - Docker
Web Application - Nginx
Bonus​ Web Application (REST API) - Go
Requirements:

Get a local kubernetes cluster up and running using microk8s
1) Enable DNS, Registry and Helm3 services
2) Create a GitHub repo for the challenge in order to host your configuration files and scripts
3) Run a basic website based on a Nginx container
4) URL needs to be: ​challenge.domain.local
5) Web service must return ​Hello Flinks​ on “/” in a namespace named ​flinks
6) Nginx Ingress Controller must be must be installed in namespace ​ingress-controller (without using microk8s' ingress service)
7) Website must be highly available (HA) and load balanced using Nginx Ingress Controller
8) Bash script to restore all your configurations into a brand new cluster
9) Bonus A second web application pointing to URL ​challenge-api.domain.local​
10) Use Golang to build a basic CRUD functions API (in-memory, no persistence required)
11) It needs to use the same Load Balancer IP via Nginx Ingress Controller
Validation: Once objectives have been completed, we will validate Kubernetes yaml configurations in your cluster as well as end result which should be a highly available website once provisioned on a new cluster using your provisioning script.
