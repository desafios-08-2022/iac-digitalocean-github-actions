# iac-digitalocean-github-actions

crie e populo o arquivo terraform.tfvars conforme exemplo
o Token da DO é na console no menu API

```
terraform plan -out plan1
terraform apply plan1
cp kube_config.yaml ~/.kube/config  # Cuidado - este comando irá sobrepor o arquivo config da pasta ~/.kube

kubectl apply -f kube-news/k8s/deployment.yaml
```
```
watch kubectl get svc
```

espere gerar o IP, acesse a aplicação no navegador e faça seus testes!


terraform destroy