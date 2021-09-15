# API REST

Publicado em: 8 de maio de 2020•5 minutos (tempo de leitura)

IR PARA SEÇÃO

- [O que é API REST?](https://www.redhat.com/pt-br/topics/api/what-is-a-rest-api#o-que-é-api-rest)
- [REST](https://www.redhat.com/pt-br/topics/api/what-is-a-rest-api#rest)
- [Por que escolher a Red Hat?](https://www.redhat.com/pt-br/topics/api/what-is-a-rest-api#por-que-escolher-a-red-hat)

## O que é API REST?

API REST, também chamada de API RESTful, é uma [interface de programação de aplicações](https://www.redhat.com/pt-br/topics/api/what-are-application-programming-interfaces) (API ou API web) que está em conformidade com as restrições do estilo de arquitetura REST, permitindo a interação com serviços web RESTful. REST é a sigla em inglês para "Representational State Transfer", que em português significa tansferência de estado representacional. Essa arquitetura foi criada pelo cientista da computação Roy Fielding.

## O que é API?

Uma API é um conjunto de definições e protocolos usado no desenvolvimento e na integração de aplicações. Às vezes, as APIs são descritas como um contrato entre um provedor e um usuário de informações, estabelecendo o conteúdo exigido pelo consumidor (a chamada) e o conteúdo exigido pelo produtor (a resposta). Por exemplo, o design da API de um serviço meteorológico pode especificar que o usuário forneça um CEP e o produtor responda em duas partes, a primeira contendo a temperatura mais elevada e a segunda com a temperatura mais baixa. 

Em outras palavras, ao interagir com um computador ou sistema para recuperar informações ou executar uma função, a API ajudará a comunicar o que você quer ao sistema para que ele entenda e realize o que foi solicitado. 

Pense nas APIs como um mediador entre os usuários ou clientes e os recursos ou serviços web que eles querem obter. As APIs também servem para que organizações compartilhem recursos e informações e, ao mesmo tempo, mantenham a segurança, o controle e a obrigatoriedade de autenticação, pois permitem determinar quem tem acesso e o que pode ser acessado. 

Outra vantagem de usar APIs é que não é necessário saber todos os detalhes sobre o armazenamento em cache, como os recursos são recuperados ou qual é a origem deles.

[Saiba mais sobre APIs](https://www.redhat.com/pt-br/topics/api/what-are-application-programming-interfaces)

![img](https://www.redhat.com/cms/managed-files/styles/max_size/s3/ilustracion_ots_1.png?itok=aF_jCITC)

#### Red Hat Open Technology Sessions

Assista a série de webinars gratuitos da Red Hat e descubra como impulsionar a inovação tecnológica usando modelos colaborativos.

[Assista aos webinars on demand](https://www.redhat.com/pt-br/open-tech-sessions?intcmp=7013a000002ptzhAAA)

## REST

REST não é um protocolo ou padrão, mas sim um conjunto de restrições de arquitetura. Os desenvolvedores de API podem implementar a arquitetura REST de maneiras variadas.

Quando um cliente faz uma solicitação usando uma API RESTful, essa API transfere uma representação do estado do recurso ao solicitante ou endpoint. Essa informação (ou representação) é entregue via HTTP utilizando um dos vários formatos possíveis: Javascript Object Notation (JSON), HTML, XLT, Python, PHP ou texto sem formatação. O formato JSON é a linguagem de programação mais usada porque, apesar de seu nome, é independente de qualquer outra linguagem e pode ser lido por máquinas e humanos. 

Lembre-se também de que cabeçalhos e parâmetros são importantes nos métodos HTTP de uma solicitação HTTP de API RESTful porque contêm informações relevantes sobre o identificador, bem como metadados, autorização, Uniform Resource Identifier (URI), cache, cookies e outras informações da solicitação. Há os cabeçalhos da solicitação e os cabeçalhos da resposta, cada um contendo as informações de suas respectivas conexões HTTP e códigos de status.

Para que uma API seja considerada do tipo RESTful, ela precisa está em conformidade com os seguintes critérios:

- Ter uma arquitetura cliente/servidor formada por clientes, servidores e recursos, com solicitações gerenciadas por HTTP.
- Estabelecer uma comunicação [stateless](https://www.redhat.com/pt-br/topics/cloud-native-apps/stateful-vs-stateless) entre cliente e servidor. Isso significa que nenhuma informação do cliente é armazenada entre solicitações GET e toda as solicitações são separadas e desconectadas.
- Armazenar dados em cache para otimizar as interações entre cliente e servidor.
- Ter uma interface uniforme entre os componentes para que as informações sejam transferidas em um formato padronizado. Para tanto, é necessário que:
  - os recursos solicitados sejam identificáveis e estejam separados das representações enviadas ao cliente;
  - os recursos possam ser manipulados pelo cliente por meio da representação recebida com informações suficientes para tais ações;
  - as mensagens autodescritivas retornadas ao cliente contenham informações suficientes para descrever como processá-las;
  - hipertexto e hipermídia estão disponíveis. Isso significa que após acessar um recurso, o cliente pode usar hiperlinks para encontrar as demais ações disponíveis para ele no momento.
- Ter um sistema em camadas que organiza os tipos de servidores (responsáveis pela segurança, pelo carregamento de carga e assim por diante) envolvidos na recuperação das informações solicitadas em hierarquias que o cliente não pode ver.
- Possibilitar código sob demanda (opcional): a capacidade de enviar um código executável do servidor para o cliente quando solicitado para ampliar a funcionalidade disponível ao cliente. 

Embora uma API REST precise estar em conformidade com os critérios acima, ela é considerada mais fácil de usar do que um protocolo prescrito, como o Protocolo Simples de Acesso a Objetos (SOAP). Esse tipo de protocolo tem requisitos específicos, como o sistema de mensageria XML, além de precisar cumprir com exigências de segurança incorporada e transações, o que o torna mais lento e pesado. 

Em comparação, a arquitetura REST é composta de um conjunto de diretrizes que podem ser implementadas conforme necessário. Isso faz com que as APIs REST sejam mais rápidas, leves e escaláveis, o que é ideal para a [Internet das Coisas (IoT)](https://www.redhat.com/pt-br/topics/internet-of-things) e o [desenvolvimento de aplicativos mobile](https://www.redhat.com/pt-br/topics/mobile). 

[Leia mais sobre a diferença entre REST e SOAP](https://www.redhat.com/pt-br/topics/integration/whats-the-difference-between-soap-rest)[Conheça o Red Hat OpenShift API Management](https://developers.redhat.com/products/red-hat-openshift-api-management/getting-started)

## Por que escolher a Red Hat?

[Red Hat® Integration](https://www.redhat.com/pt-br/products/integration) é uma solução orientada a APIs que proporciona conectividade de aplicações, transformação de dados, composição e orquestração de serviços, streaming de mensagens em tempo real, coleta de dados de mudanças e gerenciamento de APIs. Tudo isso em um único lugar para conectar aplicações e dados em infraestruturas híbridas. Essa solução é combinada a uma plataforma nativa em nuvem e uma cadeia de ferramentas para viabilizar o desenvolvimento de aplicações modernas. 

[Red Hat 3scale API Management](https://www.redhat.com/pt-br/technologies/jboss-middleware/3scale) é um componente do Red Hat Integration que permite compartilhar, distribuir, controlar e monetizar APIs em uma plataforma de infraestrutura desenvolvida para proporcionar alto desempenho, controle, segurança e crescimento. Implemente os componentes do 3scale on-premise, na nuvem ou em ambos. 

[Conheça as soluções Red Hat Application Services](https://www.redhat.com/pt-br/products/middleware)

### Recursos em destaque

- Ebook: [O Caminho para a Adoção de Aplicações Nativas em Nuvem](https://www.redhat.com/pt-br/resources/path-to-cloud-native-applications-ebook)
- Ebook: [Como Ensinar um Elefante a Dançar](https://www.redhat.com/pt-br/resources/teaching-an-elephant-to-dance-executive-summary-ebook)

### Leia mais sobre as APIs

- Tópico: [Introdução a APIs](https://www.redhat.com/pt-br/topics/api)
- Artigo: [O que são APIs?](https://www.redhat.com/pt-br/topics/api/what-are-application-programming-interfaces)
- Artigo: [O que é design de APIs?](https://www.redhat.com/pt-br/topics/api/what-is-api-design)
- Artigo: [O que é gerenciamento de APIs?](https://www.redhat.com/pt-br/topics/api/what-is-api-management)
- Artigo: [O que é monetização de APIs?](https://www.redhat.com/pt-br/topics/api/what-is-api-monetization)
- Artigo: [O que é GraphQL?](https://www.redhat.com/pt-br/topics/api/what-is-graphql)
- Artigo: [O que é a segurança de APIs?](https://www.redhat.com/pt-br/topics/security/api-security)
- Artigo: [Por que escolher a Red Hat para o gerenciamento de APIs?](https://www.redhat.com/pt-br/topics/api/why-choose-red-hat-apis)
- Vídeo: [Integração ágil: o impacto que as APIs causam nos negócios, com Steve Willmott](https://www.redhat.com/pt-br/about/videos/agile-integration-business-impact-apis-steve-willmott)

### Treinamento gratuito

[Red Hat Agile Integration Technical Overview (DO040)](https://www.redhat.com/pt-br/services/training/do040-red-hat-agile-integration-technical-overview)
Aprenda o básico da integração ágil

### Ferramentas de integração

[![Red Hat Integration logo](https://www.redhat.com/cms/managed-files/red-hat-integration.svg?itok=bAXqG8y5)](https://www.redhat.com/pt-br/products/integration)

Um conjunto abrangente de tecnologias de integração e mensageria.

[Saiba mais](https://www.redhat.com/pt-br/products/integration)

[![Red Hat 3scale API Management](https://www.redhat.com/cms/managed-files/red-hat-3scale-api-management--stacked.svg?itok=YjGbF77O)](https://www.redhat.com/pt-br/technologies/jboss-middleware/3scale)

Uma plataforma de gerenciamento de APIs.

[Saiba mais](https://www.redhat.com/pt-br/technologies/jboss-middleware/3scale)

[![img](https://www.redhat.com/cms/managed-files/Logo-Red_Hat-OpenShift_API_Management-B-Standard-RGB_0.svg?itok=cqP8Jyz_)](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/openshift-api-management)

Serviço de gerenciamento de APIs gerenciadas para o Red Hat OpenShift Dedicated.

[Saiba m](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/openshift-api-management)