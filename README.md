This Capstone Project is the enhancement of the previously submitted project https://github.com/kapil24nagar/project-ml-microservice-kubernetes to use the AWS EKS instead of the locally installed Kubernetes cluster. 

Requirements: 
1. CircleCI
2. Docker Desktop/Hub
3. GitHub
4. Used these orbs
    a) circleci/aws-eks@1.1.0s
    b) circleci/kubernetes@0.4.0
    Added AWS and Docker credentials (AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, AWS_DEFAULT_REGION, DOCKER_USER, DOCKER_PASS) as the circleci project environemnt variables.
    
 Screenshots shows
 1. Circle CI green pipeline, i.e., completing all the jobs. 
 2. Docker Hub from showing the used image.
 3. EKS cluster
 4. EKS Nodes as EC2 instances
 5. Load balancer
 6. Application accessible from the browser.
