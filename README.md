<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=codewars" alt="DIO - Project"></a>
<a href="https://en.wikipedia.org/wiki/Artificial_intelligence"><img src="https://img.shields.io/badge/AI-Project-FED564?logo=openai" alt="AI - Project"></a>
<a href="https://markdownlivepreview.com/" title="Vá para a página inicial do Editor"><img src="https://img.shields.io/badge/Markdown-%23000000.svg?logo=markdown&logoColor=white"></a>
<a href="https://azure.microsoft.com/pt-br/" title="Azure"><img src="https://custom-icon-badges.demolab.com/badge/Microsoft%20Azure-0089D6?logo=msazure&logoColor=white"></a>

## Resumo: Computação em Nuvem com Azure ☁️

### Como a Computação em Nuvem ☁️ Funciona ⚙️

  * **Modelos "As a Service"**: a nuvem opera com base em modelos de serviço (IaaS, PaaS, SaaS). Isso significa que, em vez de comprar e gerenciar tudo sozinho, eu posso contratar recursos sob demanda pela internet. Foi uma mudança interessante em relação à infraestrutura local.
  * **Custos e Comparativos**: os **custos do modelo local (On-Premise)**, percebendo o alto investimento inicial (CapEx) que geralmente é necessário. No entanto, vi que o **ambiente cloud** foca mais em despesas operacionais (OpEx), sendo assim eu posso pagar apenas pelo meu uso.
* **Modelos de Implementação**:
    * **On-Premise vs. Ambiente Cloud**: Entendi as diferenças em gerenciamento, como a nuvem pode oferece mais escalabilidade, e como os custos e o controle variam entre os dois.
    * **Modelo Híbrido (Hybrid Model)**: Percebir que o modelo híbrido pode ser uma ótima solução pelo fato de combinar a infraestrutura privada com os serviços da nuvem pública. Isso me dá Agilidade para usar o melhor de cada um.
    * **Qual Modelo Escolher**: Recebi orientações sobre como decidir qual modelo de nuvem (público, privado ou híbrido) se encaixa melhor nas minhas necessidades ou nas de um projeto.
* **Plataforma e Infraestrutura Global**:
    * **Platform**: Conheci o conceito de "plataforma" na nuvem, o que me ajudou a entender como os serviços são construídos e disponibilizados.
    * **Regiões e Zonas (Regions & Zones)**: Aprendi como a infraestrutura global da nuvem é organizada. Entender sobre regiões geográficas e zonas de disponibilidade me mostrou como é possível ter alta disponibilidade e resiliência para as aplicações.

---

### Fundamentos da Plataforma de Aplicações no Azure 🚀 🖲

* **Modelos de Computação em Nuvem**:  Comparei os diferentes modelos, o que fez Aumentar minha compreensão sobre suas características e quando usar cada um.
* **Aspectos Financeiros**:
    * **Comparar CapEx e OpEx**: Entendi em detalhes a diferença entre as despesas de capital (CapEx), como comprar servidores, e as despesas operacionais (OpEx), como pagar pelo uso de serviços na nuvem. Me deu uma visão mais clara de como a nuvem favorece o modelo OpEx.
* **Benefícios da Nuvem**:
    *  Escalabilidade (aumentar ou diminuir recursos conforme a necessidade), elasticidade, agilidade para lançar novos projetos, alcance global, confiabilidade e segurança.
    
* **Tipos de Serviço de Nuvem (As a Service)**:
    * **IaaS (Infraestrutura como Serviço)**:  o provedor cuida da infraestrutura física (servidores, armazenamento, rede), e eu cuido do sistema operacional, middleware e outras aplicações.
    * **PaaS (Plataforma como Serviço)**: No PaaS, o provedor gerencia a configuração e o gerenciamento de aplicativos, incluindo a atualização de bibliotecas e frameworks, o ambiente de desenvolvimento. O Azure App Service é um exemplo de serviço de PaaS que fornece um ambiente de desenvolvimento pronto para uso, incluindo ferramentas e bibliotecas necessárias para desenvolver e testar aplicativos.
    * **SaaS (Software como Serviço)**: No SaaS, o provedor fornece aplicações completas para uso, sem que o usuário precise gerenciar a infraestrutura o usuário pode acessar as aplicações diretamente pela internet.
    * **Modelo de Responsabilidade Compartilhada**: garante que tanto o provedor de nuvem quanto o usuário estejam comprometidos em manter a segurança e disponibilidade dos dados e aplicativos.
* **Componentes de Arquitetura do Azure**:
    * **Regiões**: os data centers do Azure espalhados pelo mundo onde meus recursos ficam hospedados.
    * **Zonas de Disponibilidade**: são locais fisicamente separados dentro de uma região, cada um com sua própria energia, refrigeração e rede. Isso é essencial para proteger as aplicações contra falhas em um único datacenter.
    * **Pares de Regiões**:  o Azure conecta regiões dentro da mesma área geográfica para facilitar a recuperação de desastres.
    * **Regiões Soberanas do Azure**:  Existem regiões especiais (como nos EUA e China) que atendem a requisitos bem rigorosos de conformidade e onde os dados devem permanecer.
    * **Recursos do Azure**: são recursos que eu posso criar e gerenciar no Azure, como máquinas virtuais, bancos de dados, Azure Blob Storage, File Storage e Disk Storage para armazenar dados.
    * **Assinaturas do Azure e Grupos de Gerenciamento**: Poder ser usando para organizar meus recursos, controlar o acesso e gerenciar os custos no Azure.
* **Computação e Rede**:
    * **Serviços de Computação do Azure**: são os recursos e ferramentas oferecidos pela Microsoft para executar aplicações e processos em nuvem, como Máquinas Virtuais, Azure App Service e Azure Functions.
    * **Serviços de Contêineres do Azure**: são recursos da plataforma Azure que permitem que você execute aplicações em contêineres, como Docker, de forma eficiente e escalável. como Azure Kubernetes Service (AKS) e Azure Container Instances (ACI).
* **Armazenamento (Storage)**:
    * **Domínio de Objetivo do Armazenamento**: são  diferentes tipos de armazenamento disponíveis no Azure e para que eles são utilizados.
    * **Redundância de Armazenamento**: O Azure oferece diferentes opções de redundância para garantir que os dados estejam seguros e disponíveis, mesmo em caso de falhas de hardware ou desastres naturais. (LRS - Locally Redundant Storage), (ZRS - Zone-Redundant Storage), (GRS - Geo-Redundant Storage), (RA-GRS - Read-Access Geo-Redundant Storage)
    * **Serviços de Armazenamento do Azure e Pontos de Extremidade**: os principais serviços de armazenamento são (Blob, File, Queue, Table, Disk Storage) Cada um desses serviços de armazenamento tem suas próprias características, desempenho, durabilidade e casos de uso.
    * **Camadas de Acesso de Armazenamento do Azure (Blob)**: As camadas de acesso (Hot, Cool, Archive) para otimizar os custos de armazenamento, com base na frequência de acesso aos dados.
    * **Azure Data Box**:  dispositivos físicos que posso usar para transferir grandes quantidades de dados para o Azure, de forma online ou offline.
    * **Hands-On**: Vir na prática! como **criar um armazenamento Blob** Isso ajudou a ver os passos mesmo sem tem assinatura ativamente.
      
## Conclusão:

Foi essencial compreender sobre os princípios da computação em nuvem, sobre os modelos como IaaS, PaaS e SaaS, a diferença entre CapEx e OpEx, e como a nuvem favorece o modelo OpEx. sobre os benefícios da computação em nuvem como escalabilidade, elasticidade, agilidade e segurança. os componentes de arquitetura do Azure, como regiões, zonas de disponibilidade e recursos. A parte prática de criar um armazenamento Blob.
