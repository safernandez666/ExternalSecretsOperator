# ExternalSecretsOperator

External Secrets Operator on Kubernetes with Hashicorp Vault

### Install Vault with Helm

``` bash
helm repo add hashicorp https://helm.releases.hashicorp.com
helm install vault hashicorp/vault --namespace vault --create-namespace -f hashicorp-vault/values.yaml
```
