## <a>Introdução</a>

O cenário reclaciona a interação dos usuários com o sistema, de forma detalhada sobre a execução de uma atividade do software. Assim, a abordagem de **Design Baseado em Cenários** é um processo que utiliza diferentes tipos de cenários como representação básica e fundamental durante todas as atividades envolvidas na concepção de uma solução de IHC (Rosson e Carroll, 2002; Carroll, 1995)<a id="anchor_1" href="#FRM1">^1^</a>.

## <a>Por que utilizar Design Baseado em Cenários?</a>

De acordo com o livro "Interação Humano-Computador e Experiência do usuário", a equipe de design (incluindo representantes dos usuários) tem a oportunidade de discutir e analisar como as atividades dos usuários são afetadas pela tecnologia existente e como elas poderiam ser afetadas pelo sistema sendo desenvolvido, a partir do **Design Baseado em Cenários**. Desse modo, cenários são uma ferramenta útil e barata para gerar e avaliar diversas ideias durante as atividades de design<a id="anchor_1" href="#FRM1">^1^</a>.

## <a>Modelo de Cenário</a>

De acordo com Weidenhaupt, em seu estudo sobre o uso de cenários no desenvolvimento de software, foram identificados cinco formas para a descrição de cenários, sendo elas: texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações<a id="anchor_2" href="#FRM2">^2^</a>.
Uma das formas mais utilizadas é a de **texto estruturado** e devido a essa razão, por questões de mais acessibilidade a materiais base, adotamos o mesmo modelo.
Segundo a tese "Evolução de Cenários Através de um Mecanismo de
Rastreamento Baseado em Transformações", essa notação utiliza uma linguagem natural semi-estruturada (ancorada no mundo real), partindo da premissa que a utilização da linguagem da aplicação e não do software facilita o entendimento e a validação dos requisitos por parte dos clientes<a id="anchor_2" href="#FRM2">^2^</a>.

Em geral, cada cenário apresenta um ator principal e um objetivo principal. Tal objetivo pode ser desdobrado em subobjetivos, numa atividade de planejamento que se passa na cabeça dos atores. Quando essa atividade mental for importante para uma situação, o cenário pode incluir informações sobre planejamento e avaliação das ações realizadas. Cada cenário costuma ter um título que descreve brevemente a situação, sem muitos detalhes; os atores que participam do cenário; uma breve descrição da situação inicial em que os atores se encontram; e referências a outros cenários que permitam aos atores atingir os mesmos objetivos de diferentes maneiras<a id="anchor_3" href="#FRM3">^3^</a>.

Neste projeto, detalhamos os cenários utilizando técnicas textuais descritivas e estruturadas e complementamos com especificações detalhadas dos elementos característicos de cada cenário em tabelas e cada elemento conta com "Perguntas utilizadas para refinar cada elemento de um cenário ou auxiliar a análise."<a id="anchor_3" href="#FRM3">^3^</a>. Para uma visão mais aprofundada sobre os elementos característicos de cada cenário, consulte a Tabela 1.

<p style="text-align: center"><b>Tabela 1:</b> Descrição do modelo texto estruturado.</p>

|Elemento|Descricação|
|-----------|---------------|
|Título | identifica o cenário |
| Objetivos | efeitos na situação que motivam as ações realizadas pelos atores |
|Ambiente|  detalhes da situação que motivam ou explicam os objetivos, ações e reações dos atores do cenário|
| Atores | pessoas interagindo com o computador ou outros elementos do ambiente; características pessoais relevantes ao cenário |
| Planejamento | atividade mental dirigida para transformar um objetivo em um comportamento ou conjunto de ações |
| Ações | comportamento observável |
| Eventos |  ações externas ou reações produzidas pelo computador ou outras características do ambiente; algumas delas podem ser ocultas ao ator mas importantes para o cenário |
| Avaliação |  atividade mental dirigida para interpretar a situação |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Rosson e Carroll (2002); Cooper (1999)<a id="anchor_3" href="#FRM3">^3^</a>.</p></font>

<br>
Na figura 1, temos um exemplo de utilização da notação para a descrição de um cenário para um sistema de controle de luzes.


<font size="3"><p style="text-align: center"><b>Figura 1:</b> Exemplo de descrição de um cenário.</p></font>

<p align="center">
  <img src="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/assets/ModeloTextoEstruturado.png?raw=true" alt="Modelo" />
</p>

<font size="3"><p style="text-align: center"><b>Fonte:</b> SERRANO, Milene. SERRANO, Mauricio. Requisitos – Aula 10.</p></font>

## <a>Cenários identificados</a>
Os cenários identificados foram construídos a partir dos requisitos elicitados e priorizados documentados na seção <a href="/2024.1-DiarioOficialdaUniao/elicitacao/priorizacao/#tabela-de-requisitos-priorizados">Priorização</a>. Os atores escolhidos para cada cenário fazem parte do artefato <a href="/2024.1-DiarioOficialdaUniao/elicitacao/personas">Personas</a>.


### <a>C03 - Configurar o aplicativo</a>

Atores: Diana Sousa (graduanda em Psicologia e bolsista de pesquisa pela UnB)

Diana Sousa, ao utilizar o aplicativo Diário Oficial da União em seu dispositivo móvel, sente a necessidade de ajustar as configurações para atender às suas necessidades específicas, incluindo melhor acessibilidade e personalização de conteúdo. Ela busca principalmente ajustar o contraste e ativar o suporte para tecnologia assistiva, como o talkback, além de configurar notificações e filtros para receber apenas informações relevantes dos órgãos de seu interesse. Diana acessa o menu de configurações do aplicativo, onde enfrenta um processo não muito intuitivo que envolve várias etapas para cada ajuste desejado. Ela ajusta o contraste para facilitar a leitura, ativa o talkback para auxílio na navegação, e configura as notificações para receber alertas apenas de novas edições que incluem tópicos específicos de sua área de estudo. Cada ação requer que ela navegue por diferentes submenus, o que torna o processo tedioso e suscetível a erros. Ao final das configurações, Diana verifica se as alterações foram aplicadas corretamente revisitando cada opção ajustada. A experiência deixa claro que, embora possível, a configuração é mais complexa e demorada do que o necessário, indicando uma área de melhoria para uma interface mais simplificada e eficiente.


A tabela 4 descreve o cenário que tem como objetivo configurar o aplicativo.

<p style="text-align: center"><b>Tabela 4:</b> Configurar aplicativo.</p>
<center>

| Elemento     | Descrição | Perguntas selecionadas |
|--------------|-----------|------------------------|
| Título       | Configurar Aplicativo do Diário Oficial da União | N/A |
| Objetivo     | Os atores querem personalizar as configurações do aplicativo para facilitar o acesso às informações e garantir que o conteúdo seja acessível e relevante às suas necessidades específicas, como ativar alto contraste ou talkback para usuários com deficiência visual. O objetivo está relacionado a garantir que todas as informações relevantes sejam facilmente acessíveis e que o usuário possa consumir, manipular ou destruir informações de acordo com suas preferências e necessidades. | Por que os atores querem ou precisam alcançar esse objetivo? Quais informações são criadas, consumidas, manipuladas ou destruídas pelo alcance do objetivo? Que outros objetivos estão relacionados a esse?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ambiente     | O cenário ocorre sempre que o usuário deseja ajustar o aplicativo para melhorar sua experiência ou quando há mudanças em suas necessidades de acessibilidade ou interesse em conteúdos específicos. As pressões incluem a necessidade de rapidez e eficiência na personalização, bem como a dependência de uma conexão estável à internet. As tecnologias envolvidas incluem dispositivos móveis e o próprio aplicativo, que deve ser intuitivo e acessível. | Em que situações o cenário ocorre? Quais pressões existem para o alcance do objetivo? Quais são as tecnologias utilizadas no ambiente? Como os usuários as utilizam?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ator         | Diana Sousa, graduanda em Psicologia e bolsista de pesquisa pela UnB, que precisa personalizar o aplicativo para atender às suas necessidades acadêmicas e pessoais. | (N/A) |
| Planejamento | Diana atualmente alcança seu objetivo navegando pelas configurações padrão do aplicativo, mas gostaria de ter uma interface mais personalizável e intuitiva. Ela precisa decidir sobre configurações como filtros de conteúdo e notificações, e essas decisões dependem de quão bem o sistema suporta suas necessidades. Uma decisão errada pode levar a uma sobrecarga de informações ou falta de acesso a informações críticas. | Como os atores alcançam o objetivo atualmente? Como gostariam de fazê-lo? Que decisões os atores precisam tomar a cada momento? De que maneira o ambiente e o sistema auxiliam ou impedem que os atores tomem decisões adequadas? Quais as consequências de uma decisão errada? Que ações realizam? Como essas ações estão relacionadas? Em que ordem os atores precisam realizar as ações? Gostariam de realizá-las em outra ordem?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ação         | As precondições incluem ter o aplicativo instalado e estar logado. Diana realiza as ações através do menu de configurações, onde ajusta as preferências. Ela gostaria de ter atalhos mais diretos para certas configurações. Erros como configurações mal ajustadas podem ser revertidos através do menu de configurações, mas podem causar perda de tempo e frustração. | Quais as precondições para essa ação? Como os atores as realizam? Os atores gostariam de fazer isso de outra maneira? Como o fariam? De que informações ou conhecimento os atores precisam para realizar essa ação? Que recursos estão disponíveis para realizá-la? Quais erros podem ser cometidos ao realizá-la? Como podem ser desfeitos? Quais suas consequências? Quais informações são criadas, consumidas, manipuladas ou destruídas pela realização da ação?<a id="anchor_3" href="#FRM3">^3^</a> |
| Evento       | Eventos que disparam a necessidade de alcançar o objetivo incluem mudanças nas necessidades de acessibilidade de Diana ou interesse em áreas específicas do diário oficial. A conclusão das configurações desencadeia uma experiência de usuário mais personalizada e eficiente. | Quais eventos disparam a necessidade de alcançar o objetivo? Quais eventos são disparados pela conclusão desse objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Avaliação    | Diana pode avaliar o sucesso de suas ações verificando se as configurações aplicadas refletem suas preferências no aplicativo. O resultado bem-sucedido é um aplicativo que atende melhor às suas necessidades específicas, facilitando o acesso e a gestão da informação. | Como os atores conseguem saber se uma ação foi concluída e realizada com sucesso? Qual é o resultado do alcance do objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |

</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> Arthur Alves.</p></font>

| Denominação     | Configurar o Aplicativo |
|-----------------|-------------------------|
| Objetivo/meta   | Permitir que o usuário ajuste as configurações do aplicativo DOU para atender às suas necessidades específicas de acessibilidade e personalização de conteúdo. |
| Contexto        | **Contexto:** Diana Sousa precisa ajustar o aplicativo DOU para melhorar a acessibilidade e personalizar o conteúdo. <br> **Local:** Menu de configurações do aplicativo DOU. <br> **Tempo:** A configuração pode levar de 5 a 15 minutos, dependendo da quantidade de ajustes necessários. <br> **Pré-condição:** Diana deve estar autenticada no sistema e ter acesso ao menu de configurações. |
| Atores          | Diana Sousa (Usuário Primário); <br> Sistema do DOU (Usuário Secundário) |
| Recursos        | Aplicativo do DOU; <br> Conexão à internet. |
| Episódios       | 1. Diana faz login no aplicativo do DOU. <br> 2. Diana acessa o menu de configurações. <br> 3. Diana ajusta o contraste e ativa o suporte para talkback. <br> 4. Diana configura notificações e filtros para receber informações de órgãos específicos. <br> 5. Diana revisa todas as configurações para garantir que foram aplicadas corretamente. |
| Exceção         | 1. Se ocorrer um erro ao salvar as configurações, uma mensagem de erro é exibida e Diana é orientada a tentar novamente. <br> 2. Se houver um problema de conexão, uma mensagem de erro é exibida e Diana é instruída a tentar novamente mais tarde. |
| Restrição       | 1. As configurações devem estar de acordo com os padrões de acessibilidade. <br> 2. A conexão à internet deve estar estável durante o processo de configuração. <br> 3. O sistema deve permitir que as configurações sejam facilmente revertidas ou ajustadas novamente. |


#### <a>Análise do Cenário</a>

- A necessidade de ajustar configurações de acessibilidade, como contraste e suporte para talkback.
- A necessidade de configurar notificações e filtros de conteúdo relevante.
- A complexidade e o tempo necessário para navegar por diferentes submenus e ajustar cada configuração.
- A importância de uma interface de configuração mais intuitiva e eficiente para melhorar a experiência do usuário.

### <a>C04 - Filtrar Publicações por Temas</a>

Atores: Robson Pinto (Servidor Público Federal)

Robson Pinto é Servidor Público Federal no Tribunal Superior do Trabalho (TST) e formado em Economia. Ele utiliza o Diário Oficial da União (DOU) para acompanhar decisões judiciais, alterações nas leis trabalhistas, regulamentações e outras informações pertinentes ao direito do trabalho. Manter-se atualizado com as políticas e diretrizes do governo federal que impactam o sistema judiciário é essencial para seu trabalho. Robson precisa frequentemente encontrar informações específicas no DOU, mas o volume de publicações é grande e a busca pode ser demorada. Embora já existam filtros como data e órgão emissor, ele sente falta de filtros mais refinados, como temas específicos e outros critérios que facilitem a localização das informações relevantes. Alguns dos filtros que Robson considera importantes incluem:

- Tema (Direito Trabalhista, Direito Ambiental, Políticas Públicas)
- Impacto Geográfico (Nacional, Regional, Estadual)

Em um dia específico, Robson precisa encontrar todas as publicações relacionadas ao tema "Direito Trabalhista" e especificamente as portarias que têm impacto nacional. Sem esses filtros, ele gasta muito tempo navegando por diversas publicações, muitas das quais não são relevantes para sua pesquisa. Robson percebe que a implementação de filtros temáticos e outros critérios avançados no aplicativo do DOU seria extremamente benéfica. Isso permitiria que ele encontrasse as informações de forma rápida e precisa, economizando tempo e melhorando a eficiência de seu trabalho.

A tabela 5 descreve o cenário que tem como objetivo filtrar as publicações.

<p style="text-align: center"><b>Tabela 5:</b> Filtrar Publicações por Temas.</p>
<center>

| Elemento     | Descrição | Perguntas selecionadas |
|--------------|-----------|------------------------|
| Título       | Filtrar Publicações por Temas | N/A |
| Objetivo     | Robson deseja filtrar publicações do DOU por temas e outros critérios avançados para localizar informações específicas de forma eficiente. | Por que os atores querem ou precisam alcançar esse objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ambiente     | O cenário ocorre no escritório de Robson, onde ele utiliza um tablet para acessar o DOU e realizar suas pesquisas. | Em que situações o cenário ocorre? Quais são as tecnologias utilizadas no ambiente?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ator         | Robson Pinto, Servidor Público Federal no TST, que acompanha o DOU para se manter atualizado sobre decisões judiciais e alterações nas leis trabalhistas. | (N/A) |
| Planejamento | Atualmente, Robson utiliza filtros básicos como data e órgão emissor, mas gostaria de filtros temáticos e avançados para melhorar sua busca. | Como os atores alcançam o objetivo atualmente? Como gostariam de fazê-lo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ação         | As precondições incluem ter acesso ao aplicativo do DOU e a necessidade de localizar informações específicas. Robson tenta usar os filtros atuais, mas encontra dificuldades devido à falta de filtros temáticos. | Quais as precondições para essa ação? Como os atores as realizam? Quais problemas ou dificuldades podem surgir ao realizá-la?<a id="anchor_3" href="#FRM3">^3^</a> |
| Evento       | A necessidade de encontrar todas as portarias relacionadas ao Direito Trabalhista com impacto nacional. | Quais eventos disparam a necessidade de alcançar o objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Avaliação    | Robson saberá que atingiu seu objetivo quando conseguir usar filtros temáticos e avançados para encontrar publicações específicas no DOU de forma rápida e precisa. | Como os atores conseguem saber se uma ação foi concluída e realizada com sucesso? Qual é o resultado do alcance do objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |


<font size="3"><p style="text-align: center"><b>Fonte:</b> Arthur Alves.</p></font>

</center>

| Denominação     | Filtros Temáticos |
|-----------------|-------------------------------------------------|
| Objetivo/meta   | Permitir que Robson filtre publicações do DOU por temas e outros critérios avançados para localizar informações específicas de forma eficiente. |
| Contexto        | **Contexto:** Robson precisa encontrar publicações específicas relacionadas ao Direito Trabalhista. <br> **Local:** No menu de filtros avançados do aplicativo do DOU. <br> **Tempo:** A busca pode levar de 5 a 15 minutos, dependendo dos critérios de filtro aplicados. <br> **Pré-condição:** Robson deve estar autenticado no sistema e ter acesso ao menu de filtros avançados. |
| Atores          | Robson Pinto (Usuário Primário); <br> Sistema do DOU (Usuário Secundário) |
| Recursos        | Aplicativo do DOU; <br> Conexão à internet; <br> Banco de dados de publicações. |
| Episódios       | 1. Robson faz login no aplicativo do DOU. <br> 2. Robson acessa o menu de filtros avançados. <br> 3. Robson seleciona os critérios de filtro desejados (e.g., tema, impacto geográfico). <br> 4. O sistema aplica os filtros e exibe as publicações relevantes. <br> 5. Robson revisa as publicações e encontra a informação necessária. |
| Exceção         | 1. Se ocorrer um erro na aplicação dos filtros, uma mensagem de erro é exibida e Robson é orientado a tentar novamente. <br> 2. Se houver um problema de conexão, uma mensagem de erro é exibida e Robson é instruído a tentar novamente mais tarde. |
| Restrição       | 1. O sistema deve garantir que os filtros sejam aplicados corretamente e as informações sejam precisas. <br> 2. A conexão à internet deve estar estável durante o processo de busca. <br> 3. Os filtros devem estar atualizados e cobrir uma ampla gama de temas e critérios. |


#### <a>Análise do Cenário</a>

- A dificuldade de encontrar informações específicas devido ao grande volume de publicações.
- A falta de filtros refinados que facilitariam a localização de informações relevantes.
- O tempo gasto navegando por publicações irrelevantes.
- A importância de filtros temáticos e outros critérios avançados para melhorar a eficiência e a precisão das buscas no DOU.


### <a>C05 - Busca por Palavras-chave</a>
Atores: Camila Oliveira (Assessora Jurídica)

Camila Oliveira é assessora jurídica em um escritório de advocacia e seu trabalho envolve garantir a conformidade legal das publicações do STJ no Diário Oficial da União (DOU). Parte essencial do seu trabalho é revisar e editar os atos antes da publicação. Frequentemente, Camila precisa buscar palavras-chave específicas em várias edições do DOU para localizar atos ou referências relevantes rapidamente. No entanto, o aplicativo atual do DOU não possui uma funcionalidade de busca por palavras-chave eficiente, o que a obriga a ler manualmente vários diários para encontrar a informação necessária. Em um dia específico, Camila precisa encontrar todas as menções a uma nova regulamentação que foi discutida em diversas edições do DOU ao longo das últimas semanas. Sem uma ferramenta de busca eficaz, ela gasta horas tentando localizar cada menção, o que atrasa seu trabalho e gera frustração. A falta de uma funcionalidade de busca por palavras-chave torna o processo extremamente ineficiente, especialmente quando há urgência em revisar e preparar os atos para publicação. Camila percebe que a implementação de uma funcionalidade de busca por palavras-chave no aplicativo do DOU melhoraria significativamente sua produtividade e eficiência. Isso permitiria que ela localizasse rapidamente as informações necessárias, garantindo que os atos sejam revisados e publicados dentro dos prazos estipulados.


A tabela 6 descreve o cenário que tem como objetivo achar diários por palavras-chave.

<p style="text-align: center"><b>Tabela 6:</b> Obter diários por palavras-chave.</p>
<center>

| Elemento     | Descrição | Perguntas selecionadas |
|--------------|-----------|------------------------|
| Título       | Busca por Palavras-chave | N/A |
| Objetivo     | Camila deseja localizar rapidamente menções a regulamentações específicas no DOU usando uma busca por palavras-chave. | Por que os atores querem ou precisam alcançar esse objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ambiente     | O cenário ocorre no escritório de advocacia onde Camila trabalha, utilizando o aplicativo do DOU em um tablet. | Em que situações o cenário ocorre? Quais são as tecnologias utilizadas no ambiente?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ator         | Camila Oliveira, assessora jurídica que revisa e edita atos antes da publicação no DOU. | (N/A) |
| Planejamento | Atualmente, Camila procura manualmente as palavras-chave nas edições do DOU. Gostaria de fazer isso de forma rápida e eficiente utilizando uma ferramenta de busca. | Como os atores alcançam o objetivo atualmente? Como gostariam de fazê-lo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ação         | As precondições incluem ter acesso ao aplicativo do DOU e estar logada. Camila utiliza o aplicativo para procurar manualmente as palavras-chave, enfrentando dificuldades devido à falta de uma funcionalidade de busca. | Quais as precondições para essa ação? Como os atores as realizam? Quais problemas ou dificuldades podem surgir ao realizá-la?<a id="anchor_3" href="#FRM3">^3^</a> |
| Evento       | A necessidade de revisar menções a uma nova regulamentação publicada no DOU em diversas edições. | Quais eventos disparam a necessidade de alcançar o objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Avaliação    | Camila saberá que atingiu seu objetivo quando conseguir encontrar rapidamente todas as menções às palavras-chave no DOU utilizando a ferramenta de busca. | Como os atores conseguem saber se uma ação foi concluída e realizada com sucesso? Qual é o resultado do alcance do objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Arthur Alves.</p></font>

</center>

| Denominação     | Busca por Palavras-chave |
|-----------------|--------------------------|
| Objetivo/meta   | Permitir que o usuário, como Camila Oliveira, localize rapidamente atos e referências específicas no DOU usando palavras-chave. |
| Contexto        | **Contexto:** Camila precisa encontrar menções a uma nova regulamentação no DOU. <br> **Local:** Função de busca no aplicativo DOU. <br> **Tempo:** A busca pode levar de 2 a 10 minutos, dependendo da quantidade de dados. <br> **Pré-condição:** Camila deve estar autenticada no sistema e ter o aplicativo atualizado. |
| Atores          | Camila Oliveira (Usuário Primário); <br> Sistema do DOU (Usuário Secundário) |
| Recursos        | Aplicativo do DOU; <br> Conexão à internet; <br> Banco de dados de publicações. |
| Episódios       | 1. Camila faz login no aplicativo do DOU. <br> 2. Camila acessa a função de busca por palavras-chave. <br> 3. Camila insere a palavra-chave da regulamentação que deseja encontrar. <br> 4. O sistema processa a busca e exibe os resultados relevantes. <br> 5. Camila revisa os resultados e localiza a informação necessária. |
| Exceção         | 1. Se ocorrer um erro na busca, uma mensagem de erro é exibida e Camila é orientada a tentar novamente. <br> 2. Se houver um problema de conexão, uma mensagem de erro é exibida e Camila é instruída a tentar novamente mais tarde. |
| Restrição       | 1. As palavras-chave devem ser precisas para obter resultados relevantes. <br> 2. A conexão à internet deve estar estável durante o processo de busca. <br> 3. O sistema deve garantir que as publicações estejam indexadas corretamente para facilitar a busca. |


#### <a>Análise do Cenário</a>

- A necessidade de ler manualmente várias edições do DOU para encontrar palavras-chave específicas.
- A falta de uma funcionalidade de busca por palavras-chave no aplicativo do DOU.
- O atraso e a frustração causados pela ineficiência na busca manual de informações.
- A importância de uma ferramenta de busca eficaz para melhorar a produtividade e garantir a conformidade legal das publicações.

### <a>C06 - Design responsivo que se adapta a tablets e smartphones</a>
Atores: Dona Kláudia (Gerente de Qualidade Agrícola)
Dona Kláudia é Gerente de Qualidade Agrícola em uma grande cooperativa rural. Parte essencial de seu trabalho é acompanhar publicações de regulamentações sobre agrotóxicos e produtos fitossanitários no Diário Oficial da União (DOU) para garantir a conformidade regulatória na produção agrícola, bem como identificar novas oportunidades e restrições no mercado. Dona Kláudia frequentemente precisa acessar essas informações enquanto está em campo, longe de seu escritório. No entanto, o aplicativo do DOU não é otimizado para tablets e smartphones, tornando a leitura e navegação das publicações muito difíceis em dispositivos móveis. Ela precisa ampliar a tela constantemente, rolar lateralmente e lidar com textos e botões mal dimensionados, o que atrapalha seu trabalho e consome muito tempo. Em um dia específico, enquanto estava em uma visita a uma das fazendas da cooperativa, Dona Kláudia recebeu uma notificação sobre uma nova regulamentação publicada no DOU. Ao tentar acessar o documento em seu tablet, ela enfrentou dificuldades com a interface não responsiva. O texto estava pequeno demais para ser lido facilmente, e a navegação entre as seções do documento era complicada, resultando em uma experiência frustrante. Dona Kláudia percebe que uma interface responsiva, que se adapta automaticamente ao tamanho da tela de tablets e smartphones, melhoraria significativamente sua eficiência. Isso permitiria que ela acessasse as informações necessárias de forma rápida e confortável, independentemente de sua localização. Com um design responsivo, Dona Kláudia poderia garantir que a produção agrícola da cooperativa estivesse sempre em conformidade com as regulamentações mais recentes, sem os inconvenientes atuais.


A tabela 7 descreve o cenário que tem como objetivo um design responsivo que se adapta a tablets e smartphones.

<p style="text-align: center"><b>Tabela 7:</b> Design responsivo para tablets e smartphones.</p>
<center>

| Elemento     | Descrição | Perguntas selecionadas |
|--------------|-----------|------------------------|
| Título       | Design responsivo que se adapta a tablets e smartphones | N/A |
| Objetivo     | Dona Kláudia deseja acessar facilmente as publicações do DOU em dispositivos móveis para garantir conformidade regulatória e identificar novas oportunidades e restrições. | Por que os atores querem ou precisam alcançar esse objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ambiente     | O cenário ocorre principalmente no campo, onde Dona Kláudia utiliza tablets e smartphones para acessar o DOU. | Em que situações o cenário ocorre? Quais são as tecnologias utilizadas no ambiente?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ator         | Dona Kláudia, Gerente de Qualidade Agrícola, que precisa acompanhar as regulamentações sobre agrotóxicos e produtos fitossanitários no DOU. | (N/A) |
| Planejamento | Atualmente, Dona Kláudia tenta acessar o DOU em dispositivos móveis, mas enfrenta dificuldades com a interface não responsiva. Gostaria de fazer isso de forma rápida e eficiente. | Como os atores alcançam o objetivo atualmente? Como gostariam de fazê-lo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ação         | As precondições incluem ter o aplicativo instalado e estar logado. Dona Kláudia utiliza o aplicativo do DOU em seu tablet ou smartphone, lidando com uma interface mal dimensionada e de difícil navegação. | Quais as precondições para essa ação? Como os atores as realizam? Quais problemas ou dificuldades podem surgir ao realizá-la?<a id="anchor_3" href="#FRM3">^3^</a> |
| Evento       | A necessidade de acessar uma nova regulamentação publicada no DOU enquanto está em campo. | Quais eventos disparam a necessidade de alcançar o objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Avaliação    | Dona Kláudia saberá que atingiu seu objetivo quando conseguir acessar e ler facilmente as publicações do DOU em seu dispositivo móvel. | Como os atores conseguem saber se uma ação foi concluída e realizada com sucesso? Qual é o resultado do alcance do objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Arthur Alves.</p></font>

</center>

| Denominação     | Design Responsivo que se Adapta a Tablets e Smartphones |
|-----------------|---------------------------------------------------------|
| Objetivo/meta   | Permitir que usuários como Dona Kláudia acessem o DOU de maneira eficiente em dispositivos móveis, independentemente do tamanho da tela. |
| Contexto        | **Contexto:** Dona Kláudia precisa acessar o DOU enquanto está em campo. <br> **Local:** Aplicativo do DOU em tablets e smartphones. <br> **Tempo:** A consulta pode levar de 5 a 20 minutos, dependendo da quantidade de informações. <br> **Pré-condição:** Dona Kláudia deve ter o aplicativo instalado e atualizado em seu dispositivo móvel. |
| Atores          | Dona Kláudia (Usuário Primário); <br> Sistema do DOU (Usuário Secundário) |
| Recursos        | Aplicativo do DOU com design responsivo; <br> Conexão à internet. |
| Episódios       | 1. Dona Kláudia faz login no aplicativo do DOU em seu tablet. <br> 2. Dona Kláudia navega até a publicação relevante. <br> 3. O sistema adapta automaticamente a interface ao tamanho da tela. <br> 4. Dona Kláudia ajusta o zoom e navega pelo documento sem dificuldades. <br> 5. Dona Kláudia revisa as informações necessárias de forma eficiente. |
| Exceção         | 1. Se o design responsivo não funcionar corretamente, uma mensagem de erro é exibida e Dona Kláudia é orientada a tentar novamente. <br> 2. Se houver um problema de conexão, uma mensagem de erro é exibida e Dona Kláudia é instruída a tentar novamente mais tarde. |
| Restrição       | 1. O design responsivo deve garantir uma boa experiência de usuário em diferentes tamanhos de tela. <br> 2. A conexão à internet deve estar estável durante o acesso às informações. <br> 3. O sistema deve permitir ajustes manuais de zoom e navegação para melhorar a usabilidade. |


#### <a>Análise do Cenário</a>

- A dificuldade de acessar e ler publicações no DOU em dispositivos móveis devido à falta de uma interface responsiva.
- A necessidade constante de ampliar a tela e rolar lateralmente para ler textos e acessar botões.
- A frustração e o tempo perdido ao tentar acessar informações importantes enquanto está em campo.
- A importância de uma interface responsiva para melhorar a eficiência e a conformidade regulatória na produção agrícola.

### <a>C07 - Compatibilidade com as Versões Mais Recentes de Sistemas Operacionais Móveis</a>
Atores: Diana Sousa (Bolsista e Graduanda)

Diana Sousa é bolsista e graduanda, pesquisadora pelo PIBIT, trabalhando com sistemas embarcados automotivos. Ela acompanha o Diário Oficial da União (DOU) pelo celular para verificar verbas destinadas pelo Ministério da Educação para sua faculdade. Diana depende do aplicativo do DOU para estar informada sobre as publicações de interesse, e frequentemente precisa acessar essas informações enquanto está em trânsito ou em diferentes locais de estudo e pesquisa. Recentemente, Diana atualizou o sistema operacional do seu smartphone para a versão mais recente. Desde a atualização, ela começou a enfrentar problemas de compatibilidade com o aplicativo do DOU. O aplicativo apresenta falhas ao carregar, trava frequentemente, e algumas funcionalidades essenciais, como notificações e a visualização de documentos, não estão funcionando corretamente. Essas dificuldades têm impactado negativamente a capacidade de Diana de acompanhar as verbas e demais informações relevantes de forma eficiente. Em um dia específico, Diana precisa urgentemente verificar uma publicação recente sobre a destinação de verbas para um projeto de pesquisa em que está envolvida. Ao tentar abrir o aplicativo do DOU, o aplicativo trava repetidamente, impedindo-a de acessar a informação necessária. Sem conseguir utilizar o aplicativo, Diana perde tempo precioso tentando encontrar um tablet disponível para acessar o DOU pelo navegador web. Diana percebe que a compatibilidade do aplicativo do DOU com as versões mais recentes dos sistemas operacionais móveis é crucial para garantir sua eficiência e produtividade. Com um aplicativo compatível e atualizado, ela poderia acessar as informações necessárias em qualquer lugar e a qualquer momento, sem enfrentar interrupções ou falhas técnicas.

A tabela 8 descreve o cenário que tem como objetivo uma plataforma que seja compatível com as versões mais recentes de SO móveis.

<p style="text-align: center"><b>Tabela 8:</b> Compatibilidade com versões mais recentes de SO móveis.</p>
<center>


| Elemento     | Descrição | Perguntas selecionadas |
|--------------|-----------|------------------------|
| Título       | Compatibilidade com as Versões Mais Recentes de Sistemas Operacionais Móveis | N/A |
| Objetivo     | Diana deseja acessar facilmente o aplicativo do DOU em seu smartphone atualizado para verificar verbas destinadas pelo Ministério da Educação. | Por que os atores querem ou precisam alcançar esse objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ambiente     | O cenário ocorre em diversos locais onde Diana utiliza seu smartphone, incluindo trânsito e locais de estudo. | Em que situações o cenário ocorre? Quais são as tecnologias utilizadas no ambiente?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ator         | Diana Sousa, bolsista e graduanda que acompanha o DOU pelo celular para verificar verbas destinadas para sua faculdade. | (N/A) |
| Planejamento | Atualmente, Diana enfrenta problemas de compatibilidade com o aplicativo do DOU em seu smartphone atualizado. Ela gostaria de acessar o DOU sem falhas técnicas. | Como os atores alcançam o objetivo atualmente? Como gostariam de fazê-lo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ação         | As precondições incluem ter o aplicativo do DOU instalado e o smartphone atualizado. Diana tenta utilizar o aplicativo, mas enfrenta travamentos e falhas. | Quais as precondições para essa ação? Como os atores as realizam? Quais problemas ou dificuldades podem surgir ao realizá-la?<a id="anchor_3" href="#FRM3">^3^</a> |
| Evento       | A necessidade de verificar uma publicação recente sobre a destinação de verbas para um projeto de pesquisa. | Quais eventos disparam a necessidade de alcançar o objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Avaliação    | Diana saberá que atingiu seu objetivo quando conseguir acessar e utilizar o aplicativo do DOU em seu smartphone atualizado sem problemas de compatibilidade. | Como os atores conseguem saber se uma ação foi concluída e realizada com sucesso? Qual é o resultado do alcance do objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Arthur Alves.</p></font>

</center>

| Denominação     | Compatibilidade com as Versões Mais Recentes de Sistemas Operacionais Móveis |
|-----------------|-------------------------------------------------------------------------------|
| Objetivo/meta   | Garantir que o aplicativo DOU funcione corretamente em dispositivos com as versões mais recentes de sistemas operacionais móveis. |
| Contexto        | **Contexto:** Diana Sousa atualizou o sistema operacional de seu smartphone e enfrenta problemas com o aplicativo DOU. <br> **Local:** Aplicativo do DOU em dispositivos móveis atualizados. <br> **Tempo:** A resolução dos problemas pode levar de 10 a 30 minutos. <br> **Pré-condição:** Diana deve ter o aplicativo instalado e atualizado em seu dispositivo móvel. |
| Atores          | Diana Sousa (Usuário Primário); <br> Sistema do DOU (Usuário Secundário) |
| Recursos        | Aplicativo do DOU; <br> Conexão à internet; <br> Equipe de desenvolvimento do DOU. |
| Episódios       | 1. Diana faz login no aplicativo do DOU após atualizar seu sistema operacional. <br> 2. Diana tenta acessar uma publicação e o aplicativo trava. <br> 3. Diana entra em contato com o suporte técnico e descreve o problema. <br> 4. A equipe de desenvolvimento analisa e resolve o problema de compatibilidade. <br> 5. Diana atualiza o aplicativo e verifica se o problema foi resolvido. |
| Exceção         | 1. Se o problema de compatibilidade não for resolvido imediatamente, Diana é notificada sobre o prazo estimado para a solução. <br> 2. Se houver um problema de conexão, uma mensagem de erro é exibida e Diana é instruída a tentar novamente mais tarde. |
| Restrição       | 1. O aplicativo deve ser compatível com as versões mais recentes dos sistemas operacionais móveis. <br> 2. A equipe de desenvolvimento deve estar disponível para resolver problemas de compatibilidade rapidamente. <br> 3. A conexão à internet deve estar estável durante a atualização e uso do aplicativo. |


#### <a>Análise do Cenário</a>

- A dificuldade de acessar o DOU em smartphones com sistemas operacionais atualizados devido a problemas de compatibilidade.
- As falhas constantes ao carregar o aplicativo, travamentos e mal funcionamento de funcionalidades essenciais.
- A perda de tempo e a frustração causados pela necessidade de recorrer a outros dispositivos ou métodos para acessar as informações necessárias.
- A importância de garantir a compatibilidade do aplicativo do DOU com as versões mais recentes dos sistemas operacionais móveis para melhorar a eficiência e produtividade dos usuários.


### <a>C08 - Suporte Multilíngue para Facilitar o Acesso por Usuários Não-nativos</a>

Atores: Thomas Edson (Estudante Estrangeiro de Pós-Graduação)

Thomas Edson é um estudante de pós-graduação alemão que está realizando uma pesquisa sobre políticas públicas brasileiras em uma universidade no Brasil. Ele precisa acessar frequentemente o Diário Oficial da União (DOU) para consultar legislações, regulamentos e outras publicações que são fundamentais para sua pesquisa. Embora Thomas tenha um bom entendimento de português, ele ainda encontra dificuldades com termos técnicos e jurídicos, o que torna a leitura das publicações no DOU um desafio. Atualmente, o aplicativo do DOU não oferece suporte multilíngue, o que significa que todas as informações estão disponíveis apenas em português. Isso obriga Thomas a utilizar ferramentas de tradução externas que nem sempre são precisas, causando interpretações errôneas e atrasos em sua pesquisa. Thomas se sente frustrado porque essa barreira linguística está afetando a eficiência e a precisão de seu trabalho acadêmico. Em um dia específico, Thomas precisa consultar rapidamente uma legislação recente que impacta diretamente a linha de pesquisa de sua tese. Ao tentar entender o texto complexo em português e usar traduções automáticas, ele acaba confundido e inseguro sobre a interpretação correta da lei. Isso resulta em mais tempo gasto e a necessidade de pedir ajuda a colegas brasileiros, o que nem sempre é prático ou imediato. Thomas percebe que um suporte multilíngue no aplicativo do DOU, com traduções para inglês, seria extremamente benéfico. Isso permitiria a ele e a outros pesquisadores estrangeiros acessar as informações de maneira mais precisa e eficiente, melhorando a qualidade da pesquisa e economizando tempo.

A tabela 9 descreve o cenário que tem como objetivo suporte multilíngue para a plataforma.

<p style="text-align: center"><b>Tabela 9:</b> Suporte Multilíngue.</p>
<center>

| Elemento     | Descrição | Perguntas selecionadas |
|--------------|-----------|------------------------|
| Título       | Suporte Multilíngue para Facilitar o Acesso por Usuários Não-nativos | N/A |
| Objetivo     | Thomas deseja acessar facilmente as publicações do DOU em inglês para facilitar sua pesquisa acadêmica sobre políticas públicas brasileiras. | Por que os atores querem ou precisam alcançar esse objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ambiente     | O cenário ocorre na universidade e nos locais de estudo de Thomas, onde ele utiliza seu laptop e smartphone para acessar o DOU. | Em que situações o cenário ocorre? Quais são as tecnologias utilizadas no ambiente?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ator         | Thomas Müller, estudante de pós-graduação estrangeiro que pesquisa políticas públicas brasileiras. | (N/A) |
| Planejamento | Atualmente, Thomas utiliza ferramentas de tradução externas para entender as publicações do DOU, o que é impreciso e consome tempo. Gostaria de acessar o DOU diretamente em inglês. | Como os atores alcançam o objetivo atualmente? Como gostariam de fazê-lo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ação         | As precondições incluem ter acesso ao aplicativo do DOU e estar logado. Thomas tenta ler e entender as publicações em português, usando traduções automáticas para ajudá-lo. | Quais as precondições para essa ação? Como os atores as realizam? Quais problemas ou dificuldades podem surgir ao realizá-la?<a id="anchor_3" href="#FRM3">^3^</a> |
| Evento       | A necessidade de consultar uma legislação recente que impacta diretamente sua pesquisa acadêmica. | Quais eventos disparam a necessidade de alcançar o objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Avaliação    | Thomas saberá que atingiu seu objetivo quando conseguir acessar e entender as publicações do DOU em inglês sem a necessidade de ferramentas de tradução externas. | Como os atores conseguem saber se uma ação foi concluída e realizada com sucesso? Qual é o resultado do alcance do objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Arthur Alves.</p></font>

</center>

| Denominação     | Suporte Multilíngue |
|-----------------|---------------------|
| Objetivo/meta   | Permitir que usuários estrangeiros, como Thomas, acessem informações no DOU em inglês para melhorar a eficiência e a precisão na pesquisa. |
| Contexto        | **Contexto:** Thomas precisa consultar legislações e regulamentos no DOU em inglês. <br> **Local:** Na seção de publicações do DOU. <br> **Tempo:** A consulta pode levar de 10 a 20 minutos, dependendo da quantidade de informações a serem traduzidas. <br> **Pré-condição:** O usuário deve estar autenticado no sistema e ter o aplicativo configurado para o idioma desejado. |
| Atores          | Thomas Edson (Usuário Primário); <br> Sistema de Tradução (Usuário Secundário); <br> DOU (Usuário Secundário) |
| Recursos        | Aplicativo do DOU com suporte multilíngue; <br> Conexão à internet; <br> Banco de dados de traduções. |
| Episódios       | 1. Thomas faz login no aplicativo do DOU. <br> 2. Thomas acessa a seção de configurações de idioma. <br> 3. Thomas seleciona o idioma inglês. <br> 4. O sistema aplica a configuração e traduz as interfaces e publicações para o inglês. <br> 5. Thomas navega até a seção de publicações e consulta as legislações e regulamentos necessários. |
| Exceção         | 1. Se ocorrer um erro na tradução, uma mensagem de erro é exibida e Thomas é orientado a tentar novamente. <br> 2. Se houver um problema de conexão, uma mensagem de erro é exibida e Thomas é instruído a tentar novamente mais tarde. |
| Restrição       | 1. O sistema deve garantir que as traduções estejam atualizadas e precisas. <br> 2. As traduções devem estar de acordo com os termos jurídicos oficiais. <br> 3. A conexão à internet deve estar estável durante o processo de tradução. |


#### <a>Análise do Cenário</a>

- A dificuldade de entender termos técnicos e jurídicos em português.
- A necessidade de usar ferramentas de tradução externas, que nem sempre são precisas.
- A frustração e o tempo gasto devido à barreira linguística.
- A importância de um suporte multilíngue no aplicativo do DOU para melhorar a eficiência e precisão na pesquisa acadêmica.

### <a>C09 - Suporte Técnico com Tempo de Resposta de 24 Horas</a>

Atores: Kauan Barreto (Coordenador de Projetos Sociais)

Kauan Barreto é Coordenador de Projetos Sociais com pós-graduação em Serviço Social. Ele frequentemente utiliza o Diário Oficial da União (DOU) para acompanhar a publicação de editais, chamadas públicas e legislação relacionada a projetos sociais. Sua função envolve identificar oportunidades de financiamento e parcerias, além de se manter atualizado sobre políticas e programas governamentais relevantes. Recentemente, Kauan enfrentou um problema técnico ao tentar acessar um edital importante no aplicativo do DOU. O aplicativo não carregava a página correta, impedindo-o de visualizar as informações necessárias. Diante dessa situação, Kauan precisou de suporte técnico para resolver o problema rapidamente, já que o prazo para inscrição no edital estava se aproximando. O suporte técnico do DOU, no entanto, demorou vários dias para responder à solicitação de Kauan, causando grande frustração e ansiedade. Durante esse período, Kauan teve que encontrar soluções alternativas, como pedir ajuda a colegas e usar dispositivos diferentes, mas sem sucesso. O atraso na resposta do suporte técnico resultou em uma perda significativa de tempo e colocou em risco a participação de sua organização no edital. Kauan percebe que um suporte técnico com um tempo de resposta garantido de 24 horas é crucial para garantir que ele possa acessar as informações necessárias de forma eficiente e sem interrupções. Um suporte rápido e eficaz permitiria que ele solucionasse problemas técnicos rapidamente, garantindo a continuidade de seu trabalho e a competitividade de sua organização nos processos de seleção de projetos.

A tabela 10 descreve o cenário que tem como objetivo suporte técnico em até 24 horas.

<p style="text-align: center"><b>Tabela 10:</b> Suporte Técnico em até 24 horas.</p>
<center>


| Elemento     | Descrição | Perguntas selecionadas |
|--------------|-----------|------------------------|
| Título       | Suporte Técnico com Tempo de Resposta de 24 Horas | N/A |
| Objetivo     | Kauan deseja receber suporte técnico eficiente e com um tempo de resposta de 24 horas para resolver problemas de acesso ao DOU. | Por que os atores querem ou precisam alcançar esse objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ambiente     | O cenário ocorre no escritório de Kauan, onde ele utiliza um smartphone para acessar o DOU e acompanhar editais e legislações. | Em que situações o cenário ocorre? Quais são as tecnologias utilizadas no ambiente?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ator         | Kauan Barreto, Coordenador de Projetos Sociais, que precisa acessar editais e legislações no DOU para identificar oportunidades de financiamento e parcerias. | (N/A) |
| Planejamento | Atualmente, Kauan depende de um suporte técnico que demora dias para responder, causando atrasos. Ele gostaria de receber suporte técnico com um tempo de resposta de 24 horas. | Como os atores alcançam o objetivo atualmente? Como gostariam de fazê-lo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ação         | As precondições incluem ter acesso ao aplicativo do DOU e enfrentar um problema técnico. Kauan tenta resolver o problema, mas precisa do suporte técnico do DOU. | Quais as precondições para essa ação? Como os atores as realizam? Quais problemas ou dificuldades podem surgir ao realizá-la?<a id="anchor_3" href="#FRM3">^3^</a> |
| Evento       | A necessidade urgente de acessar um edital importante que não está carregando corretamente no aplicativo do DOU. | Quais eventos disparam a necessidade de alcançar o objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Avaliação    | Kauan saberá que atingiu seu objetivo quando conseguir acessar o suporte técnico e resolver problemas técnicos em até 24 horas, garantindo acesso contínuo às informações do DOU. | Como os atores conseguem saber se uma ação foi concluída e realizada com sucesso? Qual é o resultado do alcance do objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Arthur Alves.</p></font>

</center>

| Denominação     | Suporte Técnico com Tempo de Resposta de 24 Horas |
|-----------------|---------------------------------------------------|
| Objetivo/meta   | Garantir que Kauan receba suporte técnico eficiente e com um tempo de resposta de 24 horas para resolver problemas de acesso ao DOU. |
| Contexto        | **Contexto:** Kauan precisa acessar um edital importante no DOU. <br> **Local:** No menu de suporte técnico do aplicativo do DOU. <br> **Tempo:** O tempo de resposta deve ser de até 24 horas. <br> **Pré-condição:** Kauan deve estar autenticado no sistema e ter acesso ao menu de suporte técnico. |
| Atores          | Kauan Barreto (Usuário Primário); <br> Suporte Técnico (Usuário Secundário); <br> Sistema do DOU (Usuário Secundário) |
| Recursos        | Aplicativo do DOU; <br> Conexão à internet; <br> Equipe de suporte técnico. |
| Episódios       | 1. Kauan faz login no aplicativo do DOU. <br> 2. Kauan acessa o menu de suporte técnico. <br> 3. Kauan descreve o problema e envia uma solicitação de suporte. <br> 4. O sistema registra a solicitação e encaminha para a equipe de suporte técnico. <br> 5. A equipe de suporte técnico analisa e responde à solicitação em até 24 horas. <br> 6. Kauan recebe a resposta e verifica se o problema foi resolvido. |
| Exceção         | 1. Se o suporte técnico não conseguir resolver o problema em 24 horas, Kauan é notificado sobre o atraso e recebe uma previsão de tempo para a solução. |
| Restrição       | 1. O suporte técnico deve estar disponível 24/7. <br> 2. O sistema deve garantir que as solicitações sejam encaminhadas imediatamente após serem enviadas. <br> 3. A conexão à internet deve estar estável durante o processo de solicitação. |


#### <a>Análise do Cenário</a>

- A dificuldade de acessar informações importantes devido a problemas técnicos.
- A demora na resposta do suporte técnico, causando frustração e ansiedade.
- A perda de tempo e o risco de perder prazos importantes.
- A importância de um suporte técnico com tempo de resposta de 24 horas para garantir a continuidade e eficiência do trabalho.

## <a>Referência Bibliográfica</a>

> <a id="FRM1" href="#anchor_1">1.</a> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, capítulo 6, tópico 6.3.5 Design Baseado em Cenários, página 122, G. D. J. (2021) *Interação Humano-Computador e Experiência do usuário.* Autopublicação. ISBN: 978-65-00-19677-1.

> <a id="FRM2" href="#anchor_2">2.</a> Bergmann, Ulf. Evolução de Cenários Através de um Mecanismo de Rastreamento Baseado em Transformações. Capítulo 3.1 Modelo de Cenário, p.47. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>.

> <a id="FRM3" href="#anchor_3">3.</a> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021). *Interação Humano-Computador e Experiência do Usuário*. Autopublicação. Capítulo 8, Tópico 8.3 Cenários, p. 175. ISBN: 978-65-00-19677-1. Inclui Tabela 8.3: Perguntas utilizadas para refinar cada elemento de um cenário ou auxiliar a análise.


## <a>Bibliografia</a>

> Requisitos de Software. Carteira Digital de Trânsito, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.2-Carteira_Digital_de_Transito/modelagem/cenarios/>. Acesso em: 14 de maio de 2024 às 23:41.

> Requisitos de Software. Bilheteria Digital, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/>. Acesso em: 14 de maio de 2024 às 23:50.

> Bergmann, Ulf. Evolução de Cenários Através de um Mecanismo de
Rastreamento Baseado em Transformações. Rio de Janeiro - RJ, 2003.
224p. Tese de Doutorado - Departamento de Informática, Pontifícia
Universidade Católica do Rio de Janeiro. Disponível em: <https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>.

> <a id="FRM2" href="#anchor_2">2.</a> Bergmann, Ulf. Evolução de Cenários Através de um Mecanismo de Rastreamento Baseado em Transformações. Capítulo 3.1 Modelo de Cenário, p.47. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>.

## Histórico de versão
|Versão|Data|Data Prevista de Revisão|Descrição|Autor|Revisor|
| :------: | :----------: |:-----------: | :----------------------: | :---------: |:---------: |
| `1.0` | 15/05/2024 | 19/05/2024 |Criação da Documentação de Cenários | [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky) | Douglas Marinho, João Artur, Henrique Torres e Luiz Gustavo |