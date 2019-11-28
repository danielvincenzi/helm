# Helm

[Click here](https://helm.sh/)

## Install

Clone:

- ``` git clone https://github.com/harkayal/helm.git && cd helm ```

Download:

- ``` curl -L https://git.io/get_helm.sh | bash```

Apply & check:

- ``` kubectl apply -f helm-rbac.yaml ```
- ``` helm init --service-account=tiller --history-max 300 ```
- ``` kubectl get deployment tiller-deploy -n kube-system ```

Oh my God!
