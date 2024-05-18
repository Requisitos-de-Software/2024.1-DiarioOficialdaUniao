## O que é um cenário?

O cenário reclaciona a interação dos usuários com o sistema, de forma detalhada sobre a execução de uma atividade do software. Assim, a abordagem de **Design Baseado em Cenários** é um processo que utiliza diferentes tipos de cenários como representação básica e fundamental durante todas as atividades envolvidas na concepção de uma solução de IHC (Rosson e Carroll, 2002; Carroll, 1995)<a id="anchor_1" href="#FRM1">^1^</a>.

## Por que utilizar Design Baseado em Cenários?

De acordo com o livro "Interação Humano-Computador e Experiência do usuário", a equipe de design (incluindo representantes dos usuários) tem a oportunidade de discutir e analisar como as atividades dos usuários são afetadas pela tecnologia existente e como elas poderiam ser afetadas pelo sistema sendo desenvolvido, a partir do **Design Baseado em Cenários**. Desse modo, cenários são uma ferramenta útil e barata para gerar e avaliar diversas ideias durante as atividades de design<a id="anchor_1" href="#FRM1">^1^</a>.

## Modelo de Cenário

De acordo com Weidenhaupt, em seu estudo sobre o uso de cenários no desenvolvimento de software, foram identificados cinco formas para a descrição de cenários, sendo elas: texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações<a id="anchor_2" href="#FRM2">^2^</a>.
Uma das formas mais utilizadas é a de **texto estruturado** e devido a essa razão, por questões de mais acessibilidade a materiais base, adotamos o mesmo modelo.
Segundo a tese "Evolução de Cenários Através de um Mecanismo de
Rastreamento Baseado em Transformações", essa notação utiliza uma linguagem natural semi-estruturada (ancorada no mundo real), partindo da premissa que a utilização da linguagem da aplicação e não do software facilita o entendimento e a validação dos requisitos por parte dos clientes<a id="anchor_2" href="#FRM2">^2^</a>.

Em geral, cada cenário apresenta um ator principal e um objetivo principal. Tal objetivo pode ser desdobrado em subobjetivos, numa atividade de planejamento que se passa na cabeça dos atores. Quando essa atividade mental for importante para uma situação, o cenário pode incluir informações sobre planejamento e avaliação das ações realizadas. Cada cenário costuma ter um título que descreve brevemente a situação, sem muitos detalhes; os atores que participam do cenário; uma breve descrição da situação inicial em que os atores se encontram; e referências a outros cenários que permitam aos atores atingir os mesmos objetivos de diferentes maneiras<a id="anchor_3" href="#FRM3">^3^</a>.

Neste projeto, detalhamos os cenários utilizando descrições textuais estruturadas e complementamos com especificações detalhadas dos elementos característicos de cada cenário em tabelas e cada elemento conta com "Perguntas utilizadas para refinar cada elemento de um cenário ou auxiliar a análise."<a id="anchor_3" href="#FRM3">^3^</a>. Para uma visão mais aprofundada sobre os elementos característicos de cada cenário, consulte a Tabela 1.

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

## Cenários identificados

### C01 - Efetuar a leitura de uma publicação
Atores: Usuário do aplicativo Diário Oficial da União

O usuário do aplicativo Diário Oficial da União utiliza o aplicativo em seu dispositivo móvel com o objetivo de ler publicações oficiais relevantes para se manter informado sobre mudanças legislativas e administrativas. A leitura dessas publicações requer a manipulação de dados, como a aplicação de filtros específicos, para acessar informações pertinentes. Este processo acontece em locais que proporcionem uma boa conexão à internet, como residências ou escritórios, onde o usuário pode se concentrar na leitura. A ação de ler envolve abrir o aplicativo, navegar até a seção desejada e selecionar a publicação. O aplicativo oferece ajustes como modificação do tamanho da fonte e contraste para facilitar a leitura, especialmente úteis para usuários com necessidades especiais de acessibilidade. Eventualmente, o usuário pode enfrentar interrupções se houver falhas no aplicativo ou problemas de conexão, o que pode impedir o acesso às publicações. Após a leitura, o usuário verifica se as informações acessadas são relevantes e se as configurações visuais proporcionaram uma leitura confortável. O sucesso desta atividade é medido pela facilidade de acesso à informação relevante e pela qualidade da experiência de leitura no aplicativo. A configuração eficaz das preferências de leitura permite ao usuário otimizar o uso do aplicativo para atender às suas necessidades informativas específicas.

A tabela 2 descreve o cenário que tem como objetivo efetuar a leitura de uma publicação.

<p style="text-align: center"><b>Tabela 2:</b> Leitura de uma publicação.</p>
<center>

| Elemento    | Descrição                                                                                                                                                                                 | Perguntas selecionadas |
|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------|
| Título      | Efetuar a leitura de uma publicação no aplicativo Diário Oficial da União                                                                                                                 | N/A                    |
| Objetivo    | Os atores querem efetuar a leitura de publicações no aplicativo para se manterem atualizados sobre normativas e informações oficiais relevantes, o que requer a manipulação de dados como a escolha de filtros específicos para a leitura. Esta ação está relacionada ao objetivo de manter-se informado sobre mudanças legislativas ou informativas que afetem suas áreas de interesse. | Por que os atores querem ou precisam alcançar esse objetivo? Quais informações são criadas, consumidas, manipuladas ou destruídas pelo alcance do objetivo? Que outros objetivos estão relacionados a esse?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ambiente    | O cenário ocorre em qualquer local onde o usuário tenha acesso a uma conexão de internet segura, geralmente em ambientes que proporcionam tranquilidade para leitura, como escritórios ou residências. A necessidade de acesso rápido e eficiente às informações e a dependência de dispositivos móveis e acesso à internet são pressões comuns neste contexto. | Em que situações o cenário ocorre? Quais pressões existem para o alcance do objetivo? Quais são as tecnologias utilizadas no ambiente? Como os usuários as utilizam?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ator        | Diana Sousa, graduanda em Psicologia e bolsista de pesquisa pela UnB, que utiliza o aplicativo para acessar publicações oficiais relevantes para sua pesquisa acadêmica e prática profissional. | N/A |
| Planejamento | Diana costuma acessar o aplicativo durante suas horas de estudo e pesquisa, selecionando publicações de acordo com sua área de estudo. Ela planeja suas sessões de leitura para coincidir com atualizações de conteúdo relevantes, decidindo sobre quais publicações acessar com base em resumos ou alertas oferecidos pelo aplicativo. Decisões inadequadas podem resultar em perda de tempo com conteúdo não pertinente. | Como os atores alcançam o objetivo atualmente? Como gostariam de fazê-lo? Que decisões os atores precisam tomar a cada momento? De que maneira o ambiente e o sistema auxiliam ou impedem que os atores tomem decisões adequadas? Quais as consequências de uma decisão errada?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ação        | Diana inicia o aplicativo, utiliza as opções de filtragem para selecionar publicações de seu interesse, e lê os documentos diretamente no seu dispositivo móvel. O aplicativo permite ajustar o formato de visualização para melhorar a experiência de leitura, como modificar o tamanho da fonte ou o contraste. Erros na configuração podem ser corrigidos através de ajustes nas configurações, mas podem temporariamente dificultar a leitura. | Quais as precondições para essa ação? Como os atores as realizam? Os atores gostariam de fazer isso de outra maneira? Como o fariam? De que informações ou conhecimento os atores precisam para realizar essa ação? Que recursos estão disponíveis para realizá-la? Quais erros podem ser cometidos ao realizá-la? Como podem ser desfeitos? Quais suas consequências? Quais informações são criadas, consumidas, manipuladas ou destruídas pela realização da ação?<a id="anchor_3" href="#FRM3">^3^</a> |
| Evento       | Diana recebe notificações do aplicativo quando novas publicações que correspondem aos seus filtros são disponibilizadas. Essas notificações são configuradas para garantir que ela não perca conteúdo relevante. | Quais eventos disparam a necessidade de alcançar o objetivo? Quais eventos são disparados pela conclusão desse objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Avaliação    | Diana avalia a eficácia das ações realizadas verificando se as publicações acessadas são relevantes e se as configurações de visualização permitem uma leitura confortável. O sucesso é determinado pela capacidade de acessar rapidamente as informações necessárias e pela facilidade de leitura das publicações. | Como os atores conseguem saber se uma ação foi concluída e realizada com sucesso? Qual é o resultado do alcance do objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |



</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> Eric Silveira e Arthur Alves.</p></font>

#### Análise de Cenário
A análise do cenário de leitura de publicações no aplicativo Diário Oficial da União revela aspectos que podem afetar negativamente a experiência do usuário e que são importantes para considerar em futuras melhorias da interação humano-computador (IHC):

- O processo para filtrar e selecionar as publicações desejadas pode ser complexo e não intuitivo, especialmente para novos usuários ou aqueles com necessidades especiais de acessibilidade. Isso pode levar a uma experiência frustrante e ao consumo de tempo desnecessário.

### C02 - Receber notificações gerais
Atores: Usuário do aplicativo Diário Oficial da União

O usuário do aplicativo Diário Oficial da União utiliza o aplicativo em seu dispositivo móvel com o objetivo de manter-se atualizado sobre as notificações gerais emitidas pela plataforma. Para isso, o usuário precisa configurar suas preferências de notificação de acordo com suas necessidades específicas. Este processo ocorre em qualquer local que tenha acesso à internet, onde o usuário acessa o menu de configurações e ajusta as notificações para receber apenas as informações desejadas. As configurações incluem ativar ou desativar notificações gerais, e personalizar alertas para edições extras ou específicas, garantindo que apenas o conteúdo relevante seja entregue. O usuário pode enfrentar desafios se o aplicativo não carregar corretamente ou se houver falhas de conexão, o que pode impedir o recebimento de notificações. Ao concluir as configurações, o usuário avalia se as notificações recebidas estão conforme o esperado, o que valida o sucesso das ações realizadas. Esta configuração personalizada permite ao usuário otimizar a forma como recebe atualizações importantes, adaptando a experiência do aplicativo para melhor atender às suas necessidades de informação.


A tabela 3 descreve o cenário que tem como objetivo receber notificações gerais.

<p style="text-align: center"><b>Tabela 3:</b> Notificações gerais.</p>
<center>

| Elemento     | Descrição | Perguntas selecionadas |
|--------------|-----------|------------------------|
| Título       | Receber notificações gerais | N/A |
| Objetivo     | Receber notificações gerais da plataforma Diário Oficial da União utilizando o aplicativo correspondente. Este objetivo está relacionado à necessidade de manter o usuário informado sobre atualizações relevantes sem que ele precise buscar ativamente essas informações no aplicativo. | Por que os atores querem ou precisam alcançar esse objetivo? Quais informações são criadas, consumidas, manipuladas ou destruídas pelo alcance do objetivo? Que outros objetivos estão relacionados a esse?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ambiente     | O cenário ocorre sempre que há atualizações ou informações novas que precisam ser comunicadas ao usuário. O ambiente envolve o uso cotidiano do aplicativo em diversos contextos, dependendo da conectividade e disponibilidade do usuário para interagir com o aplicativo. | Em que situações o cenário ocorre? Quais pressões existem para o alcance do objetivo? Quais são as tecnologias utilizadas no ambiente? Como os usuários as utilizam?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ator         | Usuário do aplicativo Diário Oficial da União, que depende das notificações para se manter atualizado sem a necessidade de acessar o aplicativo constantemente. | N/A |
| Planejamento | O usuário configura suas preferências de notificação no aplicativo para garantir que receba apenas as informações relevantes. Este planejamento é crucial para a personalização da experiência do usuário e para garantir que as notificações sejam úteis e não intrusivas. | Como os atores alcançam o objetivo atualmente? Como gostariam de fazê-lo? Que decisões os atores precisam tomar a cada momento? De que maneira o ambiente e o sistema auxiliam ou impedem que os atores tomem decisões adequadas? Quais as consequências de uma decisão errada? Que ações realizam? Como essas ações estão relacionadas? Em que ordem os atores precisam realizar as ações? Gostariam de realizá-las em outra ordem?<a id="anchor_3" href="#FRM3">^3^</a> |
| Ação         | O usuário acessa o menu de configurações do aplicativo para ajustar suas preferências de notificação. Este processo envolve selecionar os tipos de notificação que deseja receber e personalizar outros aspectos, como som ou vibração. | Quais as precondições para essa ação? Como os atores as realizam? Os atores gostariam de fazer isso de outra maneira? Como o fariam? De que informações ou conhecimento os atores precisam para realizar essa ação? Que recursos estão disponíveis para realizá-la? Quais erros podem ser cometidos ao realizá-la? Como podem ser desfeitos? Quais suas consequências? Quais informações são criadas, consumidas, manipuladas ou destruídas pela realização da ação?<a id="anchor_3" href="#FRM3">^3^</a> |
| Evento       | A chegada de novas informações ou atualizações dentro da plataforma dispara a necessidade de notificar o usuário, conforme suas configurações personalizadas. A conclusão bem-sucedida das configurações resulta no recebimento adequado e tempestivo das notificações. | Quais eventos disparam a necessidade de alcançar o objetivo? Quais eventos são disparados pela conclusão desse objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |
| Avaliação    | O usuário verifica se as notificações recebidas correspondem às suas configurações e se as informações são entregues de maneira oportuna e relevante. A satisfação do usuário com as notificações recebidas indica o sucesso do cenário. | Como os atores conseguem saber se uma ação foi concluída e realizada com sucesso? Qual é o resultado do alcance do objetivo?<a id="anchor_3" href="#FRM3">^3^</a> |


</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> Eric Silveira e Arthur Alves.</p></font>

#### Análise do Cenário
A análise do cenário de recebimento de notificações gerais no aplicativo Diário Oficial da União destaca várias questões que podem impactar negativamente a experiência do usuário e que deveriam ser abordadas para melhorar a interação humano-computador (IHC):

- As configurações e o recebimento de notificações dependem de uma conexão contínua e estável com a internet. Interrupções na conectividade podem não apenas impedir o acesso ao processo de configuração, mas também afetar a recepção de notificações importantes, limitando a utilidade do aplicativo em condições de conectividade precária.


### C03 - Configurar o aplicativo

Atores: Diana Sousa (graduanda em Psicologia e bolsista de pesquisa pela UnB)

Diana Sousa, ao utilizar o aplicativo Diário Oficial da União em seu dispositivo móvel, sente a necessidade de ajustar as configurações para atender às suas necessidades específicas, incluindo melhor acessibilidade e personalização de conteúdo. Ela busca principalmente ajustar o contraste e ativar o suporte para tecnologia assistiva, como o talkback, além de configurar notificações e filtros para receber apenas informações relevantes dos órgãos de seu interesse. Diana acessa o menu de configurações do aplicativo, onde enfrenta um processo não muito intuitivo que envolve várias etapas para cada ajuste desejado. Ela ajusta o contraste para facilitar a leitura, ativa o talkback para auxílio na navegação, e configura as notificações para receber alertas apenas de novas edições que incluem tópicos específicos de sua área de estudo. Cada ação requer que ela navegue por diferentes submenus, o que torna o processo tedioso e susceptível a erros. Ao final das configurações, Diana verifica se as alterações foram aplicadas corretamente revisitando cada opção ajustada. A experiência deixa claro que, embora possível, a configuração é mais complexa e demorada do que o necessário, indicando uma área de melhoria para uma interface mais simplificada e eficiente.


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

#### Análise do Cenário
A análise do cenário proposto para a configuração do aplicativo Diário Oficial da União revela pontos que podem ser problemáticos e que devem ser considerados para um eventual redesenho da interação humano-computador (IHC):

- O cenário atual não especifica claramente como os usuários recebem feedback sobre a eficácia das configurações que eles ajustam. Por exemplo, após ajustar as notificações ou filtros, não está claro como ou quando os usuários são notificados de que suas ações foram bem-sucedidas. A falta de feedback imediato pode deixar os usuários incertos sobre se suas ações tiveram o efeito desejado, o que pode levar a repetições desnecessárias e frustração.



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