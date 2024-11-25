# TUTORIAL KUBERNETS

## Este conteúdo faz parte do bootcamp Microsoft Azure Advanced da [DIO](https://www.dio.me/)

**Kubernetes** (ou **K8s**) é uma plataforma de **orquestração de containers** que automatiza o processo de **implantação**, **escalação** e **gerenciamento** de aplicativos em containers. Containers são uma forma de empacotar e isolar aplicações e suas dependências, o que facilita a execução e a portabilidade entre diferentes ambientes, como desenvolvimento, teste e produção.

Aqui estão os principais conceitos e benefícios do Kubernetes:

### 1. **Orquestração de Containers:**
   Kubernetes gerencia um conjunto de containers, coordenando onde e como eles são executados. Ele ajuda a garantir que os containers estejam sempre rodando, seja em máquinas físicas ou virtuais, e pode mover os containers de um host para outro conforme necessário.

### 2. **Escalabilidade Automática:**
   Kubernetes pode automaticamente escalar o número de containers para cima ou para baixo com base na demanda. Por exemplo, se uma aplicação precisar de mais recursos devido ao aumento de tráfego, o Kubernetes pode criar mais instâncias (pods) dessa aplicação automaticamente.

### 3. **Alta Disponibilidade e Resiliência:**
   Kubernetes é projetado para garantir que as aplicações estejam sempre disponíveis, mesmo se houver falhas no sistema. Se um container falhar, o Kubernetes pode reiniciá-lo automaticamente. Ele também pode mover os containers para outras máquinas ou pods para garantir que os serviços continuem funcionando sem interrupções.

### 4. **Gestão de Configurações:**
   Kubernetes permite o gerenciamento centralizado de configurações e segredos de maneira segura, facilitando o processo de configuração para os containers e aplicativos que estão sendo executados.

### 5. **Infraestrutura como Código (IaC):**
   O Kubernetes permite que a infraestrutura e as aplicações sejam descritas em arquivos de configuração, normalmente no formato YAML ou JSON. Isso facilita a automação e o versionamento da infraestrutura.

### 6. **Componentes Principais do Kubernetes:**
   - **Pod**: A menor unidade de execução no Kubernetes, que pode conter um ou mais containers.
   - **Deployment**: Define o estado desejado para um conjunto de pods, como o número de réplicas de um aplicativo que você quer manter.
   - **Service**: Um recurso que define como os pods se comunicam entre si e com o mundo exterior, equilibrando a carga entre os pods.
   - **Ingress**: Define como acessar um serviço Kubernetes a partir do exterior de um cluster, geralmente via HTTP ou HTTPS.
   - **Namespace**: Fornece uma maneira de dividir um cluster em diferentes "espaços", permitindo que diferentes equipes ou ambientes (produção, desenvolvimento, etc.) compartilhem o mesmo cluster.

### 7. **Ecossistema Kubernetes:**
   Kubernetes não é apenas uma plataforma autônoma; ele tem um ecossistema muito vasto com ferramentas complementares, como:
   - **Helm**: Um gerenciador de pacotes para Kubernetes.
   - **Prometheus**: Para monitoramento e alertas.
   - **Istio**: Para gerenciamento de tráfego e segurança de rede.

### 8. **Portabilidade:**
   Como Kubernetes pode ser executado em diferentes provedores de nuvem e em ambientes on-premises, ele permite que você crie ambientes de aplicação altamente portáteis, que podem ser facilmente movidos de uma infraestrutura para outra.


