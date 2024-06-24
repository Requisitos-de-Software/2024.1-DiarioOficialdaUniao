## <a>Introdução</a>

A rastreabilidade de requisitos é fundamental para a gestão eficaz de projetos de software, assegurando que os requisitos sejam implementados e verificáveis durante todo o ciclo de vida do desenvolvimento. A rastreabilidade backward-from, que liga os requisitos às suas fontes originais, é crucial para entender as motivações por trás de cada requisito, facilitando a análise de impacto e a gestão de mudanças<a id="anchor_1" href="#REF1">^1^</a>.

Este modelo de rastreabilidade permite identificar rapidamente as partes do sistema afetadas por mudanças nos requisitos, mitigando riscos e mantendo a integridade do projeto. Assim, qualquer alteração pode ser gerida de forma controlada e transparente, garantindo a qualidade e a conformidade do produto final<a id="anchor_1" href="#REF1">^1^</a>.

## <a>Metodologia</a>

Para a execução dessa rastreabilidade, primeiro classificaremos as informações, pois segundo o meta-modelo de Toranzo que teremos por base, existem quatro níveis de classificação, sendo eles: ambiental, organizacional, gerencial e desenvolvimento<a id="anchor_5" href="#REF5">^5^</a>. A figura 01 ilustra esses modelos a seguir:

<center>
Figura 01: Classificação da informação do rastreamento.

![Figura de Classificação](https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/pos-rastreabilidade/assets/figuraClassificacao.png?raw=True)

<font size="3"><p style="text-align: center"><b>Fonte:</b> Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática<a id="anchor_5" href="#REF5">^5^</a>.</p></font>
</center>

 - O **nível ambiental** congrega informações oriundas do contexto ambiental onde a organização está inserida e que podem afetar o sistema sendo desenvolvido<a id="anchor_3" href="#REF3">^3^</a>;
 - O **nível organizacional** reúne informações relacionadas à organização (missão, objetivos, metas e padrões) e que podem impactar os requisitos do sistema<a id="anchor_3" href="#REF3">^3^</a>;
 - O **nível gerencial** agrega informações que permitem associar tarefas a requisitos, e que podem auxiliar a gerência do projeto<a id="anchor_3" href="#REF3">^3^</a>;
 - O **nível desenvolvimento** abarca informações relacionadas aos diversos artefatos gerados no processo de desenvolvimento (documento de requisitos, diagramas, programas, casos de testes, ...)<a id="anchor_3" href="#REF3">^3^</a>.

Após essa classificação, iremos utilizar o *Modelo Intermediário para o Rastreamento de Requisitos*, cujo tem por objetivo fornecer resultado de uma combinação de fatores, como: boas práticas, estudos de casos, abstração, entre outros<a id="anchor_4" href="#REF4">^4^</a>. A literatura apresenta diversos trabalhos enfocando os tipos de relacionamentos associados à rastreabilidade, são eles os elos de rastreabilidade<a id="anchor_3" href="#REF3">^3^</a>, os principais são:

- **Satisfação:** classe origem tem dependência de satisfação com a classe destino.
- **Recurso:** classe origem tem dependência de recurso com a classe
destino.
- **Responsabilidade:** registra a participação, responsabilidade e ação de pessoas sobre artefatos.
- **Representação:** captura a representação ou modelagem dos requisitos
em outras linguagens.
- **Alocado:** classe origem está relacionada à classe destino, que
representa um subsistema.
- **Agregação:** indica “composição” de elementos.

No modelo, existem algumas notações para identificar os diferentes tipos de relacionamentos: Satisfação *<sat\>*, Recurso *<rec\>*, Responsabilidade *<resp\>*, Representação *<rep\>* e Alocado *<alo\>*<a id="anchor_4" href="#REF4">^4^</a>.

### 


| Tipo | Descrição | ID |
| ---- | --------- | --- |
| RF01 | Autenticação de usuários para acesso seguro. | [OBS01](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS01) |
| RF02 | Visualização de edições diárias do Diário Oficial. | [OBS02](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS02) |
| RF03 | Busca por palavras-chave em documentos. | [OBS03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS03) |
| RF04 | Filtragem de conteúdo por data, categoria ou órgão emissor. | [OBS04](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS04) |
| RF05 | Download de edições e documentos em formatos PDF. | [OBS05](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS05) |
| RF06 | Notificações push sobre novas publicações relevantes. | [OBS06](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS06) |
| RF07 | Acesso a edições anteriores arquivadas. | [OBS07](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS07) |
| RF08 | Integração com sistemas de assinatura digital. | [OBS08](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS08) |
| RF09 | Compartilhamento de documentos via redes sociais e email. | [OBS09](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS09) |
| RF10 | O aplicativo deve permitir buscas detalhadas por tópicos específicos. | [IS01](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS01) |
| RF11 | O aplicativo deve oferecer a funcionalidade de salvar documentos para consulta offline. | [IS02](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS02) |
| RF12 | O aplicativo deve enviar notificações personalizadas sobre novas publicações relevantes. | [IS03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS03) |
| RF13 | O aplicativo deve oferecer acesso ao histórico de publicações legislativas. | [IS04](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS04) |
| RF14 | O aplicativo deve ter um sistema de marcadores para rastrear alterações em documentos específicos. | [IS05](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS05) |
| RF15 | O aplicativo deve fornecer uma interface que facilite a leitura de textos legislativos. | [IS06](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS06) |
| RF16 | O aplicativo deve incluir uma funcionalidade de compartilhamento de documentos. | [IS07](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS07) |
| RF17 | O aplicativo deve manter um índice atualizado e pesquisável de todos os documentos publicados. | [IS08](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS08) |
| RF18 | Sistema de busca avançada | [ENT01](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT01) |
| RF19 | Funcionalidades de acessibilidade | [ENT02](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT02) |
| RF20 | Ferramentas de usabilidade aprimoradas | [ENT03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT03) |
| RF21 | Otimização do processo de busca diária | [ENT04](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT04) |
| RF22 | Suporte multilíngue no sistema | [ENT05](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT05) |
| RF23 | Sistema de notificações personalizadas | [ENT06](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT06) |
| RF24 | Interface do usuário altamente intuitiva | [ENT08](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT08) |
| RF25 | Funcionalidades avançadas de documentos | [ENT10](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT10) |
| RF26 | Melhoria na interação entre usuários | [ENT11](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT11) |



| Tipo  | Descrição | ID    |
|-------|-------------------------------------|-------|
| RNF01 | Alta disponibilidade do sistema, com 99,9% de uptime. | [OBS10](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS10) |
| RNF02 | Compatibilidade com as versões mais recentes de sistemas operacionais móveis. | [OBS11](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS11) |
| RNF03 | Design responsivo que se adapta a tablets e smartphones. | [OBS12](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS12) |
| RNF04 | Segurança de dados com criptografia de ponta-a-ponta. | [OBS13](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS13) |
| RNF05 | Suporte multilíngue para facilitar o acesso por usuários não-nativos. | [OBS14](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS14) |
| RNF06 | Tempo de resposta de busca inferior a 2 segundos. | [OBS15](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS15) |
| RNF07 | Implementação de medidas de acessibilidade para usuários com deficiência. | [OBS16](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS16) |
| RNF08 | Facilidade de atualização de conteúdo pelo gestor do sistema. | [OBS17](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS17) |
| RNF09 | Suporte técnico com tempo de resposta de 24 horas. | [OBS18](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS18) |
| RNF10 | O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar. | [IS09](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS09) |
| RNF11 | O aplicativo deve garantir a segurança e a privacidade dos dados dos usuários. | [IS10](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS10) |
| RNF12 | O aplicativo deve estar disponível 24/7, com exceção de períodos de manutenção programada. | [IS11](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS11) |
| RNF13 | O aplicativo deve apresentar um tempo de resposta rápido (< 2 segundos) nas buscas. | [IS12](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS12) |
| RNF14 | O aplicativo deve ser acessível de acordo com os padrões da WCAG 2.1. | [IS13](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS13) |
| RNF15 | O aplicativo deve ter um mecanismo robusto de backup e recuperação de dados. | [IS14](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS14) |
| RNF16 | O aplicativo deve ser escalável para acomodar um crescente número de usuários e documentos. | [IS15](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS15) |
| RNF17 | O aplicativo deve oferecer suporte multilíngue para atender a uma base de usuários diversificada. | [IS16](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS16) |
| RNF18 | Medidas de segurança robustas | [ENT07](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT07) |
| RNF19 | Requisitos para suporte e manutenção | [ENT09](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT09) |



## <a>Referência bibliográfica</a>

> <a id="REF1" href="#anchor_1">1. </a> Página 4, 2.1 Rastreabilidade. SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf.

> <a id="REF3" href="#anchor_3">3. </a>Página 09 e 10, 2.3.2 Meta-modelo proposto por Toranzo. TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002.

> <a id="REF4" href="#anchor_4">4. </a>Página 199, 5 Modelo Intermediário para o Rastreamento de Requisitos. TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002.

> <a id="REF5" href="#anchor_5">5. </a>Página 196, 3 Classificação das Informações a serem Rastreadas. TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002.


## <a>Bibliografia</a>

> <a">1. </a>SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 15 de jun de 2024.

> <a">2. </a>TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acesso em: 14 de jun de 2024.

# <a>Histórico de Versão</a>
|Versão|Data|Data Prevista de Revisão|Descrição|Autor|Revisor|
| :------: | :----------: |:-----------: | :-----------: | :---------: |:---------: |
|`1.0`|15/06/2024|16/06/2024|Criação do Documento, inserção da introdução e da metodologia. | [Eric Silveira](https://github.com/ericbky)|[Arthur Alves](https://github.com/Arthrok) e [Douglas Marinho](https://github.com/M4RINH0)|