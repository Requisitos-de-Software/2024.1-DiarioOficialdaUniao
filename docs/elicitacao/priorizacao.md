# Priorização

## <a>Introdução</a>

As técnicas de priorização de requisitos têm como principal objetivo ajudar os projetos de desenvolvimento de software a determinar quais requisitos são mais importantes, essenciais ou urgentes para serem implementados. Isso é crucial porque, em qualquer projeto de software, há uma quantidade limitada de recursos, como tempo, dinheiro e mão de obra. Portanto, é fundamental garantir que esses recursos sejam alocados da maneira mais eficiente possível para atender às necessidades e expectativas dos clientes ou usuários finais.

## <a>Participantes</a>

No dia 16 de abril de 2024, às 19h30, foi realizada uma reunião online entre três membros da equipe e o usuário José Roberto, servidor público do TST, utilizando a plataforma [Microsoft Teams](https://teams.microsoft.com). Durante a reunião, eles discutiram e priorizaram os requisitos do projeto, colaborando ativamente para identificar e classificar as necessidades essenciais. Isso garantiu um alinhamento estratégico e eficiente para as próximas etapas do projeto. A ata da reunião de priorização está disponível em [Link da ata](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/reuniao/reuniaoPriorizacao/#5-encaminhamentos). A tabela 1 apresenta os participantes da reunião.

<font size="3"><p style="text-align: center">Tabela 1: Participantes.</p></font>

<center>

| Nome                                             | Função                   |
| ------------------------------------------------ | ------------------------ |
|[Douglas Marinho](https://github.com/M4RINH0) | Entrevistador              |
|[João Artur](https://github.com/joao-artl) | Entrevistador              |
|[Luiz Gustavo](https://github.com/LuizGust4vo) | Entrevistador              |
| José Roberto | Usuário |

</center>

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>

## <a>Técnicas Utilizadas</a>

  - [Three Level Scale](#three-level-scale)
  - [MoSCoW](#moscow)
  - [In or Out](#in-or-out)

## <a>Three Level Scale</a>

Na abordagem da técnica de priorização Three Level Scale, os requisitos são divididos em três categorias de acordo com sua prioridade relativa: alta, média e baixa. Este método foi aplicado por um desenvolvedor em conjunto com um usuário, onde o desenvolvedor desempenhou o papel de facilitador, orientando o usuário durante o processo.

A chave para o sucesso dessa técnica reside na concordância das partes interessadas sobre o significado de cada nível de prioridade na escala. Assim, durante o processo de priorização, consideramos tanto a urgência quanto a importância de cada requisito. Desta forma, as categorias de prioridade foram definidas da seguinte maneira:

- Alta prioridade: requisitos que são tanto importantes quanto urgentes, e devem ser implementados na próxima release.

- Média prioridade: requisitos importantes, mas que não têm urgência imediata, portanto, podem ser programados para uma release futura.

- Baixa prioridade: requisitos que não são nem importantes nem urgentes, e sua implementação pode ser adiada para um momento posterior.

Embora a técnica não envolva a atribuição de classificações numéricas aos requisitos, mas sim uma categorização em grupos de prioridade, é crucial considerar as dependências entre eles. As interdependências podem influenciar a importância e o impacto dos requisitos, portanto, é recomendado avaliá-las durante o processo de priorização. Dessa forma, as decisões informadas sobre a priorização podem ser tomadas levando em conta todas as interações entre os requisitos.

## <a>MoSCoW</a>

A ideia central do método MoSCoW é classificar os requisitos ou funcionalidades do projeto em quatro categorias, ajudando a equipe a focar nos elementos mais importantes e decisivos para o sucesso do projeto. As quatro categorias formam um acrônimo - Must have, Should have, Could have e Won't have.

- As definições de cada categoria são:
    - **M**ust have: Esses são os requisitos essenciais para que o projeto seja considerado um sucesso. Eles são críticos e não podem ser deixados de fora.
    - **S**hould have: Esses são os requisitos importantes, mas não vitais para o sucesso do projeto. Eles são considerados secundários em relação aos "Must haves", mas ainda são significativos e devem ser incluídos se possível.
    - **C**uld have: Esses são os requisitos desejáveis, mas não essenciais. Eles são considerados opcionais e podem ser incluídos se houver tempo e recursos disponíveis. 
    - **W**on't have: Esses são os requisitos que a equipe decidiu explicitamente não incluir no escopo do projeto, pelo menos na iteração atual. Eles podem ser considerados para futuras versões do projeto, mas não serão abordados no momento. Isso geralmente é feito devido a restrições de tempo, recursos ou prioridades.

## <a>In or Out</a>

A técnica "In or Out" é uma abordagem simples para priorizar requisitos. Consiste em listar os requisitos e, junto com um grupo de stakeholders, tomar uma decisão binária: "Está dentro ou está fora?". Ao aplicar essa técnica, é importante ter em mente os objetivos do negócio e procurar reduzir a lista de requisitos para apenas o mínimo necessário para aquela versão. Posteriormente, ao implementar essa versão, o processo pode ser repetido com os requisitos restantes para a próxima entrega.


## <a>Tabela de Requisitos Priorizados</a>

<figcaption>Tabela 2: Tabela de priorização de requisitos.</figcaption>

| Tipo | Descrição         | <a id="anchor_IS" style="visibility: hidden;"></a> ID | Three Level Scale | MoSCoW | In or Out |
| ---- | ---------------- | ----------------- | ------------ | ---- | --------- |
|RF01|	Autenticação de usuários para acesso seguro.	| OBS01 |  Alto | Must Have | In |
|RF02|	Visualização de edições diárias do Diário Oficial.|	OBS02|  Alto | Must Have | In |
|RF03|	Busca por palavras-chave em documentos.	|OBS03|  Baixo  | Could Have | In |
|RF04|	Filtragem de conteúdo por data, categoria ou órgão emissor.	|OBS04|  Alto | Must Have | In |
|RF05|	Download de edições e documentos em formatos PDF.	|OBS05|  Médio | Won't Have | Out |
|RF06|	Notificações push sobre novas publicações relevantes.|	OBS06|  Médio | Could Have | In |
|RF07|	Acesso a edições anteriores arquivadas.	|OBS07|  Médio | Must Have | In |
|RF08|	Integração com sistemas de assinatura digital.	|OBS08| Baixo | Won't Have| Out |
|RF09|	Compartilhamento de documentos via redes sociais e email.|OBS09 |  Baixo | Must Have | In |
| RF10  | O aplicativo deve permitir buscas detalhadas por tópicos específicos.               | IS01  | Médio             | Could Have | In |
| RF11  | O aplicativo deve oferecer a funcionalidade de salvar documentos para consulta offline. | IS02  | Alto              | Must Have  | In |
| RF12  | O aplicativo deve enviar notificações personalizadas sobre novas publicações relevantes. | IS03  | Médio             | Could Have | In |
| RF13  | O aplicativo deve oferecer acesso ao histórico de publicações legislativas.         | IS04  | Baixo             | Won't Have | Out |
| RF14  | O aplicativo deve ter um sistema de marcadores para rastrear alterações em documentos específicos. | IS05  | Médio  | Could Have | In |
| RF15  | O aplicativo deve fornecer uma interface que facilite a leitura de textos legislativos. | IS06  | Alto   | Must Have  | In |
| RF16  | O aplicativo deve incluir uma funcionalidade de compartilhamento de documentos.     | IS07  | Médio             | Won't Have | Out |
| RF17  | O aplicativo deve manter um índice atualizado e pesquisável de todos os documentos publicados. | IS08  | Baixo | Won't Have | Out |
|RNF01|	Alta disponibilidade do sistema, com 99,9% de uptime.	| OBS10 |  Alto | Won't Have | Out |
|RNF02|	Compatibilidade com as versões mais recentes de sistemas operacionais móveis.|	OBS11|  Médio | Could Have | In |
|RNF03|	Design responsivo que se adapta a tablets e smartphones.	|OBS12| Alto | Must Have | In |
|RNF04|	Segurança de dados com criptografia de ponta-a-ponta.	|OBS13| Alto | Must Have| In |
|RNF05|	Suporte multilíngue para facilitar o acesso por usuários não-nativos.	|OBS14| Médio | Won't Have | Out |
|RNF06|	Tempo de resposta de busca inferior a 2 segundos.|	OBS15| Alto | Must Have | In |
|RNF07|	Implementação de medidas de acessibilidade para usuários com deficiência.	|OBS16| Alto | Must Have | In |
|RNF08|	Facilidade de atualização de conteúdo pelo gestor do sistema.	|OBS17|  Médio | Must Have | In |
|RNF09|	Suporte técnico com tempo de resposta de 24 horas.|OBS18 |  Médio | Must Have | In |
| RNF10 | O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar.        | IS09  | Alto              | Must Have  | In |
| RNF11 | O aplicativo deve garantir a segurança e a privacidade dos dados dos usuários.      | IS10  | Alto              | Must Have  | In |
| RNF12 | O aplicativo deve estar disponível 24/7, com exceção de períodos de manutenção programada. | IS11  | Alto | Must Have  | In |
| RNF13 | O aplicativo deve apresentar um tempo de resposta rápido (< 2 segundos) nas buscas. | IS12  | Alto              | Must Have  | In |
| RNF14 | O aplicativo deve ser acessível de acordo com os padrões da WCAG 2.1.               | IS13  | Médio             | Could Have | In |
| RNF15 | O aplicativo deve ter um mecanismo robusto de backup e recuperação de dados.        | IS14  | Médio             | Won't Have | Out |
| RNF16 | O aplicativo deve ser escalável para acomodar um crescente número de usuários e documentos. | IS15  | Alto | Must Have  | In |
| RNF17 | O aplicativo deve oferecer suporte multilíngue para atender a uma base de usuários diversificada. | IS16  | Médio | Won't Have | Out |


<font size="3"><p style="text-align: center">Fonte: [Douglas Marinho](https://github.com/M4RINH0), [João Artur](https://github.com/joao-artl) e [Luiz Gustavo](https://github.com/LuizGust4vo).</p></font>
</br>

## <a>Gravação da Reunião</a>

<iframe width="640" height="480" src="https://www.youtube.com/embed/VJBoFk9SVfA?si=qF1-Jg9Ru15jWvFv" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## <a>Bibliografia</a>

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 50 slides. color. Disponível no [link](https://aprender3.unb.br/pluginfile.php/2844984/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf). Acesso em 7 de abr. 2024.

> Requisitos de Software. Bilheteria Digital (2023.1). Disponível em: https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital. Acesso em: 10 abr. 2024

> COHN, Mike. Succeeding with Agile: Software Development Using Scrum. Addison-Wesley, 2010. Acesso em: 03 mai. 2024

## <a>Histórico de Versão</a>
|Versão|Data|Data Prevista de Revisão|Descrição|Autor|Revisor|
| :------: | :----------: |:-----------: | :-----------: | :---------: |:---------: |
|`1.0`|07/04/2024|08/04/2024| Criação do documento sobre priorização de requisitos | [João Artur](https://github.com/joao-artl)|[Henrique Torres](https://github.com/henriqtorresl)|
|`1.1`|08/04/2024|08/04/2024| Adicionando seção sobre MoSCoW | [João Artur](https://github.com/joao-artl)|[Luiz Gustavo](https://github.com/LuizGust4vo)|
|`1.2`|10/04/2024|11/04/2024| Correção bug tabela e adicionado fonte nas tabelas | [Arthur Alves](https://github.com/arthrok)|[João Artur](https://github.com/joao-artl)|
|`1.3`|10/04/2024|15/04/2024| Adição do método First Things First | [Douglas Marinho](https://github.com/M4RINH0)|[João Artur](https://github.com/joao-artl)|
|`1.4`|16/04/2024|17/04/2024| Priorização dos requisitos | [Douglas Marinho](https://github.com/M4RINH0), [João Artur](https://github.com/joao-artl) e [Luiz Gustavo](https://github.com/LuizGust4vo) |[Diego Sousa](https://github.com/DiegoSousaLeite) |
|`1.5`|02/05/2024|03/05/2024| Alteração de priorização FTF para In Or Out | [Douglas Marinho](https://github.com/M4RINH0)|[João Artur](https://github.com/joao-artl) |