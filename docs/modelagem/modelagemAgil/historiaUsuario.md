# Histórias de Usuário

## <a> Introdução </a>

De acordo PRESSMAN e MAXIM(2016)<a id="anchor_1" href="#REF1">^1^</a>, uma história de usuário é descrita como um elemento que descreve os resultados, características e funcionalidades que os usuários finais esperam do software a ser desenvolvido.

Em seu livro, PRESSMAN e MAXIM(2016)<a id="anchor_1" href="#REF1">^1^</a> também definem que a elaboração de uma história do usuário envolve o ato de escutar relatos do cliente que detalham as funcionalidades, características e resultados esperados do software. O cliente, por sua vez, atribui um valor de prioridade a cada história, baseando-se na importância relativa da funcionalidade para o negócio. Posteriormente, os membros da equipe avaliam cada história e determinam o custo associado, expresso em semanas de desenvolvimento, proporcionando uma base para a alocação de recursos e planejamento.

## <a> Metodologia </a>
Template das histórias de usuário na tabela 1.

<center>

<font size="3">Tabela 1:Template de tabela para histórias de usuário.</font>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| USXX                   | Titulo                                  |
| Descrição              | _Eu, como um_ [tipo usuário],<br> _quero_ [compromisso com as tarefas], <br> _para que eu possa_ [objetivo a ser alcançado].|
| Critérios de Aceitação | -XXX <br> -XXX <br>                     |
| Prioridade             | Baixa, Média ou Alta               |

<font size="3">Fonte: [Diego Sousa](https://github.com/DiegoSousaLeite).</font>

</center>

## <a> Histórias de Usuário </a>

<center>

<font size="3">Tabela 1:Template de tabela para histórias de usuário.</font>

| **ID**  | **Descrição** | **Critérios de Aceitação** |**Valor de negócio**|**Prioridade (Three level)**|
|---------| ------------- |----------------------------|--------------------|----------------------------|
| US01         |Eu, como usuário,  gostaria que o sistema ajuste automaticamente a data de término para a data atual quando eu inserir apenas a data de início no filtro de pesquisas de diários, afim de que eu possa visualizar todos os documentos relevantes até a data de hoje sem precisar inserir manualmente a data de término|<a>1</a> - Caso apenas a data de início seja inserida pelo usuário, o sistema deve automaticamente ajustar a data de término para a data atual e assim, garantir que a mesma esteja sempre atualizada no dia atual.<br><a>2</a> - O sistema deve garantir que o filtro aplicado retornará corretamente os diários publicados daquele período determinado.|???????|??????|
| US02         |Eu, como usuário,  gostaria que o sistema tivesse uma limitação de diários exibidos no resultado de pesquisa por página, afim de que eu possa navegar pelos resultados de forma mais intuitiva e organizada, evitando a sobrecarga visual causada pela atualização constante ao rolar a página.|<a>1</a> - O resultado de pesquisas deve ser separado por páginas.<br><a>2</a> - A limitação de exibição dos diários deve ser de 30 diários por página.<br><a>3</a> - O resultado de busca deve garantir que todos os diários que se enquadram na aplicação do filtro, ou sem filtros também, sejam exibidos, limitados nas páginas corretamente.|???????|??????|
| US03         |Eu, como usuário,  gostaria que o sistema tivesse uma limitação de diários exibidos na guia **Meu Diário** por página, afim de que eu possa navegar pelos resultados de forma mais intuitiva e organizada, evitando a sobrecarga visual causada pela atualização constante ao rolar a página.|<a>1</a> - A guia **Meu Diário**  deve ser separado por páginas.<br><a>2</a> - A limitação de exibição dos diários deve ser de 30 diários por página.<br><a>3</a> - O resultado de busca deve garantir que todos os diários que se enquadram na aplicação do filtro, ou sem filtros também, sejam exibidos, limitados nas páginas corretamente.<br><a>4</a> - A guia deve mostrar a exibição dos números de diários encontrados por página, com o texto centralizado e padronizado como nas outras guias, no seguinte formato: [numero] resultados encontrados.|???????|??????|
| US04         |Eu, como usuário,  gostaria que o sistema tivesse uma configuração por limitação de datas, na guia **Meu Diário**, afim de que eu possa filtras meus resultados nessa página por diferentes períodos.|<a>1</a> - O sistema deve garantir que só apareça como opção, datas válidas.<br><a>2</a> - O sistema deve permitir que o usuário escolha datas de início e término, mas não deve exigir que ambas sejam preenchidas obrigatoriamente.<br><a>3</a> - Caso apenas a data de início seja inserida pelo usuário, o sistema deve automaticamente ajustar a data de término para a data atual e assim, garantir que a mesma esteja sempre atualizada no dia atual.|???????|??????|

<font size="3">Fonte: Autores.</font>

</center>


## <a> Gravação da Reunião </a>

## <a>Referência Bibliográfica</a>
> <a id="REF1" href="#anchor_1">1.</a> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016.

## <a>Bibliografia</a>

> Histórias de Usuário Bilheteria Digital. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/>. Acesso em 21 de maio de 2024.

> Histórias de Usuário Lichess. Disponível em: <https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/us/>. Acesso em 21 de maio de 2024.
>
> EBY, Kate. Baixe modelos de história de usuário gratuitos. Smartsheet, 22 ago. 2018. Disponível em: <https://pt.smartsheet.com/user-story-templates>. Acesso em: 24 maio 2024.

## <a> Histórico de Versão </a>

| Versão | Data | Data Prevista de Revisão | Descrição | Autor | Revisor |
| :------: | :----------: | :-----------: | :-----------: | :---------: | :---------: |
| `1.0` | 21/05/2024 | 22/05/2024 | Criação do documento sobre histórias de usuário | [João Artur](https://github.com/joao-artl) | [Diego Sousa](https://github.com/DiegoSousaLeite) e [Douglas Marinho](https://github.com/M4RINH0) |
| `1.1` | 24/05/2024 | 24/05/2024 | Adição de template | [Diego Sousa](https://github.com/DiegoSousaLeite) | [João Artur](https://github.com/joao-artl) e [Douglas Marinho](https://github.com/M4RINH0) |