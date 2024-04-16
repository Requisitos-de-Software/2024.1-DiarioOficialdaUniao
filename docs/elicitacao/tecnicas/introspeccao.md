# Introspecção

## Introdução

A **Introspecção** é uma técnica de elicitação de requisitos que envolve uma profunda reflexão pessoal dos desenvolvedores ou analistas para identificar as necessidades essenciais de um software. Este método exige imaginar-se no lugar dos usuários, antecipando desafios e requisitos críticos através de cenários hipotéticos. Focado na perspectiva interna, facilita a descoberta de insights intuitivos sobre funcionalidades importantes, contribuindo significativamente para o desenvolvimento de soluções mais alinhadas com as expectativas dos usuários.

## Metodologia
O processo de introspecção foi conduzido individualmente pelos estudantes [Diego Sousa](https://github.com/DiegoSousaLeite) e [João Artur](https://github.com/joao-artl) para elicitar os requisitos do aplicativo Diário Oficial da União. A técnica envolveu a reflexão pessoal para imaginar as funcionalidades e características necessárias para atender às necessidades de estudantes usuários do aplicativo. Após a etapa individual, os requisitos identificados foram compilados em duas tabelas, tabela 2 para os requisitos funcionais e tabela 3 para os não funcionais. A equipe então revisou o aplicativo existente para verificar a presença dos requisitos elicitados, avaliando quais já estavam implementados e quais ainda precisavam ser atendidos. Este método permitiu uma análise detalhada e consciente das funcionalidades essenciais para o aplicativo, garantindo uma abordagem sistemática e estruturada na definição dos requisitos.

## Cronograma

<font size="3"><p style="text-align: center">Tabela 1: Participantes.</p></font>

<center>

| Nome                                             | Data                   |  Hora |
| ------------------------------------------------ | ------------------------ | -------------- |
| [Diego Sousa](https://github.com/DiegoSousaLeite)   |  14/04/2024|  14:30 |
| [João Artur](https://github.com/joao-artl) |  16/04/2024|   16:00 |

</center>

<font size="3"><p style="text-align: center">Fonte: [Diego Sousa](https://github.com/DiegoSousaLeite) e [João Artur](https://github.com/joao-artl).</p></font>


## Requisitos elicitados

### [Diego Sousa](https://github.com/DiegoSousaLeite)
Para utilizar o método de introspecção na identificação de requisitos para o aplicativo do Diário Oficial da União, coloquei-me na posição de um estudante que precisa acessar frequentemente este tipo de informação para pesquisas acadêmicas. Sem ter o aplicativo à frente, pensei nas funcionalidades essenciais que facilitariam o meu dia a dia, como a capacidade de fazer buscas rápidas por tópicos específicos, salvar documentos para consulta offline e receber notificações sobre novas publicações relevantes às minhas áreas de estudo. Refleti sobre as dificuldades comuns que enfrento, como a navegação em grandes volumes de dados e a necessidade de encontrar informações históricas de forma eficiente, e como um aplicativo poderia oferecer soluções para esses desafios.

### [João Artur](https://github.com/joao-artl)
No processo de introspecção, imaginei-me como um estudante que utiliza o aplicativo do Diário Oficial da União para se manter atualizado sobre os últimos desenvolvimentos legislativos que podem afetar minha pesquisa e vida acadêmica. Pensei sobre o que eu gostaria que o aplicativo fizesse sem ter uma versão física dele, como ter uma interface amigável que possa ajudar na digestão de informações complexas e um sistema de marcadores para acompanhar alterações em leis ou decretos que são cruciais para o meu campo de estudo. Também levei em conta a importância de acessar estas informações de maneira confiável e segura, considerando a integridade dos dados como um requisito não funcional indispensável.

### Funcionais

Legenda das Tabelas 2 e 3:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- ISx: Requisito nºx elicitado pela introspecção.

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Funcionais.</p></font>

<center>

| Tipo | Descrição                                                   | <a id="anchor_IS" style="visibility: hidden;"></a> ID | Implementado |
| ---- | ----------------------------------------------------------- | ----------------------------------------------------- | ------------ |
| RF01 | O aplicativo deve permitir buscas detalhadas por tópicos específicos.  | IS01                                       | Não          |
| RF02 | O aplicativo deve oferecer a funcionalidade de salvar documentos para consulta offline.      | IS02                 | Sim          |
| RF03 | O aplicativo deve enviar notificações personalizadas sobre novas publicações relevantes. | IS03                     | Não          |
| RF04 | O aplicativo deve oferecer acesso ao histórico de publicações legislativas.      | IS04                             | Não          |
| RF05 | O aplicativo deve ter um sistema de marcadores para rastrear alterações em documentos específicos. | IS05           | Não          |
| RF06 | O aplicativo deve fornecer uma interface que facilite a leitura de textos legislativos.           | IS06            | Sim          |
| RF07 | O aplicativo deve incluir uma funcionalidade de compartilhamento de documentos.        | IS07                       | Sim          |
| RF08 | O aplicativo deve manter um índice atualizado e pesquisável de todos os documentos publicados.   | IS08             | Não          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Diego Sousa](https://github.com/DiegoSousaLeite) e [João Artur](https://github.com/joao-artl).</p></font>


### Não funcionais

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Não-Funcionais.</p></font>

<center>

| Tipo  | Descrição                                     | <a id="anchor_ISNF" style="visibility: hidden;"></a>ID | Implementado |
| ----- | --------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ | ------------ |
| RNF01 | O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar.     | IS09                        | Não         |
| RNF02 | O aplicativo deve garantir a segurança e a privacidade dos dados dos usuários.         | IS10                  | Sim         |
| RNF03 |O aplicativo deve estar disponível 24/7, com exceção de períodos de manutenção programada.      | IS11          | Sim         |
| RNF04 | O aplicativo deve apresentar um tempo de resposta rápido (< 2 segundos) nas buscas.    | IS12                  | Sim         |
| RNF05 | O aplicativo deve ser acessível de acordo com os padrões da WCAG 2.1. | IS13                                   | Sim         |
| RNF06 |O aplicativo deve ter um mecanismo robusto de backup e recuperação de dados.      | IS14                        | Não         |
| RNF07 |O aplicativo deve ser escalável para acomodar um crescente número de usuários e documentos.      | IS15         | Sim         |
| RNF08 | O aplicativo deve oferecer suporte multilíngue para atender a uma base de usuários diversificada. |  IS16      | Nã          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Diego Sousa](https://github.com/DiegoSousaLeite) e [João Artur](https://github.com/joao-artl).</p></font>



## <a>Bibliografia</a>
> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 06):  Elicitação de Requisitos - Técnicas . **UnB Gama**, Brasília, 2024. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2844983/mod_resource/content/4/Elicitacao%20de%20Req%202.pdf>>. Acesso em: 10/04/2024.


## <a>Histórico de Versão</a>
|Versão|Data|Data Prevista de Revisão|Descrição|Autor|Revisor|
| :------: | :----------: |:-----------: | :-----------: | :---------: |:---------: |
|`1.0`|06/04/2024|06/04/2024| Introdução e ideias iniciais | [Diego Sousa](https://github.com/DiegoSousaLeite) e [João Artur](https://github.com/joao-artl)| [Arthur Alves](https://github.com/arthrok) |
|`1.1`|16/04/2024|16/04/2024| Adição da aba de requisitos | [Diego Sousa](https://github.com/DiegoSousaLeite) e [João Artur](https://github.com/joao-artl)| [Arthur Alves](https://github.com/arthrok) |
|`1.1`|16/04/2024|16/04/2024| Correção tabela e bibliografia | [Diego Sousa](https://github.com/DiegoSousaLeite) e [João Artur](https://github.com/joao-artl)| [Arthur Alves](https://github.com/arthrok) |