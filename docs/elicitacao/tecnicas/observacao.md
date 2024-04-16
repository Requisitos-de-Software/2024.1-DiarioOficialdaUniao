# Observação

## Introdução

A **Observação** é uma técnica chave na elicitação de requisitos, permitindo aos desenvolvedores capturar detalhes críticos sobre o uso real de sistemas pelos usuários. Observando diretamente usuários e processos, analistas podem identificar necessidades não expressas verbalmente e nuances importantes do contexto operacional. Em situações onde observadores externos não estão disponíveis, desenvolvedores, como Arthur Alves, podem assumir os papéis das personas, como Diana Sousa, para experimentar e entender profundamente as exigências do sistema. Esta abordagem prática oferece uma visão rica e autêntica do ambiente de usuário, enriquecendo o desenvolvimento do software com insights precisos e relevantes.

## Metodologia
Em 13 de abril de 2024, das 14h às 15h, membros da equipe se reuniram numa sessão virtual no Microsoft Teams, conforme listado na Tabela 1, para conduzir uma Observação Participativa. Durante essa sessão, o Engenheiro de Software teve um papel ativo, orientando o usuário nas ações a serem executadas no aplicativo do Diário Oficial da União. O observador, que ficou encarregado dessa tarefa, instruiu o usuário passo a passo, enquanto este último compartilhava sua tela de celular em tempo real, facilitando o processo de análise pelo Engenheiro de Software. Os requisitos identificados a partir dessa observação estão documentados nas Tabelas 2 e 3.

## Participantes

<font size="3"><p style="text-align: center">Tabela 1: Participantes.</p></font>

<center>

| Nome                                             | Função                   |
| ------------------------------------------------ | ------------------------ |
| [Diego Sousa](https://github.com/DiegoSousaLeite)| Observador               |
| [Arthur Alves](https://github.com/arthrok) | Representante da persona |

</center>

<font size="3"><p style="text-align: center">Fonte: [Diego Sousa](https://github.com/DiegoSousaLeite).</p></font>


## Requisitos elicitados
Legenda das Tabelas 2 e 3:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- OBSx: Requisito nºx elicitado pela observação.

### Requisitos funcionais
<font size="3"><p style="text-align: center">Tabela 2: Requisitos Funcionais.</p></font>

<center>

|Tipo| Descrição | <a id="anchor_OBS" style="visibility: hidden;"></a> ID | Implementado|
|----|-----------|--------------------------------------------------------|-------------|
|RF01|	Autenticação de usuários para acesso seguro.	| OBS01 | Sim|
|RF02|	Visualização de edições diárias do Diário Oficial.|	OBS02| Sim|
|RF03|	Busca por palavras-chave em documentos.	|OBS03| Não|
|RF04|	Filtragem de conteúdo por data, categoria ou órgão emissor.	|OBS04| Sim |
|RF05|	Download de edições e documentos em formatos PDF.	|OBS05| Não |
|RF06|	Notificações push sobre novas publicações relevantes.|	OBS06| Não|
|RF07|	Acesso a edições anteriores arquivadas.	|OBS07| Sim|
|RF08|	Integração com sistemas de assinatura digital.	|OBS08| Não|
|RF09|	Compartilhamento de documentos via redes sociais e email.|OBS09 | Sim |

</center>

<font size="3"><p style="text-align: center">Fonte: [Diego Sousa](https://github.com/DiegoSousaLeite).</p></font>

### Não Funcioanais
<font size="3"><p style="text-align: center">Tabela 3: Requisitos Não-Funcionais.</p></font>

<center>

|Tipo| Descrição | <a id="anchor_OBS" style="visibility: hidden;"></a> ID | Implementado|
|----|-----------|--------------------------------------------------------|-------------|
|RFN01|	Alta disponibilidade do sistema, com 99,9% de uptime.	| OBS10 | Sim|
|RFN02|	Compatibilidade com as versões mais recentes de sistemas operacionais móveis.|	OBS11| Não|
|RFN03|	Design responsivo que se adapta a tablets e smartphones.	|OBS12| Sim|
|RFN04|	Segurança de dados com criptografia de ponta-a-ponta.	|OBS13| Não|
|RFN05|	Suporte multilíngue para facilitar o acesso por usuários não-nativos.	|OBS14| Não |
|RFN06|	Tempo de resposta de busca inferior a 2 segundos.|	OBS15| Sim|
|RFN07|	Implementação de medidas de acessibilidade para usuários com deficiência.	|OBS16| Não|
|RFN08|	Facilidade de atualização de conteúdo pelo gestor do sistema.	|OBS17| Sim|
|RFN09|	Suporte técnico com tempo de resposta de 24 horas.|OBS18 | Sim|

</center>

<font size="3"><p style="text-align: center">Fonte: [Diego Sousa](https://github.com/DiegoSousaLeite).</p></font>

## <a>Bibliografia</a>
> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 06):  Elicitação de Requisitos - Técnicas . **UnB Gama**, Brasília, 2024. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2844983/mod_resource/content/4/Elicitacao%20de%20Req%202.pdf>>. Acesso em: 10/04/2024.


## <a>Histórico de Versão</a>
|Versão|Data|Data Prevista de Revisão|Descrição|Autor|Revisor|
| :------: | :----------: |:-----------: | :-----------: | :---------: |:---------: |
|`1.0`|06/04/2024|06/04/2024| Introdução e ideias iniciais | [Diego Sousa](https://github.com/DiegoSousaLeite)| [Arthur Alves](https://github.com/arthrok) e [João Artur](https://github.com/joao-artl) |
|`1.1`| 15/04/2024 | 16/04/2024 | Adição da aba de requisitos elicitados | [Diego Sousa](https://github.com/DiegoSousaLeite)| [Arthur Alves](https://github.com/arthrok) e [João Artur](https://github.com/joao-artl) |