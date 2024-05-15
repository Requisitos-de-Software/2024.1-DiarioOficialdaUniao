# Casos de Uso

## <a>Introdução</a>

O diagrama de casos de uso é uma representação visual que descreve as interações entre um sistema e seus usuários externos, destacando as principais funcionalidades do sistema e como os usuários as utilizam.

## <a>Metodologia</a>

Para criar este artefato, seguimos a abordagem tradicional de representação dos casos de uso por meio de diagramas UML. Utilizamos o LucidChart, uma ferramenta online para criação de diagramas, como nossa plataforma de escolha.

## <a>Componentes e Símbolos</a>

Um diagrama de casos de uso é composto pelos seguintes elementos:

### <a>Atores</a>

Os atores representam os usuários e sistemas envolvidos nas interações com o sistema. Eles são comumente representados por ícones de bonecos de palitos.

<p align="center">
  <img src="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/main/docs/modelagem/images/ator-uml.png?raw=true" alt="Ator" />
</p>
<div style="text-align: center">
<p> Figura 1: Ator (Fonte: Douglas Marinho, 2024).</p>
</div>

### <a>Cenário</a>

O cenário é a sequência de eventos que ocorre quando um usuário interage com o sistema. É representado por uma caixa que delimita as atividades dentro do escopo do sistema.

<p align="center">
  <img src="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/main/docs/modelagem/images/container-uml.png?raw=true" alt="Cenário" />
</p>
<div style="text-align: center">
<p> Figura 2: Cenário (Fonte: Douglas Marinho, 2024).</p>
</div>

### <a>Caso de Uso</a>

Um caso de uso descreve uma funcionalidade ou atividade realizada pelo usuário. É representado por uma forma oval horizontal e deve ser descrito com verbos no infinitivo.

<p align="center">
  <img src="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/main/docs/modelagem/images/usecase-uml.png?raw=true" alt="Casos de Uso" />
</p>
<div style="text-align: center">
<p> Figura 3: Caso de uso (Fonte: Douglas Marinho, 2024).</p>
</div>

### <a>Comunicação (ou Ação)</a>

As comunicações representam as ações que conectam os usuários aos casos de uso. Elas podem ser de dois tipos:

- **Inclusão:** Indica que um caso de uso depende da execução de outro caso de uso.
  
  - Notação no diagrama: *<<includes\>\>*
  
- **Extensão:** Indica que um caso de uso pode ser estendido por outro, adicionando novos passos ou funcionalidades.
  
  - Notação no diagrama: *<<extends\>\>*

<p align="center">
  <img src="https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/main/docs/modelagem/images/action-uml.png?raw=true" alt="Comunicação" />
</p>
<div style="text-align: center">
<p> Figura 4: Comunicação (Fonte: Douglas Marinho, 2024).</p>
</div>

## <a>Diagrama de Casos de Uso</a>

<!-- ![Figura 5: Diagrama de casos de uso (Fonte: Douglas Marinho, 2024).](images/usecase-diagram-v2.png)
<div style="text-align: center">
<p> Figura 5: Diagrama de casos de uso 2ª versão. <a href="../images/usecase-diagram-v1.png"> 1ª versão</a>. (Fonte: Douglas Marinho, 2024).</p>
</div> -->

## <a>Bibliografia</a>

> Macedo, Lucas. "Caso de uso". Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/casos_de_uso/](https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/casos_de_uso/). Acesso em: 15 mai. 2024.

> Lucidchart. "Diagrama de Caso de Uso UML". Disponível em: [https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml](https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml). Acesso em: 15 maio 2024.

> <a>Barbosa, S. D. J.; Silva, B. S.</a> "Interação Humano-Computador". Rio de Janeiro: Elsevier, 2011.


## <a>Histórico de Versão</a>

|Versão|Data|Data Prevista de Revisão|Descrição|Autor|Revisor|
| :------: | :----------: |:-----------: | :-----------: | :---------: |:---------: |
|`1.0`|15/05/2024|15/05/2024| Criação do documento sobre Casos de uso | [Douglas Marinho](https://github.com/M4RINH0)|[Henrique Torres](https://github.com/henriqtorresl)|