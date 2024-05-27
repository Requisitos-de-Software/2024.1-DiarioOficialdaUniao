## <a id="introducao">Introdução</a>

O <b>*backlog do produto*</b> em um ambiente **Scrum** é essencialmente uma lista dinâmica que guia a equipe de desenvolvimento ao longo do projeto, contendo todos os itens que precisam ser desenvolvidos para enriquecer o produto. Este artefato inclui funcionalidades, funções, requisitos, aprimoramentos e correções, todos meticulosamente priorizados e estimados para garantir que agreguem valor ao cliente. Importante ressaltar que o backlog é frequentemente reorganizado para refletir as prioridades em mudança e garantir a eficácia do desenvolvimento, evitando a inclusão de tarefas menores, que não contribuem significativamente para os objetivos estratégicos do produto<a id="anchor_1" href="#FRM1">^1^</a>. Neste artefato iremos definir o backlog, tendo como base o <b>*Diário Oficial da União*</b> e suas funcionalidades, iremos definir temas, épicos e executar a validação dos mesmos.


## <a>Metodologia</a>

A partir dos requisitos elicitados durante as [Entrevistas](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/modelagemAgil/entrevista/), procedemos à definição de temas e épicos claros, os quais servem para estruturar e simplificar a compreensão das [Histórias de Usuários](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/modelagemAgil/historiaUsuario/#historias-de-usuario_1). Essas histórias serão prioritariamente avaliadas e refinadas em colaboração com o Product Owner (PO), considerando o mesmo com base no [Perfil do Usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/perfilUsuario/#processo) previamente definido, para serem definidas estratégicamente no nosso <b>*backlog do produto*</b>. Esse processo é fundamental para garantir que as funcionalidades desenvolvidas estejam alinhadas com as expectativas e requisitos dos usuários finais, facilitando assim a entrega de soluções que não apenas atendam, mas superem as necessidades identificadas. 


## <a>Definição dos temas</a>

Após a fase de elicitação dos requisitos, detalhada em nosso documento de requisitos, identificamos vários temas principais nos quais os requisitos podem ser agrupados. Abaixo, detalhamos cada um desses temas, destacando suas características e objetivos principais:

- **Autenticação e Segurança:** Este tema abrange todos os aspectos necessários para garantir a segurança e a integridade do acesso ao sistema. Inclui requisitos como autenticação robusta de usuários, criptografia de dados sensíveis e mecanismos para prevenção de acessos não autorizados. Essencial para proteger informações confidenciais e garantir que apenas usuários legítimos possam acessar o sistema.
- **Interface do Usuário e Acessibilidade:** Focamos na usabilidade e na acessibilidade da interface do usuário, garantindo que o sistema seja intuitivo e acessível para todos, incluindo pessoas com deficiências. Este tema inclui o design responsivo, suporte a tecnologias assistivas e diretrizes para garantir a conformidade com as normas de acessibilidade.
- **Funcionalidades de Conteúdo e Busca:** Este tema trata das funcionalidades relacionadas à organização, busca e visualização de conteúdo dentro do sistema. Inclui ferramentas avançadas de busca, filtros personalizados e maneiras eficientes de navegar e recuperar os dados desejados pelos usuários.
- **Notificações e Interatividade:** Envolvendo a comunicação proativa do sistema com o usuário, este tema aborda como os usuários recebem alertas sobre eventos relevantes ou ações necessárias. Inclui personalização de notificações e interação em tempo real para melhor engajamento do usuário.
- **Gestão e Manutenção do Sistema:** Este tema é dedicado às operações de back-end necessárias para manter o sistema funcionando de forma eficiente e contínua. Abrange desde a manutenção regular até atualizações de sistema e suporte técnico, garantindo alta disponibilidade e desempenho confiável.
- **Funcionalidades Adicionais e Acessórias:** Inclui funcionalidades complementares que enriquecem a experiência do usuário ou fornecem capacidades adicionais ao sistema. Inclui integrações com outros sistemas, suporte multilíngue e expansões modulares que podem ser personalizadas conforme as necessidades do negócio.

## <a>Épicos</a> 

A seguir, a Tabela 1 apresenta os épicos desenvolvidos a partir dos temas identificados. Esta organização facilita a compreensão de como as áreas focais foram delineadas para abordar especificamente as necessidades do sistema em diferentes aspectos.

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Relação dos temas com os épicos</p></font>

<table border="1">
  <tr>
    <th>Tema</th>
    <th>Épicos</th>
  </tr>
  <tr>
    <td rowspan="1">Tema 1: Autenticação e Segurança</td>
    <td><a id="epico01" href="#épico-1-autenticação-segura-e-gestão-de-usuárioso">Épico 1: Autenticação Segura e Gestão de Usuários</a></td>
  </tr>
  <tr>
    <td rowspan="1">Tema 2: Interface do Usuário e Acessibilidade</td>
    <td><a id="epico02" href="#épico-2-acessibilidade-e-usabilidade">Épico 2: Acessibilidade e Usabilidade</a></td>
  </tr>
  <tr>
    <td rowspan="1">Tema 3: Funcionalidades de Conteúdo e Busca</td>
    <td><a id="epico03" href="#épico-3-busca-e-organização-de-conteúdo">Épico 3: Busca e Organização de Conteúdo</a></td>
  </tr>
  <tr>
    <td rowspan="1">Tema 4: Notificações e Interatividade</td>
    <td><a id="epico04" href="#épico-4-interacao-e-notificacao">Épico 4: Interação e Notificação</a></td>
  </tr>
  <tr>
    <td rowspan="1">Tema 5: Gestão e Manutenção do Sistema</td>
    <td><a id="epico05" href="#épico-5-infraestrutura-e-suporte">Épico 5: Infraestrutura e Suporte</a></td>
  </tr>
  <tr>
    <td rowspan="3" style="vertical-align: middle;">Tema 6: Funcionalidades Adicionais e Acessórias</td>
    <td><a id="epico06" href="#épico-6-funcionalidades-avançadas-de-documentos">Épico 6: Funcionalidades Avançadas de Documentos</a></td>
  </tr>
  <tr>
    <td><a id="epico07" href="#épico-7-multilíngue-e-internacionalização">Épico 7: Multilíngue e Internacionalização</a></td>
  </tr>
</table>


<font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

### <a id="épico-1-autenticação-segura-e-gestão-de-usuárioso" href="epico01">Épico 1: Autenticação Segura e Gestão de Usuários</a>

Este épico foca em estabelecer um sistema de autenticação seguro e eficaz. Visa desenvolver mecanismos que verifiquem a identidade dos usuários com precisão, impedindo acessos não autorizados e protegendo informações sensíveis através de políticas robustas de segurança.

A tabela 2 apresenta os requisitos funcionais e não funcionais que foram identificados e categorizados sob o épico "Autenticação Segura e Gestão de Usuários".

<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Requisitos identificados para o épico: Autenticação Segura e Gestão de Usuários</p></font>

<center>

| Tipo | Descrição|
|------|----------|
|RNF01| Autenticação de usuários para acesso seguro.|
|RF09|	Melhoria na interação entre usuários.|

</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

### <a id="épico-2-acessibilidade-e-usabilidade">Épico 2: Acessibilidade e Usabilidade</a>
Dentro deste épico, trabalhamos para garantir que o sistema seja acessível e fácil de usar para todos os usuários, independentemente de suas habilidades físicas ou tecnológicas. Isso inclui a implementação de recursos de acessibilidade como a otimização da interface do usuário para facilitar a navegação e a interação.

A tabela 3 apresenta os requisitos funcionais que foram identificados e categorizados sob o épico "Acessibilidade e Usabilidade".

<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Requisitos identificados para o épico: Acessibilidade e Usabilidade</p></font>

<center>

| Tipo | Descrição|
|------|----------|
|RF02|Funcionalidades de acessibilidade.|
|RF03|Ferramentas de usabilidade aprimoradas.|
|RF07|Interface do usuário altamente intuitiva.|

</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

### <a id="épico-3-busca-e-organização-de-conteúdo">Épico 3: Busca e Organização de Conteúdo</a>
O foco aqui é em aprimorar as funcionalidades de busca e organização de conteúdo, permitindo aos usuários encontrar rapidamente o que precisam. Esse épico envolve o desenvolvimento de filtros avançados, capacidades de pesquisa poderosas e interfaces intuitivas para a gestão eficiente de dados e informações.

A tabela 4 apresenta os requisitos funcionais que foram identificados e categorizados sob o épico "Busca e Organização de Conteúdo".

<font size="3"><p style="text-align: center"><b>Tabela 4</b> - Requisitos identificados para o épico: Busca e Organização de Conteúdo</p></font>

<center>

| Tipo | Descrição|
|------|----------|
|RF01|Sistema de busca avançada.|
|RF04|Otimização do processo de busca diária.|

</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

### <a id="épico-4-interacao-e-notificacao">Épico 4: Interação e Notificação</a>
Este épico foca em como o sistema pode melhorar a interação e a notificação para os usuários. Inclui o desenvolvimento de sistemas de notificação personalizados e interfaces interativas que mantêm os usuários bem informados e ativamente envolvidos. Essas funcionalidades garantem que os usuários recebam atualizações relevantes.

A tabela 5 apresenta os requisitos funcionais que foram identificados e categorizados sob o épico "Interação e Notificação".

<font size="3"><p style="text-align: center"><b>Tabela 5</b> - Requisitos identificados para o épico: Interação e Notificação</p></font>

<center>

| Tipo | Descrição|
|------|----------|
|RF05|Suporte multilíngue no sistema.|
|RF09|Melhoria na interação entre usuários.|

</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

### <a id="épico-5-infraestrutura-e-suporte">Épico 5: Infraestrutura e Suporte</a>
Foca em garantir que o sistema seja confiável e esteja sempre disponível quando necessário. Abrange a implementação de uma infraestrutura robusta que suporta operações contínuas e eficientes, bem como a disponibilização de suporte técnico para resolver quaisquer problemas que os usuários possam enfrentar.

A tabela 6 apresenta os requisitos funcionais e não funcionais que foram identificados e categorizados sob o épico "Infraestrutura e Suporte".

<font size="3"><p style="text-align: center"><b>Tabela 6</b> - Requisitos identificados para o épico: Infraestrutura e Suporte</p></font>

<center>

| Tipo | Descrição|
|------|----------|
|RF02|Funcionalidades de acessibilidade.|
|RF05|Suporte multilíngue no sistema.|
|RNF02|Requisitos para suporte e manutenção|

</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

### <a id="épico-6-funcionalidades-avançadas-de-documentos">Épico 6: Funcionalidades Avançadas de Documentos</a>
Este épico visa expandir as capacidades do sistema em relação à gestão de documentos, incluindo funcionalidades como edição avançada, compartilhamento seguro e rastreamento de modificações em documentos importantes.

A tabela 7 apresenta os requisitos funcionais que foram identificados e categorizados sob o épico "Funcionalidades Avançadas de Documentos".

<font size="3"><p style="text-align: center"><b>Tabela 7</b> - Requisitos identificados para o épico: Funcionalidades Avançadas de Documentos</p></font>

<center>

| Tipo | Descrição|
|------|----------|
|RF01|Sistema de busca avançada.|
|RF05|Suporte multilíngue no sistema.|
|RF08|Funcionalidades avançadas de documentos.|

</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

### <a id="épico-7-multilíngue-e-internacionalização">Épico 7: Multilíngue e Internacionalização</a>
Aqui, o objetivo é desenvolver um sistema que suporte múltiplos idiomas e culturas, facilitando o uso por usuários globais. Isso inclui a tradução de interfaces, adaptação de conteúdos e consideração de nuances culturais que influenciam a interação do usuário com o sistema.

A tabela 8 apresenta os requisitos funcionais que foram identificados e categorizados sob o épico "Multilíngue e Internacionalização".

<font size="3"><p style="text-align: center"><b>Tabela 8</b> - Requisitos identificados para o épico: Multilíngue e Internacionalização</p></font>

<center>

| Tipo | Descrição|
|------|----------|
|RF02|Funcionalidades de acessibilidade.|
|RF05|Suporte multilíngue no sistema.|

</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>


## <a>Backlog</a>
O <b>*backlog do produto*</b>, como já citado na <a href="#introducao">Introdução</a> é uma lista organizada de tudo o que é necessário no projeto, incluindo todas as funcionalidades, requisitos técnicos, melhorias e correções que são prioritárias para a equipe<a id="anchor_1" href="#FRM1">^1^</a>.

Cada item do backlog é uma história de usuário que representa uma necessidade específica dos usuários finais, agrupada sob temas relevantes e classificada em épicos para uma melhor clareza. Estas histórias estão priorizadas para garantir que o trabalho mais importante seja realizado primeiro. Confira na Tabela 9 o backlog.

<font size="3"><p style="text-align: center"><b>Tabela 9</b> - Backlog de histórias de usuário</p></font>

| **ID**|**Tema**|**Épico**|**Prioridade (Three Level)**|
|-------|--------|---------|----------------------------|
| US01 | Funcionalidades de Conteúdo e Busca       | Busca e Organização de Conteúdo        | |
| US02 | Interface do Usuário e Acessibilidade     | Acessibilidade e Usabilidade           | |
| US03 | Interface do Usuário e Acessibilidade     | Acessibilidade e Usabilidade           | |
| US04 | Funcionalidades de Conteúdo e Busca       | Busca e Organização de Conteúdo        | |
| US05 | Funcionalidades de Conteúdo e Busca       | Busca e Organização de Conteúdo        | |
| US06 | Funcionalidades Adicionais e Acessórias   | Multilíngue e Internacionalização      | |
| US07 | Funcionalidades de Conteúdo e Busca       | Busca e Organização de Conteúdo        | |
| US08 | Funcionalidades Adicionais e Acessórias   | Multilíngue e Internacionalização      | |
| US09 | Notificações e Interatividade             | Interação e Notificação              | |
| US10 | Funcionalidades de Conteúdo e Busca       | Busca e Organização de Conteúdo        | |
| US11 | Notificações e Interatividade             | Interação e Notificação              | |
| US12 | Funcionalidades de Conteúdo e Busca       | Busca e Organização de Conteúdo        | |
| US13 | Autenticação e Segurança                  | Autenticação Segura e Gestão de Usuários | |
| US14 | Interface do Usuário e Acessibilidade     | Acessibilidade e Usabilidade           | |
| US15 | Funcionalidades de Conteúdo e Busca       | Busca e Organização de Conteúdo        | |
| US16 | Gestão e Manutenção do Sistema            | Infraestrutura e Suporte               | |
| US17 | Interface do Usuário e Acessibilidade     | Acessibilidade e Usabilidade           | |
| US18 | Funcionalidades Adicionais e Acessórias   | Funcionalidades Avançadas de Documentos | |
| US19 | Interface do Usuário e Acessibilidade     | Acessibilidade e Usabilidade ||
| US20 | Notificações e Interatividade | Interação e Notificação ||
| US21 | Funcionalidades Adicionais e Acessórias | Funcionalidades Avançadas de Documentos ||
| US22 | Funcionalidades Adicionais e Acessórias | Funcionalidades Avançadas de Documentos ||

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

## <a> Reunião para elicitação dos requisitos</a>

No dia 24 de maio de 2024, às 16h30, foi realizada uma reunião presencial, na FGA, entre três membros da equipe e o Product Owner(PO) Júlio, estudante pesquisador. Durante a reunião, eles discutiram e elecitaram os requisitos do projeto atráves da técnica de entrevista. Isso garantiu um alinhamento estratégico e eficiente para as próximas etapas do projeto. A ata da reunião de elicitação está disponível em [Link da ata](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoPriorizacao/#5-encaminhamentos). A tabela 10 apresenta os participantes da reunião.

<font size="3"><p style="text-align: center">Tabela 3: Participantes.</p></font>

<center>

| Nome                                             | Função                   |
| ------------------------------------------------ | ------------------------ |
|[Arthur Alves](https://github.com/arthrok)| Entrevistador              |
|[Eric Silveira](https://github.com/ericbky)| Entrevistador              |
|[João Artur](https://github.com/joao-artl) | Entrevistador              |
| Júlio | Product Owner |

</center>

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>

## <a> Gravação da validação das Histórias de Usuários</a>

link

## <a>Referência Bibliográfica</a>

> <a id="FRM1" href="#anchor_1">1.</a> O que é backlog do produto Scrum e como fazer um. Lucid Software Inc. 2024.  Disponível em: <https://www.lucidchart.com/blog/pt/como-fazer-um-backlog-do-produto>

## <a>Bibliografia</a>

> O que é backlog do produto Scrum e como fazer um. Lucid Software Inc. 2024.  Disponível em: <https://www.lucidchart.com/blog/pt/como-fazer-um-backlog-do-produto>

> SERRANO, Milene. SERRANO, Mauricio. Requisitos – Aula 15.

## Histórico de versão
|Versão|Data|Data Prevista de Revisão|Descrição|Autor|Revisor|
| :------: | :----------: |:-----------: | :----------------------: | :---------: |:---------: |
| `1.0` | 24/05/2024 | 25/05/2024 |Criação da Documentação do Backlog | [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky) | Diego Sousa, Douglas Marinho, Henrique Torres, João Artur e Luiz Gustavo |
| `1.1` | 27/05/2024 | 27/05/2024 | Adicionando gravação da reunião| [João Artur](https://github.com/joao-artl) | [Diego Sousa](https://github.com/DiegoSousaLeite)|