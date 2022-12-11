# datadog



Documentação sobre a instalação e configuração do DataDog monitoramento em ambinete Kubernetes

Pré-requisitos O uso do Operador Datadog requer os seguintes pré-requisitos: Kubernetes Cluster versão >= v1.14.X: Os testes foram feitos em versões >= 1.14.0. Ainda assim, deve funcionar em versões >= v1.11.0. Para versões anteriores, devido ao suporte limitado de CRD, o Operador pode não funcionar conforme o esperado. Helm para implantar o datadog-operator. Kubectl CLI para instalar o datadog-agent.
