# Hacktiba-IntroSecKubernetes

Script da demo do evento Hacktiba

## Criando um cluster Kubernetes na Azure

- Cuidado! Se você já possui uma conta na Azure, esse lab pode aumentar o seu custo, não faça isso no seu ambiente produtivo!

Existe um template pronto para utilizarmos não iremos reinventar a roda vamos usar esse mesmo para analisar os eventos nele. 
[Quickstart: Deploy an Azure Kubernetes Service (AKS) cluster using an ARM template](https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-rm-template?tabs=azure-cli)

## Utilizando Kind
Esse é free nao precisa de preocupar!
- [Instalando o Kind](https://kind.sigs.k8s.io/docs/user/quick-start/)
- [Kind com multiplos nodes](https://mcvidanagama.medium.com/set-up-a-multi-node-kubernetes-cluster-locally-using-kind-eafd46dd63e5)

## Utilizando o Grype
O Grype é um scan de imagens que pode ser executado localmente. Mais detalhes [aqui](https://github.com/anchore/grype)

## Utilizando Kube-bench
O Kube-bench é uma ferramenta que verifica se o Kubernetes está implantado com segurança executando as verificações documentadas no CIS Kubernetes Benchmark.
Nesse [repo](https://github.com/aquasecurity/kube-bench/tree/main) tem as instruções.

## Utilizando o Kubescape
O Kubescape é uma plataforma de segurança Kubernetes de código aberto que fornece cobertura de segurança abrangente da esquerda para a direita em todo o ciclo de vida de desenvolvimento e implantação. Ele oferece recursos de proteção, gerenciamento de postura e segurança de tempo de execução para garantir proteção robusta para ambientes Kubernetes.
Mais detalhes [aqui](https://github.com/kubescape/kubescape)

## Utilizando KubeHound
KubeHound cria um gráfico de caminhos de ataque em um cluster Kubernetes, permitindo identificar rotas diretas e de vários saltos que um invasor é capaz de seguir, visualmente ou por meio de consultas gráficas complexas.
Mais detalhes de como instalar [aqui](https://kubehound.io/user-guide/getting-started/)
