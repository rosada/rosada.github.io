---
layout: default
---

# Hi, welcome
So, because as **devops engineer** I often forgot about the project I do, and also I want to have wiki for myself, I am using this free pages.

Just see my profile here : 
[Linkendin](https://www.linkedin.com/in/arifrosada/).


## KUBE-JENKINS-ARGOCD-HARBOR
this is my code to automate build fresh RKE cluster, so when you do RKE UP + kubectl apply you will get Kubernetes cluster with ArgoCD, Jenkins,Harbor.
what will be installed is :
* Jenkins to automate deployment of the application, Jenkins will be installed as add-on and will setup to load grovy script to initiate first jenkins job
* Harbor is docker registry, just install it
* ArgoCD is Continues Delivery tools, so argo will read the manifest repo 

Here is the code and how to install : [KUBERNETES]().

## ANSIBLE-VAGRANT-WEBSERVER
this is my code from learning course, so the idea is I want to create apache website with mysql DB and nginx as LB, using ansible role.
What will be installed is :
* 4 Linux servers with Ubuntu OS running
* Give them the role, for example 1 particular IP will be the LB
* Webserver role will install apache and insert demo_app
* The database will be mysql and automate creation of the database + user
* The LB role using nginx proxy to webserver


Here is the code and how to install : [Ansible-infra](https://github.com/rosada/ansible-infra).




## Update again later
