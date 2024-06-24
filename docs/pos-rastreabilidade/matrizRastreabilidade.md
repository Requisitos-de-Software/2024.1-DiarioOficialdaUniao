## <a>Introdução</a>

A rastreabilidade de requisitos é uma técnica fundamental no processo de desenvolvimento de software, permitindo a conexão entre os requisitos e os artefatos gerados ao longo do ciclo de vida do projeto. A rastreabilidade assegura que cada requisito seja devidamente implementado e verificado, facilitando a identificação de dependências e impactos de mudanças, além de proporcionar uma visão clara do progresso e da conformidade do projeto<a id="anchor_1" href="#REF1">^1^</a>.

## <a>Metodologia</a>

Existem diversas abordagens para implementar a rastreabilidade, sendo as mais comuns centradas em referências cruzadas ou documentos. Referências cruzadas são simples e eficientes, utilizando hipertexto, esquemas de numeração, indexação e uso de tags. Já as técnicas baseadas em documentos envolvem o uso de modelos e templates para transformar e integrar documentos de forma coesa<a id="anchor_2" href="#REF2">^2^</a>. Iremos utilizar para desenvolver a matriz de rastreabilidade o uso de referência cruzada, através de uma tabela para representação. A seguir na figura 01 temos um exemplo de matriz de rastreabilidade: 

<center>
Figura 01: Exemplo de Matriz de Rastreabilidade.

![Exemplo de Matriz de Rastreabilidade](https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/pos-rastreabilidade/assets/exemploMatriz.png?raw=True)

<font size="3"><p style="text-align: center"><b>Fonte:</b> Requisitos – Aula 26. Página 29<a id="anchor_3" href="#REF3">^3^</a>.</p></font>
</center>

## <a>Matriz de Rastreabilidade</a>

A matriz de rastreabilidade é uma ferramenta essencial em projetos de software, permitindo rastrear a origem e a implementação dos requisitos ao longo do ciclo de vida do projeto. Ela ajuda a garantir que todos os requisitos sejam atendidos e que as mudanças possam ser gerenciadas de forma eficaz. A seguir, a Tabela 01 mostra a matriz de rastreabilidade do projeto<a id="anchor_2" href="#REF2">^2^</a>.

<center>
Tabela 01: Matriz de Rastreabilidade do Projeto

|**Requisito**|**Descrição**|**Elicitação**|
|--------------|-------------|--------------|
|RF01| Autenticação de usuários para acesso seguro.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS01)|
|RF02| Visualização de edições diárias do Diário Oficial.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS02)|
|RF03| Busca por palavras-chave em documentos.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS03)|
|RF04| Filtragem de conteúdo por data, categoria ou órgão emissor.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS04)|
|RF05| Download de edições e documentos em formatos PDF.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS05)|
|RF06| Notificações push sobre novas publicações relevantes.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS06)|
|RF07| Acesso a edições anteriores arquivadas.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS07)|
|RF08| Integração com sistemas de assinatura digital.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS08)|
|RF09| Compartilhamento de documentos via redes sociais e email.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS09)|
|RF10| O aplicativo deve permitir buscas detalhadas por tópicos específicos.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS01)|
|RF11| O aplicativo deve oferecer a funcionalidade de salvar documentos para consulta offline.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS02)|
|RF12| O aplicativo deve enviar notificações personalizadas sobre novas publicações relevantes.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS03)|
|RF13| O aplicativo deve oferecer acesso ao histórico de publicações legislativas.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS04)|
|RF14| O aplicativo deve ter um sistema de marcadores para rastrear alterações em documentos específicos.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS05)|
|RF15| O aplicativo deve fornecer uma interface que facilite a leitura de textos legislativos.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS06)|
|RF16| O aplicativo deve incluir uma funcionalidade de compartilhamento de documentos.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS07)|
|RF17| O aplicativo deve manter um índice atualizado e pesquisável de todos os documentos publicados.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS08)|
|RF18| Sistema de busca avançada.|[Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT01)|
|RF19| Funcionalidades de acessibilidade.|[Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT02)|
|RF20| Ferramentas de usabilidade aprimoradas.|[Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT03)|
|RF21| Otimização do processo de busca diária.|[Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT04)|
|RF22| Suporte multilíngue no sistema.|[Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT05)|
|RF23| Sistema de notificações personalizadas.|[Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT06)|
|RF24| Interface do usuário altamente intuitiva.|[Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT08)|
|RF25| Funcionalidades avançadas de documentos.|[Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT10)|
|RF26| Melhoria na interação entre usuários.|[Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT11)|
|RNF01| Alta disponibilidade do sistema, com 99,9% de uptime.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS10)|
|RNF02| Compatibilidade com as versões mais recentes de sistemas operacionais móveis.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS11)|
|RNF03| Design responsivo que se adapta a tablets e smartphones.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS12)|
|RNF04| Segurança de dados com criptografia de ponta-a-ponta.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS13) |
|RNF05| Suporte multilíngue para facilitar o acesso por usuários não-nativos.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS14)|
|RNF06| Tempo de resposta de busca inferior a 2 segundos.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS15)|
|RNF07| Implementação de medidas de acessibilidade para usuários com deficiência.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS16)|
|RNF08| Facilidade de atualização de conteúdo pelo gestor do sistema.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS17)|
|RNF09| Suporte técnico com tempo de resposta de 24 horas.|[Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS18)|
|RNF10| O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS09) |
|RNF11| O aplicativo deve garantir a segurança e a privacidade dos dados dos usuários.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS10)|
|RNF12| O aplicativo deve estar disponível 24/7, com exceção de períodos de manutenção programada.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS11)|
|RNF13| O aplicativo deve apresentar um tempo de resposta rápido (< 2 segundos) nas buscas.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS12)|
|RNF14| O aplicativo deve ser acessível de acordo com os padrões da WCAG 2.1.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS13)|
|RNF15| O aplicativo deve ter um mecanismo robusto de backup e recuperação de dados.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS14)|
|RNF16| O aplicativo deve ser escalável para acomodar um crescente número de usuários e documentos.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS15)|
|RNF17| O aplicativo deve oferecer suporte multilíngue para atender a uma base de usuários diversificada.|[Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS16)|
|--| Medidas de segurança robustas.|[Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT07)|
|--| Requisitos para suporte e manutenção.|[Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT09)|



<font size="3"><p style="text-align: center"><b>Fonte:</b> [Eric Silveira](https://github.com/ericbky) e [Arthur Alves](https://github.com/Arthrok).</p></font>
</center>


## <a>Referência Bibliográfica</a>

> <a id="REF1" href="#anchor_1">1. </a>Página 3, 2.1 Rastreabilidade. SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf.

> <a id="REF2" href="#anchor_2">2. </a>Página 12, 3.1 Técnicas e ferramentas: suporte à questã da rastreabilidade. SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf.

> <a id="REF3" href="#anchor_3">3. </a> Página 29. Requisitos – Aula 26. SERRANO, Milene. SERRANO, Maurício. Acesso em 16 de junho de 2024.


## <a>Bibliografia</a>

> <a">1. </a>SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 15 de jun de 2024.

> <a">2. </a>TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acesso em: 14 de jun de 2024.

> <a">3. </a>Requisitos – Aula 26. SERRANO, Milene. SERRANO, Maurício. Acesso em 16 de junho de 2024.

## <a>Histórico de Versão</a>
|Versão|Data|Data Prevista de Revisão|Descrição|Autor|Revisor|
| :------: | :----------: |:-----------: | :-----------: | :---------: |:---------: |
|`1.0`|15/06/2024|16/06/2024|Criação do Documento, definição da metodologia e inserção da matriz. | [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky)|[João Artur](https://github.com/joao-artl) e [Douglas Marinho](https://github.com/M4RINH0)|