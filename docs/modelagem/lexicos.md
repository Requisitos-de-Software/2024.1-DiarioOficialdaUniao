# Léxicos

## <a> Introdução </a>

De acordo com Sayão e Carvalho (2006)<a id="anchor_1" href="#REF1">^1^</a>, Léxicos são ferramentas que auxiliam no entendimento entre clientes, usuários e profissionais de software ao registrar termos e símbolos do domínio da aplicação. Os léxicos, garantem uma compreensão comum dos termos técnicos e específicos, minimizando interpretações diversas. Construir um léxico envolve a identificação de atores, recursos, verbos e estados relevantes, facilitando a comunicação e consulta durante o desenvolvimento de software. Os integrantes responsáveis pela criação dos léxicos deste projeto foram [João Artur](https://github.com/joao-artl) e [Luiz Gustavo](https://github.com/LuizGust4vo).

## <a> Metodologia </a>

Para elaborar os léxicos, seguimos a notação do Léxico Ampliado da Linguagem (LAL) apresentada por Sayão e Carvalho (2006)<a id="anchor_1" href="#REF1">^1^</a>, utilizando os conceitos detalhados na Tabela 1.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Léxicos do tipo LAL</p></font>

| Tipo do símbolo | Noção | Impacto |
|-----------------|-------|-------|
| Sujeito | Quem é o sujeito | Ações que executa |
| Verbo | Quem realiza, quando acontece e quais os procedimentos | Quais os reflexos das ações no ambiente e novos estados decorrentes |
| Objeto | Definir o objeto e identificar outros objetos com os quais ele se relaciona | Ações que podem ser aplicadas ao objeto  |
| Estado | O que indica e ações que levaram a esse estado | Identificar outros estados que podem ocorrer a partir do estado que se descreve  |

<font size="3"><p style="text-align: center">Fonte: SAYÃO e CARVALHO<a id="anchor_1" href="#REF1">^1^</a>.</p></font>

</figure>

A tabela 2 mostra um exemplo de como um léxico pode ser construído de acordo com a tabela mostrada acima.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Exemplo de símbolo de um léxico do tipo LAL</p></font>

| Tipo do Símbolo | Noção     | Impactos   |
|----|----|-------|
| **Sujeito**     | Pessoa que pode utilizar a biblioteca; pode ser aluno, professor ou funcionário da universidade  | Usuário é cadastrado no sistema<br/><br/> Usuário é retirado do cadastro de usuários <br/><br/> Usuário retira obras da biblioteca <br/><br/> Usuário devolve obras anteriormente retiradas <br/><br/> Usuário renova datas para devolução de obras anteriormente retiradas |

<font size="3"><p style="text-align: center">Fonte: SAYÃO e CARVALHO<a id="anchor_1" href="#REF1">^1^</a>.</p></font>

</figure>

A tabela 3 mostra o template criado com base nos Léxicos do projeto [Libre Office Writer](https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/lexicos/) e que será usado para definir os léxicos deste projeto.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Template Léxicos</p></font>

| Léxico | Descrição |
|-----|-----------|
| Classificação | Estado/Objeto/Verbo |
| Impacto | Descrição de ações e de seus efeitos |
| Noção | Símbolo. |
| Sinônimos | Dicionário de palavras |

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>
</figure>

## <a> Léxicos </a>

### <a> L01: Filtrar Publicações </a>

O léxico "Filtrar Publicações" representado na tabela 4, descreve um conjunto de termos e conceitos relacionados à ação de filtrar informações no Sistema. Ele faz uso dos requisitos <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS03</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS04</a> e <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">IS01</a>.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 4</b> - Léxico 1: Filtrar Publicações</p></font>

| L01 | Descrição |
|-----|-----------|
| Classificação | Verbo |
| Impacto | Recebe informações sobre publicações oficiais, pode filtrar conteúdo por data, categoria, ou autoridade emissora. |
| Noção | Ação de aplicar filtros em uma busca no sistema, como estado, município, data, ou categoria. |
| Sinônimos | Refinar busca, Selecionar critérios, Aprimorar busca. |

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>
</figure>

### <a> L02: Diário Oficial </a>

O léxico "Diário Oficial" representado na tabela 5, descreve a publicação de Diários Oficiais e avisos importantes dentro do Diário Oficial da União. Ele faz uso dos requisitos <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS02</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS06</a> e <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">IS05</a>.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 5</b> - Léxico 2: Publicação Oficial</p></font>

| L02 | Descrição |
|-----|-----------|
| Classificação | Objeto |
| Impacto | Sua principal finalidade é informar todos os assuntos oficiais e tornar público todas as decisões tomadas, reuniões, editais, nomeações e todos os demais assuntos que possam interressar à população. |
| Noção | É um jornal impresso e/ou online governamental municipal, federativo e/ou estadual. |
| Sinônimos | Publicações, Jornais Oficiais |

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>
</figure>

### <a> L03: Usuário </a>

O léxico "Usuário", representado na tabela 6, descreve os termos e conceitos relacionados às pessoas que interagem com o sistema em questão. Este léxico classifica o usuário como um objeto e detalha seu impacto como alguém que interage ativamente com o sistema. Ele faz uso dos requisitos <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS02</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS05</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS06</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS08</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS09</a> e <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">IS03</a>.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 6</b> - Léxico 3: Usuário</p></font>

| L03 | Descrição |
|-----|-----------|
| Classificação | Objeto |
| Impacto | Pessoa que interage com o sistema. Pode ser um funcionário público, um profissional da educação, um membro de sindicato, ou um estudante realizando pesquisas. |
| Noção | O usuário pode ser alguém que queira visualizar publicações de diários oficiais ou decretos governamentais. |
| Sinônimos | Cidadão, Utilizador, Stakeholder. |

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>
</figure>

### <a> L04: Favoritar </a>

O léxico "Favoritar", representado na tabela 7, descreve a ação de escolher um ou mais diários para separar dos demais. Ele faz uso dos requisitos <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS02</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS04</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS07</a> e <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">IS02</a>.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 7</b> - Léxico 4: Favoritar</p></font>

| L04 | Descrição |
|-----|-----------|
| Classificação | Verbo |
| Impacto | Quando um diário oficial é favoritado, significa que ele possui alguma informação relevante para o usuário, logo, se um diário é muito favoritado, significa que ele é importante para muitos usuários |
| Noção | Definir um diário oficial como sendo preferido, mais relevante que os demais |
| Sinônimos | Marcar, separar, preferir |

<font size="3"><p style="text-align: center">Fonte: [Luiz Gustavo](https://github.com/LuizGust4vo).</p></font>
</figure>

### <a> L05: Diário Publicado </a>

O léxico "Diário Publicado", representado na tabela 8, descreve o estado de um diário oficial quando ele se torna público. Ele faz uso dos requisitos <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS02</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS05</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS06</a> e <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">IS03</a>.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 8</b> - Léxico 5: Diário Publicado</p></font>

| L05 | Descrição |
|-----|-----------|
| Classificação | Estado |
| Impacto | Transparência e acesso à informação, qualquer cidadão pode acompanhar os assuntos oficiais, permitindo a participação popular e o combate à corrupção |
| Noção | Todos os assuntos oficiais do diário tornam-se de livre acesso |
| Sinônimos | Não possui sinônimos |

<font size="3"><p style="text-align: center">Fonte: [Luiz Gustavo](https://github.com/LuizGust4vo).</p></font>
</figure>

### <a> L06: Configuração de Notificações </a>

O léxico "Configuração de Notificações", representado na tabela 9, descreve o conjunto de ações e opções disponíveis para os usuários ajustarem como desejam receber avisos e atualizações do sistema. Ele faz uso dos requisitos <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS06</a> e <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">IS03</a>.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 9</b> - Léxico 6: Configuração de Notificações</p></font>

| L06 | Descrição |
|-----|-----------|
| Classificação | Objeto |
| Impacto | As configurações de notificações permitem que os usuários recebam alertas sobre publicações relevantes no Diário Oficial da União de acordo com suas preferências e interesses específicos. |
| Noção | Os usuários podem personalizar as configurações de notificações para receberem informações específicas, garantindo que estejam sempre atualizados sobre os conteúdos que lhes interessam. |
| Sinônimos | Configurações de Notificações, Preferências de Alerta, Ajustes de Avisos |

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>
</figure>

## <a> Relacionamento dos Léxicos </a>

O Relacionamento dos léxicos, representado na tabela 10, mostra como cada léxico é associado a outros léxicos relevantes, com uma descrição detalhada de como essas entidades estão conectadas. A tabela serve não só como uma ferramenta de referência rápida, mas também como uma base para a revisão e melhoria.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 10</b> - Tabela de Relacionamento dos Léxicos</p></font>

| Léxico | Relaciona-se com   | Descrição do Relacionamento  |
|--------|--------------------|------------------------------|
| [L01: Filtrar Publicações](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l01-filtrar-publicações) | [L02: Diário Oficial](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l02-diário-oficial), [L03: Usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuário)    | O usuário ([L03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuário)) utiliza o sistema para filtrar publicações de Diários Oficiais ([L02](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l02-diário-oficial))|
| [L02: Diário Oficial](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l02-diário-oficial)  | [L03: Usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuário), [L05: Diário Publicado](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l05-diário-publicado)| O Diário Oficial ([L02](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l02-diário-oficial)) torna-se um Diário Publicado ([L05](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l05-diário-publicado)) e é acessado pelo Usuário ([L03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuário)) |
| [L03: Usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuário)   | [L02: Diário Oficial](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l02-diário-oficial), [L04: Favoritar](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l04-favoritar), [L03: Usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuário), [L05: Diário Publicado](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l05-diário-publicado), [L06: Configuração de Notificações](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l06-configuração-de-notificações)| O Usuário ([L03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuário)) interage com todos os outros elementos do sistema de acordo com suas necessidades |
| [L04: Favoritar](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l04-favoritar)  | [L02: Diário Oficial](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l02-diário-oficial), [L03: Usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuário) | O Usuário ([L03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuário)) seleciona Diários Oficiais ([L02](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l02-diário-oficial)) como favoritos para acesso rápido |
| [L05: Diário Publicado](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l05-diário-publicado)  | [L02: Diário Oficial](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l02-diário-oficial), [L03: Usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuário)    | Após a publicação, o Diário Oficial ([L02](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l02-diário-oficial)) é acessível ao Usuário ([L03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuário)) como um Diário Publicado ([L05](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l05-diário-publicado)) |
| [L06: Configuração de Notificações](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l06-configuração-de-notificações) | [L03: Usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuário) | O Usuário ([L03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuário)) configura notificações para receber atualizações personalizadas |

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>
</figure>

## <a>Referência Bibliográfica</a>

> <a id="REF1" href="#anchor_1">1.</a> SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. 

## <a>Bibliografia</a>

> Léxicos Bilheteria Digital. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/>. Acesso em 10 de maio de 2024.

> Léxicos Libre Office Writer . Disponível em: <https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/lexicos/>. Acesso em 10 de maio de 2024

## <a> Histórico de Versão </a>

| Versão | Data | Data Prevista de Revisão | Descrição | Autor | Revisor |
| :------: | :----------: | :-----------: | :-----------: | :---------: | :---------: |
| `1.0` | 10/05/2024 | 12/05/2024 | Criação do documento sobre Léxicos | [João Artur](https://github.com/joao-artl) | [Diego Sousa](https://github.com/DiegoSousaLeite) e [Douglas Marinho](https://github.com/M4RINH0) |
| `1.1` | 11/05/2024 | 13/05/2024 | Adicionando Léxicos (01, 02 e 03)| [João Artur](https://github.com/joao-artl) | [Diego Sousa](https://github.com/DiegoSousaLeite) e [Douglas Marinho](https://github.com/M4RINH0) |
| `1.2` | 15/05/2024 | 16/05/2024 | Adicionando mais Léxicos (04 e 05) | [Luiz Gustavo](https://github.com/LuizGust4vo) | [João Artur](https://github.com/joao-artl) |
| `1.3` | 17/05/2024 | 18/05/2024 | Adicionando Léxico 06| [João Artur](https://github.com/joao-artl) | [Diego Sousa](https://github.com/DiegoSousaLeite) e [Douglas Marinho](https://github.com/M4RINH0) |
| `1.4` | 17/05/2024 | 18/05/2024 | Adicionando tabela de relacionamentos| [João Artur](https://github.com/joao-artl) | [Diego Sousa](https://github.com/DiegoSousaLeite) e [Douglas Marinho](https://github.com/M4RINH0) |