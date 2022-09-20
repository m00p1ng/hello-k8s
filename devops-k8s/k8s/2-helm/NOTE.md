```sh
$ helm repo udate
$ helm install my-release bitnami/mongodb

$ helm create <project_name>
$ helm template -f email-service-values.yml microservice
$ helm template -f email-service-values.yml --set appReplicas=2 microservice

$ helm lint

$ helm install -f email-service-values.yml emailservice microservice

$ helm ls

$ helm delete emailservice
```
