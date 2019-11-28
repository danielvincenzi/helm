# Helm

[Click here](https://helm.sh/)

## Installing

Clone:

- ``` git clone https://github.com/danvincenzi/helm.git && cd helm ```
- ``` curl -L https://git.io/get_helm.sh | bash```
- ``` kubectl apply -f helm-rbac.yaml ```
- ``` helm init --service-account=tiller --history-max 300 ```
- ``` kubectl get deployment tiller-deploy -n kube-system ```
