# Screenshots

## AWS S3
##### Amazon Simple Storage Service Screenshot
<figure>
    <img src="S3_Screenshot.PNG">
    <figcaption>Amazon Simple Storage Service Screenshot</figcaption>
</figure>

## AWS RDS
##### Amazon Relational Database Service Screenshot
<figure>
    <img src="RDS_Screenshot.PNG">
    <figcaption>Amazon Relational Database Service Screenshot</figcaption>
</figure>

## Deployment Pipeline
##### DockerHub showing containers that you have pushed
<figure>
    <img src="/screenshots/DockerHub/DockerHub_Before_Pushing_Images_Screenshot.PNG"
         alt="DockerHub Before Pushing Images Screenshot">
    <figcaption>DockerHub Before Pushing Images Screenshot</figcaption>
</figure>
<figure>
    <img src="/screenshots/DockerHub/DockerHub_After_Pushing_Images_Screenshot.PNG"
         alt="DockerHub After Pushing Images Screenshot">
    <figcaption>DockerHub After Pushing Images Screenshot</figcaption>
</figure>

##### GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook)
<figure>
    <img src="/screenshots/Travis_CI/Travis_CI_Webhook.PNG"
         alt="Travis CI Webhook">
    <figcaption>Travis CI Webhook</figcaption>
</figure>

##### Travis CI showing a successful build and deploy job
<figure>
    <img src="/screenshots/Travis_CI/Travis_CI_Screenshot.PNG"
         alt="Travis CI Screenshot">
    <figcaption>Travis CI Screenshot</figcaption>
</figure>

## Kubernetes
##### To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
<figure>
    <img src="/screenshots/Kubectl/kubectl_get_pods_Screenshot.PNG"
         alt="kubectl get pods Screenshot">
    <figcaption>kubectl get pods Screenshot</figcaption>
</figure>

##### To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
<figure>
    <img src="/screenshots/Kubectl/kubectl_describe_services_1_Screenshot.PNG"
         alt="kubectl describe services 1 Screenshot">
    <figcaption>kubectl describe services 1 Screenshot</figcaption>
</figure>
<figure>
    <img src="/screenshots/Kubectl/kubectl_describe_services_2_Screenshot.PNG"
         alt="kubectl describe services 2 Screenshot">
    <figcaption>kubectl describe services 2 Screenshot</figcaption>
</figure>

##### To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
<figure>
    <img src="/screenshots/Kubectl/kubectl_describe_hpa_1_Screenshot.PNG"
         alt="kubectl describe hpa 1 Screenshot">
    <figcaption>kubectl describe hpa 1 Screenshot</figcaption>
</figure>
<figure>
    <img src="/screenshots/Kubectl/kubectl_describe_hpa_2_Screenshot.PNG"
         alt="kubectl describe_hpa 2 Screenshot">
    <figcaption>kubectl describe_hpa 2 Screenshot</figcaption>
</figure>

##### To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```

<figure>
    <img src="/screenshots/Kubectl/kubectl_logs_backend_feed_Screenshot.PNG">
    <figcaption>kubectl logs backend feed Screenshot</figcaption>
</figure>
<figure>
    <img src="/screenshots/Kubectl/kubectl_logs_backend_user_Screenshot.PNG">
    <figcaption>kubectl logs backend user Screenshot</figcaption>
</figure>
<figure>
    <img src="/screenshots/Kubectl/kubectl_logs_frontend_Screenshot.PNG">
    <figcaption>kubectl logs frontend Screenshot</figcaption>
</figure>
<figure>
    <img src="/screenshots/Kubectl/kubectl_logs_reverse_proxy_Screenshot.PNG">
    <figcaption>kubectl logs reverse proxy Screenshot</figcaption>
</figure>
