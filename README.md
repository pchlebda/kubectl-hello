# Hello world app dockerized being able to run on kubernetes

## How to run
* Run command `kubectl apply -f deploy.yaml`
* Execute `kubectl get svc` and get external ip from load balancer
* Go to web browser ${EXTERNAL_IP}/hello
