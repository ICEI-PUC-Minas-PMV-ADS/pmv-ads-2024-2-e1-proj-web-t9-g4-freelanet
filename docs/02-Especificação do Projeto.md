# Especificações do Projeto

## Perfis de Usuários

<table>
<tbody>
<tr>
<th colspan="2">Perfil 1: Empresas </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">
Empresas de pequeno e médio porte que necessitam de serviços de TI. 
</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
1. Rápida resolução de problemas técnicos;
2. Acesso a especialistas qualificados;
3. Serviços de TI sem necessidade de contratação de um profissional interno;
 
</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr>
<th colspan="2">Perfil 2: Freelancers de TI </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">
Profissionais independentes de TI com habilidades técnicas diversificadas.
</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
1. Plataforma eficaz para promover seus serviços;
2. Conexão direta com clientes com necessidades específicas;
3. Oportunidades de trabalho flexíveis.

</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr>
<th colspan="2">Perfil 3: Profissionais Iniciantes </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">
Recém-formados ou profissionais de TI que buscam ganhar experiência.
</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
1. Visibilidade para suas habilidades;
2. Oportunidades para construir um portfólio;
3. Entrada facilitada no mercado de TI.

</td>
</tr>
</tbody>
</table>


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`                                             |PARA ... `MOTIVO/VALOR`                 |
|--------------------|--------------------------------------------------------------------------------|----------------------------------------|
|Freelancer de TI | Criar um perfil detalhado e listar meus serviços   | Atrair clientes com necessidades específicas. |
|Empresa | Filtrar e encontrar rapidamente freelancers qualificados  | Resolver meus problemas técnicos de maneira eficiente.  |
|Profissional Iniciante|Oportunidades para ganhar experiência  | Construir meu portifólio  |

## Requisitos

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-01| O sistema deve permitir que os Freelancers podem adicionar suas habilidades, experiência, e um portfólio de trabalhos realizados. Empresas poderão detalhar seus projetos e necessidades de TI.   | ALTA | 
|RF-02| O sistema deve permitir que os Freelancers apresentem seu portifólio diretamente em seus perfis, fazendo com que as empresas visualizem os perfis completos incluindo projetos anteriores e avaliações.   | ALTA | 
|RF-03| O sistema deve permitir que as empresas façam buscas por freelancers com base em habilidades específicas, localização, avaliações, experiência e também a utilização de filtros avançados para algum serviço mais específico.    | ALTA |
|RF-04| O sistema deve permitir que os freelancers e iniciantes busquem oportunidades de trabalho publicadas pelas empresas, utilizando filtros como tipo de projeto, prazo e orçamento.    | ALTA |
|RF-05| O sistema deve permitir que as empresas possam publicar suas demandas de TI, detalhando as necessidades do projeto (como desenvolvimento de software, manutenção de redes), prazos e orçamentos.  | ALTA |
|RF-06| O sistema deve permitir que os freelancers podem se candidatar às oportunidades publicadas pelas empresas e com isso, as empresas devem receber, revisar e selecioncar caso desejem, as candidaturas com base em suas habilidades.    | ALTA |
|RF-07| O sistema deve permitir que após a conclusão de um trabalho, as empresas devem avaliar os freelancers, fornecendo notas e feedback textual. As avaliações ficarão visíveis no perfil do freelancer    | MÉDIA |
|RF-08| O sistema deve permitir que os freelancers também possam avaliar as empresas com as quais trabalharam, fornecendo feedback sobre a clareza das demandas e a comunicação.   | MÉDIA |
|RF-09| O sistema deve deve notificar os usuários sobre eventos, como novas oportunidades publicadas, candidaturas recebidas, avaliações de projetos. As notificações serão exibidas dentro da plataforma e enviadas por email.  | BAIXA |
|RF-10| O sistema deve permitir que empresas e freelancers se comuniquem por mensagens internas, discutindo os detalhes do projeto antes ou durante sua execução.  | MÉDIA |

**Prioridade: Alta / Média / Baixa.  

### Requisitos Não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-01| A aplicação deve ser publicada em um ambiente acessível público na Internet.  | ALTA | 
|RNF-02| A aplicação deverá ser responsiva permitindo a visualização em dispositivos diversos de forma adequada.  | ALTA | 
|RNF-03| A aplicação deve ter bom nível de contraste entre os elementos da tela.  | MÉDIA | 
|RNF-04| A aplicação deve ser compatível com os navegadores O site deve ser compatível com os principais navegadores do mercado: Google Chrome, Opera, Firefox e Microsoft Edge.  | ALTA | 
|RNF-05| A plataforma deve garantir a segurança dos dados dos usuários  | ALTA | 


**Prioridade: Alta / Média / Baixa.
