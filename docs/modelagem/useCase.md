# Casos de Uso

## <a>Introdução</a>

O diagrama de casos de uso é uma representação visual que descreve as interações entre um sistema e seus usuários externos, destacando as principais funcionalidades do sistema e como os usuários as utilizam.

## <a>Metodologia</a>

Para criar este artefato, seguimos a abordagem tradicional de representação dos casos de uso por meio de diagramas UML. Utilizamos o LucidChart, uma ferramenta online para criação de diagramas, como nossa plataforma de escolha.

## <a>Componentes e Símbolos</a>

Um diagrama de casos de uso é composto pelos seguintes elementos:

### <a>Atores</a>

Os atores representam os usuários e sistemas envolvidos nas interações com o sistema. Eles são comumente representados por ícones de bonecos de palitos.

<font size="3"><p style="text-align: center"><b>Figura 1:</b> Ator</p></font>
<p align="center">
  <img src="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/main/docs/modelagem/images/ator-uml.png?raw=true" alt="Ator" />
</p>
<font size="3"><p style="text-align: center">Fonte: [Douglas Marinho](https://github.com/M4RINH0).</p></font>

### <a>Cenário</a>

O cenário é a sequência de eventos que ocorre quando um usuário interage com o sistema. É representado por uma caixa que delimita as atividades dentro do escopo do sistema.

<font size="3"><p style="text-align: center"><b>Figura 2:</b> Cenário</p></font>
<p align="center">
  <img src="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/main/docs/modelagem/images/container-uml.png?raw=true" alt="Cenário" />
</p>
<font size="3"><p style="text-align: center">Fonte: [Douglas Marinho](https://github.com/M4RINH0).</p></font>

### <a>Caso de Uso</a>

Um caso de uso descreve uma funcionalidade ou atividade realizada pelo usuário. É representado por uma forma oval horizontal e deve ser descrito com verbos no infinitivo.

<font size="3"><p style="text-align: center"><b>Figura 3:</b> Caso de uso</p></font>

<p align="center">
  <img src="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/main/docs/modelagem/images/usecase-uml.png?raw=true" alt="Casos de Uso" />
</p>
<font size="3"><p style="text-align: center">Fonte: [Douglas Marinho](https://github.com/M4RINH0).</p></font>

### <a>Comunicação (ou Ação)</a>

As comunicações representam as ações que conectam os usuários aos casos de uso. Elas podem ser de dois tipos:

- **Inclusão:** Indica que um caso de uso depende da execução de outro caso de uso.
  
  - Notação no diagrama: *<<includes\>\>*
  
- **Extensão:** Indica que um caso de uso pode ser estendido por outro, adicionando novos passos ou funcionalidades.
  
  - Notação no diagrama: *<<extends\>\>*

<font size="3"><p style="text-align: center"><b>Figura 4:</b> Comunicação</p></font>
<p align="center">
  <img src="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/main/docs/modelagem/images/action-uml.png?raw=true" alt="Comunicação" />
</p>
<font size="3"><p style="text-align: center">Fonte: [Douglas Marinho](https://github.com/M4RINH0).</p></font>


## <a>Diagrama de Casos de Uso</a>

<font size="3"><p style="text-align: center"><b>Figura 5:</b> Diagrama de casos de uso.</p></font>

<img src="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/main/docs/modelagem/images/diagrama-UseCase.png?raw=true" alt="Diagrama UML" />

<font size="3"><p style="text-align: center">Fonte: [Douglas Marinho](https://github.com/M4RINH0).</p></font>


Seguem abaixo, a especificação dos casos de uso que foram identificados.

### UC01. Consultar Documentos Legislativos

<font size="3"><p style="text-align: center">Tabela 1: Especificação do caso de uso - Consultar Documentos Legislativos.</p></font>

| UC01 | Consultar Documentos Legislativos |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Requisitos** | Conexão com a internet |
| **Condição de entrada** | O usuário acessa a aplicação e seleciona a opção de consulta de documentos legislativos |
| **Fluxo principal** | <ol> <li> O sistema apresenta a interface de busca de documentos legislativos <li> O usuário insere os critérios de busca <li> O sistema busca e exibe os documentos legislativos que correspondem aos critérios inseridos </ol>|
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | **Conexão com a internet perdida** <ol> <li> O sistema detecta a perda de conexão <li> O sistema apresenta uma mensagem de erro "Falha na conexão. Tentar novamente?" e opções "Sim" e "Retornar à tela inicial" <ul> <li> O usuário seleciona "Sim" e o sistema tenta reconectar <li> O usuário seleciona "Retornar à tela inicial" e a operação é cancelada </ul> </ol> |
| **Pós-condições** | O usuário visualiza os documentos legislativos de acordo com os critérios de busca inseridos |
| **Rastreabilidade** | [IS01](../elicitacao/tecnicas/introspeccao.md#funcionais) [IS04](../elicitacao/tecnicas/introspeccao.md#funcionais) [OBS03](../elicitacao/tecnicas/observacao.md#requisitos-funcionais) |

<font size="3"><p style="text-align: center">Fonte: [Henrique Torres](https://github.com/henriqtorresl).</p></font>

### UC02. Salvar Documentos para Consulta Offline

<font size="3"><p style="text-align: center">Tabela 2: Especificação do caso de uso - Salvar Documentos para Consulta Offline.</p></font>

| UC02 | Salvar Documentos para Consulta Offline |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Média |
| **Requisitos** | Conexão com a internet (para salvar) |
| **Condição de entrada** | O usuário acessa a aplicação e seleciona um documento legislativo para salvar |
| **Fluxo principal** | <ol> <li> O sistema exibe o documento legislativo selecionado <li> O usuário seleciona a opção de salvar o documento para consulta offline <li> O sistema salva o documento no dispositivo do usuário </ol> |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | **Conexão com a internet perdida durante o salvamento** <ol> <li> O sistema detecta a perda de conexão <li> O sistema apresenta uma mensagem de erro "Falha na conexão. Tentar novamente?" e opções "Sim" e "Retornar à tela inicial" <ul> <li> O usuário seleciona "Sim" e o sistema tenta reconectar e salvar novamente <li> O usuário seleciona "Retornar à tela inicial" e a operação é cancelada </ul> </ol> |
| **Pós-condições** | O documento legislativo está disponível para consulta offline no dispositivo do usuário |
| **Rastreabilidade** | [IS02](../elicitacao/tecnicas/introspeccao.md#funcionais) [OBS05](../elicitacao/tecnicas/observacao.md#requisitos-funcionais) |

<font size="3"><p style="text-align: center">Fonte: [Henrique Torres](https://github.com/henriqtorresl).</p></font>

### UC03. Receber Notificações Personalizadas

<font size="3"><p style="text-align: center">Tabela 3: Especificação do caso de uso - Receber Notificações Personalizadas.</p></font>

| UC03 | Receber Notificações Personalizadas |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Requisitos** | Conexão com a internet |
| **Condição de entrada** | O usuário ativa a opção de notificações personalizadas nas configurações da aplicação |
| **Fluxo principal** | <ol> <li> O sistema apresenta opções de configuração de notificações <li> O usuário seleciona os critérios para notificações personalizadas <li> O sistema salva as configurações de notificações <li> O sistema envia notificações de acordo com os critérios selecionados pelo usuário </ol> |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | **Falha na entrega da notificação** <ol> <li> O sistema detecta a falha na entrega <li> O sistema registra a falha e tenta reenviar a notificação quando a conexão for restabelecida </ol> |
| **Pós-condições** | O usuário recebe notificações personalizadas sobre novas publicações relevantes |
| **Rastreabilidade** | [IS03](../elicitacao/tecnicas/introspeccao.md#funcionais) [OBS06](../elicitacao/tecnicas/observacao.md#requisitos-funcionais) |

<font size="3"><p style="text-align: center">Fonte: [Henrique Torres](https://github.com/henriqtorresl).</p></font>

### UC04. Acessar Histórico de Publicações Legislativas

<font size="3"><p style="text-align: center">Tabela 4: Especificação do caso de uso - Acessar Histórico de Publicações Legislativas.</p></font>

| UC04 | Acessar Histórico de Publicações Legislativas |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Requisitos** | Conexão com a internet |
| **Condição de entrada** | O usuário acessa a aplicação e seleciona a opção de histórico de publicações |
| **Fluxo principal** | <ol> <li> O sistema apresenta a interface de histórico de publicações <li> O usuário insere os critérios de busca no histórico <li> O sistema busca e exibe as publicações legislativas que correspondem aos critérios inseridos </ol>|
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | **Conexão com a internet perdida** <ol> <li> O sistema detecta a perda de conexão <li> O sistema apresenta uma mensagem de erro "Falha na conexão. Tentar novamente?" e opções "Sim" e "Retornar à tela inicial" <ul> <li> O usuário seleciona "Sim" e o sistema tenta reconectar <li> O usuário seleciona "Retornar à tela inicial" e a operação é cancelada </ul> </ol> |
| **Pós-condições** | O usuário visualiza o histórico de publicações legislativas conforme os critérios inseridos |
| **Rastreabilidade** | [IS04](../elicitacao/tecnicas/introspeccao.md#funcionais) [OBS07](../elicitacao/tecnicas/observacao.md#requisitos-funcionais) |

<font size="3"><p style="text-align: center">Fonte: [Henrique Torres](https://github.com/henriqtorresl).</p></font>

### UC05. Filtrar Documentos por Data, Categoria ou Órgão Emissor

<font size="3"><p style="text-align: center">Tabela 5: Especificação do caso de uso - Filtrar Documentos por Data, Categoria ou Órgão Emissor.</p></font>

| UC05 | Filtrar Documentos por Data, Categoria ou Órgão Emissor |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Requisitos** | Conexão com a internet |
| **Condição de entrada** | O usuário acessa a aplicação e seleciona a opção de filtragem de documentos |
| **Fluxo principal** | <ol> <li> O sistema apresenta a interface de filtragem de documentos <li> O usuário seleciona os critérios de filtragem desejados (data, categoria, órgão emissor) <li> O sistema busca e exibe os documentos que correspondem aos critérios de filtragem inseridos </ol>|
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | **Conexão com a internet perdida** <ol> <li> O sistema detecta a perda de conexão <li> O sistema apresenta uma mensagem de erro "Falha na conexão. Tentar novamente?" e opções "Sim" e "Retornar à tela inicial" <ul> <li> O usuário seleciona "Sim" e o sistema tenta reconectar <li> O usuário seleciona "Retornar à tela inicial" e a operação é cancelada </ul> </ol> |
| **Pós-condições** | O usuário visualiza os documentos filtrados conforme os critérios inseridos |
| **Rastreabilidade** | [OBS04](../elicitacao/tecnicas/observacao.md#requisitos-funcionais) |

<font size="3"><p style="text-align: center">Fonte: [Henrique Torres](https://github.com/henriqtorresl).</p></font>

## <a>Bibliografia</a>

> Macedo, Lucas. "Caso de uso". Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/casos_de_uso/](https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/casos_de_uso/). Acesso em: 15 mai. 2024.

> Lucidchart. "Diagrama de Caso de Uso UML". Disponível em: [https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml](https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml). Acesso em: 15 maio 2024.

> <a>Barbosa, S. D. J.; Silva, B. S.</a> "Interação Humano-Computador". Rio de Janeiro: Elsevier, 2011.

> <a>SERRANO M., SERRANO M. Requisitos</a> - Aula 13. Disponível na plataforma Aprender3. Acessado em 08 de dez. de 2022.

## <a>Histórico de Versão</a>

|Versão|Data|Data Prevista de Revisão|Descrição|Autor|Revisor|
| :------: | :----------: |:-----------: | :-----------: | :---------: |:---------: |
|`1.0`|15/05/2024|15/05/2024| Criação do documento sobre Casos de uso | [Douglas Marinho](https://github.com/M4RINH0)|[Henrique Torres](https://github.com/henriqtorresl)|
|`1.1`|16/05/2024|16/05/2024| Adicionando as tabelas dos casos de uso especificados | [Henrique Torres](https://github.com/henriqtorresl) | [Douglas Marinho](https://github.com/M4RINH0) |
|`1.2`|17/05/2024|18/05/2024| Adição do Diagrama UML | [Douglas Marinho](https://github.com/M4RINH0)|[Eric Silveira](https://github.com/ericbky)|