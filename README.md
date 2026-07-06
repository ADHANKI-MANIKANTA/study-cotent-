# study-cotent-

linux -> Docker -> Kubernetes -> Jenkins/Grafana/Prometheus

study-cotent  for future reference 
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/c82203ba-876b-471c-8120-cbef84c28250" />
<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/59aa656c-733e-42c5-909b-d64853e19abf" />
<img width="1315" height="1027" alt="image" src="https://github.com/user-attachments/assets/e1c90e79-5160-41fc-8118-4f0b1cba39cb" />
<img width="1576" height="931" alt="image" src="https://github.com/user-attachments/assets/46c1409d-850d-429a-94ae-2e7450997a85" />
<img width="1815" height="871" alt="image" src="https://github.com/user-attachments/assets/94d5653e-c356-4c9c-9667-b475b87183ad" />

<img width="1600" height="886" alt="image" src="https://github.com/user-attachments/assets/976e937b-780b-4c9c-a3d2-110c89a7c682" />

sample issue 
To print the number if it greater than all its right side number in the input
input -> 2 7 3 4 6 4 -5 1
Output -> 7 6 4 1


first interview Queation 
what kind of alerts do you acknowledge 

what are the alerts you worked on.

how do you categorise the alerts and severity for the alert 

what kind of application it is , is it customer based application ?

for customer traffic have you observed any CPU utilization, and how you troubleshooted the issue ?

about HPA in pods , and 

how do we configer HPA for this application( horizontal pod auto scalar )


          Why do we need HPA?
How does HPA know the traffic is high?
How to debug when CPU reaches 100%?
What are requests and limits in Kubernetes?
How can we define those thresholds?
What kind of performance tests are there?
How do we perform these tests – give one line answers?
If we have given only requests and no limits, what happens?
If only requests are defined for a pod, what is the default limit value?
If a pod is not getting scheduled, what will be the pod state?
How can we troubleshoot a pod in Pending state?
How to troubleshoot insufficient resources issue?
What are other reasons why a pod may not get scheduled?
If a pod is showing 3/4 running, what does it mean?
Difference between readiness and liveness probes – one line answer?
What are the parameters for readiness and liveness probes?
If liveness check fails, what will be the pod state?
If readiness check fails, what happens to the pod?
What does it mean if a pod has no node assigned?
What are the reasons for a pod not getting assigned to a node?
What are the mismatches in tolerations?
Where can we check if a node is not coming up and the reason?
What is ASG in ECS and how is it assigned?
What is CAS in Kubernetes? ( cluster auto scalar )
 
 
what kind of alerts do you acknowledge 

what are the alerts you worked on.

how do you categorise the alerts and severity for the alert 

what kind of application it is , is it customer based application ?

for customer traffic have you observed any CPU utilization, and how you troubleshooted the issue ?

about HPA in pods , and 

how do we configer HPA for this application( horizontal pod auto scalar )


          Why do we need HPA?
How does HPA know the traffic is high?
How to debug when CPU reaches 100%?
What are requests and limits in Kubernetes?
How can we define those thresholds?
What kind of performance tests are there?
How do we perform these tests – give one line answers?
If we have given only requests and no limits, what happens?
If only requests are defined for a pod, what is the default limit value?
If a pod is not getting scheduled, what will be the pod state?
How can we troubleshoot a pod in Pending state?
How to troubleshoot insufficient resources issue?
What are other reasons why a pod may not get scheduled?
If a pod is showing 3/4 running, what does it mean?
Difference between readiness and liveness probes – one line answer?
What are the parameters for readiness and liveness probes?
If liveness check fails, what will be the pod state?
If readiness check fails, what happens to the pod?
What does it mean if a pod has no node assigned?
What are the reasons for a pod not getting assigned to a node?
What are the mismatches in tolerations?
Where can we check if a node is not coming up and the reason?
What is ASG in ECS and how is it assigned?
What is CAS in Kubernetes? ( cluster auto scalar )
 
<img width="1242" height="677" alt="image" src="https://github.com/user-attachments/assets/7e859df6-bbba-4f38-80f2-f75cc092d2e6" />




Full docker flow how it works if we run any command on CLI
 
 
User runs: docker run nginx
      ↓
Docker CLI sends request
      ↓
Docker Daemon receives
      ↓
Check image locally
      ↓
Pull from registry (if needed)
      ↓
Create container layer
      ↓
Setup namespaces & cgroups
      ↓
Configure networking
      ↓
Start application process
      ↓
Container is UP and RUNNING


https://chatgpt.com/share/69aa854d-d2e8-8011-93ec-eef2f57def39

https://chatgpt.com/share/69aa854d-d2e8-8011-93ec-eef2f57def39

check this profile for terraform 
https://www.linkedin.com/redir/redirect/?url=https%3A%2F%2Fgithub%2Ecom%2FSowmyadevi2005&urlhash=C9_j&isSdui=true

<img width="1434" height="922" alt="image" src="https://github.com/user-attachments/assets/248f8e90-e2e5-412f-985a-cfee90b3f061" />

 <img width="1591" height="945" alt="image" src="https://github.com/user-attachments/assets/c4bf99d8-0863-4e72-9766-a85f561cce65" />

<img width="1514" height="670" alt="image" src="https://github.com/user-attachments/assets/2279e185-db27-4566-9d5f-b768c658eafc" />

<img width="1607" height="683" alt="image" src="https://github.com/user-attachments/assets/4bb9a671-e0ac-4ab2-8746-89875d3dcaaa" />



<img width="1906" height="1191" alt="image" src="https://github.com/user-attachments/assets/eddaf948-e450-4ffe-8189-0c65150a4a08" />

<img width="786" height="400" alt="image" src="https://github.com/user-attachments/assets/7b333bf6-54ed-4f1c-962b-1bb59406b0b2" />

Developer → Git Repo → CI Pipeline Trigger → Build → Unit Test
→ Code Quality Scan → Build Artifact → Docker Image Build
→ Push to Artifact Repository → Deploy to Dev Environment
→ Integration Testing → Deploy to QA Environment
→ QA Testing → Security Scans → UAT Environment
→ Approval → Production Deployment → Monitoring



Environment	Who Uses It	Purpose
Dev	Developers	Test new code quickly
QA / Testing	QA team	Functional testing
UAT / Staging	Product team / client	Final validation
Production	End users	Live application

<img width="1899" height="1142" alt="image" src="https://github.com/user-attachments/assets/a167106e-a6be-4897-8b2a-12774d0b3518" />


<img width="1906" height="1024" alt="image" src="https://github.com/user-attachments/assets/f087fd24-b6f9-45f3-974b-797b89abcc12" />

<img width="1888" height="988" alt="image" src="https://github.com/user-attachments/assets/ff854959-9b9f-41f7-aeee-eb54f8585265" />



https://www.linkedin.com/feed/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BbPoqluwlRsyA1wW7o7P%2Fpg%3D%3D



[2/5, 10:23] Gowtham Bro HDFC Zeta: https://www.frontlinesedutech.com/s/mycourses
[2/5, 10:23] Gowtham Bro HDFC Zeta: gowthamsaivarma001@gmail.com
[2/5, 10:23] Gowtham Bro HDFC Zeta: Gowtham@123
[2/5, 10:24] Gowtham Bro HDFC Zeta: Or gowthamsaivarma000@gmail.com


<img width="1468" height="952" alt="image" src="https://github.com/user-attachments/assets/ca11898d-6641-4d0c-8051-2e53071bcded" />

<img width="1918" height="1018" alt="image" src="https://github.com/user-attachments/assets/69f2cabe-5e4e-4f57-bb75-40c4a836590e" />


<img width="1195" height="904" alt="image" src="https://github.com/user-attachments/assets/4de001c6-e697-4824-94ba-b21824c11285" />
<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/2bc2f531-a546-4d3c-92fc-14f31a6d56dc" />
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/11adf57a-a275-4535-b9b1-462a904ed437" />
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/136dc826-cc80-4773-9bda-a1ab1a6adbb4" />
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/61991485-cefb-44ae-bca6-b3ae3f63c48b" />
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/a7707ba9-6862-456b-bd4a-5875ebcde4e0" />
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/9a5b5411-75ac-4f13-8eb9-3e26b54c5208" />
<img width="1282" height="733" alt="image" src="https://github.com/user-attachments/assets/81185b50-f20b-4791-9936-2ef4d6c20ef8" />
<img width="800" height="495" alt="image" src="https://github.com/user-attachments/assets/a896922d-6d0c-4381-bd0f-bdbe926a2bc0" />
<img width="1294" height="1098" alt="image" src="https://github.com/user-attachments/assets/96aa49fb-541a-470e-8311-28b4c6637284" />
<img width="2748" height="1826" alt="image" src="https://github.com/user-attachments/assets/f2d10fab-b9ca-48bf-8d5f-cb89a8e2e31e" />
<img width="680" height="1001" alt="image" src="https://github.com/user-attachments/assets/ce125894-79c6-437b-a333-89ec2ebd38bd" />
<img width="2627" height="4343" alt="image" src="https://github.com/user-attachments/assets/75ffcf84-387a-4efb-b197-6d814e57b078" />
<img width="1600" height="1351" alt="image" src="https://github.com/user-attachments/assets/72c4c5e9-5f2d-4f88-8f89-fc4de1cba7f3" />
<img width="1291" height="1600" alt="image" src="https://github.com/user-attachments/assets/158d2920-1e1e-42d8-901b-4e2f491726bb" />

<img width="1024" height="553" alt="image" src="https://github.com/user-attachments/assets/7a7b003d-8931-479f-aee7-05400d630b1f" />

<img width="800" height="612" alt="image" src="https://github.com/user-attachments/assets/4b3cc366-f9db-4544-9fd1-1236f5bfec01" />

<img width="1875" height="1177" alt="image" src="https://github.com/user-attachments/assets/98f9b8ec-4bb9-4548-887b-055874021ddb" />
<img width="1365" height="1929" alt="image" src="https://github.com/user-attachments/assets/5bee56fd-cd02-446e-bde1-9e761f647993" />
<img width="800" height="574" alt="image" src="https://github.com/user-attachments/assets/8bd64805-4aee-4e0e-97b2-24d9cfe0765f" />
<img width="464" height="200" alt="image" src="https://github.com/user-attachments/assets/f00f3d91-6206-43b0-9bcc-716bbaca22f3" />
<img width="1402" height="882" alt="image" src="https://github.com/user-attachments/assets/4c7cbcaa-ecec-4201-bc12-f854c5a1f9c9" />

<img width="1793" height="1793" alt="image" src="https://github.com/user-attachments/assets/e3dc8f5c-3856-49d7-a95b-5992a94f46b0" />
<img width="1684" height="480" alt="image" src="https://github.com/user-attachments/assets/49e34db1-3d2e-41f3-b93c-c550fb3554ce" />
checking inside the container like inside pod for debugging, by using above command 
kubectl exec -it <pond name which you want enter inside > --bin/bash

kubectl commands
kubectl get nodes
kubectl get pod
kubectl get services
kubectl create deployment nginx-depl --image=nginx
kubectl get deployment
kubectl get replicaset
kubectl edit deployment nginx-depl
debugging
kubectl logs {pod-name}
kubectl exec -it {pod-name} -- bin/bash
create mongo deployment
kubectl create deployment mongo-depl --image=mongo
kubectl logs mongo-depl-{pod-name}
kubectl describe pod mongo-depl-{pod-name}
delete deployment
kubectl delete deployment mongo-depl
kubectl delete deployment nginx-depl
create or edit config file
vim nginx-deployment.yaml
kubectl apply -f nginx-deployment.yaml
kubectl get pod
kubectl get deployment
delete with config
kubectl delete -f nginx-deployment.yaml
#Metrics
kubectl top The kubectl top command returns current CPU and memory usage for a cluster’s pods or nodes, or for a particular pod or node if specified.
 
Master node
 
API Server → receives request
Scheduler → assigns node
Controller → maintains state
etcd → stores everything
 
worker node
Kubelet → manages pods
Container runtime → runs containers
Kube-proxy → networking
 
END-TO-END FLOW (REAL PROJECT)
Let’s say you deploy an app:
Step 1:
kubectl apply -f deployment.yaml
👉 Goes to API Server
Step 2:
API Server stores data in etcd
Step 3:
Scheduler picks a worker node
Step 4:
Kubelet on that node:
pulls image
starts container
Step 5:
Kube-proxy enables networking
Step 6:
Controller Manager ensures:
correct replicas
auto-healing
🔥 REAL PROJECT USAGE
Where you interact:
As DevOps/SRE:
API Server → via kubectl
Kubelet → debugging (describe pod)
Kube-proxy → network issues
etcd → backup & restore
Common Production Issues:
❌ Pod not scheduled → Scheduler issue
❌ Pod not running → Kubelet / runtime issue
❌ Service not working → kube-proxy issue
❌ Cluster broken → etcd issue
💯 INTERVIEW ANSWER (SHORT & STRONG)
👉
“Kubernetes control plane components like API server, scheduler, controller manager, and etcd manage the cluster state and orchestration, while worker node components like kubelet, container runtime, and kube-proxy are responsible for running and networking application workloads.”
 
Taints & Tolerations?
👉 They are used to control which pods can run on which nodes
 
Simple Idea
Taint (on Node) → “Don’t allow pods here ❌”
Toleration (on Pod) → “I can run here ✅”

1. TAINT (Applied on Node)
👉 You add taint to a node:
kubectl taint nodes node1 key=value:NoSchedule
Meaning:
👉
“No pod can be scheduled on this node unless it tolerates this taint”
🔹 Types of Taints
1. NoSchedule
👉 Pod will NOT be scheduled
2. NoExecute
👉
Pod won’t be scheduled
Existing pods will be removed ❌
3. PreferNoSchedule
👉 Try to avoid, but not strict
🔹 2. TOLERATION (Applied on Pod)
👉 Pod config:
tolerations:
  - key: "key"
    operator: "Equal"
    value: "value"
    effect: "NoSchedule"
👉 Meaning:
“This pod is allowed to run on tainted nodes”
🔥 Real Example (Production)
Scenario:
You have a special node for database
👉 Add taint:
kubectl taint nodes db-node type=database:NoSchedule
👉 Now:
Normal pods ❌ cannot run there
Only DB pods with toleration ✅ can run
 
<img width="1852" height="1055" alt="image" src="https://github.com/user-attachments/assets/32421c21-530b-4918-aebb-86f043dd3a5b" />
<img width="1829" height="1024" alt="image" src="https://github.com/user-attachments/assets/e4732af5-bba7-481d-b6fd-5a116746debe" />
<img width="1832" height="1035" alt="image" src="https://github.com/user-attachments/assets/b84349b0-4791-4825-8759-a61c1d65dad1" />
<img width="1668" height="735" alt="image" src="https://github.com/user-attachments/assets/17941bb0-5043-4d92-b32f-7f058c14b7a7" />


kubectl commands
 
 
kubectl get nodes

kubectl get pod

kubectl get services

kubectl create deployment nginx-depl --image=nginx

kubectl get deployment

kubectl get replicaset

kubectl edit deployment nginx-depl
 
debugging
 
kubectl logs {pod-name}

kubectl exec -it {pod-name} -- bin/bash

create mongo deployment

kubectl create deployment mongo-depl --image=mongo

kubectl logs mongo-depl-{pod-name}

kubectl describe pod mongo-depl-{pod-name}

delete deployment

kubectl delete deployment mongo-depl

kubectl delete deployment nginx-depl
 
create or edit config file
 
vim nginx-deployment.yaml

kubectl apply -f nginx-deployment.yaml

kubectl get pod

kubectl get deployment
 
delete with config
 
kubectl delete -f nginx-deployment.yaml

#Metrics

kubectl top The kubectl top command returns current CPU and memory usage for a cluster’s pods or nodes, or for a particular pod or node if specified.
 
 
kubectl get svc kubernetes -o yaml , to view the svc file in terming in yaml formate
 
 
kubectl get all,configmaps,secrets,pvc -n <namespace> to check what is in namespaces in side
 
 
kubectl config set-context --current --namespace=dev, to change one name space ot another
 
kubectl config set-context --current --namespace=prod, to switch to another namae space
 
Check Current Namespace

kubectl config view --minify | grep namespace

or

kubectl config get-contexts
 
 
4. Temporary Usage (Without Switching)

If you don’t want to switch permanently:

kubectl get pods -n dev
 
Real DevOps Usage Scenario
 
When node is overloaded:
 
kubectl describe node <node>

kubectl top node <node>

kubectl get pods -A --field-selector spec.nodeName=<node>
 
👉 Then:
 
Identify high CPU pods

Check logs

Reschedule or scale
 
 
Get Pods from Only One Namespace on Node

kubectl get pods -n dev -o wide | grep <node-name>
 
Check Resource Usage (Important for SRE)

kubectl top node <node-name>

✔️ Helps you understand:

CPU usage

Memory usage
 
Describe Node (Quick Overview)

kubectl describe node <node-name>

✔️ Shows:

Allocated resources

Running pods list

CPU/Memory usage
 
---------------------------------
 
1. Cluster & Context Commands

kubectl cluster-info

kubectl version

kubectl config view

kubectl config get-contexts

kubectl config use-context <context-name>

📦 2. Pod Commands (MOST IMPORTANT)

kubectl get pods

kubectl get pods -A

kubectl get pods -o wide

kubectl describe pod <pod-name>

kubectl logs <pod-name>

kubectl logs -f <pod-name>   # live logs

kubectl exec -it <pod-name> -- /bin/bash

kubectl delete pod <pod-name>
 
👉 Debugging pod:
 
kubectl get pod <pod> -o yaml

kubectl describe pod <pod>

🚀 3. Deployment Commands

kubectl get deployments

kubectl create deployment nginx --image=nginx

kubectl apply -f deployment.yaml

kubectl delete deployment <name>
 
kubectl scale deployment <name> --replicas=3

kubectl rollout status deployment <name>

kubectl rollout history deployment <name>

kubectl rollout undo deployment <name>
 
👉 Update image:
 
kubectl set image deployment/<name> nginx=nginx:latest

🌐 4. Service Commands

kubectl get svc

kubectl describe svc <name>

kubectl expose deployment <name> --type=NodePort --port=80

kubectl delete svc <name>

🔁 5. ReplicaSet Commands

kubectl get rs

kubectl describe rs <name>

kubectl delete rs <name>

📂 6. Namespace Commands

kubectl get ns

kubectl create ns dev

kubectl delete ns dev

kubectl config set-context --current --namespace=dev

📊 7. Node Commands

kubectl get nodes

kubectl describe node <node-name>

kubectl cordon <node>        # mark unschedulable

kubectl uncordon <node>

kubectl drain <node>         # remove pods safely

🔐 8. ConfigMap & Secrets

kubectl get configmaps

kubectl create configmap my-config --from-literal=key=value

kubectl describe configmap my-config
 
kubectl get secrets

kubectl create secret generic my-secret --from-literal=password=1234

kubectl describe secret my-secret

📦 9. YAML Apply & Delete (DAY-TO-DAY)

kubectl apply -f file.yaml

kubectl delete -f file.yaml

kubectl create -f file.yaml
 
👉 Dry run:
 
kubectl apply -f file.yaml --dry-run=client

🔍 10. Debugging & Troubleshooting (VERY IMPORTANT 🔥)

kubectl describe pod <pod>

kubectl logs <pod>

kubectl logs <pod> -c <container>
 
kubectl get events

kubectl top pod

kubectl top node
 
👉 Check resource usage (Metrics Server needed):
 
kubectl top pods

🔗 11. Networking Commands

kubectl get ingress

kubectl describe ingress <name>
 
kubectl port-forward pod/<pod> 8080:80

📈 12. HPA (Auto Scaling)

kubectl get hpa

kubectl autoscale deployment <name> --cpu-percent=50 --min=1 --max=5

kubectl describe hpa <name>

🧠 13. Advanced (DevOps Real Work)

kubectl get all

kubectl get all -A
 
kubectl edit deployment <name>

kubectl patch deployment <name> -p '{"spec":{"replicas":2}}'
 
kubectl label pod <pod> env=prod

kubectl annotate pod <pod> team=devops

🧹 14. Cleanup Commands

kubectl delete pod --all

kubectl delete all --all

📜 15. Output Formatting

kubectl get pods -o yaml

kubectl get pods -o json

kubectl get pods -o wide

⚡ 16. Shortcuts (VERY USEFUL)

kubectl get po        # pods

kubectl get svc       # services

kubectl get deploy    # deployments

kubectl get ns        # namespaces

🔥 REAL DEVOPS SCENARIO COMMANDS
 
👉 Restart deployment:
 
kubectl rollout restart deployment <name>
 
👉 Check failing pod quickly:
 
kubectl describe pod <pod>

kubectl logs <pod>
 
👉 Exec into container:
 
kubectl exec -it <pod> -- sh

🚀 PRO TIPS (Interview + Job)

Always start debugging with:

kubectl get pods

kubectl describe pod

kubectl logs

Most used in real job:

logs

describe

exec

get (with -o wide)

 View All Resources in a Namespace (MOST COMMON)
kubectl get all -n <namespace>
👉 Example:
kubectl get all -n dev
✔️ Shows:
Pods
Services
Deployments
ReplicaSets
⚠️ Note: It does NOT show everything (like secrets/configmaps)
 
List Specific Resources in Namespace
👉 Pods:
kubectl get pods -n dev
👉 Services:
kubectl get svc -n dev
👉 Deployments:
kubectl get deploy -n dev
👉 ConfigMaps:
kubectl get cm -n dev
👉 Secrets:
kubectl get secrets -n dev
 

Kubernetes Cluster
│
├── Control Plane (Master)
│   ├── API Server
│   ├── Scheduler
│   ├── Controller Manager
│   └── etcd (database)
│
├── Worker Nodes
│   ├── Node 1
│   │   ├── kubelet
│   │   ├── kube-proxy
│   │   └── Pods
│   │       ├── Pod
│   │       │   ├── Container (Docker/CRI)
│   │       │   └── Volumes
│   │       └── Pod
│   │
│   └── Node 2
│       └── Pods...
│
├── Namespaces (Logical Layer)
│   ├── default
│   ├── dev
│   ├── prod
│   │   ├── Deployments
│   │   │   └── ReplicaSets
│   │   │       └── Pods → (running on Nodes)
│   │   │
│   │   ├── Services
│   │   ├── ConfigMaps
│   │   ├── Secrets
│   │   ├── Ingress
│   │   └── PVC (Storage)
│   │
│   └── kube-system

 

 Request Flow (User → Ingress → Service → Pod)
User (Browser / Client)
│
├── DNS (Route53 / Domain)
│       ↓
│   Resolves to Load Balancer IP
│
├── Load Balancer (ALB / NLB)
│       ↓
│   Forwards request to Kubernetes Cluster
│
├── Ingress Controller (NGINX / ALB Ingress)
│       ↓
│   Checks routing rules (host/path)
│
├── Service (ClusterIP / NodePort)
│       ↓
│   Load balances request
│
├── Pod (Selected by Service)
│       ↓
│   Application Container
│
└── Response goes back same path 🔁
 
User (Browser / Client)

│

├── DNS (Route53)

│       ↓

│   Resolves to Load Balancer DNS

│

├── External Load Balancer

│   ├── AWS ALB (Application Load Balancer)  ← (Most Common ✅)

│   └── AWS NLB (Network Load Balancer)      ← (For TCP/High performance)

│       ↓

│   Sends traffic to Kubernetes

│

├── Ingress Controller

│   ├── NGINX Ingress Controller

│   └── AWS ALB Ingress Controller

│       ↓

│   Routes based on host/path

│

├── Service (Internal Load Balancer)

│   ├── ClusterIP   ← (default, internal only)

│   ├── NodePort    ← (used by Ingress sometimes)

│   └── LoadBalancer ← (creates external LB if needed)

│       ↓

│   Load balances traffic to pods

│

├── Pod

│       ↓

│   Container (Application)

│

└── Response goes back 🔁
 
User (Browser / Client)

│

├── DNS (Route53)

│       ↓

│

├── External Load Balancer (AWS ALB)

│       ↓

│

├── Ingress Controller

│       ├── /user   → user-service

│       ├── /order  → order-service

│       ├── /pay    → payment-service

│       ↓

│

├── Services (K8s Services)

│   ├── user-service (ClusterIP)

│   ├── order-service (ClusterIP)

│   ├── payment-service (ClusterIP)

│

├── Pods (Microservices)

│   ├── user-service pods

│   │       ↓

│   │   User DB (RDS)

│   │

│   ├── order-service pods

│   │       ↓

│   │   Order DB (RDS)

│   │

│   ├── payment-service pods

│   │       ↓

│   │   Payment DB (RDS)

│

└── Internal Service-to-Service Calls

    user-service → order-service → payment-service
 
1. CrashLoopBackOff (Most Asked in Interviews)
❌ Reason:
Application crash on startup
Wrong config (env variables missing)
DB not reachable
Port mismatch
🔍 Check:
kubectl describe pod <pod>
kubectl logs <pod>
kubectl logs <pod> --previous
✅ Fix:
Correct env variables / secrets
Fix application error
Ensure DB/service is reachable
🔥 2. ImagePullBackOff
❌ Reason:
Wrong image name/tag
Private repo without credentials
Image not available
🔍 Check:
kubectl describe pod <pod>
✅ Fix:
Correct image name
Add imagePullSecret
Push image to registry
 
 
🧠 How to Check if DB Connection is Working
✅ 1. Check Application Logs (FIRST STEP 🔥)
kubectl logs <pod-name>
👉 Look for errors like:
connection refused
timeout
authentication failed
✔️ If you see these → DB issue confirmed
✅ 2. Exec Into Pod (REAL DEBUGGING)
kubectl exec -it <pod-name> -- sh
Now you are inside container
🔍 3. Test Network Connectivity
👉 Ping DB (if allowed)
ping <db-host>
 
If DB connection fails, I first check logs to identify the error type. Then I exec into the pod and test connectivity using netcat or telnet. Based on whether it’s a network, authentication, or DNS issue, I fix security groups, credentials, or endpoint configuration.”
 
What Cluster Autoscaler does:
Watches Kubernetes API server
Detects:

👉 "Unschedulable Pods" (Pending pods)
Checks:

👉 Which node group (ASG) can fit this pod
Calls cloud provider (AWS):

👉 Increase nodes in Auto Scaling Group
New node joins cluster
Scheduler places pending pods
✅ Problem solved
 
What ASG Does
1. Maintain Desired Capacity
Example:
Desired = 2
Min = 1
Max = 5
👉 ASG ensures:
Always 2 instances running
If 1 dies → it creates a new one automatically ✅
2. Scale Up (Increase Instances)
When:
High traffic
CPU usage high
👉 ASG launches new EC2 instances
3. Scale Down (Save Cost)
When:
Traffic is low
👉 ASG terminates extra instances





Simple Definition
👉 HPA scales:
Pods (NOT nodes)
👉 Based on:
CPU usage
Memory usage
Custom metrics
⚙️ How HPA Works (Step-by-Step)
🔼 Scale UP
Example:
You have:
Deployment → 2 Pods
Traffic increases → CPU goes high (say 80%)
👉 HPA does:
Gets metrics from Metrics Server
Compares with target (e.g., 50% CPU)
Decides:

👉 Need more pods
Updates Deployment:
✅ More pods created → load distributed
🔽 Scale DOWN
When:
Traffic decreases
CPU low
👉 HPA reduces:
replicas: 5 → 2
✅ Saves resources
📊 Core Formula (VERY IMPORTANT)
Desired Replicas=Current Replicas×Current Metric ValueTarget Metric ValueDesired\ Replicas = Current\ Replicas \times \frac{Current\ Metric\ Value}{Target\ Metric\ Value}Desired Replicas=Current Replicas×Target Metric ValueCurrent Metric Value
👉 This is how HPA calculates scaling.
🏗️ HPA YAML Example
apiVersion: autoscaling/v2
kind: HorizontalPodAutoscaler
metadata:
  name: my-app-hpa
spec:
  scaleTargetRef:
    apiVersion: apps/v1
    kind: Deployment
    name: my-app
  minReplicas: 2
  maxReplicas: 10
  metrics:
  - type: Resource
    resource:
      name: cpu
      target:
        type: Utilization
        averageUtilization: 50
replicas: 2 → 5
 
annotations:

  prometheus.io/scrape: "true"

  prometheus.io/port: "8080"
 
Container Metrics
From:
cAdvisor
👉 Built into Kubernetes (via kubelet)
 
Kubernetes Objects
From:
kube-state-metrics
👉 Gives:
Pod status
Deployment replicas
Node status
 
 
. Kubernetes System Metrics
a. Node Metrics
From:
Node Exporter
👉 Gives:
CPU
Memory
Disk


Pods / Nodes expose /metrics

        ↓

Prometheus discovers targets

        ↓

Prometheus scrapes metrics (pull)

        ↓

Stores in time-series DB

        ↓

Grafana visualizes
 
 
Build → Test → Package → Deploy

📄 .gitlab-ci.yml (Exam Friendly + Clean)

stages:

  - build

  - test

  - package

  - deploy
 
STEP 1: BUILD

build_job:

  stage: build

  image: node:18

  script:

    - echo "Build Stage Started"

    - npm install

    - npm run build
 
# 🧪 STEP 2: TEST

test_job:

  stage: test

  image: node:18

  script:

    - echo "Test Stage Started"

    - npm test
 
# 📦 STEP 3: PACKAGE (Docker)

package_job:

  stage: package

  image: docker:latest

  services:

    - docker:dind

  script:

    - echo "Building Docker Image"

    - docker build -t my-app:$CI_COMMIT_ID .

    - echo "Pushing Docker Image"

    - docker push my-app:$CI_COMMIT_ID
 
# 🚀 STEP 4: DEPLOY

deploy_job:

  stage: deploy

  image: alpine:latest

  script:

    - echo "Deploy Stage Started"

    - echo "kubectl apply -f deployment.yaml"

  only:

    - main
 
mvn clean:    Removes the target directory and all generated files.

mvn compile:  Compiles the source code.

mvn test:     Runs the unit tests.

mvn package:  Compiles, tests, and packages the code into a JAR or WAR.

mvn install:  Packages and installs the artifact into the local repository.

mvn deploy:   Deploys the artifact to a remote repository.

mvn dependency:tree:          Shows the dependency tree.

mvn dependency:analyze:       Analyzes dependencies for unused or declared but unused ones.

mvn site:                     Generates project documentation.

mvn archetype:generate:       Generates a new project from an archetype.
 
pipeline {

    agent any
 
    environment {

        IMAGE_NAME = "my-app"

        IMAGE_TAG = "${BUILD_NUMBER}"

        DOCKER_REGISTRY = "docker.io/your-dockerhub-username"

        KUBE_NAMESPACE = "default"

        HELM_RELEASE = "my-app-release"

    }
 
    stages {
 
        stage('Checkout Code') {

            steps {

                git branch: 'main',

                    url: 'https://github.com/your-repo.git'

            }

        }
 
        stage('Build') {

            steps {

                echo "Building application..."

                sh 'mvn clean package -DskipTests'

            }

        }
 
        stage('Unit Tests') {

            steps {

                echo "Running tests..."

                sh 'mvn test'

            }

        }
 
        stage('Static Code Analysis (SAST)') {

            steps {

                echo "Running SonarQube scan..."

                sh '''

                    mvn sonar:sonar \

                    -Dsonar.projectKey=my-app \

                    -Dsonar.host.url=http://sonarqube:9000 \

                    -Dsonar.login=admin \

                    -Dsonar.password=admin

                '''

            }

        }
 
        stage('Build Docker Image') {

            steps {

                echo "Building Docker image..."

                sh """

                    docker build -t $DOCKER_REGISTRY/$IMAGE_NAME:$IMAGE_TAG .

                """

            }

        }
 
        stage('Push Docker Image') {

            steps {

                echo "Pushing image to registry..."

                withCredentials([usernamePassword(credentialsId: 'docker-hub-creds', usernameVariable: 'USER', passwordVariable: 'PASS')]) {

                    sh """

                        echo $PASS | docker login -u $USER --password-stdin

                        docker push $DOCKER_REGISTRY/$IMAGE_NAME:$IMAGE_TAG

                    """

                }

            }

        }
 
        stage('Deploy to Kubernetes (Helm)') {

            steps {

                echo "Deploying to Kubernetes..."

                sh """

                    helm upgrade --install $HELM_RELEASE ./helm-chart \

                    --set image.repository=$DOCKER_REGISTRY/$IMAGE_NAME \

                    --set image.tag=$IMAGE_TAG \

                    --namespace $KUBE_NAMESPACE

                """

            }

        }

    }
 
    post {

        success {

            echo "Pipeline Success 🚀"

        }
 
        failure {

            echo "Pipeline Failed ❌"

        }

    }

}
 
VPC

│

├── Public Subnet

│   ├── Internet Gateway (IGW)

│   ├── Load Balancer (ALB/NLB)

│   ├── Bastion Host (Jump Server)

│   └── NAT Gateway

│

├── Private Subnet

│   ├── Application Servers (EC2 / K8s Nodes)

│   ├── Pods (Microservices)

│   ├── Databases (RDS)

│   └── Internal Services
 
User (Browser / Client)

│

├── DNS (Route53)

│       ↓

│   Resolves domain → Load Balancer IP

│

├── External Load Balancer

│   └── Application Load Balancer (Public Subnet)

│       ↓

│

├── Ingress Controller (Kubernetes)

│       ↓

│   Routes based on path/host

│

├── Service (ClusterIP)

│       ↓

│   Load balances traffic internally

│

├── Pod (Application)

│       ↓

│   Container (Your App Code)

│       ↓

│   (Optional) Database Call

│

└── Response returns back 🔁
 
resources allocation testing 

failover testing
 
load balancer strategies 

equal distribution 

Waite based routing 

round robin 

 
✅ How do you handle auto scaling?
Answer:
“I handle auto scaling at both the infrastructure level and the application level to ensure high availability and performance.
🔹 1. Infrastructure Level (AWS Auto Scaling)
In Amazon Web Services, I use Auto Scaling Groups (ASG):
I define minimum, desired, and maximum instance count
Attach ASG to an Application Load Balancer
Configure scaling policies based on:
CPU utilization (e.g., scale out if CPU > 70%)
Request count per target
👉 Example:

If traffic increases, ASG automatically launches new EC2 instances and registers them with the load balancer.

If traffic decreases, it terminates extra instances to save cost.
🔹 2. Application Level (Kubernetes Auto Scaling)
At the application level, I use Kubernetes Horizontal Pod Autoscaler (HPA):
HPA monitors metrics like CPU/memory
Automatically increases/decreases pod count
👉 Example:

If CPU crosses 70%, pods scale from 2 → 6

If load drops, it scales back down
 
DevOps beginner
 
1.
 
You define an Auto Scaling Group (ASG)

This is a group of EC2 instances (servers) managed together.
 
You set scaling rules (policies)

Example rules:
 
Scale Out (add servers) → if CPU > 70% for 5 mins
 
Scale In (remove servers) → if CPU < 30% for 10 mins
 
Auto Scaling monitors your metrics (via CloudWatch)
 
When thresholds are hit →

Auto Scaling automatically launches or terminates servers.
 
2.
 
Benefits of Auto Scaling

Handles variable traffic → Always right-sized
 
High availability → Automatically replaces failed servers
 
Cost-efficient → You don’t pay for idle servers
 
Elasticity → Scales up or down automatically

 
Adhanki Manikanta
 📷 
.
 
Adhanki Manikanta
Hi, I’m Manikanta and I have around 3 years of experience in Production Support and DevOps roles, primarily working with cloud-based and containerized environments. Mention all the tools and technolo…
.
 
Node Selector mismatch: Pod specifies a label to run on a node, but no node has that label.
Node Affinity / Anti-Affinity: Rules restrict which nodes the pod can (or cannot) run on, so scheduler can’t find a matching node.
Taints & Tolerations: Node blocks pods using taints, and if the pod doesn’t have matching tolerations, it won’t be scheduled.
 
Adhanki Manikanta
pipeline { agent any environment { IMAGE_NAME = "my-app" IMAGE_TAG = "${BUILD_NUMBER}" DOCKER_REGISTRY = "docker.io/your-dockerhub-username" KUBE_NAMESPACE = "default" HELM_RELEASE = "my-app-release"…
.



 <img width="919" height="685" alt="image" src="https://github.com/user-attachments/assets/a652ab76-2c6b-475a-a7cd-487cf22b8d64" />

 <img width="800" height="982" alt="image" src="https://github.com/user-attachments/assets/1a2174e0-06a6-44cd-8a2b-ca1e3ee59c4a" />
<img width="800" height="436" alt="image" src="https://github.com/user-attachments/assets/53c508cc-aeb4-4e6e-b752-10e6a055a2a1" />
<img width="1600" height="1057" alt="image" src="https://github.com/user-attachments/assets/8eef5b4c-d641-4c5a-8e03-7aac7eabe2a4" />
<img width="861" height="745" alt="image" src="https://github.com/user-attachments/assets/27206a1a-aa23-48e9-8e7c-58b1cc6fa5a2" />
Are you a Devops engineer looking to innovate, contribute in a fast-paced startup? We are looking to add a Devops engineer to our engineering team.
We are a world-changing team of AI researchers and engineers working on thecutting edge of generative AI. We are building systems work across telephony,chat, video, email & text for the purposes of assisting & accelerating humanworkforce with artificial agents.
Our focus is helping customers improve their outcomes in the areas of BusinessProcess (Customer service, IT support, Accounting, Human resources, Legalservices, Marketing, IP Legal etc.)
Key Responsibilities:
Help with new feature development - work closely with other engineering teams to provide platform solutions to new products.
Define and clearly document infrastructure related development and processes.
Implement and manage CI/CD pipelines for software releases.
Develop and maintain automated deployment scripts.
Monitor and troubleshoot system and application issues.
Design and implement cloud infrastructure to support our products.
Optimize existing cloud infrastructure for performance and cost.
Work with security and compliance teams to ensure infrastructure meets organizational and regulatory requirements.
Must have qualifications:
Strong knowledge and hands-on experience with AWS.
Experience with Docker, Kubernetes, Jenkins.
Experience with setting up and using opensource tools for monitoring, alerting, logging, scaling.
Experience with automation with tools like Ansible/Terraform.
Excellent OS fundamentals.
Good communication skills.
Experience in Python.
complete architecture 
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/a8a9e4bc-42a0-44cc-a8bd-34d4b3dd66e3" />

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/413d12fe-968f-493e-89d5-b95457c0e218" />
 
 <img width="800" height="1183" alt="image" src="https://github.com/user-attachments/assets/9962620a-b3ae-4c0c-95cf-24921dd484e2" />

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/f050641b-9f75-4299-80bc-a9e3825af972" />
    +----------------------+
                |   Multi-Cluster K8s  |
                | (EKS Clusters N=100) |
                +----------+-----------+
                           |
         -----------------------------------------
         |                 |                     |
  Prometheus Agent   kube-state-metrics     cAdvisor
         |                 |                     |
         --------------> Remote Write ------------
                           |
                    +------------------+
                    | Metrics Gateway  |
                    | (Thanos/Cortex)  |
                    +--------+---------+
                             |
                       (Kafka Stream)
                             |
     ---------------------------------------------------
     |            |               |                     |
Collector   Cost Engine     ML Engine          Pricing Service
Service      (Go)           (Python)             (Go)
     |            |               |                     |
     -------------------Event Bus (Kafka)---------------
                             |
                    +-------------------+
                    | Aggregation Layer |
                    | (Precompute Cost) |
                    +---------+---------+
                              |
                     +------------------+
                     | Timeseries DB    |
                     | (TimescaleDB)    |
                     +------------------+
                              |
                     +------------------+
                     | Dashboard API    |
                     +------------------+
                              |
                          Frontend




 
This is a complex and highly valuable project. To get a high-quality, actionable response from an AI (like a technical architect or a senior developer), you need a prompt that covers the **data ingestion layer**, the **cost calculation logic**, and the **frontend visualization**.
Here is a comprehensive prompt you can use to generate the architecture, tech stack, and implementation plan for your cloud cost optimization tool.
---
## The Master Prompt
> **Role:** Act as a Senior Cloud Architect and Full-Stack Developer.
>
> **Task:** Design a comprehensive microservices-based web application called **"CloudThrift"** that monitors Kubernetes (K8s) clusters in AWS to provide granular pod-level cost analysis and optimization suggestions.
>
> **Requirements:**
> 1. **Data Collection Layer:** How will the app collect CPU, Memory, and Network metrics from individual pods? (Discuss Prometheus, Metrics Server, or custom sidecars).
> 2. **Cost Attribution Engine:** >    - Explain the logic for mapping AWS EC2/Fargate instance pricing (on-demand vs. spot) to individual pod resource consumption.
>    - Address how to handle "unallocated resources" (idle capacity on a node).
> 3. **Microservices Architecture:** Define the following services:
>    - **Collector Service:** Ingests metrics from K8s.
>    - **Pricing Service:** Fetches real-time data from AWS Price List API.
>    - **Analytics & ML Service:** Analyzes trends and generates optimization suggestions (e.g., "Right-size this pod from 2vCPU to 0.5vCPU to save \$40/month").
>    - **Dashboard API:** Serves data to the frontend.
> 4. **Infrastructure & Integration:**
>    - Use AWS-specific tools (Cost Explorer API, CUR reports, IAM roles).
>    - Suggest a database schema (Time-series for metrics vs. Relational for metadata).
> 5. **Frontend/UI:** Describe a dashboard layout that shows:
>    - Total Cluster Cost vs. Optimized Potential Cost.
>    - A table of "Top 10 Most Expensive Pods."
>    - A "Suggestions" tab with a one-click "Apply Optimization" (Terraform/HPA update) concept.
>
> **Output Format:** Provide a high-level system architecture diagram (in Mermaid or text), a recommended tech stack, and a step-by-step roadmap for building the MVP.
---
## Key Technical Concepts to Include
If you are building this yourself, keep these specific terms in mind as you refine your project:
### 1. The Cost Equation
To get the cost per pod, you generally use the formula:
$$\text{Pod Cost} = \left( \frac{\text{Pod CPU Usage}}{\text{Node Total CPU}} \times \text{Node Hourly Cost} \right) + \left( \frac{\text{Pod RAM Usage}}{\text{Node Total RAM}} \times \text{Node Hourly Cost} \right)$$
### 2. Tech Stack Recommendations
* **Backend:** Go (Golang) is preferred for K8s tooling due to the client-go library.
* **Metrics:** **Prometheus** for data collection and **Kube-state-metrics**.
* **Cost Data:** Integration with **OpenCost** (an open-source standard for K8s cost monitoring).
* **Database:** **TimescaleDB** or **InfluxDB** for storing historical cost/metric data.
* **Frontend:** **React** with **Tailwind CSS** and **Recharts** for the dashboard visualizations.
### 3. The "Optimization" Logic
Don't just show the cost. Your application becomes "Senior Level" when it suggests:
* **Right-sizing:** Adjusting Request/Limit values in the YAML.
* **Spot Instance Advisor:** Identifying workloads that can safely run on Spot instances instead of On-Demand.
* **Idle Detection:** Identifying namespaces or pods that are provisioned but using 0% CPU.
 




<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/6e946036-5a29-44fd-9322-4954a87185e2" />
https://chatgpt.com/share/69eb912a-ec60-83e8-8901-67b5313dad23
cloudthrift-backend/
│
├── cmd/                         # Entry points (multiple binaries possible)
│   └── api/
│       └── main.go              # Starts HTTP server
│
├── internal/                    # Private app logic (not exportable)
│
│   ├── config/                  # App configuration
│   │   └── config.go
│
│   ├── logger/                  # Logging setup
│   │   └── logger.go
│
│   ├── server/                  # HTTP server setup
│   │   ├── router.go
│   │   └── middleware.go
│
│   ├── handlers/                # API handlers (controllers)
│   │   ├── cost_handler.go
│   │   ├── cluster_handler.go
│   │   └── health_handler.go
│
│   ├── services/                # Business logic layer
│   │   ├── cost_service.go
│   │   ├── metrics_service.go
│   │   ├── pricing_service.go
│   │   └── optimization_service.go
│
│   ├── repositories/            # DB access layer
│   │   ├── cost_repository.go
│   │   ├── cluster_repository.go
│   │   └── base_repository.go
│
│   ├── models/                  # Structs (DB + API)
│   │   ├── cost.go
│   │   ├── cluster.go
│   │   ├── node.go
│   │   └── pod.go
│
│   ├── clients/                 # External integrations
│   │   ├── prometheus_client.go
│   │   ├── aws_pricing_client.go
│   │   └── kubernetes_client.go
│
│   ├── processors/              # Core computation logic
│   │   └── cost_processor.go    # 🔥 Cost calculation logic
│
│   ├── cache/                   # Caching (Redis later)
│   │   └── cache.go
│
│   └── utils/                   # Helpers
│       ├── math.go
│       └── time.go
│
├── pkg/                         # Reusable libraries (exportable)
│   └── response/
│       └── response.go          # Common API response format
│
├── api/                         # API contracts (optional but good)
│   └── openapi.yaml
│
├── configs/                     # YAML/ENV configs
│   └── config.yaml
│
├── scripts/                     # Dev scripts
│   └── setup.sh
│
├── deployments/                 # K8s / Docker
│   ├── Dockerfile
│   └── k8s.yaml
│
├── go.mod
├── go. Sum
└── README.md


<img width="1908" height="874" alt="image" src="https://github.com/user-attachments/assets/77601923-f228-46e0-b5f8-1341a8d7fcd8" />
<img width="1318" height="517" alt="image" src="https://github.com/user-attachments/assets/6e21190b-ec57-4e25-a441-74dd22407ee5" />
<img width="1563" height="954" alt="image" src="https://github.com/user-attachments/assets/aab4d09b-e987-43bb-a184-efc6436b7c58" />
  <img width="1471" height="1098" alt="image" src="https://github.com/user-attachments/assets/20e23c2c-52cb-47a1-91b8-7d2ea6aea259" />
<img width="1422" height="1257" alt="image" src="https://github.com/user-attachments/assets/3ff47afa-cc10-4486-a87f-95f7f09c349c" />

 <img width="1195" height="1096" alt="image" src="https://github.com/user-attachments/assets/89d9a1e5-11df-434c-89b0-c7aff98a98e7" />
<img width="1300" height="1225" alt="image" src="https://github.com/user-attachments/assets/fa696a12-257f-4e45-987f-1f77bfb6242b" />
<img width="1366" height="1117" alt="image" src="https://github.com/user-attachments/assets/6073390f-2a6b-44a5-b47c-6b6c0d2e191e" />

 <img width="1714" height="1416" alt="image" src="https://github.com/user-attachments/assets/31e30fff-d77c-4dc3-a0ee-b7f6e51f19a1" />
<img width="800" height="673" alt="image" src="https://github.com/user-attachments/assets/285833d4-f1a8-44ca-8a85-3c8b8400979b" />
<img width="1371" height="1387" alt="image" src="https://github.com/user-attachments/assets/2bfe3100-578c-4b8b-8ff8-7d26ef54cb11" />
<img width="1636" height="661" alt="image" src="https://github.com/user-attachments/assets/98a78fb8-bd99-4c2f-a0f5-b22afd9ac104" />

 <img width="1786" height="913" alt="image" src="https://github.com/user-attachments/assets/35ed601f-6974-4ad6-9648-c6562ab3aa59" />

 <img width="1422" height="817" alt="image" src="https://github.com/user-attachments/assets/04e8d50b-5b1c-48b4-a48d-7b838738068b" />

<img width="2244" height="1297" alt="image" src="https://github.com/user-attachments/assets/df8cad86-19ac-4f4d-99d9-2c524415cf54" />
<img width="1957" height="1216" alt="image" src="https://github.com/user-attachments/assets/186b33c2-5999-4844-9a39-b36411e2f654" />
<img width="2248" height="1309" alt="image" src="https://github.com/user-attachments/assets/988c08d7-ade6-45fb-97b4-36d6be2934af" />
https://instances.vantage.sh/
                          

Hi Adhanki Manikanta
Daily Routine Start
My day as a DevOps engineer typically begins with a quick health check of critical systems. I start by reviewing overnight alerts in tools like Prometheus/Grafana or Datadog, scanning Slack/Teams for urgent incidents (e.g., pipeline failures or downtime), and triaging any PagerDuty escalations to ensure SLAs are met—prioritizing fixes like restoring a broken deployment before stand-ups. This is followed by a 15-minute team stand-up to align on priorities, then diving into automation backlog tasks such as optimizing CI/CD workflows or infrastructure tweaks. I then check the CI/CD pipelines to see if any deployments failed. During the Daily Stand-up, I align with the dev teams to unblock any infrastructure dependencies. My focus then shifts to 'SRE-style' work: 50% on operational tasks (fixing pipeline bottlenecks or scaling issues) and 50% on engineering projects like automating manual workflows or optimizing cloud costs."
HPA Configuration Steps
Horizontal Pod Autoscaler (HPA) in Kubernetes automatically scales pod replicas based on observed metrics, and I've configured it extensively for microservices handling millions of requests daily. To set it up: (1) Ensure Metrics Server is installed (kubectl top nodes works); (2) Create an HPA YAML manifest targeting a Deployment; (3) Apply with kubectl apply -f hpa.yaml; (4) Monitor via kubectl get hpa and kubectl describe hpa. Key parameters include: apiVersion: autoscaling/v2, scaleTargetRef (targets Deployment kind/name), minReplicas/maxReplicas (e.g., 3/20), behavior (scaleUp/scaleDown policies for stabilizationWindowSeconds), and metrics array defining targets like CPU utilization.
HPA Metrics Overview
HPA supports three metric types: resource metrics (CPU/memory requests/limits), object metrics (e.g., pods/sec from another object), and external/custom metrics (app-specific via Prometheus Adapter). I configure based on workload: CPU for compute-bound apps (target 70% average), memory for data-heavy services, or custom like requests-per-second (RPS) for web apps—integrated via metricSelector with Prometheus queries exposed through custom.metrics.k8s.io.
Metrics for HPA Selection
Primary metrics I consider: CPU utilization (70-80% target for balanced scaling), memory usage (60-75% to avoid OOMKills), custom app metrics (e.g., queue length >50 or RPS >100 via Prometheus), and external metrics from tools like Datadog for business KPIs (e.g., error rate). Selection basis: workload profiling—CPU for stateless APIs, memory+RPS combo for e-commerce spikes; always test in staging with load tools like Locust to avoid flapping.
Terraform Architecture Experience
Yes, I've built multiple full-stack architectures using Terraform, such as a multi-region EKS cluster with VPCs, ALBs, RDS, and auto-scaling groups. In one project, I modularized it: root module calls child modules for networking (VPC/subnets), compute (EKS nodes), and storage (EFS/S3); used remote state in S3 with DynamoDB locking; applied via terraform init/plan/apply in GitHub Actions CI/CD. This ensured reproducible, versioned infra across dev/stage/prod.
Largest Automation Achievement
The biggest automation I led was a fully self-service GitOps pipeline using ArgoCD, Terraform Cloud, and Crossplane for provisioning 100+ tenant namespaces on EKS, reducing manual infra tickets by 85%. It integrated OPA Gatekeeper for policy-as-code, automated cert rotations via cert-manager, and scaled via KEDA. Impact: Deployment time dropped from 2 days to 15 minutes, costs optimized 40% via spot instances, and engineer productivity boosted—handling 5x traffic growth without downtime.
HPA Configuration Basis
I base HPA config on app profiling (historical Prometheus data), SLOs (e.g., 99.9% availability), and load testing: set CPU target at 70% for steady scaling, minReplicas to handle baseline traffic, maxReplicas for bursts (with cooldown 300s), and multiple metrics to prevent single-point failures. Always enable stabilizationWindowSeconds (300s scale-up, 5min scale-down) and monitor for thrashing via kubectl get hpa --watch.
Application Architecture Built
Yes, at my company, I architected a resilient e-commerce backend on AWS EKS: ingress via ALB/NLB, services in namespaces with Istio service mesh for traffic splitting/mTLS, persistent Kafka for order queues, and observability stack (Prometheus + Grafana Loki). Built via Terraform modules (network/compute/addons), deployed GitOps-style with FluxCD syncing Helm charts; added HPA/VPA for pods, Cluster Autoscaler for nodes. Process: requirements gathering → TOGAF diagramming → Terraform POC → CI/CD integration → prod rollout with canary blue-green deploys—achieved 99.99% uptime under Black Friday loads.
Message Queue Tools
For message queues, I use Kafka (high-throughput event streaming), RabbitMQ (task queues with ACKs), SQS/SNS (serverless AWS), and Redis Streams (lightweight pub/sub). Selection depends on needs: Kafka for ordered, durable logs; RabbitMQ for RPC patterns; SQS for decoupled microservices.
Kafka Configuration Process
To configure Kafka: (1) Provision cluster via Strimzi Helm on K8s (helm install kafka strimzi/strimzi-kafka-operator); (2) Create Kafka topic (kubectl apply -f topic.yaml with partitions=10, replicas=3); (3) Set broker configs in CRD (e.g., replicationFactor: 3, min.insync.replicas: 2); (4) Enable TLS/auth with OAuth/OIDC; (5) Integrate with Schema Registry and Kafka Connect for CDC. Tuned for 1M+ msg/sec: num.network.threads=8, log.segment.bytes=1GB.
Terraform Provisioning Knowledge
Absolutely—Terraform provisioning uses HCL: define providers (e.g., provider "aws" {region = "us-east-1"}), resources (e.g., resource "aws_eks_cluster" "main" {name = "prod"}), data sources, variables/outputs, and modules. Workflow: init (download providers), plan (diff preview), apply (provision idempotently), destroy. I use workspaces for envs, Terragrunt for DRY, and Sentinel for policy.
AI Tools in Daily Workflow
In my DevOps role, I leverage GitHub Copilot for faster IaC/Terraform scripting (suggests 70% of boilerplate), Cursor AI for debugging pipelines, Amazon Q for AWS troubleshooting, and ChatGPT/Claude for diagramming (Mermaid from natural language). Also use Firefly for architecture viz and Perplexity for quick research on edge cases like K8s operators—boosts productivity 30% without compromising security.
 
 
 
1. tell me how your day will starts as a devops engineer, what will do?
2. how to configure HPA ? what are the parameters of HPA and on what metrics basis you configure HPA ?
3. what are metrics that we you consider to configure HPA.?
4. have you aver build any architecture through terraform ?
5. what is biggest thing that you automated and build in your current role ? what is the impact of it ?
6. on what basis you do configure HPA, ?
7. have you aver build any architecture of application.? take me anything that you build on your company, how you did?
8. what kind of tools do use in message queue?
9. how to configure kafka.?
10. do you know how to write terraform provisioning?
11. what are all the ai tools that you use in your day to day life ?
 
he asked about some other tools related to voice testing.

1}  You are part of an SRE team managing a microservices application deployed on Kubernetes. One of the critical services (payment-service) is running inside a container. Recently, alerts started firing because the service is intermittently going down. On investigation, you notice: Pods are restarting frequently kubectl describe pod shows: Last State: Terminated (Exit Code: 137) Application logs do not show any clear error before termination CPU usage looks normal, but memory usage spikes occasionally What does exit code 137 indicate in this scenario? Why might this issue not appear directly in application logs? How would you confirm the root cause of the problem? What are the possible reasons for this happening in a Kubernetes environment?
 
2} How would you approach troubleshooting this issue step by step? How would you determine if the issue is with the pipeline itself vs the target environment? What tools or commands would you use to debug the failure in Kubernetes? How would you handle this situation if it is blocking a critical production release?
 
3} You are asked to design and implement monitoring & observability for this service using industry-standard tools.? Make sure 1. properly collect metrics, logs, and traces. 2. Provide dashboards and alerts. 3. Ensure the solution is scalable, cost-efficient, and secure 4. Integrate health checks and service-level indicators/alerting.
 
4} we have certain date transfor job will be runnign on cloud it will run only for 3 hours day to transfor huge data in day time we we dont have any work with that which component or which feture you use , how do you set up cost effectively
 
5} we have an e-com application with microservice and checkout service is failing continued and getting alerts and mails from client , it having high spike count lik 10milion requests so how do truble shoot ? what are yoru first 5 steps do you take first action on that if that is not infra isssue it is appliaction issue ? if fix takes more time still service is down how do handel and what you will do.

Designs, implements, and maintains scalable, reliable, and secure infrastructure solutions    Builds and manages CI/CD pipelines to support rapid and consistent software delivery    Automates infrastructure provisioning using tools like Terraform, Ansible, or CloudFormation    Implements and manages containerization and orchestration technologies (e.g., Docker, Kubernetes)    Monitors system performance and availability using observability tools (e.g., Prometheus, Grafana)    Develops automation tools to reduce manual operational tasks (toil) and improve efficiency    Collaborates with development, QA, and operations teams to ensure smooth software releases    Maintains and optimizes cloud infrastructure (e.g., AWS, Azure) for scalability and cost- efficiency    Enforces security best practices in deployment, infrastructure, and operational processes    Participates in incident response, root cause analysis, and postmortem reviews to improve resilience    Implements and tracks SLOs, SLIs, and error budgets to guide reliability engineering efforts    Optimizes system performance and supports capacity planning across environments    Proficient in scripting and programming languages (e.g., Python, Go, Bash)    Experienced with CI/CD tools and version control systems (e.g., Jenkins, GitLab, Git)    Applies Agile and DevOps methodologies to drive continuous improvement and collaboration 


DevOps / Site Reliability Engineer with 3.3 years of solid experience in Application production
support, Linux, Cloud operations, CI/CD automation, monitoring, and container platforms. Strong
background in incident management, reliability engineering, and DevOps practices with hands-on
exposure to AWS, Docker, Kubernetes, Jenkins, Terraform, and modern observability tools. Proven
ability to support business-critical applications, reduce downtime, and collaborate effectively across
development and operations teams.
TECHNICAL SKILLS
• Cloud & OS: AWS (EC2, IAM, EKS, VPC, S3 – basic), Linux
• Containers & Platforms: Docker, Kubernetes, Helm Charts
• CI/CD & Version Control: Jenkins, Git, GitHub, Bitbucket
• Infrastructure & Automation: Terraform (basic)
• Monitoring & Observability: Kibana, Elasticsearch, Grafana, Prometheus
• ITSM & Collaboration: ServiceNow, Jira, Confluence, ITIL
• Methodologies & Architecture: Agile, Microservices

what kind of alerts do you acknowledge 
what are the alerts you worked on.
how do you categorise the alerts and severity for the alert 
what kind of application it is , is it customer based application ?
for customer traffic have you observed any CPU utilization, and how you troubleshooted the issue ?
about HPA in pods , and 
how do we configer HPA for this application( horizontal pod auto scalar )

          Why do we need HPA?
How does HPA know the traffic is high?
How to debug when CPU reaches 100%?
What are requests and limits in Kubernetes?
How can we define those thresholds?
What kind of performance tests are there?
How do we perform these tests – give one line answers?
If we have given only requests and no limits, what happens?
If only requests are defined for a pod, what is the default limit value?
If a pod is not getting scheduled, what will be the pod state?
How can we troubleshoot a pod in Pending state?
How to troubleshoot insufficient resources issue?
What are other reasons why a pod may not get scheduled?
If a pod is showing 3/4 running, what does it mean?
Difference between readiness and liveness probes – one line answer?
What are the parameters for readiness and liveness probes?
If liveness check fails, what will be the pod state?
If readiness check fails, what happens to the pod?
What does it mean if a pod has no node assigned?
What are the reasons for a pod not getting assigned to a node?
What are the mismatches in tolerations?
Where can we check if a node is not coming up and the reason?
What is ASG in ECS and how is it assigned?
What is CAS in Kubernetes? ( cluster auto scalar )

1 .we have one server the CPU and memory is good no issue with that but load average is too high ?

2 . in server CPU and memory and disk all are good still the server is responding slow ?

3. in NFS server we have added a directory and i want to check if client able to see it or not ?

4 . how can i check CPU and memory and disk stats for one week back ?

5 .what is load average ?

6 . Load average metrics means what ?

7. while trying to delete any directory it is showing resources are busy try again ?

8. how can i know is any directory or file who is using which user or which processer , which we are trying to delete ?
 
9. i want to remove the permission to root user to not connect with ssh how ?

10.  what is OOM and what are reasons for OOM ?

11 . what causes high disk usage , or CPU usage ?

12 . if CPU and disk usage is tooo high what we do ?

13. if system slow what you do, all are good CPU and memory and disk ?

14 . how can we know which process is causing for load average high ?
 
 
 


Role & Responsibilities
1) Administer and support distributed Linux systems (RHEL/CentOS 7/8) including authentication, NFS/automount, and desktop environments (KDE/GNOME/VNC).
2) Troubleshoot and resolve performance, network, and authentication issues to ensure system stability and availability.
3) Provide first-line user support with clear communication and timely solutions.
4) Collaborate with network/security teams for issue resolution.
5) Maintain documentation of incidents, fixes, and system changes.
6) Work with peers, L2, and L3 teams to continuously improve system performance.
 
 

1) Diploma/degree in CS/IT or equivalent experience.
2) 2–3 years of Linux administration experience (RHEL/CentOS 7/8).
3) Strong troubleshooting skills for Linux workstation and enterprise environments.
4) Good analytical and problem-solving ability.
Excellent communication and user engagement skills.
5) Willingness to work in 24×7 shift support.
6) RHCE, RHCSA or similar certification preferred.
7) knowledge of AWS cloud services and their integration with Linux systems.
 
 


 
 
Experience
2–4 years of Linux administration experience
 
 
1 .we have one server the CPU and memory is good no issue with that but load average is too high ?
2 . in server CPU and memory and disk all are good still the server is responding slow ?
3. in NFS server we have added a directory and i want to check if client able to see it or not ?
4 . how can i check CPU and memory and disk stats for one week back ?
5 .what is load average ?
6 . Load average metrics means what ?
7. while trying to delete any directory it is showing resources are busy try again ?
8. how can i know is any directory or file who is using which user or which processer , which we are trying to delete ?
 
9. i want to remove the permission to root user to not connect with ssh how ?
10.  what is OOM and what are reasons for OOM ?
11 . what causes high disk usage , or CPU usage ?
12 . if CPU and disk usage is tooo high what we do ?
13. if system slow what you do, all are good CPU and memory and disk ?
14 . how can we know which process is causing for load average high ? 



Hi, I’m Mani, and I have around 3 years of experience in Production Support and DevOps roles, primarily working with cloud-based and containerized environments.
Mention all the tools and technologies that you know here.

Currently, I’m working as a DevOps/SRE Engineer at MSys Technologies my day to day roles and responsibilites include, where I support cloud-hosted applications running on AWS and Kubernetes. My day-to-day responsibilities include monitoring system health using Grafana, Prometheus, and Kibana, handling P1 and P2 incidents, performing root cause analysis, and ensuring SLA compliance. I’m also involved in deployment support, troubleshooting containerized applications, and maintaining CI/CD pipelines using Jenkins.
Technically, I have hands-on experience with Linux, AWS EC2, Docker, and Kubernetes. I’ve also worked with Terraform and Ansible for basic infrastructure automation, and I’m continuously improving my skills in DevOps automation and cloud-native technologies.
 
Overall, my core strength lies in production reliability, incident management, and gradually transitioning deeper into DevOps automation and cloud-native practices.

If they ask for all projects them mention all your pojects
Previously, at GlobalLogic, I supported banking applications in production environments, where I worked extensively on monitoring, incident coordination, and collaborating with DevOps and development teams during outages and maintenance activities.


Software Engineer -SRE

 
 Designs, implements, and maintains scalable, reliable, and secure infrastructure solutions  
 Builds and manages CI/CD pipelines to support rapid and consistent software delivery  
 Automates infrastructure provisioning using tools like Terraform, Ansible, or CloudFormation  
 Implements and manages containerization and orchestration technologies (e.g., Docker,
Kubernetes)  
 Monitors system performance and availability using observability tools (e.g., Prometheus,
Grafana)  
 Develops automation tools to reduce manual operational tasks (toil) and improve efficiency  
 Collaborates with development, QA, and operations teams to ensure smooth software
releases  
 Maintains and optimizes cloud infrastructure (e.g., AWS, Azure) for scalability and cost-
efficiency  
 Enforces security best practices in deployment, infrastructure, and operational processes  
 Participates in incident response, root cause analysis, and postmortem reviews to improve
resilience  
 Implements and tracks SLOs, SLIs, and error budgets to guide reliability engineering efforts  
 Optimizes system performance and supports capacity planning across environments  
 Proficient in scripting and programming languages (e.g., Python, Go, Bash)  
 Experienced with CI/CD tools and version control systems (e.g., Jenkins, GitLab, Git)  
 Applies Agile and DevOps methodologies to drive continuous improvement and collaboration 

<img width="800" height="402" alt="image" src="https://github.com/user-attachments/assets/e2675659-6381-4145-bf17-7b8289933d5b" />

<img width="1875" height="933" alt="image" src="https://github.com/user-attachments/assets/9db02586-053e-4509-af4c-ac8f9b242611" />

<img width="1876" height="916" alt="image" src="https://github.com/user-attachments/assets/77625b1f-6fc9-41e7-99b0-588605e65300" />
<img width="1908" height="1003" alt="image" src="https://github.com/user-attachments/assets/2aea85f1-49d7-47da-9c02-e1a18a30028f" />

<img width="1915" height="1000" alt="image" src="https://github.com/user-attachments/assets/2516bb11-acd8-4200-9b2f-793e6e9a6341" />
<img width="1902" height="1116" alt="image" src="https://github.com/user-attachments/assets/c13a3dc3-515a-4f46-88fb-68573d69a75f" />

<img width="1891" height="1072" alt="image" src="https://github.com/user-attachments/assets/90021e9b-3f2d-4f93-a67e-63d852e810a1" />








alias gpull='git pull'
alias gpush='git push origin head'
alias gs='git status'
alias ga='git add -A'
alias gcd='git checkout develop'
alias gcmn='git checkout master'
alias gd='git diff'
alias gb='git branch -a'
alias gst='git stash'
alias gl='git log --oneline'
alias tf='terraform'
alias tfi='terraform init'
alias tfv='terraform validate'
alias tfc='terraform console'
alias tfp='terraform plan'
alias tfdp='terraform plan -destroy'
alias tfap='terraform apply'
alias tfa='terraform apply --auto-approve'
alias tfd='terraform destroy --auto-approve'
alias tff='terraform fmt -recursive'
alias zsh='nano ~/.zshrc'
alias szsh='source ~/.zshrc'
alias oc='kubectl'
alias ksd='kubectl scale deployment '
alias optuatg='kubectl config use-context zeta-aws-use2-optuat-general'
alias optuatp='kubectl config use-context zeta-aws-use2-optuat-pci'
alias optuata='kubectl config use-context zeta-aws-use2-optuat-analytics'
alias opt1g='kubectl config use-context zeta-aws-use2-opt1-general'
alias opt1p='kubectl config use-context zeta-aws-use2-opt1-pci'
alias usnp='kubectl config use-context zeta-aws-use2-cprod-nonpci-eks-01'
alias usp='kubectl config use-context zeta-aws-use2-cprod-pci-eks-01'
alias showroom='kubectl config use-context zone-aws-default-pp-mumbai'
alias cps1='kubectl config use-context zone-aws-common-prod-mumbai'
alias cps2='kubectl config use-context zeta-aws-aps1-commonprod-space2-eks'
alias setns='kubectl config set-context --current --namespace '
alias pod='kubectl get po'
alias po='kubectl get po'
alias dep='kubectl get deploy'
alias svc='kubectl get svc'
alias ing='kubectl get ing'
alias cm='kubectl get configmap'
alias secret='kubectl get secret'
alias rs='kubectl get rs'
alias hpa='kubectl get hpa'
alias pv='kubectl get pv'
alias pvc='kubectl get pvc'
alias sa='kubectl get sa'
alias crb='kubectl get clusterrolebinding'
alias cr='kubectl get clusterrole'
alias role='kubectl get role'
alias rb='kubectl get rolebinding'
alias ns='kubectl get ns'
alias node='kubectl get nodes'
alias crd='kubectl get crd'
alias logs='kubectl logs'
alias exec='kubectl exec -it'
alias kap='kubectl apply -f'
alias kdel='kubectl delete -f'
alias kdesc='kubectl describe'
alias kedit='kubectl edit'
alias -oy='-o yaml'
alias -ow='-o wide'
alias -oj='-o json'
alias kctx='kubectl config use-context'
alias kconf='kubectl config view'
alias kns='kubectl config set-context --current --namespace'
alias k='kubectl'
alias kall='kubectl get all'
alias ktop='kubectl top pod'
 


  
Common Container Exit Codes
Exit Code   Meaning
---------   ----------------------------------------------

0           Success (container completed normally)
1           General error (application failure)
2           Misuse of shell command (invalid syntax, etc.)
126         Command invoked cannot execute (permission issue)
127         Command not found
128         Invalid exit argument
129         Hangup signal (SIGHUP)
130         Interrupted (Ctrl + C / SIGINT)
131         Quit (SIGQUIT)
132         Illegal instruction
133         Trace trap
134         Abort (SIGABRT)
135         Bus error
136         Floating point exception
137         Killed (SIGKILL) → VERY IMPORTANT (OOMKilled / force kill)
138         User-defined signal 1
139         Segmentation fault (SIGSEGV)
140         User-defined signal 2
141         Broken pipe
142         Alarm clock
143         Terminated (SIGTERM) → Graceful shutdown
144–159     Other signal-related exits

🔹 Kubernetes-Specific Important Ones (🔥 Interview + Real Use)
137   → OOMKilled (Out Of Memory)
        - Container exceeded memory limit
        - Very common in production
143   → SIGTERM
        - Pod is gracefully terminated (deployment update / scale down)
1     → Application error
        - Check logs immediately
0     → Job completed successfully (batch jobs, cronjobs)

🔹 Quick Debug Mapping (Real Scenario Thinking)
Exit Code	What You Should Check
137	Memory limits, OOMKilled, kubectl describe pod
143	Deployment rollout / manual delete / autoscaling
1	App logs (kubectl logs)
126/127	Dockerfile / command issue
139	App crash (segfault, mostly C/C++ apps)
🔹 Pro Debug Commands (🔥 Use in real job)
kubectl get pods
kubectl describe pod <pod-name>
kubectl logs <pod-name> --previous
kubectl get events --sort-by=.metadata.creationTimestamp
🔹 Bonus (Interview Tip)
If interviewer asks:
👉 “Why did container exit with 137?”
Answer:
Exit code 137 means the container was killed by SIGKILL, most commonly due to OOMKilled when it exceeds memory limits set in Kubernetes.
 


 
