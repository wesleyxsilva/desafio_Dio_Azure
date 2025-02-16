# desafio_Dio_Azure
desafio dio microsoft Azure
# desafio_Dio_Azure
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

A computação em nuvem é uma tecnologia que permite o acesso sob demanda a recursos de TI como servidores, armazenamento, bancos de dados, redes, software pela internet, sem a necessidade de gerenciar infraestrutura física. 
O objetivo principal é oferecer escalabilidade, flexibilidade, redução de custos e alta disponibilidade para empresas e usuários.
algums Benefícios:
-Aumentar ou reduzir recursos conforme a demanda.
-Pagar apenas pelo que usar modelo pay-as-you-go.
-Serviços sempre acessíveis, com redundância e backups.
-Implantação rápida de aplicações e serviços.
-Proteção de dados e conformidade com regulamentações.


Existem três principais modelos de nuvem, cada um com suas características e casos de uso:

Nuvem Pública: que sao recursos compartilhados e disponibilizados por provedores como Microsoft Azure, AWS e Google Cloud.tem como vantagem o 
Custo inicial baixo onde não e cecessario investimento em hardware.
Escalabilidade ilimitada,manutenção gerenciada pelo provedor.sua desvantagens e o menor controle sobre a infraestrutura com preocupações com segurança e conformidade.

Nuvem Privada: tem infraestrutura dedicada a uma única organização, gerenciada internamente ou por terceiros.suas vantagens são o maior controle e personalização onde tem segurança e conformidade reforçadas, porem sua desvantagem e o custo inicial alto necessario investimento em hardware e software.
Escalabilidade limitada.

Nuvem Híbrida: tem combinação de nuvens públicas e privadas, permitindo que cargas de trabalho sejam movidas entre elas conforme necessário.suas vantagens são a flexibilidade para usar o melhor de ambos os modelos.Ideal para migrações graduais ou necessidades específicas de segurança.porem sua desvantagens são a Complexidade de gerenciamento e custos adicionais de integração.

Comparação entre Capex e Opex: 
Capex-tem gastos com investimentos iniciais em infraestrutura física, como servidores, storage e redes.com alto custo inicial e ativos depreciados ao longo do tempo com responsabilidade pela manutenção e atualizações ou seja as empresas compram e gerenciam seu próprio hardware.sua desvantagens são a falta de flexibilidade para escalar,custos fixos, mesmo com infraestrutura ociosa.

Opex- tem gastos operacionais contínuos, como assinaturas de serviços em nuvem,pagamento conforme o uso (pay-as-you-go) e sem custos iniciais elevados.Sua manutenção e atualizações gerenciadas pelo provedor.Tem flexibilidade para escalar recursos conforme a demanda com redução de custos com infraestrutura ociosa sem preocupação com gerenciamento de hardware.seu beneficios são a redução de Custos Iniciais sem necessidade de investir em hardware.Escalabilidade: Aumentar ou diminuir recursos conforme a demanda com atualizações Automáticas o Azure gerencia patches e atuallizações de segurança tem pagamento mensal ou por uso, facilitando o planejamento financeiro.

resumindo oque aprendi a computação em nuvem oferece flexibilidade, escalabilidade e redução de custos, com modelos como nuvem pública, privada e híbrida atendendo a diferentes necessidades.No Microsoft Azure, a transição de Capex para Opex permite que as empresas reduzam custos iniciais, otimizem operações e foquem em inovação, sem se preocupar com a infraestrutura física.Escolher o modelo de nuvem e a estratégia de gastos entre Capex e Opex depende das necessidades específicas de cada organização, mas a tendência é a adoção de modelos baseados em Opex para maior eficiência e competitividade.
---------------------------------------------------------------------------------------------------------------------------------------------------------
dentro do modelo de responsabilidade compartilhada temos os 3 grupos IaaS, PaaS e SaaS são modelos de serviço em nuvem que oferecem diferentes níveis de controle, flexibilidade e gerenciamento para os usuários. Onde cada um atende a necessidades específicas de infraestrutura, desenvolvimento e aplicações.

1.IaaS ou infraestrutura como Serviço fornece infraestrutura de TI básica, como servidores virtuais, armazenamento, redes e sistemas operacionais, como um serviço sob demanda.nesse modelo nos temos mais acesso de personalização daquele recurso.
2.PaaS ou plataforma como Serviço fornece um ambiente completo e elimina a necessidade de gerenciamento de servidores e sistemas operacionais permitindo que os desenvolvedores se concentrem na criação de software. 
3.SaaS ou Software como Serviço fornece aplicações completas em nuvem qu podem ser acessadas por navegador ou APIs.nesse serviço o usuário só precisa se preocupar com a utilização do serviço pois o provedor de nuvem gerencia e faz a manutenção.

O modelo de responsabilidade compartilhada define as responsabilidades entre o provedor de nuvem e o cliente.Esse modelo varia dependendo do tipo de serviço em uso no caso IaaS, PaaS ou SaaS. 

-no IaaS o provedor cuida da segurança física dos data centers, servidores, redes e o cliente e responsável por sistemas operacionais,aplicativos,dados ,configurações de rede e segurança e identidade
-no PaaS o provedor de nuvem cuida da infraestrutura,do sistema operacional,ferramentas de desenvolvimento e o cliente e responsável pelos aplicativos,  dados que armazena e as configurações de de rede.
-no SaaS o provedor cuida de tudo,de todo o gerenciamento da plataforma, da infraestrutura até o software e o cliente e responsável por Gerenciar o acesso,os dados e acessos.
----------------------------------------------------------------------------------------------------------------------------------------------------------
as regiões são compostas de um ou mais datacenters que fornecem flexibilidade e escala para reduzir a latência do cliente e preservam a residencia dos dados.
são organizados em regiões geográficas em pares de regiões de no minimo de 300 milhas e cada região é emparelhada com outra região na mesma área g eográfica.Assim garante alta disponibilidade garantindo continuidade de negócios em caso de desastres naturais, falhas de hardware ou interrupções 
Pares de regiões são duas regiões dentro da mesma geografia que são emparelhadas para garantir a continuidade dos negócios e a recuperação em caso de desastres. 
Regiões soberanas são áreas que atendem a requisitos legais e de conformidade, como o Azure Governamental.

Zonas de disponibilidade são locais físicos separados dentro de uma região que são protegidos contra falhas.
Datacenters são instalações físicas que abrigam os servidores e tambem equpamentos de rede.
Recursos são serviços individuais como máquinas virtuais e contas de armazenamento.
Grupos de recursos são contêineres que mantêm recursos relacionados para uma solução do Azure.
Uma assinatura é uma unidade lógica de serviços que está vinculada a uma conta do Azure. 
Grupos de gerenciamento são ferramentas uasdas para organizar e gerenciar assinaturas do Azure permitindo aplicar políticas, permissões e governança de maneira consistente, ou seja simplifica o gerenciamento de recursos em ambientes complexos.
Hierarquia de grupos de recursos, assinaturas e grupos de gerenciamento se referem à organização e estrutura de como os recursos como assinaturas e grupos de gerenciamento são organizados dentro de uma conta do Azure para facilitar a gestão e a governança.
