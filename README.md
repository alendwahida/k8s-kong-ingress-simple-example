# k8s-kong-ingress-simple-example

Tutorial Kong :
- Simple kong ingress use

### 1. Install Kong Gateway (OSS) on Kubernetes native
   ```bash
   kubectl apply -f https://bit.ly/kong-ingress-dbless
   ```
### 2. Install Example Project k8s-kong-ingress
   ```bash
   git clone https://github.com/alendwahida/k8s-kong-ingress-simple-example.git
   cd k8s-kong-ingress-simple-example
   kubectl apply -f .
   ```
### 3. Change host with your own domain in ingress-kong.yaml


   source: https://docs.konghq.com/gateway/2.8.x/install-and-run/kubernetes/
