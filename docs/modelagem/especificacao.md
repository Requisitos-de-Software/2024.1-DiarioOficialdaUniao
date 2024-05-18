## <a> Introdução </a>
A Especificação Suplementar abrange os requisitos do sistema que não são diretamente capturados nos casos de uso do modelo de caso de uso. Estes requisitos incluem: requisitos legais e regulamentares, como padrões de aplicativos; atributos de qualidade do sistema, tais como usabilidade, confiabilidade, desempenho e suportabilidade; além de outros requisitos, como sistemas e ambientes operacionais, compatibilidade e restrições de design.<a id="anchor_1" href="#REF1">^1^</a> Ela complementa os [casos de uso](../modelagem/useCase.md), capturando os requisitos do sistema que não foram elicitados pelo método anterior.

Para a especificação suplementar, o grupo decidiu adotar o modelo **FURPS+**.

## <a> Finalidade </a>
A finalidade deste documento é definir os requisitos do sistema Diário Oficial da União. Esta Especificação Suplementar detalha os requisitos que não são diretamente capturados nos casos de uso do modelo de casos de uso. Juntas, as Especificações Suplementares e o modelo de casos de uso fornecem um conjunto completo de requisitos do sistema.

## <a> Escopo </a>
O objetivo do aplicativo Diário Oficial da União é facilitar o acesso e a consulta das publicações oficiais para cidadãos, empresas e órgãos governamentais, permitindo que se mantenham informados sobre atos legislativos, administrativos e judiciais de maneira prática e eficiente.

## <a> Metodologia FURPS+ </a>
FURPS+<a id="anchor_2" href="#REF2">^2^</a> é um sistema para a classificação de requisitos e a identificação dos que devem ser incluídos em um projeto em desenvolvimento. A sigla representa as seguintes cinco categorias:

- **Functionality (Funcionalidade):** representa todos os aspectos funcionais do software, ou seja, seus requisitos. Esta categoria possui diversas subcategorias que variam conforme a aplicação. Sua medição considera, principalmente, o cumprimento dos requisitos especificados.

- **Usability (Usabilidade):** este atributo avalia a interface com o usuário e possui diversas subcategorias, incluindo prevenção de erros, estética e design, ajuda e documentação, consistência e padrões.

- **Reliability (Confiabilidade):** refere-se à integridade, conformidade e interoperabilidade do software. Os requisitos a serem considerados incluem a frequência e gravidade das falhas, capacidade de recuperação, previsibilidade, exatidão e tempo médio entre falhas (MTBF).

- **Performance (Desempenho):** avalia os requisitos de desempenho do software, utilizando diversas métricas, como tempo de resposta, consumo de memória, utilização da CPU, capacidade de carga e disponibilidade da aplicação.

- **Supportability (Suportabilidade):** os requisitos de suportabilidade abrangem várias características, incluindo testabilidade, adaptabilidade, manutenibilidade, compatibilidade, configurabilidade, instalabilidade, escalabilidade, localizabilidade, entre outros.

- **O simbolo "+":** inclui outros requisitos não funcionais que devem ser considerados, como requisitos de design, implementação, interface e requisitos físicos. Esses requisitos adicionais podem restringir o design, a construção e o funcionamento do sistema, incluindo limitações físicas do hardware.

Por fim, o modelo FURPS+ é uma abordagem abrangente para classificar e definir os requisitos de software, considerando diversas dimensões de qualidade e funcionalidade. É uma ferramenta valiosa para orientar o processo de desenvolvimento de software e garantir que todos os requisitos essenciais sejam abordados.

## <a> Metodologia FURPS+ aplicada ao Diario Oficial da União </a>

### <a> Funcionalidade </a>
Na seção de elicitação, foram identificados os requisitos funcionais e a tabela 2 das páginas das técnicas de requisitos de [introspecção](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/introspeccao/#funcionais) e [observação](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/observacao/#requisitos-funcionais) e a tabela 1 da [análise de interface](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/elicitacao/tecnicas/analise-de-interface/#requisitos-funcionais).


## <a> Usabilidade </a>
A Tabela 1 lista os requisitos essenciais de usabilidade para o aplicativo Diário Oficial da União. Desenvolvidos para garantir uma interface intuitiva, acessível e eficiente, esses requisitos abrangem compatibilidade com modos de alto contraste, design acessível e caminhos simplificados para realizar tarefas. O objetivo é proporcionar uma experiência de usuário melhorada, facilitando o uso e aumentando a satisfação do usuário.

<font><p style="text-align: center">**Tabela 1** - Requisitos de Usabilidade.</p></font>

<center>

| ID    | Descrição                                                                                                                                |
| ----- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| USA01 | O sistema deve ser compatível com a opção de alto contraste, exibindo cores apropriadas para essa configuração.                         |
| USA02 | O aplicativo deve incorporar e destacar recursos de acessibilidade em seu design.|
| USA03 | O sistema deve dar feedback ao [usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuario), com pop ups e mensagens, por exemplo, ao ter um [Diário Publicado](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l05-diario-publicado).                                                                         |
| USA04 | O aplicativo deve oferecer uma interface padronizada que garanta conforto visual ao usuário, seguindo os princípios de ergonomia no design de UI <a id="anchor_3" href="#REF3">^3^</a>.                                |
| USA05 | O sistema deve prevenir que o [usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuario) execute passos repetitivos. |
| USA06 | O sistema deve oferecer caminhos curtos para a realização de tarefas complexas, garantindo que estas possam ser concluídas em no máximo 5 cliques.                                                                          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Diego Sousa](https://github.com/DiegoSousaLeite).</p></font>

## <a> Confiabilidade </a>
A Tabela 2 destaca os requisitos essenciais de confiabilidade para o aplicativo Diário Oficial da União. Esses requisitos incluem a disponibilidade contínua dos servidores. Esses critérios visam garantir que o software seja robusto, resistente a falhas e capaz de manter a integridade das informações, aumentando a confiança dos usuários no sistema.

<font><p style="text-align: center">**Tabela 2** - Requisitos de Confiabilidade.</p></font>

<center>

| ID    | Descrição                                                                                                                         |
| ----- | --------------------------------------------------------------------------------------------------------------------------------- |
| CON01 | O sistema deve ser acessível 24 horas por dia, 7 dias por semana, ou seja, de maneira ininterrupta.                                                                 |
| CON02 | O sistema deve possuir as informações atualizadas dos diário oficiais.                                                  |
| CON03 | O aplicativo deve facilitar a identificação das funcionalidades disponíveis, organizando-as de maneira lógica.                                          |
| CON04 | O sistema deve permitir que o [usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuario) se recupere de problemas e erros com no máximo 3 cliques.                                                                       |
| CON05 | O aplicativo deve possuir um sistema de suporte ao [usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuario)                           |
| CON06 |O sistema deve evitar que o [usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuario) execute atividades que possam comprometer a integridade do sistema.                   |                                                                       |

</center>

<font size="3"><p style="text-align: center">Fonte: [Diego Sousa](https://github.com/DiegoSousaLeite).</p></font>

## <a> Desempenho </a>
A Tabela 3 apresenta os requisitos essenciais de desempenho para o aplicativo Diário Oficial da União. Esses requisitos incluem design simplificado, armazenamento eficiente e navegação suave, com o objetivo de garantir um desempenho otimizado do software. Ao atender a esses critérios, o aplicativo busca proporcionar uma experiência de usuário rápida e eficiente, aumentando a produtividade e a satisfação dos usuários.

<font><p style="text-align: center">**Tabela 3** - Requisitos de Desempenho.</p></font>

| ID    | Descrição                                                                                          |
| ----- | -------------------------------------------------------------------------------------------------- |
| DES01 | O sistema deve, mostrar como padrão no máximo 15 diários por página, por exemplo, ao fazer uma busca com [filtragem de publicações](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l01-filtrar-publicacoes).                               |
| DES02 | O sistema deve oferecer uma navegação fluida e sem interrupções, com caminhos organizados de forma lógica.                                      |
| DES03 | O aplicativo deve utilizar, no máximo, 1-2% do armazenamento total do dispositivo para cache de dados essenciais..                                  |
| DES04 | O aplicativo deve ter uma interface de design simplificado, seguindo os princípios de ergonomia no design de UI. <a id="anchor_3" href="#REF3">^3^</a> |
| DES05 | É essencial que a aplicação mantenha um consumo de memória razoável, limitado a 50 MB, para evitar problemas em dispositivos com sistemas operacionais desatualizados.          |

<font size="3"><p style="text-align: center">Fonte: [Diego Sousa](https://github.com/DiegoSousaLeite).</p></font>

## <a> Suportabilidade </a>
A Tabela 4 apresenta os requisitos abrangentes de suportabilidade para o LibreOffice Writer. Esses requisitos incluem a disponibilidade de serviços de atendimento ao cliente, recursos de rastreabilidade e tolerância a falhas. O objetivo é garantir que o software seja adaptável, evolutivo e resiliente diante de desafios, proporcionando uma experiência de usuário consistente e confiável ao longo do tempo.

<font><p style="text-align: center">**Tabela 4** - Requisitos de Suportabilidade.</p></font>

| ID    | Descrição                                                                                                                                                                                                                                                                  |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| SUP01 | O sistema deve incluir recursos de rastreabilidade, como mecanismos para registrar e acompanhar mudanças e correções ao longo do tempo, além de controle de versão e registros de alterações.    |
| SUP02 | O sistema deve possuir uma facilidade de manutenção através de uma estrutura modular e código bem organizado.                                                                                                                                                              |
| SUP03 | O sistema deve oferecer suporte ao [usuário](https://requisitos-de-software.github.io/2024.1-DiarioOficialdaUniao/modelagem/lexicos/#l03-usuario) através de canais apropriados e uma equipe disponível. |
| SUP04 | O sistema deve ser altamente testável, permitindo a fácil realização de testes durante o desenvolvimento e a manutenção.     |

<font size="3"><p style="text-align: center">Fonte: [Diego Sousa](https://github.com/DiegoSousaLeite).</p></font>

## <a> Outros requisitos não-funcionais </a>

- **Requisito de Licenciamento:** O sistema deve impor restrições de uso por meio de termos de uso.
- **Requisitos Físicos:** O Diário Oficial da União deve ser compatível com computadores desktop, laptops, tablets e, principalmente, smartphones, onde o aplicativo é disponibilizado.
- **Restrições de Design:** O design do sistema deve seguir boas práticas da indústria, adotando arquitetura limpa, microserviços e componentização. Deve usar cores acessíveis para pessoas com restrições visuais, mantendo a identidade da marca e compatibilidade com diferentes sistemas operacionais.
  
## <a>Referência Bibliográfica</a>
> <a id="REF1" href="#anchor_1">1.</a> MINISTÉRIO DA CIÊNCIA, TECNOLOGIA, INOVAÇÕES E COMUNICAÇÕES. Secretaria-Executiva. Diretoria de Tecnologia da Informação. Coordenação Geral de Sistemas. Especificação Suplementar. Versão 1.0. Brasília: MCTIC.
> 
> <a id="REF2" href="#anchor_2">2.</a> FERRARI, Fabrício. FURPS+. Qualidade BR, 06 de maio de 2023. Disponível em: <<https://qualidadebr.wordpress.com/2008/07/10/furps/>>. Acesso em: 17 de maio de 2024
>
> <a id="REF3" href="#anchor_3">3.</a>CH34. 11 principais princípios de ergonomia no design de UI. Disponível em: <<https://www.ch34.com.br/post/11-principais-princ%C3%ADpios-de-ergonomia-no-design-de-ui>>. Acesso em: 17 de maio de 2024.


## <a>Bibliografia</a>
> GOIS, Samily Rocha; SOBRINHO, Francisco Luiz. Especificação Suplementar: Projeto de Software Floricultura Beija-Flor. Versão 101.6. PHP Software Company, 2012.
> 
> REPOSITÓRIO DE REQUISITOS DE SOFTWARE. Especificação Suplementar. 2023. Disponível em: <<https://requisitos-de-software.github.io/2023.2-LibreOffice/modelagem/especificacaoSuplementar/#referencias-bibliograficas>>. Acesso em: 17 de maio de 2024.

## <a> Histórico de Versão </a>

| Versão | Data | Data Prevista de Revisão | Descrição | Autor | Revisor |
| :------: | :----------: | :-----------: | :-----------: | :---------: | :---------: |
| `1.0` | 17/05/2024 | 19/05/2024 | Criação do documento  | [Diego Sousa](https://github.com/DiegoSousaLeite) | [Arthur Alves](https://github.com/Arthrok) e [João Artur](https://github.com/joao-artl) |
| `1.1` | 18/05/2024 | 19/05/2024 | Correções no texto  | [Diego Sousa](https://github.com/DiegoSousaLeite) | [Arthur Alves](https://github.com/Arthrok) e [João Artur](https://github.com/joao-artl) |