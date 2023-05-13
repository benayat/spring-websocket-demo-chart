# spring-websocket-demo-chart
#### an example helm-chart for a spring boot app.
- mostly generic, to use with another app - change relevant values in values.yaml, templates/deployment.yaml, templates/service.yaml
- since I was using minikube, I had issues with exposing my app via nodePort service, so I used a simple clusterIp service with kubectl port-forward.
- since the image is currently in a private registry, I manually created a secret in my cluster. you can create an image yourself and replace the relevant values.

