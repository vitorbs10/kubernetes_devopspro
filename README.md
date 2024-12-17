## Kubernetes: Conceitos Importantes

Este repositório contém o aprendizado sobre alguns conceitos essenciais do **Kubernetes**:

- **Pod**: A menor unidade de execução no Kubernetes, onde os contêineres são executados.
- **ReplicaSet**: Garante que um número desejado de Pods esteja sempre em execução, mantendo alta disponibilidade.
- **Labels**: Metadados usados para identificar e agrupar objetos no cluster, facilitando a seleção e o gerenciamento.
- **Deployment**: Controlador que gerencia a criação e atualização de ReplicaSets e Pods, garantindo escalabilidade e versões consistentes.
- **Rollout**: Processo de atualizar uma aplicação sem downtime, permitindo a substituição gradual de Pods antigos por novos. Rollbacks podem ser realizados em caso de falha.
- **Service**: Um objeto que expõe uma aplicação executando em um conjunto de Pods, oferecendo uma maneira estável de acessar os Pods, mesmo que eles mudem de IP.
- **Endpoint**: Representa as informações de rede de um **Service**, mapeando os Pods correspondentes para o endereço IP e a porta, permitindo o tráfego entre os componentes.

Esses conceitos são fundamentais para orquestrar e gerenciar aplicações no Kubernetes, permitindo a automação e escalabilidade de ambientes de produção.

