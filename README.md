# cka/ckad-bootcamp learning path 

- [cncf-cka](https://www.cncf.io/certification/cka/)
- [candidate-handbook](https://docs.linuxfoundation.org/tc-docs/certification/lf-candidate-handbook)
- [CKA Syllabus](https://github.com/cncf/curriculum)

## Certified k8s Administrator (CKA) 2020
###  - We will have an understanding of key concepts 
             
```
- Topics include 
        - The ability to establish basic use-cases for end users
        - k8s architecture, Installation and Config
        - Application lifecycle management (Images,Containers,Pods)
        - Deployments
        - Scheduling 
        - Services/Networking 
        - Jobs and CronJobs
        - Security
        - Storage 
        - Logging  
        - Troubleshooting of k8s components
```
### - A certified K8s administrator can work proficiently to 
        - design
        - install
        - configure 
        - manage a k8s production-grade cluster  
        
###  1. Cluster Architecture, Installation & Configuration – 25%

         - Manage role based access control (RBAC)
         - Use Kubeadm to install a basic cluster
         - Manage a HA cluster
         - Provision underlying infrastructure to deploy a k8s cluster
         - Perform a version upgrade on a k8s cluster using Kubeadm
         - Implement etcd backup and restore

### 2. Services & Networking – 20% 

         - Understand 
                    - Host networking configuration on the cluster nodes
                    - connectivity between Pods
                    - ClusterIP, NodePort, LoadBalancer service types and endpoints
         - Know how to use Ingress controllers and Ingress resources
         - Know how to configure and use CoreDNS
         - Choose an appropriate CNI  plugin

### 3. Troubleshooting – 30%
        - Evaluate cluster and node logging
        - Understand how to monitor applications
        - Manage container stdout & stderr logs
        - Troubleshoot 
                  - cluster component failure
                  - application failure
                  - networking
### 4. Workloads & Scheduling – 15%

            - Understand deployments 
            - how to perform rolling update and rollbacks
            - Use ConfigMaps and Secrets to configure applications
            - how to scale applications
            - Understand the primitives used to create robust, self-healing, application deployments
            - Understand how resource limits can affect Pod scheduling
            - Awareness of manifest management and common templating tools
### 5. Storage – 10%

            - Understand 
                - storage classes 
                - persistent volumes
                - volume mode 
                - access modes 
                - reclaim policies for volumes
                - PVC (persistent volume claims) primitive
            - how to configure applications with persistent storage
