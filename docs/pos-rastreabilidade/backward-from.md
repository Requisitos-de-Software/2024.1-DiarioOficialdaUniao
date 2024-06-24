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




## AQUI





### Tabela de Níveis dos Requisitos

#### Requisito RF01

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Autenticação de usuários para acesso seguro.                                                                                              |
| ID do Requisito        | [OBS01](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS01)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS01)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito se refere à implementação de mecanismos de autenticação, garantindo que somente usuários autorizados possam acessar o sistema, o que é essencial para a segurança do aplicativo.                                                                                  |

#### Requisito RF02

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Visualização de edições diárias do Diário Oficial.                                                                                         |
| ID do Requisito        | [OBS02](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS02)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS02)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Ambiental** - Este requisito está relacionado à necessidade dos usuários de acessar as edições diárias do Diário Oficial, influenciando a frequência e a forma como os dados são disponibilizados e atualizados no sistema.                                                                                  |

#### Requisito RF03

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Busca por palavras-chave em documentos.                                                                                                   |
| ID do Requisito        | [OBS03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS03)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS03)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito está focado na implementação de funcionalidades que permitem aos usuários realizar buscas por palavras-chave, facilitando o acesso rápido e eficiente às informações desejadas.                                                                  |

#### Requisito RF04

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Filtragem de conteúdo por data, categoria ou órgão emissor.                                                                               |
| ID do Requisito        | [OBS04](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS04)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS04)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito se refere à criação de funcionalidades de filtragem que permitem aos usuários refinar suas buscas, melhorando a experiência de uso e a eficiência na localização de documentos específicos.                                                                  |

#### Requisito RF05

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Download de edições e documentos em formatos PDF.                                                                                         |
| ID do Requisito        | [OBS05](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS05)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS05)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito envolve a necessidade de permitir que os usuários baixem edições e documentos, garantindo que tenham acesso offline aos materiais necessários, o que é crucial para a continuidade do trabalho em ambientes sem conexão.                                                                      |



#### Requisito RF06

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Notificações push sobre novas publicações relevantes.                                                                                     |
| ID do Requisito        | [OBS06](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS06)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS06)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito se refere à implementação de funcionalidades específicas no aplicativo, como a configuração e envio de notificações push, além de assegurar a entrega dessas notificações aos usuários.                                                                                  |

#### Requisito RF07

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Acesso a edições anteriores arquivadas.                                                                                                   |
| ID do Requisito        | [OBS07](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS07)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS07)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Ambiental** - Este requisito está relacionado ao contexto em que os usuários precisam acessar documentos arquivados para referências e consultas, impactando diretamente a disponibilidade e organização dos dados.                                                                                  |

#### Requisito RF08

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Integração com sistemas de assinatura digital.                                                                                            |
| ID do Requisito        | [OBS08](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS08)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS08)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Este requisito se refere à necessidade de integração com outros sistemas e processos internos da organização, garantindo a conformidade e segurança na assinatura de documentos digitais.                                                                  |

#### Requisito RF09

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Compartilhamento de documentos via redes sociais e email.                                                                                 |
| ID do Requisito        | [OBS09](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS09)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS09)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito facilita a disseminação de informações, permitindo que os usuários compartilhem documentos relevantes com outras partes interessadas, melhorando a comunicação e colaboração.                                                                          |

#### Requisito RF10

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve permitir buscas detalhadas por tópicos específicos.                                                                    |
| ID do Requisito        | [IS01](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS01)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS01)              |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito foca na implementação de funcionalidades que permitem buscas avançadas, atendendo às necessidades dos usuários de encontrar informações específicas de maneira eficiente.                                                               |


#### Requisito RF11

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve oferecer a funcionalidade de salvar documentos para consulta offline.                                                                                              |
| ID do Requisito        | [IS02](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS02)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS02)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito se refere à implementação de uma funcionalidade que permita aos usuários salvar documentos para consulta offline, garantindo acesso às informações mesmo sem conexão com a internet.                                                                                  |

#### Requisito RF12

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve enviar notificações personalizadas sobre novas publicações relevantes.                                                                                         |
| ID do Requisito        | [IS03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS03)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS03)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Ambiental** - Este requisito está relacionado à necessidade de manter os usuários informados sobre novas publicações relevantes, garantindo que eles recebam atualizações personalizadas conforme suas preferências e interesses.                                                                                  |

#### Requisito RF13

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve oferecer acesso ao histórico de publicações legislativas.                                                                                                   |
| ID do Requisito        | [IS04](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS04)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS04)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Este requisito se refere à necessidade de disponibilizar um histórico completo das publicações legislativas, permitindo que os usuários acessem informações passadas de forma organizada e eficiente.                                                                  |

#### Requisito RF14

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve ter um sistema de marcadores para rastrear alterações em documentos específicos.                                                                               |
| ID do Requisito        | [IS05](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS05)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS05)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito envolve a necessidade de implementar um sistema de marcadores que permita aos usuários rastrear alterações em documentos específicos, facilitando o monitoramento de mudanças importantes.                                                                  |

#### Requisito RF15

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve fornecer uma interface que facilite a leitura de textos legislativos.                                                                                         |
| ID do Requisito        | [IS06](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS06)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS06)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito está focado na criação de uma interface de usuário que facilite a leitura de textos legislativos, garantindo que a apresentação das informações seja clara e acessível para todos os usuários.                                                                      |


#### Requisito RF16

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve incluir uma funcionalidade de compartilhamento de documentos.                                                                                             |
| ID do Requisito        | [IS07](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS07)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS07)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito se refere à implementação de uma funcionalidade que permita aos usuários compartilhar documentos diretamente a partir do aplicativo, facilitando a disseminação de informações importantes.                                                               |

#### Requisito RF17

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve manter um índice atualizado e pesquisável de todos os documentos publicados.                                                                                    |
| ID do Requisito        | [IS08](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS08)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS08)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Este requisito está relacionado à necessidade de manter um índice atualizado e pesquisável de todos os documentos publicados, garantindo que os usuários possam encontrar rapidamente as informações de que precisam.                                                                |

#### Requisito RF18

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Sistema de busca avançada                                                                                                                  |
| ID do Requisito        | [ENT01](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT01)                       |
| Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT01)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito envolve a criação de um sistema de busca avançada que permita aos usuários realizar consultas detalhadas e refinadas dentro do aplicativo, melhorando a eficiência na recuperação de informações.                                                                    |

#### Requisito RF19

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Funcionalidades de acessibilidade                                                                                                         |
| ID do Requisito        | [ENT02](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT02)                       |
| Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT02)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito está relacionado à implementação de funcionalidades que garantam a acessibilidade do aplicativo para todos os usuários, incluindo aqueles com deficiência, em conformidade com os padrões de acessibilidade.                                                                      |

#### Requisito RF20

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Ferramentas de usabilidade aprimoradas                                                                                                     |
| ID do Requisito        | [ENT03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT03)                       |
| Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT03)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito envolve a implementação de ferramentas que melhorem a usabilidade do aplicativo, garantindo que os usuários possam navegar e utilizar todas as funcionalidades de maneira intuitiva e eficiente.                                                                  |


#### Requisito RF21

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Otimização do processo de busca diária                                                                                                                  |
| ID do Requisito        | [ENT04](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT04)                       |
| Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT04)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito visa a implementação de melhorias no processo de busca diária dentro do aplicativo, tornando-o mais eficiente e rápido para os usuários.                                                                  |

#### Requisito RF22

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Suporte multilíngue no sistema                                                                                                                |
| ID do Requisito        | [ENT05](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT05)                       |
| Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT05)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito aborda a necessidade de suporte multilíngue no sistema, permitindo que usuários de diferentes línguas possam acessar e utilizar o aplicativo com facilidade.                                                                     |

#### Requisito RF23

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Sistema de notificações personalizadas                                                                                                    |
| ID do Requisito        | [ENT06](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT06)                       |
| Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT06)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito refere-se à implementação de um sistema de notificações personalizadas, permitindo que os usuários recebam alertas relevantes de acordo com suas preferências e interesses.                                                                 |

#### Requisito RF24

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Interface do usuário altamente intuitiva                                                                                                               |
| ID do Requisito        | [ENT08](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT08)                       |
| Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT08)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito envolve a criação de uma interface de usuário que seja altamente intuitiva, facilitando a navegação e a utilização do aplicativo por todos os usuários, independentemente de seu nível de experiência.                                                                 |

#### Requisito RF25

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Funcionalidades avançadas de documentos                                                                                                          |
| ID do Requisito        | [ENT10](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT10)                       |
| Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT10)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito se refere à implementação de funcionalidades avançadas de manipulação e gerenciamento de documentos, oferecendo maior flexibilidade e eficiência no uso do aplicativo.                                                                 |

#### Requisito RF26

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Melhoria na interação entre usuários                                                                                                       |
| ID do Requisito        | [ENT11](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT11)                       |
| Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT11)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Este requisito aborda a melhoria na interação entre usuários dentro do aplicativo, promovendo uma comunicação mais eficaz e colaborativa entre os membros da comunidade.                                                                  |


#### Requisito RNF01

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Alta disponibilidade do sistema, com 99,9% de uptime.                                                                                              |
| ID do Requisito        | [OBS10](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS10)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS10)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Ambiental** - Este requisito garante que o sistema esteja disponível e operacional a maior parte do tempo, minimizando interrupções no serviço oferecido aos usuários.                                                                 |

#### Requisito RNF02

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Compatibilidade com as versões mais recentes de sistemas operacionais móveis.                                                                                                                |
| ID do Requisito        | [OBS11](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS11)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS11)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito assegura que o aplicativo funcionará corretamente nas versões mais recentes dos sistemas operacionais móveis, proporcionando uma melhor experiência para os usuários.                                                                  |

#### Requisito RNF03

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Design responsivo que se adapta a tablets e smartphones.                                                                                                    |
| ID do Requisito        | [OBS12](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS12)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS12)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito envolve a criação de um design que se adapte automaticamente a diferentes tamanhos de tela, garantindo uma experiência de usuário consistente e agradável em tablets e smartphones.                                                                 |

#### Requisito RNF04

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Segurança de dados com criptografia de ponta-a-ponta.                                                                                                               |
| ID do Requisito        | [OBS13](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS13)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS13)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Este requisito assegura a proteção das informações dos usuários através de criptografia de ponta-a-ponta, garantindo que os dados estejam seguros durante a transmissão e o armazenamento.                                                                 |

#### Requisito RNF05

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Suporte multilíngue para facilitar o acesso por usuários não-nativos.                                                                                                          |
| ID do Requisito        | [OBS14](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS14)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS14)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito garante que o sistema suporte múltiplas línguas, permitindo que usuários de diferentes nacionalidades possam utilizar o aplicativo em seu idioma nativo.                                                                 |

#### Requisito RNF06

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Tempo de resposta de busca inferior a 2 segundos.                                                                                              |
| ID do Requisito        | [OBS15](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS15)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS15)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito visa garantir que as consultas ao sistema sejam rápidas e eficientes, melhorando a experiência do usuário e a usabilidade do aplicativo.                                                                 |

#### Requisito RNF07

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Implementação de medidas de acessibilidade para usuários com deficiência.                                                                                                                |
| ID do Requisito        | [OBS16](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS16)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS16)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito garante que o sistema seja acessível a todos os usuários, incluindo aqueles com deficiência, seguindo as melhores práticas de acessibilidade.                                                                  |

#### Requisito RNF08

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Facilidade de atualização de conteúdo pelo gestor do sistema.                                                                                                    |
| ID do Requisito        | [OBS17](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS17)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS17)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Este requisito assegura que o gestor do sistema possa atualizar o conteúdo de forma eficiente e sem complicações, garantindo a atualização contínua das informações disponíveis.                                                                 |

#### Requisito RNF09

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Suporte técnico com tempo de resposta de 24 horas.                                                                                                               |
| ID do Requisito        | [OBS18](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS18)                       |
| Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS18)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito assegura que o suporte técnico esteja disponível para resolver problemas de usuários em um tempo máximo de 24 horas, melhorando a confiabilidade e a satisfação do usuário.                                                                 |

#### Requisito RNF10

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar.                                                                                                          |
| ID do Requisito        | [IS09](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS09)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS09)                 |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito visa garantir que o aplicativo seja fácil de usar e que os usuários possam navegar pela interface de forma intuitiva, melhorando a usabilidade geral.                                                                 |


#### Requisito RNF11

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve garantir a segurança e a privacidade dos dados dos usuários.                                                            |
| ID do Requisito        | [IS10](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS10)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS10)               |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Garantir que os dados dos usuários sejam protegidos contra acessos não autorizados e violações de privacidade.                             |

#### Requisito RNF12

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve estar disponível 24/7, com exceção de períodos de manutenção programada.                                                 |
| ID do Requisito        | [IS11](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS11)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS11)               |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Assegurar que o sistema esteja sempre disponível para os usuários, exceto durante a manutenção programada.                                             |

#### Requisito RNF13

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve apresentar um tempo de resposta rápido (< 2 segundos) nas buscas.                                                       |
| ID do Requisito        | [IS12](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS12)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS12)               |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Garantir que o sistema responda rapidamente às consultas dos usuários.                                                             |

#### Requisito RNF14

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve ser acessível de acordo com os padrões da WCAG 2.1.                                                                     |
| ID do Requisito        | [IS13](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS13)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS13)               |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Ambiental** - Assegurar que o sistema esteja em conformidade com os padrões de acessibilidade web estabelecidos.                                                |

#### Requisito RNF15

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve ter um mecanismo robusto de backup e recuperação de dados.                                                              |
| ID do Requisito        | [IS14](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS14)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS14)               |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Garantir que os dados possam ser recuperados de forma segura e eficiente em caso de falhas ou desastres.


#### Requisito RNF16

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve ser escalável para acomodar um crescente número de usuários e documentos.                                                |
| ID do Requisito        | [IS15](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS15)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS15)               |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Garantir que o sistema possa crescer e se adaptar a um aumento na carga de trabalho sem comprometer o desempenho.                       |

#### Requisito RNF17

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | O aplicativo deve oferecer suporte multilíngue para atender a uma base de usuários diversificada.                                          |
| ID do Requisito        | [IS16](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS16)                       |
| Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS16)               |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Ambiental** - Assegurar que o sistema possa ser utilizado por usuários que falam diferentes idiomas, facilitando a inclusão.                                                 |

#### Requisito RNF18

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Medidas de segurança robustas                                                                                                             |
| ID do Requisito        | [ENT07](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT07)                            |
| Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT07)                       |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Implementar medidas rigorosas para proteger o sistema contra ameaças de segurança, garantindo a integridade e confidencialidade dos dados.               |

#### Requisito RNF19

| Informações            | Detalhes                                                                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito      | Requisitos para suporte e manutenção                                                                                                      |
| ID do Requisito        | [ENT09](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT09)                            |
| Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT09)                       |
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Definir requisitos claros para o suporte e a manutenção do sistema, assegurando que ele permaneça operacional e atualizado ao longo do tempo.                     |

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