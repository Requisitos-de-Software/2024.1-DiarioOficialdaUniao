## O que é um cenário?

O cenário reclaciona a interação dos usuários com o sistema, de forma detalhada sobre a execução de uma atividade do software. Assim, a abordagem de **Design Baseado em Cenários** é um processo que utiliza diferentes tipos de cenários como representação básica e fundamental durante todas as atividades envolvidas na concepção de uma solução de IHC (Rosson e Carroll, 2002; Carroll, 1995)<a id="anchor_1" href="#FRM1">^1^</a>.

## Por que utilizar Design Baseado em Cenários

De acordo com o livro "Interação Humano-Computador e Experiência do usuário", a equipe de design (incluindo representantes dos usuários) tem a oportunidade de discutir e analisar como as atividades dos usuários são afetadas pela tecnologia existente e como elas poderiam ser afetadas pelo sistema sendo desenvolvido, a partir do **Design Baseado em Cenários**. Desse modo, cenários são uma ferramenta útil e barata para gerar e avaliar diversas ideias durante as atividades de design<a id="anchor_1" href="#FRM1">^1^</a>.

## Modelo de Cenário

De acordo com Weidenhaupt, em seu estudo sobre o uso de cenários no desenvolvimento de software, foram identificados cinco formas para a descrição de cenários, sendo elas: texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações.
Uma das formas mais utilizadas é a de **texto estruturado** e devido a essa razão, por questões de mais acessibilidade a materiais base, adotamos o mesmo modelo<a id="anchor_2" href="#FRM2">^2^</a>.
Segundo a tese "Evolução de Cenários Através de um Mecanismo de
Rastreamento Baseado em Transformações", essa notação utiliza uma linguagem natural semi-estruturada (ancorada no mundo real), partindo da premissa que a utilização da linguagem da aplicação e não do software facilita o entendimento e a validação dos requisitos por parte dos clientes<a id="anchor_2" href="#FRM2">^2^</a>.


As estrutura do modelo do cenário e suas especificações sobre cada tópico estão na tabela a seguir:

<p style="text-align: center"><b>Tabela 1:</b> Descrição do modelo texto estruturado.</p>

|Elemento|Descricação|
|-----------|---------------|
|Título (title)| identifica o cenário.|
|Objetivo (goal)| estabelece a finalidade de um cenário. O cenário deve descrever de que modo este objetivo deve ser alcançado.|
|Contexto (context)| descreve o estado inicial de um cenário, suas précondições, o local (físico) e tempo. Na sua definição podem ser especificadas restrições sobre estes elementos (constraint).|
|Recurso (resource)| identifica os objetos passivos com os quais lidam os atores. Na sua definição podem ser especificadas restrições sobre os objetos a serem lidados pelo cenário (constraint)|
|Ator (actor)| Pessoa ou estrutura organizacional que tem um papel no cenário.|
|Episódio (episode)| Cada episódio representa uma ação realizada por um ator onde participam outros atores utilizando recursos disponíveis. Um episódio também pode se referir a outro cenário. Episódios podem conter restrições (constraint) e exceções (exception). Uma restrição é 50 qualquer imposição que restrinja um episódio de um cenário. Uma exceção é o tratamento para uma situação excepcional ou de erro.|

<font size="3"><p style="text-align: center"><b>Fonte:</b> Evolução de Cenários Através de um Mecanismo de Rastreamento Baseado em Transformações.</p></font>

<br>
Na figura 1, temos um exemplo de utilização da notação para a descrição de um cenário para um sistema de controle de luzes.


<font size="3"><p style="text-align: center"><b>Figura 1:</b> Exemplo de descrição de um cenário.</p></font>

<p align="center">
  <img src="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/assets/ModeloTextoEstruturado.png?raw=true" alt="Modelo" />
</p>

<font size="3"><p style="text-align: center"><b>Fonte:</b> SERRANO, Milene. SERRANO, Mauricio. Requisitos – Aula 10.</p></font>

## Cenários identificados

### C01 - Efetuar a leitura de uma publicação
A tabela 2 descreve o cenário que tem como objetivo efetuar a leitura de uma publicação.

<p style="text-align: center"><b>Tabela 2:</b> Leitura de uma publicação.</p>
<center>

| Elemento| Descrição|
|------------|-----------------|
| Título | Efetuar a leitura de uma publicação  |
| Objetivo   | Efetuar a leitura de uma publicação no aplicativo Diário Oficial da União|
| Contexto   | Pré-condição: Ter o aplicativo instalado e estar conectado à internet <br> Local: Em qualquer lugar com acesso ao aplicativo <br> Tempo: Variável dependendo do tamanho da publicação 
| Recursos   | Celular ou dispositivo móvel<br> Aplicativo do Diário Oficial da União<br> Acesso a internet |
| Ator   | Usuário |
| Episódios  | Usuário abre o aplicativo Diário Oficial da União<br> Usuário navega até a a opção "Meu Diário", ou seleciona alguma seção que contém as publicações desejadas<br> Usuário seleciona a publicação desejada <br> Usuário faz a leitura da publicação  |
| Restrições | Conexão com a internet para acessar o aplicativo |
| Exceção| Aplicativo não carrega ou apresenta falhas<br> Publicação não disponível no momento |

</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> Eric Silveira.</p></font>

### C02 - Receber notificações gerais
A tabela 3 descreve o cenário que tem como objetivo receber notificações gerais.

<p style="text-align: center"><b>Tabela 3:</b> Notificações gerais.</p>
<center>

| Elemento| Descrição |
|------------|--------------|
| Título  | Receber notificações gerais|
| Objetivo| Receber notificações gerais da plataforma Diário Oficial da União utilizando o aplicativo correspondente|
| Contexto| Pré-condição: Ter o aplicativo da plataforma Diário Oficial da União instalado<br> Local: Em qualquer lugar com acesso ao aplicativo  <br> Tempo: Variado, podendo ocorrer a qualquer momento  |
| Recursos| Celular ou dispositivo móvel <br> Aplicativo da plataforma Diário Oficial da União  <br> Internet|
| Ator | Usuário|
| Episódios  | Usuário abre o aplicativo da plataforma Diário Oficial da União  <br> Usuário navega até a seção de configurações/notificações<br> Usuário configura as preferências de notificações  <br> Usuário recebe notificações gerais da plataforma Diário Oficial da União |
| Restrições | Conexão com a internet para acessar o aplicativo  |
| Exceção | Aplicativo não carrega ou apresenta falhas  <br> Notificações não estão disponíveis no momento <br>Não há atualizações no aplicativo para que o usuário seja notificado|

</center>

<font size="3"><p style="text-align: center"><b>Fonte:</b> Eric Silveira.</p></font>


### C03 - Configurar o aplicativo

Atores: Diana Sousa (graduanda em Psicologia e bolsista de pesquisa pela UnB)

Diana Sousa, ao utilizar o aplicativo Diário Oficial da União em seu dispositivo móvel, sente a necessidade de ajustar as configurações para atender às suas necessidades específicas, incluindo melhor acessibilidade e personalização de conteúdo. Ela busca principalmente ajustar o contraste e ativar o suporte para tecnologia assistiva, como o talkback, além de configurar notificações e filtros para receber apenas informações relevantes dos órgãos de seu interesse. Diana acessa o menu de configurações do aplicativo, onde enfrenta um processo não muito intuitivo que envolve várias etapas para cada ajuste desejado. Ela ajusta o contraste para facilitar a leitura, ativa o talkback para auxílio na navegação, e configura as notificações para receber alertas apenas de novas edições que incluem tópicos específicos de sua área de estudo. Cada ação requer que ela navegue por diferentes submenus, o que torna o processo tedioso e susceptível a erros. Ao final das configurações, Diana verifica se as alterações foram aplicadas corretamente revisitando cada opção ajustada. A experiência deixa claro que, embora possível, a configuração é mais complexa e demorada do que o necessário, indicando uma área de melhoria para uma interface mais simplificada e eficiente.


A tabela 3 descreve o cenário que tem como objetivo configurar o aplicativo.

<p style="text-align: center"><b>Tabela 3:</b> Configurar aplicativo.</p>
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