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

|**Requisito**|**Descrição**|**Elicitação**|**Pré-Rastreabilidade**|**Tipo**|**Implementado**|
|--------------|-------------|--------------|-----------------------|--------|----------------|
|RF01|Sistema de busca avançada|ENT01|IS01|O aplicativo deve permitir buscas detalhadas por tópicos específicos.|Não|
|RF02|Funcionalidades de acessibilidade|ENT02|IS02|O aplicativo deve oferecer a funcionalidade de salvar documentos para consulta offline.|Sim|
|RF03|Ferramentas de usabilidade aprimoradas|ENT03|IS03|O aplicativo deve enviar notificações personalizadas sobre novas publicações relevantes.|Não|
|RF04|Otimização do processo de busca diária|ENT04|IS04|O aplicativo deve oferecer acesso ao histórico de publicações legislativas.|Não|
|RF05|Suporte multilíngue no sistema|ENT05|IS16|O aplicativo deve oferecer suporte multilíngue para atender a uma base de usuários diversificada.|Não|
|RF06|Sistema de notificações personalizadas|ENT06|IS03|O aplicativo deve enviar notificações personalizadas sobre novas publicações relevantes.|Não|
|RF07|Interface do usuário altamente intuitiva|ENT08|IS09|O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar.|Não|
|RF08|Funcionalidades avançadas de documentos|ENT10|IS08|O aplicativo deve manter um índice atualizado e pesquisável de todos os documentos publicados.|Não|
|RF09|Melhoria na interação entre usuários|ENT11|-|Descrição não fornecida|Não|
|RNF01|Medidas de segurança robustas|ENT07|IS10|O aplicativo deve garantir a segurança e a privacidade dos dados dos usuários.|Sim|
|RNF02|Requisitos para suporte e manutenção|ENT09|IS11|O aplicativo deve estar disponível 24/7, com exceção de períodos de manutenção programada.|Sim|
|RNF03|Tempo de resposta rápido|ENT12|IS12|O aplicativo deve apresentar um tempo de resposta rápido (< 2 segundos) nas buscas.|Sim|
|RNF04|Acessibilidade|ENT13|IS13|O aplicativo deve ser acessível de acordo com os padrões da WCAG 2.1.|Sim|
|RNF05|Backup e recuperação|ENT14|IS14|O aplicativo deve ter um mecanismo robusto de backup e recuperação de dados.|Não|
|RNF06|Escalabilidade|ENT15|IS15|O aplicativo deve ser escalável para acomodar um crescente número de usuários e documentos.|Sim|

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