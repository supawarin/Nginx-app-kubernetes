# Nginx-app-kubernetes
example nginx app use nginx-configMap run on kubernetes


### 1. Create nginx-config.yaml on you're project ####


### command : kubectl apply -f nginx-config.yaml  ####


<img width="497" alt="sc1" src="https://user-images.githubusercontent.com/83863431/182579782-886b62f1-a071-47ea-8299-7f6c86b03465.png">


### 2. Create nginx-deploy.yaml  ####


### command : kubectl apply -f nginx-deploy.yaml ####


<img width="596" alt="sc2" src="https://user-images.githubusercontent.com/83863431/182580618-426ea56c-9d3b-4168-b312-400c83bf2957.png">


### 3. Create nginx-service.yaml  ####


### command : kubectl apply -f nginx-service.yaml ####


<img width="417" alt="sc3" src="https://user-images.githubusercontent.com/83863431/182580904-7a2009bc-c252-43e4-ac12-4328643a9deb.png">


### kubectl get pods  $  kubectl get svc  to check pod and service Running or not ####


If Running , go to you're localhost ( this example is http://localhost:30008 )


And I have example database run on kubernetes . Good luck!
