# Criação do projeto
Primeiro item é criar um projeto no GCP (alcateiadev)

# Criando a VM para o Github Runner
1. Criar uma VM na região E2 e E2-medium (2 vCPU e 4 GB)
   1. Mudar a imagem para Ubuntu 18.04
2. Acessar por SSH
3. Instalar java 1.8
   1. sudo apt-get install openjdk-8-jdk
4. Instalar Helm
   1. $ curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
      $ chmod 700 get_helm.sh
      $ ./get_helm.sh
5. Instalar o Girhub Runner
   1. Na sua conta pessoal, ir em setting, Actions e Runner
   2. Seguir os passos para instalação
6. Dar um push na branch master e verificar se o build roda normalmente

