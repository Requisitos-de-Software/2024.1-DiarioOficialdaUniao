## <a>Introdução</a>

A rastreabilidade de requisitos é fundamental para a gestão eficaz de projetos de software, assegurando que os requisitos sejam implementados e verificáveis durante todo o ciclo de vida do desenvolvimento. A rastreabilidade backward-from, que liga os requisitos às suas fontes originais, é crucial para entender as motivações por trás de cada requisito, facilitando a análise de impacto e a gestão de mudanças<a id="anchor_1" href="#REF1">^1^</a>.

Este modelo de rastreabilidade permite identificar rapidamente as partes do sistema afetadas por mudanças nos requisitos, mitigando riscos e mantendo a integridade do projeto. Assim, qualquer alteração pode ser gerida de forma controlada e transparente, garantindo a qualidade e a conformidade do produto final<a id="anchor_1" href="#REF1">^1^</a>.

## <a>Metodologia</a>

Para a execução dessa rastreabilidade, primeiro classificaremos as informações, pois segundo o meta-modelo de Toranzo que teremos por base, existem quatro níveis de classificação, sendo eles: ambiental, organizacional, gerencial e desenvolvimento<a id="anchor_5" href="#REF5">^5^</a>. A figura 01 ilustra esses modelos a seguir:

<center>
**Figura 01:** Classificação da informação do rastreamento.

![Figura de Classificação](https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/pos-rastreabilidade/assets/figuraClassificacao.png?raw=True)

<font size="3"><p style="text-align: center"><b>Fonte:</b> Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática<a id="anchor_5" href="#REF5">^5^</a>.</p></font>
</center>

 - O **nível ambiental** congrega informações oriundas do contexto ambiental onde a organização está inserida e que podem afetar o sistema sendo desenvolvido<a id="anchor_3" href="#REF3">^3^</a>;
 - O **nível organizacional** reúne informações relacionadas à organização (missão, objetivos, metas e padrões) e que podem impactar os requisitos do sistema<a id="anchor_3" href="#REF3">^3^</a>;
 - O **nível gerencial** agrega informações que permitem associar tarefas a requisitos, e que podem auxiliar a gerência do projeto<a id="anchor_3" href="#REF3">^3^</a>;
 - O **nível desenvolvimento** abarca informações relacionadas aos diversos artefatos gerados no processo de desenvolvimento (documento de requisitos, diagramas, programas, casos de testes, ...)<a id="anchor_3" href="#REF3">^3^</a>.


A seguir, a Tabela 01 representa a estrutura utilizada para documentar as origens dos requisitos no artefato. Ela detalha informações essenciais como o nome, identificador único, origem e nível do requisito, permitindo um rastreamento eficaz e compreensão clara de cada requisito no contexto do projeto.

<p style="text-align: center"><b>Tabela 01:</b> Estrutura das tabelas dos requisitos do backward from.</p>

| Informações | Detalhes|
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Nome do Requisito| Indica o que o requisito está pedindo ou descrevendo.|
| ID do Requisito  | Fornece um identificador único que pode ser usado para referenciar este requisito específico de maneira consistente em toda a documentação e durante o desenvolvimento. |
| Origem| Especifica como ou de onde o requisito foi obtido.|
| Nível (ambiental, organizacional, gerencial ou desenvolvimento) | Classifica o requisito em um nível específico para ajudar a entender seu impacto e onde ele se aplica, já explicado anteriormente. |

<font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

## <a>Tabela de Níveis dos Requisitos Funcionais</a>

A seguir, serão apresentadas as tabelas contendo os requisitos funcionais do projeto. Estas tabelas documentam informações essenciais sobre cada requisito, que proporcionam um rastreamento eficaz e uma compreensão clara dos requisitos no contexto do projeto.

??? "RF01 - Autenticação de usuários para acesso seguro."

    #### Requisito RF01

    A Tabela 02 apresenta os detalhes do requisito RF01, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 02:</b> Autenticação de usuários para acesso seguro.</p>

    | Informações | Detalhes                                                                                                              |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Autenticação de usuários para acesso seguro.                                                                                              |
    | ID do Requisito        | [OBS01](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS01)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS01)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito se refere à implementação de mecanismos de autenticação, garantindo que somente usuários autorizados possam acessar o sistema, o que é essencial para a segurança do aplicativo.                                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF02 - Visualização de edições diárias do Diário Oficial."

    #### Requisito RF02

    A Tabela 03 apresenta os detalhes do requisito RF02, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 03:</b> Visualização de edições diárias do Diário Oficial.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Visualização de edições diárias do Diário Oficial.                                                                                         |
    | ID do Requisito        | [OBS02](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS02)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS02)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Ambiental** - Este requisito está relacionado à necessidade dos usuários de acessar as edições diárias do Diário Oficial, influenciando a frequência e a forma como os dados são disponibilizados e atualizados no sistema.                                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF03 - Busca por palavras-chave em documentos."

    #### Requisito RF03

    A Tabela 04 apresenta os detalhes do requisito RF03, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 04:</b> Busca por palavras-chave em documentos.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Busca por palavras-chave em documentos.                                                                                                   |
    | ID do Requisito        | [OBS03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS03)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS03)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito está focado na implementação de funcionalidades que permitem aos usuários realizar buscas por palavras-chave, facilitando o acesso rápido e eficiente às informações desejadas.                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF04 - Filtragem de conteúdo por data, categoria ou órgão emissor."

    #### Requisito RF04

    A Tabela 05 apresenta os detalhes do requisito RF04, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 05:</b> Filtragem de conteúdo por data, categoria ou órgão emissor.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Filtragem de conteúdo por data, categoria ou órgão emissor.                                                                               |
    | ID do Requisito        | [OBS04](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS04)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS04)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito se refere à criação de funcionalidades de filtragem que permitem aos usuários refinar suas buscas, melhorando a experiência de uso e a eficiência na localização de documentos específicos.                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF05 - Download de edições e documentos em formatos PDF."

    #### Requisito RF05

    A Tabela 06 apresenta os detalhes do requisito RF05, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 06:</b> Download de edições e documentos em formatos PDF.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Download de edições e documentos em formatos PDF.                                                                                         |
    | ID do Requisito        | [OBS05](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS05)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS05)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito envolve a necessidade de permitir que os usuários baixem edições e documentos, garantindo que tenham acesso offline aos materiais necessários, o que é crucial para a continuidade do trabalho em ambientes sem conexão.                                                                      |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF06 - Notificações push sobre novas publicações relevantes."

    #### Requisito RF06

    A Tabela 07 apresenta os detalhes do requisito RF06, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 07:</b> Notificações push sobre novas publicações relevantes.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Notificações push sobre novas publicações relevantes.                                                                                     |
    | ID do Requisito        | [OBS06](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS06)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS06)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito se refere à implementação de funcionalidades específicas no aplicativo, como a configuração e envio de notificações push, além de assegurar a entrega dessas notificações aos usuários.                                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF07 - Acesso a edições anteriores arquivadas."

    #### Requisito RF07

    A Tabela 08 apresenta os detalhes do requisito RF07, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 08:</b> Acesso a edições anteriores arquivadas.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Acesso a edições anteriores arquivadas.                                                                                                   |
    | ID do Requisito        | [OBS07](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS07)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS07)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Ambiental** - Este requisito está relacionado ao contexto em que os usuários precisam acessar documentos arquivados para referências e consultas, impactando diretamente a disponibilidade e organização dos dados.                                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF08 - Integração com sistemas de assinatura digital."

    #### Requisito RF08

    A Tabela 09 apresenta os detalhes do requisito RF08, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 09:</b> Integração com sistemas de assinatura digital.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Integração com sistemas de assinatura digital.                                                                                            |
    | ID do Requisito        | [OBS08](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS08)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS08)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Este requisito se refere à necessidade de integração com outros sistemas e processos internos da organização, garantindo a conformidade e segurança na assinatura de documentos digitais.                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF09 - Compartilhamento de documentos via redes sociais e email."

    #### Requisito RF09

    A Tabela 10 apresenta os detalhes do requisito RF09, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 10:</b> Compartilhamento de documentos via redes sociais e email.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Compartilhamento de documentos via redes sociais e email.                                                                                 |
    | ID do Requisito        | [OBS09](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS09)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS09)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito facilita a disseminação de informações, permitindo que os usuários compartilhem documentos relevantes com outras partes interessadas, melhorando a comunicação e colaboração.                                                                          |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF10 - O aplicativo deve permitir buscas detalhadas por tópicos específicos."

    #### Requisito RF10

    A Tabela 11 apresenta os detalhes do requisito RF10, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 11:</b> O aplicativo deve permitir buscas detalhadas por tópicos específicos.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve permitir buscas detalhadas por tópicos específicos.                                                                    |
    | ID do Requisito        | [IS01](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS01)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS01)              |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito foca na implementação de funcionalidades que permitem buscas avançadas, atendendo às necessidades dos usuários de encontrar informações específicas de maneira eficiente.                                                               |


    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF11 - O aplicativo deve oferecer a funcionalidade de salvar documentos para consulta offline."

    #### Requisito RF11

    A Tabela 12 apresenta os detalhes do requisito RF11, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 12:</b> O aplicativo deve oferecer a funcionalidade de salvar documentos para consulta offline.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve oferecer a funcionalidade de salvar documentos para consulta offline.                                                                                              |
    | ID do Requisito        | [IS02](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS02)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS02)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito se refere à implementação de uma funcionalidade que permita aos usuários salvar documentos para consulta offline, garantindo acesso às informações mesmo sem conexão com a internet.                                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF12 - O aplicativo deve enviar notificações personalizadas sobre novas publicações relevantes."

    #### Requisito RF12

    A Tabela 13 apresenta os detalhes do requisito RF12, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 13:</b> O aplicativo deve enviar notificações personalizadas sobre novas publicações relevantes.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve enviar notificações personalizadas sobre novas publicações relevantes.                                                                                         |
    | ID do Requisito        | [IS03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS03)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS03)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Ambiental** - Este requisito está relacionado à necessidade de manter os usuários informados sobre novas publicações relevantes, garantindo que eles recebam atualizações personalizadas conforme suas preferências e interesses.                                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF13 - O aplicativo deve oferecer acesso ao histórico de publicações legislativas."

    #### Requisito RF13

    A Tabela 14 apresenta os detalhes do requisito RF13, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 14:</b> O aplicativo deve oferecer acesso ao histórico de publicações legislativas.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve oferecer acesso ao histórico de publicações legislativas.                                                                                                   |
    | ID do Requisito        | [IS04](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS04)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS04)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Este requisito se refere à necessidade de disponibilizar um histórico completo das publicações legislativas, permitindo que os usuários acessem informações passadas de forma organizada e eficiente.                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF14 - O aplicativo deve ter um sistema de marcadores para rastrear alterações em documentos específicos."

    #### Requisito RF14

    A Tabela 15 apresenta os detalhes do requisito RF14, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 15:</b> O aplicativo deve ter um sistema de marcadores para rastrear alterações em documentos específicos.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve ter um sistema de marcadores para rastrear alterações em documentos específicos.                                                                               |
    | ID do Requisito        | [IS05](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS05)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS05)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito envolve a necessidade de implementar um sistema de marcadores que permita aos usuários rastrear alterações em documentos específicos, facilitando o monitoramento de mudanças importantes.                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF15 - O aplicativo deve fornecer uma interface que facilite a leitura de textos legislativos."

    #### Requisito RF15

    A Tabela 16 apresenta os detalhes do requisito RF15, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 16:</b> O aplicativo deve fornecer uma interface que facilite a leitura de textos legislativos.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve fornecer uma interface que facilite a leitura de textos legislativos.                                                                                         |
    | ID do Requisito        | [IS06](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS06)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS06)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito está focado na criação de uma interface de usuário que facilite a leitura de textos legislativos, garantindo que a apresentação das informações seja clara e acessível para todos os usuários.                                                                      |


    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF16 - O aplicativo deve incluir uma funcionalidade de compartilhamento de documentos."

    #### Requisito RF16

    A Tabela 17 apresenta os detalhes do requisito RF16, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 17:</b> O aplicativo deve incluir uma funcionalidade de compartilhamento de documentos.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve incluir uma funcionalidade de compartilhamento de documentos.                                                                                             |
    | ID do Requisito        | [IS07](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS07)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS07)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito se refere à implementação de uma funcionalidade que permita aos usuários compartilhar documentos diretamente a partir do aplicativo, facilitando a disseminação de informações importantes.                                                               |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF17 - O aplicativo deve manter um índice atualizado e pesquisável de todos os documentos publicados."

    #### Requisito RF17

    A Tabela 18 apresenta os detalhes do requisito RF17, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 18:</b> O aplicativo deve manter um índice atualizado e pesquisável de todos os documentos publicados.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve manter um índice atualizado e pesquisável de todos os documentos publicados.                                                                                    |
    | ID do Requisito        | [IS08](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS08)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS08)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Este requisito está relacionado à necessidade de manter um índice atualizado e pesquisável de todos os documentos publicados, garantindo que os usuários possam encontrar rapidamente as informações de que precisam.                                                                |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF18 - Sistema de busca avançada."

    #### Requisito RF18

    A Tabela 19 apresenta os detalhes do requisito RF18, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 19:</b> Sistema de busca avançada.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Sistema de busca avançada                                                                                                                  |
    | ID do Requisito        | [ENT01](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT01)                       |
    | Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT01)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito envolve a criação de um sistema de busca avançada que permita aos usuários realizar consultas detalhadas e refinadas dentro do aplicativo, melhorando a eficiência na recuperação de informações.                                                                    |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF19 - Funcionalidades de acessibilidade."

    #### Requisito RF19

    A Tabela 20 apresenta os detalhes do requisito RF19, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 20:</b> Funcionalidades de acessibilidade.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Funcionalidades de acessibilidade                                                                                                         |
    | ID do Requisito        | [ENT02](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT02)                       |
    | Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT02)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito está relacionado à implementação de funcionalidades que garantam a acessibilidade do aplicativo para todos os usuários, incluindo aqueles com deficiência, em conformidade com os padrões de acessibilidade.                                                                      |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF20 - Ferramentas de usabilidade aprimoradas."

    #### Requisito RF20

    A Tabela 21 apresenta os detalhes do requisito RF20, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 21:</b> Ferramentas de usabilidade aprimoradas.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Ferramentas de usabilidade aprimoradas                                                                                                     |
    | ID do Requisito        | [ENT03](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT03)                       |
    | Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT03)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito envolve a implementação de ferramentas que melhorem a usabilidade do aplicativo, garantindo que os usuários possam navegar e utilizar todas as funcionalidades de maneira intuitiva e eficiente.                                                                  |


    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF21 - Otimização do processo de busca diária."

    #### Requisito RF21

    A Tabela 22 apresenta os detalhes do requisito RF21, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 22:</b> Otimização do processo de busca diária.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Otimização do processo de busca diária                                                                                                                  |
    | ID do Requisito        | [ENT04](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT04)                       |
    | Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT04)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito visa a implementação de melhorias no processo de busca diária dentro do aplicativo, tornando-o mais eficiente e rápido para os usuários.                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF22 - Suporte multilíngue no sistema."

    #### Requisito RF22

    A Tabela 23 apresenta os detalhes do requisito RF22, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 23:</b> Suporte multilíngue no sistema.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Suporte multilíngue no sistema                                                                                                                |
    | ID do Requisito        | [ENT05](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT05)                       |
    | Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT05)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito aborda a necessidade de suporte multilíngue no sistema, permitindo que usuários de diferentes línguas possam acessar e utilizar o aplicativo com facilidade.                                                                     |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF23 - Sistema de notificações personalizadas."

    #### Requisito RF23

    A Tabela 24 apresenta os detalhes do requisito RF23, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 24:</b> Sistema de notificações personalizadas.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Sistema de notificações personalizadas                                                                                                    |
    | ID do Requisito        | [ENT06](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT06)                       |
    | Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT06)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito refere-se à implementação de um sistema de notificações personalizadas, permitindo que os usuários recebam alertas relevantes de acordo com suas preferências e interesses.                                                                 |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF24 - Interface do usuário altamente intuitiva."

    #### Requisito RF24

    A Tabela 25 apresenta os detalhes do requisito RF24, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 25:</b> Interface do usuário altamente intuitiva.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Interface do usuário altamente intuitiva                                                                                                               |
    | ID do Requisito        | [ENT08](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT08)                       |
    | Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT08)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito envolve a criação de uma interface de usuário que seja altamente intuitiva, facilitando a navegação e a utilização do aplicativo por todos os usuários, independentemente de seu nível de experiência.                                                                 |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF25 - Funcionalidades avançadas de documentos."

    #### Requisito RF25

    A Tabela 26 apresenta os detalhes do requisito RF25, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 26:</b> Funcionalidades avançadas de documentos.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Funcionalidades avançadas de documentos                                                                                                          |
    | ID do Requisito        | [ENT10](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT10)                       |
    | Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT10)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito se refere à implementação de funcionalidades avançadas de manipulação e gerenciamento de documentos, oferecendo maior flexibilidade e eficiência no uso do aplicativo.                                                                 |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RF26 - Melhoria na interação entre usuários."

    #### Requisito RF26

    A Tabela 27 apresenta os detalhes do requisito RF26, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 27:</b> Melhoria na interação entre usuários.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Melhoria na interação entre usuários                                                                                                       |
    | ID do Requisito        | [ENT11](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT11)                       |
    | Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT11)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Este requisito aborda a melhoria na interação entre usuários dentro do aplicativo, promovendo uma comunicação mais eficaz e colaborativa entre os membros da comunidade.                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

## <a>Tabela de Níveis dos Requisitos Não Funcionais</a>

A seguir, serão apresentadas as tabelas que contêm os requisitos não funcionais do projeto. Essas tabelas detalham informações cruciais sobre cada requisito, permitindo um rastreamento eficaz e uma compreensão clara no contexto do projeto.

??? "RNF01 - Alta disponibilidade do sistema, com 99,9% de uptime."

    #### Requisito RNF01

    A Tabela 28 apresenta os detalhes do requisito RNF01, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 28:</b> Alta disponibilidade do sistema, com 99,9% de uptime.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Alta disponibilidade do sistema, com 99,9% de uptime.                                                                                              |
    | ID do Requisito        | [OBS10](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS10)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS10)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Ambiental** - Este requisito garante que o sistema esteja disponível e operacional a maior parte do tempo, minimizando interrupções no serviço oferecido aos usuários.                                                                 |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF02 - Compatibilidade com as versões mais recentes de sistemas operacionais móveis."

    #### Requisito RNF02

    A Tabela 29 apresenta os detalhes do requisito RNF02, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 29:</b> Compatibilidade com as versões mais recentes de sistemas operacionais móveis.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Compatibilidade com as versões mais recentes de sistemas operacionais móveis.                                                                                                                |
    | ID do Requisito        | [OBS11](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS11)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS11)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito assegura que o aplicativo funcionará corretamente nas versões mais recentes dos sistemas operacionais móveis, proporcionando uma melhor experiência para os usuários.                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF03 - Design responsivo que se adapta a tablets e smartphones."

    #### Requisito RNF03

    A Tabela 30 apresenta os detalhes do requisito RNF03, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 30:</b> Design responsivo que se adapta a tablets e smartphones.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Design responsivo que se adapta a tablets e smartphones.                                                                                                    |
    | ID do Requisito        | [OBS12](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS12)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS12)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito envolve a criação de um design que se adapte automaticamente a diferentes tamanhos de tela, garantindo uma experiência de usuário consistente e agradável em tablets e smartphones.                                                                 |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF04 - Segurança de dados com criptografia de ponta-a-ponta."

    #### Requisito RNF04

    A Tabela 31 apresenta os detalhes do requisito RNF04, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 31:</b> Segurança de dados com criptografia de ponta-a-ponta.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Segurança de dados com criptografia de ponta-a-ponta.                                                                                                               |
    | ID do Requisito        | [OBS13](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS13)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS13)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Este requisito assegura a proteção das informações dos usuários através de criptografia de ponta-a-ponta, garantindo que os dados estejam seguros durante a transmissão e o armazenamento.                                                                 |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF05 - Suporte multilíngue para facilitar o acesso por usuários não-nativos."

    #### Requisito RNF05

    A Tabela 32 apresenta os detalhes do requisito RNF05, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 32:</b> Suporte multilíngue para facilitar o acesso por usuários não-nativos.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Suporte multilíngue para facilitar o acesso por usuários não-nativos.                                                                                                          |
    | ID do Requisito        | [OBS14](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS14)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS14)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito garante que o sistema suporte múltiplas línguas, permitindo que usuários de diferentes nacionalidades possam utilizar o aplicativo em seu idioma nativo.                                                                 |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF06 - Tempo de resposta de busca inferior a 2 segundos."

    #### Requisito RNF06

    A Tabela 33 apresenta os detalhes do requisito RNF06, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 33:</b> Tempo de resposta de busca inferior a 2 segundos.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Tempo de resposta de busca inferior a 2 segundos.                                                                                              |
    | ID do Requisito        | [OBS15](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS15)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS15)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito visa garantir que as consultas ao sistema sejam rápidas e eficientes, melhorando a experiência do usuário e a usabilidade do aplicativo.                                                                 |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF07 - Implementação de medidas de acessibilidade para usuários com deficiência."

    #### Requisito RNF07

    A Tabela 34 apresenta os detalhes do requisito RNF07, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 34:</b> Implementação de medidas de acessibilidade para usuários com deficiência.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Implementação de medidas de acessibilidade para usuários com deficiência.                                                                                                                |
    | ID do Requisito        | [OBS16](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS16)                       |
    | Origem

                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS16)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito garante que o sistema seja acessível a todos os usuários, incluindo aqueles com deficiência, seguindo as melhores práticas de acessibilidade.                                                                  |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF08 - Facilidade de atualização de conteúdo pelo gestor do sistema."

    #### Requisito RNF08

    A Tabela 35 apresenta os detalhes do requisito RNF08, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 35:</b> Facilidade de atualização de conteúdo pelo gestor do sistema.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Facilidade de atualização de conteúdo pelo gestor do sistema.                                                                                                    |
    | ID do Requisito        | [OBS17](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS17)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS17)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Este requisito assegura que o gestor do sistema possa atualizar o conteúdo de forma eficiente e sem complicações, garantindo a atualização contínua das informações disponíveis.                                                                 |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF09 - Suporte técnico com tempo de resposta de 24 horas."

    #### Requisito RNF09

    A Tabela 36 apresenta os detalhes do requisito RNF09, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 36:</b> Suporte técnico com tempo de resposta de 24 horas.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Suporte técnico com tempo de resposta de 24 horas.                                                                                                               |
    | ID do Requisito        | [OBS18](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS18)                       |
    | Origem                 | [Observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#OBS18)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Este requisito assegura que o suporte técnico esteja disponível para resolver problemas de usuários em um tempo máximo de 24 horas, melhorando a confiabilidade e a satisfação do usuário.                                                                 |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF10 - O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar."

    #### Requisito RNF10

    A Tabela 37 apresenta os detalhes do requisito RNF10, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 37:</b> O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar.                                                                                                          |
    | ID do Requisito        | [IS09](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS09)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS09)                 |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Este requisito visa garantir que o aplicativo seja fácil de usar e que os usuários possam navegar pela interface de forma intuitiva, melhorando a usabilidade geral.                                                                 |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF11 - O aplicativo deve garantir a segurança e a privacidade dos dados dos usuários."

    #### Requisito RNF11

    A Tabela 38 apresenta os detalhes do requisito RNF11, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 38:</b> O aplicativo deve garantir a segurança e a privacidade dos dados dos usuários.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve garantir a segurança e a privacidade dos dados dos usuários.                                                            |
    | ID do Requisito        | [IS10](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS10)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS10)               |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Garantir que os dados dos usuários sejam protegidos contra acessos não autorizados e violações de privacidade.                             |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF12 - O aplicativo deve estar disponível 24/7, com exceção de períodos de manutenção programada."

    #### Requisito RNF12

    A Tabela 39 apresenta os detalhes do requisito RNF12, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 39:</b> O aplicativo deve estar disponível 24/7, com exceção de períodos de manutenção programada.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve estar disponível 24/7, com exceção de períodos de manutenção programada.                                                 |
    | ID do Requisito        | [IS11](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS11)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS11)               |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Assegurar que o sistema esteja sempre disponível para os usuários, exceto durante a manutenção programada.                                             |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF13 - O aplicativo deve apresentar um tempo de resposta rápido (< 2 segundos) nas buscas."

    #### Requisito RNF13

    A Tabela 40 apresenta os detalhes do requisito RNF13, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 40:</b> O aplicativo deve apresentar um tempo de resposta rápido (< 2 segundos) nas buscas.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve apresentar um tempo de resposta rápido (< 2 segundos) nas buscas.                                                       |
    | ID do Requisito        | [IS12](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS12)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS12)               |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Garantir que o sistema responda rapidamente às consultas dos usuários.                                                             |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF14 - O aplicativo deve ser acessível de acordo com os padrões da WCAG 2.1."

    #### Requisito RNF14

    A Tabela 41 apresenta os detalhes do requisito RNF14, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 41:</b> O aplicativo deve ser acessível de acordo com os padrões da WCAG 2.1.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve ser acessível de acordo com os padrões da WCAG 2.1.                                                                     |
    | ID do Requisito        | [IS13](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS13)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS13)               |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Ambiental** - Assegurar que o sistema esteja em conformidade com os padrões de acessibilidade web estabelecidos.                                                |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF15 - O aplicativo deve ter um mecanismo robusto de backup e recuperação de dados."

    #### Requisito RNF15

    A Tabela 42 apresenta os detalhes do requisito RNF15, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 42:</b> O aplicativo deve ter um mecanismo robusto de backup e recuperação de dados.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve ter um mecanismo robusto de backup e recuperação de dados.                                                              |
    | ID do Requisito        | [IS14](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS14)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS14)               |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Garantir que os dados possam ser recuperados de forma segura e eficiente em caso de falhas ou desastres.

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF16 - O aplicativo deve ser escalável para acomodar um crescente número de usuários e documentos."

    #### Requisito RNF16

    A Tabela 43 apresenta os detalhes do requisito RNF16, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 43:</b> O aplicativo deve ser escalável para acomodar um crescente número de usuários e documentos.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve ser escalável para acomodar um crescente número de usuários e documentos.                                                |
    | ID do Requisito        | [IS15](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS15)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS15)               |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Desenvolvimento** - Garantir que o sistema possa crescer e se adaptar a um aumento na carga de trabalho sem comprometer o desempenho.                       |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>

??? "RNF17 - O aplicativo deve oferecer suporte multilíngue para atender a uma base de usuários diversificada."

    #### Requisito RNF17

    A Tabela 44 apresenta os detalhes do requisito RNF17, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 44:</b> O aplicativo deve oferecer suporte multilíngue para atender a uma base de usuários diversificada.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | O aplicativo deve oferecer suporte multilíngue para atender a uma base de usuários diversificada.                                          |
    | ID do Requisito        | [IS16](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS16)                       |
    | Origem                 | [Introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#IS16)               |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Ambiental** - Assegurar que o sistema possa ser utilizado por usuários que falam diferentes idiomas, facilitando a inclusão.                                                 |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</pt></fo - >

??? RNF18 "Medidas de segurança robustas."

    #### Requisito RNF18

    A Tabela 45 apresenta os detalhes do requisito RNF18, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 45:</b> Medidas de segurança robustas.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Medidas de segurança robustas                                                                                                             |
    | ID do Requisito        | [ENT07](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT07)                            |
    | Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT07)                       |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Organizacional** - Implementar medidas rigorosas para proteger o sistema contra ameaças de segurança, garantindo a integridade e confidencialidade dos dados.               |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font >

??? - RNF19 "Requisitos para suporte e manutenção."

    #### Requisito RNF19

    A Tabela 46 apresenta os detalhes do requisito RNF19, incluindo informações sobre sua origem, nível e descrição.

    <p style="text-align: center"><b>Tabela 46:</b> Requisitos para suporte e manutenção.</p>

    | Informações            | Detalhes                                                                                                                                  |
    |------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
    | Nome do Requisito      | Requisitos para suporte e manutenção                                                                                                      |
    | ID do Requisito        | [ENT09](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT09)                            |
    | Origem                 | [Entrevista](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoElicitacao/#ENT09)                       |
    | Nível (ambiental, organizacional, gerencial ou desenvolvimento) | **Gerencial** - Definir requisitos claros para o suporte e a manutenção do sistema, assegurando que ele permaneça operacional e atualizado ao longo do tempo.                     |

    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky).</p></font>


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
|`1.0`|15/06/2024|16/06/2024|Criação do Documento, inserção da introdução e da metodologia. | [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky) | [Douglas Marinho](https://github.com/M4RINH0)|
|`1.1`|23/06/2024|16/06/2024|Inserção das tabelas e dos requisitos. | [Arthur Alves](https://github.com/Arthrok) e [Eric Silveira](https://github.com/ericbky) | [Douglas Marinho](https://github.com/M4RINH0), [Diego Sousa](https://github.com/DiegoSousaLeite) e [João Artur](https://github.com/joao-artl)|