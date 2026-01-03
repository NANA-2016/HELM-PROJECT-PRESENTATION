# HELM-PROJECT-PRESENTATION

### PROJECT SETUP

Set up ecommerce directory  and in the directory set up sub directories 

Product-service,cart-servicde and order-service .

<img width="1543" height="85" alt="image" src="https://github.com/user-attachments/assets/39e241e2-4085-469a-8148-d9355bd88dac" />

After this initializa a git repository 

### DOCKERIZE THE MICROSERVICES

For each microservice, create a docker file 

<img width="1443" height="497" alt="image" src="https://github.com/user-attachments/assets/7b79ce21-8394-44d7-9229-dcd214e269ab" />

### PUSH TO DOCKER HUB.

Log in to Docker hub and and create a repository for each microservice

<img width="1526" height="257" alt="image" src="https://github.com/user-attachments/assets/8007a787-33bf-4fbb-a8ec-2037fefe423a" />

### SET UP AgroCD WITH KUBERNETES

Install AgroCD in kubernetes cluster

<img width="551" height="252" alt="image" src="https://github.com/user-attachments/assets/4a8fd3fa-2514-4ee6-bba1-89d4ca6aa2b4" />

Connect git repository to AgroCD

### KUBERNETES DEPLOYMENT

Create kubernetes deployment YAML file  for ech microservice and define the ArgoCD application YAML to manage the deployments

CREATE KUBERNETES SERVICES

Create kubernetes services YAML files for each microservice specifying the type as clusters and use ArgoCD  to apply theses services to your cluster 

<img width="1451" height="455" alt="image" src="https://github.com/user-
  attachments/assets/5c6075e7-4a85-4ba6-b209-0341acd224fe" />

  <img width="1257" height="122" alt="image" src="https://github.com/user-attachments/assets/f8beca97-f7d1-495f-8119-95015ed7db29" />

  <img width="1323" height="675" alt="image" src="https://github.com/user-attachments/assets/693e6320-1272-493a-9d3d-eaaef5ab1334" />


Above shows using agros for resource deployment 
  

  
