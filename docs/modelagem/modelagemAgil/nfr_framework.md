## <a> Introdução </a>

O **Non-Functional Requirements (NFR) Framework** é uma abordagem estruturada para tratar os requisitos não funcionais em projetos de engenharia de software. Requisitos não funcionais são aqueles que definem atributos de qualidade do sistema, como desempenho, segurança, usabilidade e confiabilidade, que são críticos para o sucesso do software, mas que não dizem respeito diretamente às funcionalidades específicas do sistema.<a id="anchor_1" href="#REF1">^1^</a>

Proposto por Lawrence Chung e colaboradores, o NFR Framework visa integrar esses requisitos ao processo de desenvolvimento de software de maneira sistemática. O framework trata os requisitos não funcionais como "softgoals", que são metas qualitativas e subjetivas, e fornece uma estrutura para representar, refinar e analisar esses softgoals.  <a id="anchor_1" href="#REF1">^1^</a>

## <a> Softgoal Interdependency Graph (SIG) </a>

O **Softgoal Interdependency Graph (SIG)** é uma ferramenta central dentro do NFR Framework que facilita a modelagem e a análise de requisitos não funcionais. O SIG permite a visualização das interdependências entre diferentes softgoals e ajuda a entender como diferentes soluções contribuem para a satisfação desses requisitos.<a id="anchor_1" href="#REF1">^1^</a>

### <a> Identificação e Representação dos Softgoals </a>

No SIG, os requisitos não funcionais são inicialmente identificados como softgoals. Esses softgoals são representados como nós no gráfico e refletem as aspirações e preocupações dos stakeholders, como exemplo na Figura 1. Cada softgoal é expresso de maneira qualitativa, permitindo uma compreensão mais ampla e flexível dos objetivos de qualidade do sistema.

### <a> Refinamento dos Softgoals </a>

Os softgoals são refinados em subgoals, que detalham as características específicas necessárias para satisfazer os requisitos não funcionais. Este refinamento pode ocorrer em vários níveis, permitindo uma decomposição detalhada dos objetivos de qualidade. Cada nível de refinamento oferece uma visão mais granular das metas a serem alcançadas.
 
### <a> Estabelecimento de Contribuições </a>

As relações de contribuição entre os diferentes softgoals e subgoals são estabelecidas. Essas contribuições podem ser positivas, negativas ou neutras e são representadas como arestas no gráfico. A análise dessas contribuições permite visualizar os trade-offs entre diferentes requisitos não funcionais, ajudando a identificar possíveis conflitos e sinergias.

### <a> Construção e Análise do SIG </a>

O SIG é construído com base nos softgoals, subgoals e nas relações de contribuição identificadas. Este gráfico fornece uma visualização clara das interdependências entre os requisitos não funcionais e facilita a análise das alternativas e soluções, como exemplo na Figura 1. A análise do SIG permite uma avaliação das opções de design e uma justificativa racional para as decisões tomadas.

### <a> Aplicação do SIG </a>

A aplicação do SIG no processo de desenvolvimento de software garante que os requisitos não funcionais sejam considerados de maneira explícita e estruturada. Ele fornece uma base sólida para a discussão e documentação das decisões de design, promovendo a rastreabilidade e a compreensão dos trade-offs envolvidos.

<font size="3"><p style="text-align: center"><b>Figura 1:</b> NFR Framework</p></font>

<p align="center">
  <img src="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/main/docs/modelagem/images/nfr.png?raw=true" alt="NFR Framework" />
</p>
<font size="3"><p style="text-align: center">Fonte: JANEIRO, José. GOMES, Joaquim. 2007/2008</p></font>

## <a> Metodologia </a>

1. **Identificação dos Softgoals**: Requisitos não funcionais são identificados e expressos como softgoals.
2. **Refinamento dos Softgoals**: Softgoals são detalhados em subgoals para especificar características específicas.
3. **Estabelecimento de Contribuições**: Relações de contribuição entre softgoals e subgoals são identificadas.
4. **Construção do Softgoal Interdependency Graph (SIG)**: Um gráfico é construído para visualizar interdependências e trade-offs.
5. **Análise e Racionalização**: Alternativas e soluções são analisadas para suportar decisões de design.

## <a> NFR 00 - Geral </a>

A Figura 2 a seguir demonstra o Softgoal Interdependency Graph para se ter uma visão geral.


<font size="3"><p style="text-align: center"><b>Figura 2</b> - SIG Geral</p></font>
<figure markdown class="usecaseElement">

![SIG GERAL](../assets/geralnfr.png)

</figure>
<font size="3"><p style="text-align: center"> Fonte: SILVA, 2019</p></font>

No entanto, dada a limitação do grupo de trabalhar apenas com Requisitos Não-Funcionais ainda não implementados pelo aplicativo, adaptou-se o SIG acima para a utilização dos tópicos necessários, presentes na Figura 3.

<font size="3"><p style="text-align: center"><b>Figura 3</b> - SIG Geral Adaptado</p></font>
<figure markdown class="usecaseElement">

![SIG GERAL](../assets/geralnfr2.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: SILVA, 2019</p></font>

## <a> Cartões de Especificação </a>

Na tabela 1 abaixo, temos o cartão de especificação do softgoal "Usabilidade".

<center>

**Tabela 1** - Cartão de especificação 1 - Usabilidade

| Tópico | Usabilidade/Fácil Aprendizado | 
| :------: | :------: |
| ID | NFR01 |
| Descrição | O requisito de "Usabilidade" refere-se à capacidade do sistema de entregar uma boa experiência interativa para os usuários do aplicativo "DOU". |
| Justificativa | Uma boa Usabilidade é fundamental para garantir que os usuários possam utilizar o aplicativo com eficiência e garantir uma satisfação aos usuários. Com uma interface intuitiva, acessível e eficiente o usuário não vai ter dificuldade em aprender a usar o aplicativo, assim, a chance de abandoná-lo é menor. |
| Origem do Requisito | <a href="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/modelagem/especificacao.md">Especificação suplementar</a> e <a href="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/elicitacao/priorizacao.md">Priorização de Requisitos</a> |
| Critério de Aceitação | <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/especificacao/#usabilidade">Requisitos de Usabilidade de 1 a 6</a> |
| Dependências | Interação do usuário com o sistema e a possibilidade de teste dos requisitos dentro do aplicativo |
| Prioridade | Alta prioridade |
| Conflito | Nenhum |
| História | 26/05/2024 |

_Fonte: [Luiz Gustavo](https://github.com/LuizGust4vo)_

</center>

## NFR 01 - Usabilidade

Os Requisitos utilizados para a confecção da Figura 4 estão presentes na Tabela 5:

- <a href="#RNF01">RNF01</a>: indica que o aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar.
- <a href="#RNF03">RNF03</a>: infere que o aplicativo deve oferecer suporte multilíngue para atender a uma base de usuários diversificada.

<font size="3"><p style="text-align: center"><b>Figura 4</b> - SIG Usabilidade</p></font>

<figure markdown markdown class="usecaseElement">

![SIG Usabilidade](../assets/usabilidade.png){width: 300}

</figure>

<font size="3"><p style="text-align: center"> Fonte: [Douglas Marinho](https://github.com/M4RINH0)</p></font>

</br>

Na tabela 2 abaixo, temos o cartão de especificação do softgoal "Confiabilidade".

<center>

**Tabela 2** - Cartão de especificação 2 - Confiabilidade

| Tópico | Confiabilidade/Segurança | 
| :------: | :------: |
| ID | NFR02 |
| Descrição | O requisito de "Confiabilidade" refere-se à capacidade do sistema de se manter ativo, disponível e seguro  |
| Justificativa | Os critérios de Confiabilidade visam garantir a robustes, resistência a falha e a integridade das informações, aumentando a confiança e credibilidade dos usuários no aplicativo |
| Origem do Requisito | <a href="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/modelagem/especificacao.md">Especificação suplementar</a> e <a href="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/elicitacao/priorizacao.md">Priorização de Requisitos</a> |
| Critério de Aceitação | <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/especificacao/#confiabilidade">Requisitos de Confiabilidade de 1 a 6</a> |
| Dependências | Monitoramento do aplicativo |
| Prioridade | Alta prioridade |
| Conflito | Nenhum |
| História | 26/05/2024 |

_Fonte: [Luiz Gustavo](https://github.com/LuizGust4vo)_

</center>

## NFR 02 - Confiabilidade

Os Requisitos utilizados para a confecção da Figura 5 estão presentes na Tabela 5:

- <a href="#RNF02">RNF02</a>: O aplicativo deve ter um mecanismo robusto de backup e recuperação de dados.
- <a href="#RNF05">RNF05</a>: O sistema deve implementar medidas para prevenir que o usuário realize ações que possam comprometer a integridade do sistema.

<font size="3"><p style="text-align: center"><b>Figura 5</b> - SIG Confiabilidade</p></font>

<figure markdown markdown class="usecaseElement">

![SIG Confiabilidade](../assets/confiabilidade.png){width: 300}

</figure>

<font size="3"><p style="text-align: center"> Fonte: [Henrique Torres](https://github.com/henriqtorresl)</p></font>

</br>

Na tabela 3 abaixo, temos o cartão de especificação do softgoal "Desempenho".

<center>

**Tabela 3** - Cartão de especificação 3 - Desempenho

| Tópico | Desempenho/Eficiência | 
| :------: | :------: |
| ID | NFR03 |
| Descrição | O requisito de "Desempenho" refere-se à capacidade do sistema de operar de maneira eficiente e responsiva, proporcionando tempo de resposta rápido e um uso eficiente dos recursos do sistema. |
| Justificativa | Garantir um bom desempenho é essencial para a satisfação do usuário, pois um sistema lento ou ineficiente pode levar a uma experiência negativa e à insatisfação. Um desempenho otimizado aumenta a produtividade dos usuários e assegura que o sistema possa escalar adequadamente para atender a um grande número de acessos simultâneos, especialmente em picos de demanda. |
| Origem do Requisito | <a href="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/modelagem/especificacao.md">Especificação suplementar</a> e <a href="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/elicitacao/priorizacao.md">Priorização de Requisitos</a> |
| Critério de Aceitação | <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/especificacao/#desempenho">Requisitos de Desempenho de 1 a 6</a> |
| Dependências | Hardware do dispositivo móvel. Qualidade da conexão com a internet |
| Prioridade | Baixa prioridade |
| Conflito | Nenhum |
| História | 26/05/2024 |

_Fonte: [Luiz Gustavo](https://github.com/LuizGust4vo)_

</center>

## NFR 03 - Desempenho

Os Requisitos utilizados para a confecção da Figura 6 estão presentes na Tabela 5:

- <a href="#RNF01">RNF01</a>: O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar.
- <a href="#RNF02">RNF02</a>: O aplicativo deve ter um mecanismo robusto de backup e recuperação de dados.
- <a href="#RNF03">RNF04</a>: Compatibilidade com as versões mais recentes de sistemas operacionais móveis.

<font size="3"><p style="text-align: center"><b>Figura 6</b> - SIG Desempenho</p></font>

<figure markdown markdown class="usecaseElement">

![SIG Desempenho](../assets/desempenho.png){width: 300}

</figure>

<font size="3"><p style="text-align: center"> Fonte: [Henrique Torres](https://github.com/henriqtorresl)</p></font>

</br>

<!-- Na tabela 4 abaixo, temos o cartão de especificação do softgoal "Suportabilidade".

<center>

**Tabela 4** - Cartão de especificação 4 - Suportabilidade

| Tópico | Suportabilidade | 
| :------: | :------: |
| ID | NFR04 |
| Descrição | O requisito de "Suportabilidade" refere-se à capacidade do sistema de ser mantido, atualizado e suportado de forma eficiente e eficaz. Isso inclui a facilidade de diagnóstico de problemas, a aplicação de correções e atualizações, e a disponibilização de suporte técnico adequado. |
| Justificativa | Suportabilidade é crucial para assegurar a continuidade e a evolução do sistema. Um sistema que é fácil de manter e atualizar reduz o tempo de inatividade e os custos associados à manutenção. Além disso, a capacidade de diagnosticar e corrigir problemas rapidamente garante que o sistema permaneça confiável e disponível para os usuários. Isso é especialmente importante em um ambiente de produção, onde a confiabilidade e a disponibilidade contínua são essenciais. |
| Origem do Requisito | <a href="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/modelagem/especificacao.md">Especificação suplementar</a> e <a href="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/elicitacao/priorizacao.md">Priorização de Requisitos</a> |
| Critério de Aceitação | <a href="https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/especificacao/#suportabilidade">Requisitos de Suportabilidade de 1 a 4</a> |
| Dependências | Equipe técnica de desenvolvimento |
| Prioridade | Média prioridade |
| Conflito | Nenhum |
| História | 26/05/2024 |

_Fonte: [Luiz Gustavo](https://github.com/LuizGust4vo)_

</center> -->

## <a> Requisitos Não-Funcionais </a>

Para aplicarmos a técnica do NFR Framework, identificamos alguns Requisitos Não-Funcionais que não foram implementados. A Tabela 5, apresentada abaixo, detalha esses requisitos.

<center>

**Tabela 5** - Requisitos Não-Funcionais Não Implementados

| ID    | Descrição                                                                                   | Rastreabilidade                                                                                                                                                                     | Implementação |
| ----- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| <a id="RNF01">RNF01</a> | O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar.                | [AI07](../../elicitacao/tecnicas/analise-de-interface.md#requisitos-não-funcionais), [IS09](../../elicitacao/tecnicas/introspeccao.md#não-funcionais)                                                                                               | Não           |
| <a id="RNF02">RNF02</a> | O aplicativo deve ter um mecanismo robusto de backup e recuperação de dados.                | [AI10](../../elicitacao/tecnicas/analise-de-interface.md#requisitos-não-funcionais),  [IS14](../../elicitacao/tecnicas/introspeccao.md#não-funcionais)                                                                                                                    | Não           |
| <a id="RNF03">RNF03</a> | O aplicativo deve oferecer suporte multilíngue para atender a uma base de usuários diversificada. | [IS16](../../elicitacao/tecnicas/introspeccao.md#não-funcionais),  [OBS14](../../elicitacao/tecnicas/observacao.md#não-funcioanais)                                                                                                                             | Não           |
| <a id="RNF04">RNF04</a> | Compatibilidade com as versões mais recentes de sistemas operacionais móveis.               | [OBS11](../../elicitacao/tecnicas/observacao.md#não-funcioanais)                                                                                                                                                  | Não           |
| <a id="RNF05">RNF05</a> | O sistema deve implementar medidas para prevenir que o usuário realize ações que possam comprometer a integridade do sistema.               | [CON06](../especificacao.md#confiabilidade)                                                                                                                                                  | Não           |

_Fonte: [Henrique Torres](https://github.com/henriqtorresl)_
</center>

## <a> Referência Bibliográfica </a>

> <a id="REF1" href="#anchor_1">1.</a> Chung, L., Nixon, B. A., Yu, E., Mylopoulos, J. Non-functional requirements in software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.

> <a id="REF2" href="#anchor_1">2.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: https://repositorio.ufpe.br/handle/123456789/34150. Acesso em: 26/05/2024.

## <a> Bibliografia </a>

> JANEIRO, José. GOMES, Joaquim. NFR Framework. ESTIC, Brasil, 2008. Disponível em: [http://jaejaneiro.orgfree.com/engsofnfr.pdf](http://jaejaneiro.orgfree.com/engsofnfr.pdf). Acesso em: 25/05/2024.
>
> NFR Framework. Disponível em: <https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/agil/nfr-framework/>. Acesso em 26 de maio de 2024.
>
> NFR Framework. Disponível em: <https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/nfr/>. Acesso em 26 de Maio de 2024.

## <a> Histórico de versão </a>

| Versão | Data | Data Prevista de Revisão | Descrição | Autor | Revisor |
| :------: | :----------: |:-----------: | :----------------------: | :---------: |:---------: |
| `1.0` | 25/05/2024 | 25/05/2024 | Criação da Documentação e conceitos sobre o NFR | [Douglas Marinho](https://github.com/M4RINH0) | [Arthur Alves](https://github.com/Arthrok) |
| `1.1` | 26/05/2024 | 27/05/2024 | Criação dos cartões de especificação | [Luiz Gustavo](https://github.com/LuizGust4vo) | [Eric Silveira](https://github.com/ericbky) |
| `1.2` | 27/05/2024 | 27/05/2024 | Adição do NFR 00 E NFR 01 | [Douglas Marinho](https://github.com/M4RINH0) | [Eric Silveira](https://github.com/ericbky) |
| `1.3` | 27/05/2024 | 27/05/2024 | Adição do NFR 02 E NFR 03 | [Henrique Torres](https://github.com/henriqtorresl) | [Eric Silveira](https://github.com/ericbky) |
| `1.4` | 27/05/2024 | 27/05/2024 | Criação da parte relacionada aos requisitos não-funcionais | [Henrique Torres](https://github.com/henriqtorresl) | [Eric Silveira](https://github.com/ericbky) |