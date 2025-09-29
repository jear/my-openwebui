# my-openwebui
```
helm repo add open-webui https://helm.openwebui.com/


helm upgrade --install -n open-webui --create-namespace open-webui open-webui/open-webui -f values.yaml --version 8.7.0  

helm repo update
helm search repo open-webui -l

helm upgrade --install -n open-webui --create-namespace open-webui open-webui/open-webui -f values.yaml --version 8.8.0  

```
