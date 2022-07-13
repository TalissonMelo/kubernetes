# Kubernates

##### kubectl apply -f "NOME_ARQUIVO".yaml

### Rollout e Revisões
 
##### kubectl rollout history deployment "NOME_ARQUIVO"
##### kubectl rollout undo deployment "NOME_ARQUIVO" -------------------------> Volta par ultima versão
##### kubectl rollout undo deployment "NOME_ARQUIVO" --to-version="VERSAO" ---> Volta para versão especificada

### Pod

##### Mapeamento de porta - kubectl port-forward pod/"NOME_ARQUIVO" 80:80
##### Deletando um pod    - kubectl delete pod "NOME_ARQUIVO"
##### Vericação de pod    - kubectl get pods --watch
##### Listagem de pods    - kubectl get pods
##### Descrever o pod     - kubectl describe pod "NOME_ARQUIVO"

### ReplicaSet

##### Deletando um ReplicaSet    - kubectl delete replicasets "NOME_ARQUIVO"

### Deployment

##### Listagem de Deployments    - kubectl get deployment
##### Deletando um Deployment    - kubectl delete deployment "NOME_ARQUIVO"