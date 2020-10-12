# Deploying an Application to a Kubernetes Engine Cluster

![project image](./img/kubernetes.png)

## Table of Contents
* [Usage](#usage)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributors](#contributors)
* [Questions](#questions)

## Usage
A Kubernetes cluster contains a master machine and multiple node machines. In order to generate a Kubernetes cluster in gcloud, configure the gcloud console with `gcloud container clusters create [CLUSTER]` where [CLUSTER] is the name of the cluster you want to generate. The next step is obtaining the authentication credetials of the cluster in order to access and interact with the cluster. By using the gcloud shell command `gcloud container clusters get-credentials [CLUSTER]`, the cluster is authenticated. 

Once the cluster has been created and authenticated, a *containerized* application can be deployed to it. There are two types of objects that Kubernetes uses to utilize the cluster's resources. A *deployment* object is what Kubernetes uses to deploy stateless applications. An example of a stateless application would be a content delivery network (CDN). A *service* object defines load balancing rules for outside acccess to the application over the Internet. 

Run the shell command `kubectl create` in the gcloud console to create a `sample-server` from a `sample-app` disk image:
`kubect1 create deployment sample-server --image=`





## Installation

## Usage

## License

## Contributors

## Questions
Contact me:

Github: [https://github.com/mohmorsi](https://github.com/mohmorsi)




