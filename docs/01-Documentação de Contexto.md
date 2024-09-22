# Documentação de Contexto

## Introdução

As pequenas organizações enfrentam frequentemente desafios na implementação e manutenção de soluções tecnológicas devido aos limitados recursos internos especializados. Ao mesmo tempo, os profissionais de TI autônomos que possuem as habilidades necessárias para atender a essas necessidades estão lutando para se conectar com essas organizações. O projeto **Freelanet** pretende desenvolver uma plataforma que facilite esta ligação, oferecendo uma solução prática para ambas as partes, permitindo às empresas atenderem aos serviços de TI de forma eficiente e aos freelancers chegarem aos seus clientes de forma mais eficaz.

## Problema

As organizações que não possuem serviços de TI robustos lutam para manter a sua infraestrutura tecnológica adequada à sua finalidade. A falta de profissionais dedicados acarreta atrasos na resolução de problemas e implementação de novas soluções, o que pode comprometer a competitividade e a eficiência operacional. Em contraste, os freelancers tecnológicos que possuem as competências necessárias para satisfazer estas exigências enfrentam desafios na promoção dos seus serviços e na procura de oportunidades adequadas. A falta de uma plataforma eficaz para conectar estas duas partes dificulta a oferta de serviços adaptados às necessidades tecnológicas da organização e a introdução de freelancers no mercado.

## Objetivos

O projeto **Freelanet** pretende desenvolver uma plataforma que facilite a conexão entre pequenas organizações que enfrentam desafios na implementação e manutenção de soluções tecnológicas com freelancers de TI, permitindo que ambas as partes atinjam seus objetivos de forma eficiente.

## Justificativa

O projeto é relevante pois resolve um problema comum enfrentado tanto por empresas quanto por freelancers de TI. Para as empresas, especialmente as de pequeno e médio porte, facilita o acesso a soluções tecnológicas de qualidade sem a necessidade de contratar um profissional interno. Para os freelancers, oferece uma plataforma específica para promover seus serviços e conectar-se diretamente com potenciais clientes. Para profissionais iniciantes, abre oportunidades para ganhar experiência e construir uma base de clientes.

Foram feitas duas entrevistas como estudo de caso:

### Entrevista 1

Após uma entrevista com Alex, responsável pela TI de uma empresa de demolição, ele destacou um desafio significativo: a contratação de um link dedicado para internet, seguida pela necessidade de implementar uma infraestrutura de rede interna completa, incluindo um firewall. A dificuldade em encontrar um profissional qualificado para essa configuração resultou em uma contratação mais cara de uma empresa especializada. Isso evidenciou a demanda por profissionais específicos dentro da área de TI, algo que a **Freelanet** poderia resolver.

### Entrevista 2

Matheus trabalhava em uma empresa de comércio digital com uma equipe limitada de TI. Ele enfrentava dificuldades em resolver problemas técnicos devido à falta de conhecimento específico e profissionais especializados. A **Freelanet** poderia acelerar a conexão com freelancers especializados, permitindo uma resolução mais rápida e eficiente de problemas.

## Público-alvo

A plataforma **Freelanet** tem três grupos principais como público-alvo:

### Empresas

Pequenas e médias empresas que enfrentam dificuldades para implementar e manter soluções tecnológicas. Características e necessidades incluem:

- Recursos limitados.
- Urgência na solução de problemas.
- Falta de conhecimento técnico interno.
- Preferência por soluções localizadas e personalizadas.

### Freelancers de TI

Profissionais independentes que oferecem serviços personalizados de TI, buscando:

- Maior visibilidade para seus serviços.
- Conexões diretas com clientes.
- Oportunidades de trabalho flexíveis e curtas.
- Avaliações positivas para garantir fluxo de trabalho.

### Profissionais Iniciantes

Profissionais recém-formados que buscam ganhar experiência e construir um portfólio, enfrentando:

- Falta de visibilidade e rede de contatos.
- Necessidade de experiência prática.
- Busca por projetos de baixa complexidade e mentoria.

## Especificação do Projeto

### Perfis de Usuários

| Perfil                | Descrição                                                        | Necessidades                                                                 |
|-----------------------|------------------------------------------------------------------|------------------------------------------------------------------------------|
| Empresas              | Empresas de pequeno e médio porte que necessitam de serviços de TI | Rápida resolução de problemas técnicos, acesso a especialistas qualificados  |
| Freelancers de TI      | Profissionais independentes de TI com habilidades diversas       | Plataforma para promover seus serviços, conexão direta com clientes          |
| Profissionais Iniciantes | Recém-formados que buscam ganhar experiência                     | Visibilidade, oportunidades de construir um portfólio                        |

### Histórias de Usuários

- **Freelancer de TI**: Quero criar um perfil detalhado e listar meus serviços para atrair clientes com necessidades específicas.
- **Empresa**: Desejo filtrar e encontrar rapidamente freelancers qualificados para resolver meus problemas técnicos de maneira eficiente.
- **Profissional Iniciante**: Quero oportunidades para ganhar experiência e construir meu portfólio.

## Requisitos do Projeto

### Requisitos Funcionais

| ID     | Descrição                                                     | Prioridade |
|--------|---------------------------------------------------------------|------------|
| RF-01  | A plataforma deve permitir que empresas postem solicitações de serviço detalhadas. | Alta       |
| RF-02  | A plataforma deve permitir que freelancers criem perfis e listem serviços oferecidos. | Alta       |
| RF-03  | A plataforma deve incluir um sistema de avaliação e feedback.  | Alta       |

### Requisitos Não Funcionais

| ID      | Descrição                                                      | Prioridade |
|---------|----------------------------------------------------------------|------------|
| RNF-01  | A plataforma deve ser acessível em diferentes dispositivos (responsividade). | Baixa      |
| RNF-02  | A plataforma deve garantir a segurança dos dados dos usuários. | Alta       |
