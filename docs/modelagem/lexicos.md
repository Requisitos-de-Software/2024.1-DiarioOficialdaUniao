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

| L03 | Descrição |
|-----|-----------|
| Classificação | Estado/Objeto/Verbo |
| Impacto | Descrição de ações e de seus efeitos |
| Noção | Símbolo. |
| Sinônimos | Dicionário de palavras |

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>
</figure>

## <a> Léxicos </a>

As tabelas de 4 a 9, representam os léxicos do projeto moldados de acordo com o template fornecido anteriormente.

### <a> L01: Filtrar Publicações </a>

O léxico "Filtrar Publicações" descreve um conjunto de termos e conceitos relacionados à ação de filtrar informações no Sistema. Ele faz uso dos requisitos <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS03</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS04</a> e <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados>IS01</a>.

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

### <a> L02: Publicação Oficial </a>

O léxico "Publicação Oficial" é essencial para garantir uma compreensão clara e consistente dos documentos legais e avisos importantes dentro do Diário Oficial da União. Ele faz uso dos requisitos <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS02</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS06</a> e <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">IS05</a>.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 5</b> - Léxico 2: Publicação Oficial</p></font>

| L02 | Descrição |
|-----|-----------|
| Classificação | Objeto |
| Impacto | Serve como meio legal de comunicação de atos governamentais, leis, e avisos importantes. |
| Noção | Documento ou informação que é publicado no Diário Oficial da União. |
| Sinônimos | Aviso oficial, Decreto, Lei. |

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>
</figure>

### <a> L03: Usuário </a>

O léxico "Usuário" descreve os termos e conceitos relacionados às pessoas que interagem com o sistema em questão. Este léxico classifica o usuário como um objeto e detalha seu impacto como alguém que interage ativamente com o sistema. Ele faz uso dos requisitos <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS02</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS05</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS06</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS08</a>, <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">OBS09</a> e <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">IS03</a>.

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

## <a>Referência Bibliográfica</a>

> <a id="REF1" href="#anchor_1">1.</a> SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. 

## <a>Bibliografia</a>

> Léxicos Bilheteria Digital. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/>. Acesso em 10 de maio de 2024.

> Léxicos Libre Office Writer . Disponível em: <https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/lexicos/>. Acesso em 10 de maio de 2024

## <a>Histórico de Versão</a>
|Versão|Data|Data Prevista de Revisão|Descrição|Autor|Revisor|
| :------: | :----------: |:-----------: | :-----------: | :---------: |:---------: |
|`1.0`|10/05/2024|12/05/2024| Criação do documento sobre Léxicos | [João Artur](https://github.com/joao-artl)|[Diego Sousa](https://github.com/DiegoSousaLeite) e [Douglas Marinho](https://github.com/M4RINH0)|
|`1.1`|11/05/2024|13/05/2024| Adicionando Léxicos | [João Artur](https://github.com/joao-artl)|[Diego Sousa](https://github.com/DiegoSousaLeite) e [Douglas Marinho](https://github.com/M4RINH0)|