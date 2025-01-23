# CKAExam-
CKA exam preparation:network policy

https://github.com/piyushsachdeva/CKA-2024/blob/main/Resources/Day26/task.md

Task 26/40
In this exercise, you will learn Authentication and Authorization in Kubernetes

Task details
Create a new kind cluster by disabling the default CNI

Install Calico Network Add-on to your Kind cluster

Create 3 deployments with as below: name: frontend , image-name: nginx , replicas=1 , containerPort name: backend , image-name: nginx , replicas=1 , containerPort name: db , image-name: mysql , replicas=1 , containerPort: 3306

Expose all of these applications on a nodePort service with the same name as the deployment name

Do the connectivity test that all of your pods are able to interact with each other.

Create a network policy and restrict the access so that only backend pod should be able to access the db service on port 3306.

Attach this network policy to the backend deployment


https://medium.com/@savitapadarya22/cka-exam-network-policies-fece0c29b9fc
