## <a>Introdução</a>

A verificação é uma abordagem metódica para avaliar e garantir a qualidade de um produto de software, assegurando que ele atenda às especificações e requisitos elicitados<a id="anchor_1" href="#REF1">^1^</a>.

Neste artefato, planejaremos o processo de <b>*verificação dos artefatos*</b> desenvolvidos pelo <a href="https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/">*Grupo 02*</a> para o aplicativo <b>*Carteira de Trabalho Digital*</b>. O objetivo é garantir que todos os componentes desenvolvidos estejam em conformidade com os requisitos estabelecidos. Isso assegura que a plataforma ofereça uma experiência robusta e alinhada às expectativas dos usuários finais. É importante citar que essa verificação em momento nenhum busca diminuir os membros do Grupo 2 ou seu trabalho, apenas aplicar os conceitos de verificação nos artefatos.


## <a>Metodologia</a>

A metodologia que utilizaremos será a de inspeção, que é aplicada para a verificação de documentos, pois seu objetivo principal é a descoberta de "defeitos" nos mesmo<a id="anchor_2" href="#REF2">^2^</a>. Será utilizado uma espécie de checklist, parte da análise estática, onde não há execução do produto<a id="anchor_1" href="#REF1">^1^</a>. Avaliaremos cada entrega com base nos artefatos desenvolvidos, utilizando checklists detalhados para garantir que todos os aspectos do projeto estejam cobertos. Isso nos permitirá verificar se todos os itens estão definidos e completos, e se não há ausência de dados ou especificações importantes.

Para estruturar a verificação, será utilizada uma checklist. Inicialmente, serão criadas tabelas contendo o ID e a respectiva pergunta a ser feita para verificar se cada item está implementado no artefato. Além disso, cada pergunta tem uma fonte (quando possível) que indica as referências bibliográficas que fundamentaram sua formulação, proporcionando uma base sólida para que o Grupo 02, no caso de haver correções a serem feitas, possam consultar as fontes.

Essa abordagem sistemática nos ajudará a identificar lacunas ou inconsistências nos artefatos, assegurando que todos os requisitos sejam atendidos de maneira completa e precisa. O uso de checklists proporciona uma maneira estruturada e repetível de conduzir a verificação, facilitando a detecção de problemas e garantindo que as entregas estejam alinhadas com as expectativas e padrões de qualidade definidos. Ao final de cada avaliação, compilaremos os resultados e destacaremos as correções necessárias para manter a integridade e a qualidade do projeto.


## <a> Características da Verificação dos Artefatos </a>

A Tabela 1 apresenta os artefatos da etapa 04, suas respectivas versões e os responsáveis pelo desenvolvimento. Esses itens serão avaliados pelo encarregado da verificação. O responsável pela execução da verificação da entrega 04 será o integrante do <b>*Grupo 01*</b> - [Arthur Alves](https://github.com/Arthrok).

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Caracteristicas das Verificações dos Artefatos da Entrega 04.</p></font>
<center>

| **Nome do Artefato** | **Versão Pré-Verificação** | **Responsável pelo Desenvolvimento do Artefato** | **Responsável pela Verificação do Artefato** | **Resultado da Verificação** |
| --------- | --------- | ----------- | ------------------ | ---------------------- |
| [Backlog](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/modelagemAgil/backlog){:target="_blank"} | `1.2` | Bruno, Caio e Larissa  | [Arthur Alves](https://github.com/Arthrok) | Verificação do Backlog |
| [História de Usuário](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/modelagemAgil/historiaUsuario){:target="_blank"} | `1.8` | Breno, Bruno, Caio, Larissa e Luana | [Arthur Alves](https://github.com/Arthrok) | Verificação da História de Usuário |
| [NFR Framework](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/modelagemAgil/NFR){:target="_blank"} | `1.8` | Breno, Larissa, Luana e Pedro | [Arthur Alves](https://github.com/Arthrok) | Verificação do NFR Framework |


</center>
<font size="3"><p style="text-align: center"><b>Fonte: </b> [Arthur Alves](https://github.com/Arthrok).</p></font>


### <a> Backlog </a>

<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Checklist para Backlog.</p></font>

| **ID** | **Descrição** | **Avaliação** | **Observações** | **Explicação e Referência** |
| ---- | ----------- | ----------- | ------------- | ------------- |
| 1 | O backlog está devidamente priorizado, com os itens mais importantes no topo? | | | Os itens mais importantes estão no topo para guiar o foco da equipe<a id="anchor_3" href="#REF3">^3^</a>. |
| 2 | O backlog está acessível e visível para todas as partes interessadas? | | | Manter o backlog em documentos isolados impede atualizações e visibilidade<a id="anchor_3" href="#REF3">^3^</a>. |
| 3 | Há justificativas claras para a priorização dos itens do backlog? | | | Priorização: os itens são ordenados por importância, com base na prioridade do cliente, urgência do feedback e dificuldade de implementação<a id="anchor_3" href="#REF3">^3^</a>. |
| 4 | As histórias de usuário estão inclusas no backlog? | | | Incluir todos os tipos de itens de trabalho (por exemplo, histórias de usuário, bugs, dívida técnica) para garantir um planejamento abrangente<a id="anchor_3" href="#REF3">^3^</a>. |
| 5 | O backlog foi priorizado com o cliente, PO ou persona? | | | A gestão eficaz do backlog envolve uma revisão regular e priorização com base no feedback de stakeholders, clientes e membros da equipe<a id="anchor_3" href="#REF3">^3^</a>. |
| 6 | Os temas e os épicos foram descritos? | | | N/A |
| 7 | Os temas estão em um grau de hierarquia maior e mais amplo que os épicos? | | | Da mesma forma que as epopéias são feitas de histórias, os temas são feitos de épicos. Os temas oferecem outro nível de organização acima dos épicos. Em muitos casos, um tema compila épicos de diversas equipes para atingir um objetivo muito mais amplo e maior do que qualquer um dos próprios épicos<a id="anchor_4" href="#REF4">^4^</a>. |
| 8 | Os temas e épicos estão alinhados com os objetivos estratégicos do projeto? | | | Eles representam objetivos de alto nível que a organização espera alcançar<a id="anchor_4" href="#REF4">^4^</a>. |
| 9 | Os épicos estão em um grau de hierarquia maior que as histórias de usuário? (Os épicos não devem ter uma narrativa simples) | | | Uma história é uma narrativa simples; uma série de histórias relacionadas e interdependentes constitui um épico. O mesmo se aplica à gestão do seu trabalho, onde a conclusão de histórias relacionadas leva à conclusão de um épico<a id="anchor_4" href="#REF4">^4^</a>. |
| 10 | Os épicos foram divididos em histórias menores para facilitar o gerenciamento e a execução? | | | Dividir um épico em histórias mais práticas ajuda a entender um projeto e a manter o impulso<a id="anchor_5" href="#REF5">^5^</a>. |

<font size="3"><p style="text-align: center"><b>Fonte: </b> [Arthur Alves](https://github.com/Arthrok).</p></font>


### <a> História de Usuário </a>

<font size="3"><p style="text-align: center"><b>Tabela 4</b> - Checklist para História de Usuário.</p></font>


| **ID** | **Descrição** | **Avaliação** | **Observações** | **Explicação e Referência** |
| ---- | ----------- | ----------- | ------------- | ------------- |
| 10 | As histórias de usuário estão escritas do ponto de vista do usuário final? | | | Uma história de usuário é uma explicação geral e informal de um recurso de software escrita do ponto de vista do usuário final<a id="anchor_6" href="#REF6">^6^</a>. |
| 11 | As histórias de usuário articulam como uma funcionalidade de software fornecerá valor ao cliente? | | | O objetivo de uma história de usuário é articular como uma peça de trabalho fornecerá um valor particular ao cliente<a id="anchor_6" href="#REF6">^6^</a>. |
| 12 | As histórias de usuário estão descritas em linguagem simples e sem detalhes técnicos? | | | As histórias de usuário são algumas frases em linguagem simples que descrevem o resultado desejado<a id="anchor_6" href="#REF6">^6^</a>. |
| 13 | As histórias de usuário são usadas para facilitar a colaboração e a criatividade da equipe? | | | As histórias ajudam a fornecer uma estrutura focada no usuário para o trabalho diário, o que impulsiona a colaboração, a criatividade e um produto melhor em geral<a id="anchor_6" href="#REF6">^6^</a>. |
| 14 | As histórias de usuário são acompanhadas por critérios de aceitação claros? | | | As histórias de usuário devem ter critérios de aceitação claramente definidos<a id="anchor_6" href="#REF6">^6^</a>. |
| 12 | O “quem”, “o que” e o “por que” estão definidos na história de usuário? | | | Cada história de usuário inclui uma persona (quem), o que ela quer e por quê<a id="anchor_6" href="#REF6">^6^</a>. |
| 13 | A participação do cliente e/ou persona na validação das histórias de usuário? | | | As histórias ajudam a fornecer uma estrutura focada no usuário para o trabalho diário, o que impulsiona a colaboração, a criatividade e um produto melhor em geral. Geralmente, uma história é escrita pelo proprietário do produto, gerente de produto ou gerente de programa e enviada para revisão<a id="anchor_6" href="#REF6">^6^</a>. |
| 13 | As histórias de usuário seguem algum modelo ou padrão? | | | N/A (Apenas para controle de organização) |
| 13 | Todos os membros do grupo contribuiram com o artefato? | | | N/A (Apenas para controle de organização) |

<font size="3"><p style="text-align: center"><b>Fonte: </b> [Arthur Alves](https://github.com/Arthrok).</p></font>


## <a> Referência Bibliografica </a>

> <a id="REF1" href="#anchor_1">1. </a>Gerência e Qualidade de Software - Aula 05 - Verificação e Validação. UNIVESP. Disponível em: <https://www.youtube.com/watch?v=1Y-1zz6rZxo&t=205s>. Acesso em: 07 de junho de 2024 às 21:00.

> <a id="REF2" href="#anchor_2">2. </a>SERRANO, Milene. SERRANO, Maurício. Apresentação: Requisitos - Aula 23. Página 19.

> <a id="REF3" href="#anchor_3">3. </a>RADIGAN, Dan. Product Backlog Explained [+ Examples]. Atlassian, 2023. Disponível em: https://www.atlassian.com/agile/scrum/backlogs. Acesso em: 9 jun. 2024.

> <a id="REF4" href="#anchor_4">4. </a>REHKOPF, Max. Epics, Stories, Themes. Atlassian, 2023. Disponível em: https://www.atlassian.com/agile/project-management/epics-stories-themes. Acesso em: 9 jun. 2024.

> <a id="REF5" href="#anchor_5">5. </a>REHKOPF, Max. Epics. Atlassian, 2023. Disponível em: https://www.atlassian.com/agile/project-management/epics. Acesso em: 9 jun. 2024.

> <a id="REF6" href="#anchor_6">6s. </a>REHKOPF, Max. User Stories. Atlassian, 2023. Disponível em: https://www.atlassian.com/agile/project-management/user-stories. Acesso em: 9 jun. 2024. 


## <a> Bibliografia </a>

> <a>1. </a>Gerência e Qualidade de Software - Aula 05 - Verificação e Validação. UNIVESP. Disponível em: <https://www.youtube.com/watch?v=1Y-1zz6rZxo&t=205s>. Acesso em: 07 de junho de 2024 às 20:00.

> <a>2. </a>SERRANO, Milene. SERRANO, Maurício. Apresentação: Requisitos - Aula 23.


## <a>Histórico de Versão</a>

| Versão| Data | Data Prevista de Revisão| Descrição  | Autor(es)  | Revisor(es) |
| ------- | ------ | ------ | ------- | -------- | -------- |
| `1.0` | 09/06/2024 | 10/06/2024 | Criação do documento | [Arthur Alves](https://github.com/Arthrok) | [Eric Silveira](https://github.com/ericbky) e [João Artur](https://github.com/joao-artl)|