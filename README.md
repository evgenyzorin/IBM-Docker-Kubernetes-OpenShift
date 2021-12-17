# :rocket: Introduction to Containers w/ Docker, Kubernetes & OpenShift by IBM

This repository contains the Labs and the Final Project of the Introduction to Containers w/ Docker, Kubernetes &amp; OpenShift course provided by IBM on Coursera.

## :file_folder: [Week 1: Understanding the Benefits of Containers](https://github.com/evgenyzorin/IBM-Docker-Kubernetes-OpenShift/tree/main/Week%201)
### Understanding the Benefits of Containers
In this module, you will learn about the concept, features, use cases, and benefits of containers, and the difference between containers and virtual machines. You will learn about the term "Docker" and the several different uses of this term. One of the most used tools from Docker is the command line interface (CLI). We will introduce you to some of the more commonly used Docker CLI commands and how they work.Containers and images are two distinct entities, and in this module, you will learn about the differences between containers and images. You will learn how to build container images using Dockerfiles.Finally, you will learn about container registries and the functionalities they provide to help developers work more securely and productively.At the end of the module, you will do a hands-on exercise in which you will write a Dockerfile, build an image and run it as a container, and store the image in a registry.
### Learning Objectives
- Describe the features, benefits, and use cases of containers, and how they are different from virtual machines.
- Explain what Docker is and the several uses of the term Docker.
- List some of the commonly used Docker CLI commands and their functions.
- Explain how Docker works as a container runtime.
- scribe the three basic steps in the container development process.
- plain the difference between containers and images.
- st some of the commonly used instructions provided by Docker for use in Dockerfiles.
- Describe the basic purpose of container registries, how they differentiate themselves, and how users interact with them.
- Build a container image and store it in a container registry.

## :file_folder: [Week 2: Understanding Kubernetes Architecture](https://github.com/evgenyzorin/IBM-Docker-Kubernetes-OpenShift/tree/main/Week%202)
### Understanding Kubernetes Architecture
In this module, you will learn what container orchestration is and how it helps to create and manage the lifecycle of complex container environments. Kubernetes is the most popular container orchestration platform. In this module, we will familiarize you with the key architectural components of Kubernetes, such as the control plane components and controllers. You will also learn about the basics of Kubernetes objects, and how specific Kubernetes objects such as Pods, ReplicaSets, and Deployments work. The Kubernetes CLI, or "kubectl", is used to manipulate objects and manage workloads in a Kubernetes cluster. We will introduce you to a few basic kubectl commands and explain the relative benefits and shortcomings of both imperative and declarative commands. Finally, at the end of this module, you will use the kubectl CLI commands to create resources on an actual Kubernetes cluster.
### Learning Objectives
- Explain container orchestration and its benefits.
- Explain what Kubernetes is, how it works, and what makes it the most popular container orchestration platform.
- Describe the architecture of a Kubernetes cluster.
- List the components of the Kubernetes control planes and nodes and explain how they work.
- Describe what Kubernetes objects are and how specific Kubernetes objects such as Pods, ReplicaSets, and Deployments work.
- Describe what the Kubernetes CLI, or kubectl, is and the functionality this tool provides for working with Kubernetes clusters.
- List some of the basic commands of kubectl CLI.
- Explain how imperative and declarative commands work, as well as the benefits and shortcomings of each.

## :file_folder: [Week 3: Managing Applications with Kubernetes](https://github.com/evgenyzorin/IBM-Docker-Kubernetes-OpenShift/tree/main/Week%203)
### Managing Applications with Kubernetes
In this module, you will learn about some key concepts such as ReplicaSets, autoscaling, rolling updates, ConfigMaps, Secrets, and service bindings, and how they can be used to manage Kubernetes applications. You will learn how to use ReplicaSets to scale applications to meet increasing demand, and then use the autoscaling feature to make this scaling dynamic, as per demand. Using the rolling updates feature, you will learn how to publish updates to your application and also roll back the changes without creating any noticeable interruptions for your users. Storing hard-coded configuration variables and sensitive information in code is never a good idea. You will learn how to use ConfigMaps and Secrets to provide configuration variables and sensitive information to your deployments and keep your code clean. Finally, you will perform a hands-on exercise to scale and update applications deployed in Kubernetes.
### Learning Objectives
- Describe how a ReplicaSet is used to scale your application.
- Explain how to create a ReplicaSet using the CLI and a YAML file.
- Explain what autoscaling is and how it can be used to dynamically scale an application.
- Explain what a rolling update is and how to use rolling updates to publish and revert changes made to your application.
- Describe what a ConfigMap is and the different ways in which you can create ConfigMaps.
- Explain what a Secret is, the different ways to create a Secret, and how to use it to provide sensitive information to your application.
- Explain what service binding is and how to bind an external service to your deployment.

## :file_folder: [Week 4: The Kubernetes Ecosystem](https://github.com/evgenyzorin/IBM-Docker-Kubernetes-OpenShift/tree/main/Week%204)
### The Kubernetes Ecosystem: OpenShift, Istio, etc.
In this module, you will learn about the growing Kubernetes ecosystem and be introduced to some additional tools that work well with Kubernetes to support cloud-native development. You’ll learn about the Cloud Native Computing Foundation (CNCF) which hosts Kubernetes, and the valuable resources it provides for navigating the ecosystem. You’ll gain an understanding of both the similarities and the differences of Red Hat OpenShift and Kubernetes, and what an OpenShift architecture looks like. You will become familiar with OpenShift builds and BuildConfigs and learn about the various build strategies and triggers offered by OpenShift. Operators use custom resources and controllers to help package software and automate tasks within a cluster. In this module, you'll learn how an operator can deploy an entire application with ease. Finally, you'll learn about Istio, a service mesh, which provides traffic management and security, and facilitates communication between services in an application. At the end of the module, you do a hands-on exercise in which you use the oc CLI to perform commands on an OpenShift cluster. You will use the OpenShift build capabilities to deploy an application from source code stored in a git repository.
### Learning Objectives
- Describe why it is necessary to have an ecosystem around Kubernetes and identify 4 tools within the Kubernetes Ecosystem.
- Explain the relationship between Red Hat OpenShift and Kubernetes, as well as their similarities and differences.
- Explain the OpenShift build strategies and the three build triggers that stipulate when a build should run.
- Explain what an operator is and how operators help automate tasks within a cluster.
- Describe the capabilities Istio provides and why these capabilities are important for microservices.

## :file_folder: [Week 5: Final Assignment - Build and Deploy a Guestbook App](https://github.com/evgenyzorin/IBM-Docker-Kubernetes-OpenShift/tree/main/Week%205)
### Final Assignment: Final Project - Build and Deploy a Guestbook App
For the Final Project, you will put into practice the tools and concepts learned in this course, and deploy a simple guestbook application with Docker and Kubernetes.The entire application will be deployed and managed on OpenShift.
### Learning Objectives
- Build and deploy a simple guestbook application.
- Use OpenShift image streams to roll out an update.
- Deploy a multi-tier version of the guestbook application.
- Create a Watson Tone Analyzer service.
- Bind the Tone Analyzer service to your application.
- Autoscale the guestbook app.
