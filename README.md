# kubernetes
This is a repository created to manage all kubernetes related stuffs.

We can deploy the application in kubernetes cluster using kubectl commands or using YAML configuration files.
Using YAML helps us to create more complex structures and apply it immediately on the fly. YAML files can be added to version control system to track the file changes. You can create number of yaml files for each application deployments, services, pods and so on.

httpd:
Here we have created a two yaml files to deploy httpd for deployment and service respectively.

httpd-basic-deployment.yml - It will run a single container within a pod using a docker image "httpd" and it will listen on port 80.
httpd-basic-service.yml - This file is for service that expose the port externally so that users will be able to access it.

Checkout this link for more informatin : https://www.learnitguide.net/2018/08/create-kubernetes-yaml-for-deployment.html
