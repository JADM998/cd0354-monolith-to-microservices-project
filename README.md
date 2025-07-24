# My submission: Refactor Monolith application into microservices

Hello, I am submitting this as part of the evidence for the Cloud Developer nanodegree program in Udacity.

I have to say that I changed a little bit of the requisites, always trying to stick to what was recommended. I decided to use Github Actions instead of CircleCI/TravisCI because it is free and is a tool I will be using in my work environment. Below are examples of Q&A where the usage of Github Actions is allowed.

1. https://knowledge.udacity.com/questions/947736
2. https://knowledge.udacity.com/questions/1018022
3. https://knowledge.udacity.com/questions/1042241

# Repository structure

I have uploaded the code for the application as stated in the course. The following folders contain the microservices required. and their dockerfile. I have not included the configuration and secrets yaml files, only the deployment and service ones.

1. `udagram-api-feed`: Contains the feed microservice
2. `udagram-api-user`: Contains the user microservice
3. `udagram-frontend`: Contains the frontend microservice
4. `udagram-reverseproxy`: Contains the reverseproxy.

Next, there is the `deployment` folder which contains the deployment and service yaml files of each microservice. Those are the configurations I used to interact with my k8s cluster.

Finally, the `screenshoot` folder in which I uploaded evidence of my usage of kubectl, dockerhub and Github Actions.

# AWS Application

This link is only going to be valid during the evaluation phase. This link conducts to the udagram application I'm running in my k8s cluster.

Link: Submitted ih the submission Details.

