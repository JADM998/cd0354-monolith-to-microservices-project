# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed
* GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook)
* Travis CI showing a successful build and deploy job

## Note to reviewer
Since I did not use Travis CI since it was no longer free I decided to showcase my building experience in the `Github Actions` folder. In that folder you can find all the workflows I have executed. Also, I have added a small sample of the logs thrown by the workflows.

## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
*This can be found inside the `pods` folder*.

* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
*This can be found inside the `services` folder*.
* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
*This can be found inside the `hpa` folder*.
* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
*This can be found inside the `logs` folder*.
