## <a>Introdução</a>

A rastreabilidade de requisitos é essencial para a gestão eficiente de projetos de software, garantindo que os requisitos sejam implementados e verificáveis ao longo de todo o ciclo de desenvolvimento.  A rastreabilidade forward-from, que liga os requisitos aos artefatos de desenho e implementação, é essencial para garantir que cada requisito seja devidamente traduzido em funcionalidades técnicas específicas<a id="anchor_1" href="#REF1">^1^</a>.

Este modelo de rastreabilidade possibilita acompanhar o progresso do desenvolvimento de forma precisa, desde os requisitos iniciais até os componentes implementados, assegurando que todas as funcionalidades estejam alinhadas com as expectativas e necessidades do cliente. Além disso, a rastreabilidade forward-from auxilia na identificação de qualquer desvio ou inconsistência no desenvolvimento, permitindo ações corretivas tempestivas e garantindo a qualidade e a conformidade do produto final<a id="anchor_1" href="#REF1">^1^</a>.

## <a>Metodologia</a>

Para implementar essa rastreabilidade, começaremos classificando as informações. Com base no meta-modelo de Toranzo, existem quatro níveis de classificação: ambiental, organizacional, gerencial e de desenvolvimento<a id="anchor_5" href="#REF5">^5^</a>. A Figura 01 ilustra esses modelos conforme descrito a seguir:

<center>
Figura 01: Classificação da informação do rastreamento.

![Figura de Classificação](https://github.com/Requisitos-de-Software/2024.1-DiarioOficialdaUniao/blob/git-pages/docs/pos-rastreabilidade/assets/figuraClassificacao.png?raw=True)

<font size="3"><p style="text-align: center"><b>Fonte:</b> Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática<a id="anchor_5" href="#REF5">^5^</a>.</p></font>
</center>

 - O **nível ambiental** congrega informações oriundas do contexto ambiental onde a organização está inserida e que podem afetar o sistema sendo desenvolvido<a id="anchor_3" href="#REF3">^3^</a>;
 - O **nível organizacional** reúne informações relacionadas à organização (missão, objetivos, metas e padrões) e que podem impactar os requisitos do sistema<a id="anchor_3" href="#REF3">^3^</a>;
 - O **nível gerencial** agrega informações que permitem associar tarefas a requisitos, e que podem auxiliar a gerência do projeto<a id="anchor_3" href="#REF3">^3^</a>;
 - O **nível desenvolvimento** abarca informações relacionadas aos diversos artefatos gerados no processo de desenvolvimento (documento de requisitos, diagramas, programas, casos de testes, ...)<a id="anchor_3" href="#REF3">^3^</a>.

Após essa classificação, utilizaremos o *Modelo Intermediário para o Rastreamento de Requisitos*, que visa fornecer resultados a partir de uma combinação de fatores, incluindo boas práticas, estudos de casos, abstração, entre outros<a id="anchor_4" href="#REF4">^4^</a>. A literatura apresenta diversos trabalhos que focam nos tipos de relacionamentos associados à rastreabilidade, conhecidos como elos de rastreabilidade<a id="anchor_3" href="#REF3">^3^</a>. Os principais são:

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

## <a>Rastreabilidade dos Requisitos Funcionais</a>


<details>
    <summary>RF01 Autenticação de usuários para acesso seguro.</summary>
    <center>
    <font size="3">Tabela 01: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.0</td>
            <td>Autenticação de usuários para acesso seguro</td>
            <td>Resolvido</td>
            <td>Teste de Login</td>
            <td>Sim</td>
            <td>Baixo</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3"> Tabela 02: Artefatos Gerados Pelos Requisitos Funcionais </font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>Login seguro</td>
            <td>Termos de Autenticação</td>
            <td>UC01 - Login</td>
            <td>Detalhes de Segurança</td>
            <td>Como usuário, quero fazer login</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF02 Visualização de edições diárias do Diário Oficial.</summary>
    <center>
    <font size="3"> Tabela 03: Estrutura de Desenvolvimento do Requisito </font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.0</td>
            <td>Visualização de edições diárias do Diário Oficial</td>
            <td>Resolvido</td>
            <td>Teste de Visualização</td>
            <td>Sim</td>
            <td>Médio</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3">Tabela 04: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>Visualização de edições</td>
            <td>Termos de Visualização</td>
            <td>UC02 - Visualização</td>
            <td>Detalhes de Visualização</td>
            <td>Como usuário, quero ver edições diárias</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF03 Busca por palavras-chave em documentos.</summary>
    <center>
    <font size="3"> Tabela 05: Estrutura de Desenvolvimento do Requisito </font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.0</td>
            <td>Busca por palavras-chave em documentos</td>
            <td>Resolvido</td>
            <td>Teste de Busca</td>
            <td>Sim</td>
            <td>Baixo</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3"> Tabela 06: Artefatos Gerados Pelos Requisitos Funcionais </font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>Busca de documentos</td>
            <td>Termos de Busca</td>
            <td>UC03 - Busca</td>
            <td>Detalhes de Busca</td>
            <td>Como usuário, quero buscar por palavras-chave</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF04 Filtragem de conteúdo por data, categoria ou órgão emissor.</summary>
    <center>
    <font size="3"> Tabela 07: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.0</td>
            <td>Filtragem de conteúdo por data, categoria ou órgão emissor</td>
            <td>Resolvido</td>
            <td>Teste de Filtragem</td>
            <td>Sim</td>
            <td>Médio</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3"> Tabela 08: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>Filtragem de conteúdo</td>
            <td>Termos de Filtragem</td>
            <td>UC04 - Filtragem</td>
            <td>Detalhes de Filtragem</td>
            <td>Como usuário, quero filtrar conteúdo por data, categoria ou órgão</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF05 Download de edições e documentos em formatos PDF.</summary>
    <center>
    <font size="3"> Tabela 09: Estrutura de Desenvolvimento do Requisito </font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.0</td>
            <td>Download de edições e documentos em formatos PDF</td>
            <td>Resolvido</td>
            <td>Teste de Download</td>
            <td>Sim</td>
            <td>Baixo</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3"> Tabela 10: Artefatos Gerados Pelos Requisitos Funcionais </font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>Download de documentos</td>
            <td>Termos de Download</td>
            <td>UC05 - Download</td>
            <td>Detalhes de Download</td>
            <td>Como usuário, quero baixar edições e documentos em PDF</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF06 Notificações push sobre novas publicações relevantes.</summary>
    <center>
    <font size="3"> Tabela 11: Estrutura de Desenvolvimento do Requisito </font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.0</td>
            <td>Notificações push sobre novas publicações relevantes</td>
            <td>Resolvido</td>
            <td>Teste de Notificação</td>
            <td>Sim</td>
            <td>Baixo</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3"> Tabela 12: Artefatos Gerados Pelos Requisitos Funcionais </font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>Recebimento de notificações</td>
            <td>Termos de Notificação</td>
            <td>UC06 - Notificações</td>
            <td>Detalhes de Notificações</td>
            <td>Como usuário, quero receber notificações push sobre novas publicações</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF07 Acesso a edições anteriores arquivadas.</summary>
    <center>
    <font size="3"> Tabela 13: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.0</td>
            <td>Acesso a edições anteriores arquivadas</td>
            <td>Resolvido</td>
            <td>Teste de Acesso</td>
            <td>Sim</td>
            <td>Médio</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3"> Tabela 14: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>Acesso a arquivos</td>
            <td>Termos de Arquivamento</td>
            <td>UC07 - Arquivamento</td>
            <td>Detalhes de Arquivamento</td>
            <td>Como usuário, quero acessar edições anteriores arquivadas</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF08 Integração com sistemas de assinatura digital.</summary>
    <center>
    <font size="3"> Tabela 15: Estrutura de Desenvolvimento do Requisito </font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.0</td>
            <td>Integração com sistemas de assinatura digital</td>
            <td>Resolvido</td>
            <td>Teste de Integração</td>
            <td>Sim</td>
            <td>Alto</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3"> Tabela 16: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>Assinatura digital</td>
            <td>Termos de Assinatura</td>
            <td>UC08 - Assinatura</td>
            <td>Detalhes de Assinatura</td>
            <td>Como usuário, quero integrar com sistemas de assinatura digital</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF09 Compartilhamento de documentos via redes sociais e email.</summary>
    <center>
    <font size="3"> Tabela 17: Estrutura de Desenvolvimento do Requisito </font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.0</td>
            <td>Compartilhamento de documentos via redes sociais e email</td>
            <td>Resolvido</td>
            <td>Teste de Compartilhamento</td>
            <td>Sim</td>
            <td>Baixo</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3"> Tabela 18: Artefatos Gerados Pelos Requisitos Funcionais </font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>Compartilhamento de documentos</td>
            <td>Termos de Compartilhamento</td>
            <td>UC09 - Compartilhamento</td>
            <td>Detalhes de Compartilhamento</td>
            <td>Como usuário, quero compartilhar documentos via redes sociais e email</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF10 - Douglas Marinho</summary>
    <center>
    <font size="3"> Tabela 19: Estrutura de Desenvolvimento do Requisito </font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.2</td>
            <td>O aplicativo deve permitir buscas detalhadas por tópicos específicos. </td>
            <td>Este requisito não conflita com outros requisitos porém seria integrado a busca comum.</td>
            <td>Verificar por meio de teste utilizando dados específicos para uma certa busca</td>
            <td>Através de relatórios de bug e feedbacks de usuários.</td>
            <td>Médio impacto: Afeta principalmente a usuários que buscam algo com maior precisão</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3"> Tabela 20: Artefatos Gerados Pelos Requisitos Funcionais </font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>C03 - Busca por Palavras-chave</td>
            <td>L01: Filtrar Publicações</td>
            <td>UC10 - Busca Detalhada</td>
            <td>DES01 - O sistema deve, mostrar como padrão no máximo 15 diários por página</td>
            <td>CUS03 - Paginação na Guia Meu Diário , US05- Busca por Palavras-chave, US07 - Filtros Temáticos e Geográficos</td>
            <td>Épico 3 - Busca e Organização de Conteúdo</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
    <center>
    Tabela 21: Elos do Requisito
    <table>
        <tr>
            <th>Tipo de Elo</th>
            <th>Categoria</th>
            <th>Elementos Rastreáveis</th>
            <th>Descrição do ELO</th>
            <th>Requisitos Relacionados</th>
        </tr>
        <tr>
            <td>Dependência</td>
            <td>Desenvolvimento</td>
            <td>Busca e seus respectivos filtros</td>
            <td>Elo que permite buscas avançadas, atendendo às necessidades dos usuários de encontrar informações específicas de maneira eficiente.</td>
            <td>RNF06, RNF13, RN03</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF11 - Douglas Marinho</summary>
    <center>
    <font size="3"> Tabela 21: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.2</td>
            <td>O aplicativo deve oferecer a funcionalidade de salvar documentos para consulta offline.</td>
            <td>Este requisito não conflita com outros requisitos em sua funcionalidade</td>
            <td>Verificar por meio de teste em proprio aplicativo durante uso offline após salvamento</td>
            <td>Através de feedbacks de usuários</td>
            <td>Médio impacto: É uma funcionalidade que auxilia pessoas que utilizam de forma recorrente o aplicativo em momentos sem rede</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3"> Tabela 22: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td> - </td>
            <td> - </td>
            <td>UC02 - Salvar Documentos para Consulta Offline</td>
            <td> - </td>
            <td> - </td>
            <td> - </td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
    <center>
    Tabela 23: Elos do Requisito
    <table>
        <tr>
            <th>Tipo de Elo</th>
            <th>Categoria</th>
            <th>Elementos Rastreáveis</th>
            <th>Descrição do ELO</th>
            <th>Requisitos Relacionados</th>
        </tr>
        <tr>
            <td>Extensão</td>
            <td>Desenvolvimento</td>
            <td>Arquivos salvos para uso offline</td>
            <td>Elo que permite o uso do app mesmo sem rede podendo reler diários salvos.</td>
            <td> - </td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF12 - Douglas Marinho</summary>
    <center>
    <font size="3"> Tabela 24: Estrutura de Desenvolvimento do Requisito </font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.2</td>
            <td>O aplicativo deve enviar notificações personalizadas sobre novas publicações relevantes.</td>
            <td>Este requisito não conflita com outros requisitos, pois é um que utiliza algo funcional do sistema</td>
            <td>Envio de notificações para recebimento</td>
            <td>Através de relátorios de bug e testes por usuários</td>
            <td>Baixo impacto: é uma formalidade a mais para lembrar o usuário para acessar o aplicativo para ver os novos diários</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3"> Tabela 25: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>C01 - Configurar o aplicativo, C04 - Design responsivo que se adapta a tablets e smartphones</td>
            <td>L06 - Configuração de Notificações</td>
            <td>UC03 - Receber Notificações Personalizadas</td>
            <td> - </td>
            <td>US09 - Notificações Personalizadas, US15 - Sistema de Marcadores para Documentos</td>
            <td>Épico 4 - Interação e Notificação</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
        <center>
    Tabela 26: Elos do Requisito
    <table>
        <tr>
            <th>Tipo de Elo</th>
            <th>Categoria</th>
            <th>Elementos Rastreáveis</th>
            <th>Descrição do ELO</th>
            <th>Requisitos Relacionados</th>
        </tr>
        <tr>
            <td>Extensão</td>
            <td>Ambiental</td>
            <td> - </td>
            <td>Elo que permite que o aplicativo envie notificações ao usúario.</td>
            <td>RF06, RF12, RF23 </td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF13 - Douglas Marinho</summary>
    <center>
    <font size="3"> Tabela 25: Estrutura de Desenvolvimento do Requisito </font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.2</td>
            <td>O aplicativo deve oferecer acesso ao histórico de publicações legislativas.</td>
            <td>Este requisito não conflita com outros requisitos, é apenas uma função a mais para acessibilidade ao usuário</td>
            <td>Verificar por meio do acesso a função após ver algum diário para ver se ficou salvo em histórico</td>
            <td>Através de feedbacks enviados por usuários</td>
            <td>Baixo Impacto: Requisito a mais para auxiliar o usuário, sem prioridade.</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3">Tabela 26: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td> - </td>
            <td> - </td>
            <td>UC04 - Acessar Histórico de Publicações Legislativas</td>
            <td> - </td>
            <td>US10 - Funcionalidade de Histórico de Pesquisa</td>
            <td> - </td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
    <center>
    Tabela 27: Elos do Requisito
    <table>
        <tr>
            <th>Tipo de Elo</th>
            <th>Categoria</th>
            <th>Elementos Rastreáveis</th>
            <th>Descrição do ELO</th>
            <th>Requisitos Relacionados</th>
        </tr>
        <tr>
            <td>Extensão</td>
            <td>Organizacional</td>
            <td>Função de historico em aplicativo</td>
            <td>Elo que permite que o aplicativo encontre diários acessados anteriormente.</td>
            <td> - </td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF14 - Douglas Marinho</summary>
    <center>
    <font size="3">Tabela 27: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.2</td>
            <td>O aplicativo deve ter um sistema de marcadores para rastrear alterações em documentos específicos.</td>
            <td>Este requisito não conflita com outros requisitos</td>
            <td>Teste do sistema de marcação para rastreio</td>
            <td>Através de feedbacks por usuários dos marcadores</td>
            <td>Baixo impacto: Afeta alguns usuarios que gostam de marcação em documentos que podem ser alterados</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3">Tabela 28: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td> - </td>
            <td> - </td>
            <td> - </td>
            <td> - </td>
            <td>US15 - Sistema de Marcadores para Documentos</td>
            <td> - </td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
    <center>
    Tabela 27: Elos do Requisito
    <table>
        <tr>
            <th>Tipo de Elo</th>
            <th>Categoria</th>
            <th>Elementos Rastreáveis</th>
            <th>Descrição do ELO</th>
            <th>Requisitos Relacionados</th>
        </tr>
        <tr>
            <td>Inclusão</td>
            <td>Gerencial</td>
            <td>Função para marcação de dados em um diário prevenindo perca de dados após alterações</td>
            <td>Elo que permite que o usuário faça marcações em diários.</td>
            <td> - </td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF15 - Douglas Marinho</summary>
    <center>
    <font size="3">Tabela 29: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.2</td>
            <td>O aplicativo deve fornecer uma interface que facilite a leitura de textos legislativos.</td>
            <td>Resoluções por meio de teste de interação</td>
            <td>Teste de uso por diversos tipos de personas</td>
            <td>Através de sugestões provindas de usuários</td>
            <td>Alto impacto: a interface deve ser boa visivelmente para o aconchego no uso do usuário</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3">Tabela 30: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>C04 - Design responsivo que se adapta a tablets e smartphones</td>
            <td> - </td>
            <td> - </td>
            <td>USA04	O aplicativo deve oferecer uma interface padronizada que garanta conforto visual ao usuário, seguindo os princípios de ergonomia no design de UI</td>
            <td>US17 - Navegação Intuitiva</td>
            <td>Épico 2 - Acessibilidade e Usabilidade</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
    <center>
    Tabela 27: Elos do Requisito
    <table>
        <tr>
            <th>Tipo de Elo</th>
            <th>Categoria</th>
            <th>Elementos Rastreáveis</th>
            <th>Descrição do ELO</th>
            <th>Requisitos Relacionados</th>
        </tr>
        <tr>
            <td>Dependência</td>
            <td>Desenvolvimento</td>
            <td>A propria interface do aplicativo</td>
            <td>Um elo de UX foco em usabilidade e acessibilidade para o usuário </td>
            <td>RF24, RNF10</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF16 - Douglas Marinho</summary>
    <center>
    <font size="3">Tabela 31: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.2</td>
            <td>O aplicativo deve incluir uma funcionalidade de compartilhamento de documentos.</td>
            <td>Este requisito não conflita com nenhum outro</td>
            <td>Verificação por meio de testes durante uso para compartilhamento de diários</td>
            <td>Através de reportes feitos por usuários</td>
            <td>Baixo impacto: um requisito que auxilia o compartilhamento de acesso a um diário porém sem grandes prioridades</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
    <center>
    <font size="3">Tabela 32: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td> - </td>
            <td> - </td>
            <td> - </td>
            <td> - </td>
            <td>US11 - Funcionalidade de Compartilhamento Aprimorada</td>
            <td>Épico 6 - Funcionalidades Avançadas de Documentos</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
    <center>
    Tabela 33: Elos do Requisito
    <table>
        <tr>
            <th>Tipo de Elo</th>
            <th>Categoria</th>
            <th>Elementos Rastreáveis</th>
            <th>Descrição do ELO</th>
            <th>Requisitos Relacionados</th>
        </tr>
        <tr>
            <td>Associação</td>
            <td>Desenvolvimento</td>
            <td>A função de compartilhar direto no aplicativo</td>
            <td>Um elo que auxilia o usuario a enviar diários a pessoas que podem ter o mesmo interesse</td>
            <td>RF09</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF17 - Douglas Marinho</summary>
    <center>
    <font size="3">Tabela 33: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.2</td>
            <td>O aplicativo deve manter um índice atualizado e pesquisável de todos os documentos publicados.</td>
            <td>Esse requisito é um complemento do RF18 de busca avançada porém focado em indices dentro dos diários</td>
            <td>Verificação por caso de teste em alterações de indices e pesquisas em documentos</td>
            <td>Por meio de feedbacks e reportes feitos por usuários</td>
            <td>Baixo impacto: Requisito de auxilio ao usuário a encontrar algum tema especifico</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3">Tabela 34: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td> - </td>
            <td> - </td>
            <td> - </td>
            <td> - </td>
            <td> - </td>
            <td> - </td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
    <center>
    Tabela 35: Elos do Requisito
    <table>
        <tr>
            <th>Tipo de Elo</th>
            <th>Categoria</th>
            <th>Elementos Rastreáveis</th>
            <th>Descrição do ELO</th>
            <th>Requisitos Relacionados</th>
        </tr>
        <tr>
            <td>Associação</td>
            <td>Organizacional</td>
            <td>A função permite a busca em indice</td>
            <td>Um elo que auxilia o usuario a encontrar temas ou assuntos por meio de busca em documento</td>
            <td>RF18</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF18 - Douglas Marinho</summary>
    <center>
    <font size="3">Tabela 35: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.0</td>
            <td>Sistema de busca avançada</td>
            <td>Este requisito não conflita com outros requisitos, porém integra como base para alguns como o RF17</td>
            <td>Por meio de teste em filtros e resultados</td>
            <td>Através de testes e reportes por usuários</td>
            <td>Médio impacto: Auxiliando na busca acelera o uso do aplicativo facilitando o acesso ao usuário</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3">Tabela 36: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>C03 - Busca por Palavras-chave</td>
            <td>L01 - Filtrar Publicações</td>
            <td>UC01 - Consultar Documentos Legislativos</td>
            <td>DES01 - O sistema deve, mostrar como padrão no máximo 15 diários por página</td>
            <td>US05 - Busca por Palavras-chave, US07 - Filtros Temáticos e Geográficos</td>
            <td>Épico 3 - Busca e Organização de Conteúdo</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
    <center>
    Tabela 37: Elos do Requisito
    <table>
        <tr>
            <th>Tipo de Elo</th>
            <th>Categoria</th>
            <th>Elementos Rastreáveis</th>
            <th>Descrição do ELO</th>
            <th>Requisitos Relacionados</th>
        </tr>
        <tr>
            <td>Dependência</td>
            <td>Desenvolvimento</td>
            <td>A função permite a busca utilizando filtros avançados</td>
            <td>Um elo que auxilia o usuario a encontrar documentos especificos com maior facilidade</td>
            <td>RF17, RF21, RNF06, RNF13, RF03, RF10</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF19 - Funcionalidades de acessibilidade.</summary>
    <center>
    <font size="3">Tabela 37: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td> 1.1</td>
            <td>Funcionalidades de acessibilidade</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Verificar atráves de testes com usuários</td>
            <td>Através de relatórios de bug e feedbacks de usuários</td>
            <td>Alto: Afeta todos os usuários do software</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
    </center>

<center>
    <font size="3">Tabela 38: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>C04 - Design responsivo que se adapta a tablets e smartphones, C05 - Compatibilidade com as Versões Mais Recentes de Sistemas Operacionais Móveis e C06 - Suporte Multilíngue para Facilitar o Acesso por Usuários Não-nativos</td>
            <td>L06 - Configuração de Notificações</td>
            <td>UC03 - Receber Notificações Personalizadas</td>
            <td>USA01, USA02, USA03, USA04, USA05 e USA06</td>
            <td>US16 - Compatibilidade com Sistemas Operacionais Móveis, US06 - Suporte Multilíngue, US19 -Design Responsivo para Dispositivos Móveis, US17 - Navegação Intuitiva e US14 - Acessibilidade para Usuários com Deficiência Visual</td>
            <td>Épico 2: Acessibilidade e Usabilidade</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
    </center>
    <center>
    <font size="3">Tabela 21: Elos do Requisito</font>
    <table>
        <tr>
            <th>Tipo de Elo</th>
            <th>Categoria</th>
            <th>Elementos Rastreáveis</th>
            <th>Descrição do ELO</th>
            <th>Requisitos Relacionados</th>
        </tr>
        <tr>
            <td>Generalização</td>
            <td>Ambiental</td>
            <td> --- </td>
            <td>Elo que permite uma melhor acessibilidade, atendendo às necessidades dos usuários de encontrar informações específicas de maneira eficiente.</td>
            <td> RF20 </td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
    </center>
</details>

<details>
    <summary>RF20 - Ferramentas de usabilidade aprimoradas</summary>
    <center>
    <font size="3">Tabela 37: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td> 1.1 </td>
            <td>Ferramentas de usabilidade aprimoradas</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Teste de Usabilidade</td>
            <td>Através de relatórios de bug e feedbacks de usuários</td>
            <td>Alto: Afeta todos os usuários do software</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
    </center>

<center>
<font size="3">Tabela 38: Artefatos Gerados Pelos Requisitos Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
        <tr>
            <td>C04 - Design responsivo que se adapta a tablets e smartphones, C05 - Compatibilidade com as Versões Mais Recentes de Sistemas Operacionais Móveis e C06 - Suporte Multilíngue para Facilitar o Acesso por Usuários Não-nativos</td>
            <td>L06 - Configuração de Notificações</td>
            <td>UC03 - Receber Notificações Personalizadas</td>
            <td>USA01, USA02, USA03, USA04, USA05 e USA06</td>
            <td>US16 - Compatibilidade com Sistemas Operacionais Móveis, US06 - Suporte Multilíngue, US19 -Design Responsivo para Dispositivos Móveis, US17 - Navegação Intuitiva e US14 - Acessibilidade para Usuários com Deficiência Visual</td>
            <td>Épico 2: Acessibilidade e Usabilidade</td>
        </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>

<center>
<font size="3">Tabela 21: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Generalização</td>
        <td>Ambiental</td>
        <td> --- </td>
        <td>Elo que permite uma melhor usabilidade do sistema, atendendo às necessidades dos usuários, de um software mais intuitivo.</td>
        <td> RF19 </td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>
</details>

<details>
    <summary>RF21 - Otimização do processo de busca diária</summary>
    <center>
    <font size="3">Tabela 37: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td> 1.1</td>
            <td>Otimização do processo de busca diária</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Verificar atráves de testes com usuários</td>
            <td>Através de relatórios de bug e feedbacks de usuários</td>
            <td>Alto: A busca é uma das principais funcionalidades do sistema</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
    </center>

<center>
<font size="3">Tabela 38: Artefatos Gerados Pelos Requisitos Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>C02 - Filtrar Publicações por Temas e C03 - Busca por Palavras-chave</td>
        <td>L01: Filtrar Publicações e L06: Configuração de Notificações </td>
        <td>UC01. Consultar Documentos Legislativos</td>
        <td>DES01</td>
        <td>US04 - Filtragem de Data em Meu Diário, US05 - Busca por Palavras-chave, US07 - Filtros Temáticos e Geográficos e US10 - Funcionalidade de Histórico de Pesquisa</td>
        <td>Épico 3: Busca e Organização de Conteúdo</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>

<center>
<font size="3">Tabela 21: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Dependência</td>
        <td>Desenvolvimento</td>
        <td>Filtros de Busca</td>
        <td>Elo que permite otimizar o processo de busca diária, garantindo eficiência na localização de informações.</td>
        <td> ---- </td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>

</details>

<details>
    <summary>RF22 - Suporte multilingue no sistema</summary>
    <center>
    <font size="3">Tabela 37: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td> 1.1</td>
            <td>Suporte multilingue no sistema</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Teste com o usuário</td>
            <td>Através de relatórios de bug e feedbacks de usuários</td>
            <td>Médio: Afeta apenas uma parcela dos usuários</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
    </center>

<center>
<font size="3">Tabela 38: Artefatos Gerados Pelos Requisitos Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>C06 - Suporte Multilíngue para Facilitar o Acesso por Usuários Não-nativos</td>
        <td> --- </td>
        <td> --- </td>
        <td> --- </td>
        <td>US06 - Suporte Multilíngue</td>
        <td>Épico 7: Multilíngue e Internacionalização</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>

<center>
<font size="3">Tabela 21: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Dependência</td>
        <td>Desenvolvimento</td>
        <td>Tradução de Conteúdos</td>
        <td>Elo que permite suporte a múltiplos idiomas no sistema, garantindo acessibilidade para diversos usuários.</td>
        <td> --- </td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>

</details>

<details>
    <summary>RF23 - Sistema de notificações personalizadas</summary>
    <center>
    <font size="3">Tabela 37: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td> 1.1</td>
            <td>Sistema de notificações personalizadas</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Teste com usuários</td>
            <td>Através de relatórios de bug e feedbacks de usuários</td>
            <td>Alto: O requisito visa uma melhor interação dos usuários com a plataforma</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
    </center>

 

<center>
<font size="3">Tabela 38: Artefatos Gerados Pelos Requisitos Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>C01 - Configurar o aplicativo</td>
        <td>L06: Configuração de Notificações</td>
        <td>UC03. Receber Notificações Personalizadas</td>
        <td>---</td>
        <td>Como usuário, quero receber notificações personalizadas sobre atualizações relevantes</td>
        <td>Sim</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>

<center>
<font size="3">Tabela 21: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Generalização</td>
        <td>Desenvolvimento</td>
        <td>Sistema de Notificações</td>
        <td>Elo que permite a personalização de notificações, garantindo que os usuários recebam informações relevantes.</td>
        <td>---</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>

</details>

<details>
    <summary>RF24 - Interface do usuário altamente intuitiva</summary>
    <center>
    <font size="3">Tabela 37: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td> 1.1</td>
            <td>Interface do usuário altamente intuitiva</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Teste de Interface</td>
            <td>Através de relatórios de bug e feedbacks de usuários</td>
            <td>Médio: Facilita a realização das tarefas</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
    </center>

<center>
    <font size="3">Tabela 38: Artefatos Gerados Pelos Requisitos Funcionais</font>
    <table>
        <tr>
            <th>Cenário</th>
            <th>Léxico</th>
            <th>Casos de Uso</th>
            <th>Especificação Suplementar</th>
            <th>História de Usuário</th>
            <th>Backlog</th>
        </tr>
        <tr>
            <td>C04 - Design responsivo que se adapta a tablets e smartphones, C05 - Compatibilidade com as Versões Mais Recentes de Sistemas Operacionais Móveis e C06 - Suporte Multilíngue para Facilitar o Acesso por Usuários Não-nativos</td>
            <td>L06 - Configuração de Notificações</td>
            <td>UC03 - Receber Notificações Personalizadas</td>
            <td>USA01, USA02, USA03, USA04, USA05 e USA06</td>
            <td>US16 - Compatibilidade com Sistemas Operacionais Móveis, US06 - Suporte Multilíngue, US19 -Design Responsivo para Dispositivos Móveis, US17 - Navegação Intuitiva e US14 - Acessibilidade para Usuários com Deficiência Visual</td>
            <td>Épico 2: Acessibilidade e Usabilidade</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>

<center>
<font size="3">Tabela 21: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Generalização</td>
        <td>Desenvolvimento</td>
        <td>Design de Interface</td>
        <td>Elo que permite a criação de uma interface altamente intuitiva, melhorando a experiência do usuário.</td>
        <td>---</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>

</details>

<details>
    <summary>RF25 - Funcionalidades avançadas de documentos</summary>
    <center>
    <font size="3">Tabela 37: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td> 1.1</td>
            <td>Funcionalidades avançadas de documentos</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>TVerificar atráves de testes com usuários</td>
            <td>Através de relatórios de bug e feedbacks de usuários</td>
            <td>Médio: Funcionalidades adiconais para os documentos</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
    </center>

 

<center>
<font size="3">Tabela 38: Artefatos Gerados Pelos Requisitos Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>US11 - Funcionalidade de Compartilhamento Aprimorada</td>
        <td>Épico 6: Funcionalidades Avançadas de Documentos</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>

<center>
<font size="3">Tabela 21: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Dependência</td>
        <td>Desenvolvimento</td>
        <td>Sistema de Documentos</td>
        <td>Elo que permite funcionalidades avançadas para gerenciar documentos de forma eficaz.</td>
        <td> --- </td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>

</details>

<details>
    <summary>RF26 - Melhoria na interação entre usuários</summary>
    <center>
    <font size="3">Tabela 37: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.1</td>
            <td>Melhoria na interação entre usuários</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Testes de Interação</td>
            <td>Através de relatórios de bug e feedbacks de usuários</td>
            <td>Baixo: Não é uma das funcionalidades principais do aplicativo</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
    </center>

<center>
<font size="3">Tabela 38: Artefatos Gerados Pelos Requisitos Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td> --- </td>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>US12 - Comentários e Anotações em Publicações e US21 - Anotações Colaborativas</td>
        <td>Épico 4: Interação e Notificação</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>

<center>
<font size="3">Tabela 21: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Extensão</td>
        <td>Desenvolvimento</td>
        <td>Ferramentas de Comunicação</td>
        <td>Elo que permite a melhoria na interação entre usuários, facilitando a comunicação e colaboração.</td>
        <td> --- </td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> [João Artur](https://github.com/joao-artl).</p></font>
</center>

</details>

## <a>Rastreabilidade dos Requisitos Não Funcionais</a>

<details>
    <summary>RNF01 Alta disponibilidade do sistema, com 99,9% de uptime.</summary>
        OBS10
</details>

<details>
    <summary>RNF02 Compatibilidade com as versões mais recentes de sistemas operacionais móveis.</summary>
    <center>
    <font size="3">Tabela x: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.1</td>
            <td>Compatibilidade com as versões mais recentes de sistemas operacionais móveis.</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Testes de Compatibilidade</td>
            <td>Atualizações e correções baseadas em relatórios de compatibilidade</td>
            <td>Médio: Pode exigir ajustes contínuos conforme novas versões de SOs são lançadas</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Artefatos Gerados Pelos Requisitos Não Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>C05 - Compatibilidade com as Versões Mais Recentes de Sistemas Operacionais Móveis</td>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>US16 - Compatibilidade com Sistemas Operacionais Móveis</td>
        <td>Épico 5 - Infraestrutura e Suporte</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Compatibilidade</td>
        <td>Desenvolvimento</td>
        <td>Sistemas Operacionais Móveis</td>
        <td>Elo que garante que o aplicativo seja compatível com as versões mais recentes de sistemas operacionais móveis, garantindo seu funcionamento adequado.</td>
        <td> --- </td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>
</details>

<details>
    <summary>RNF03 Design responsivo que se adapta a tablets e smartphones.</summary>
        
<center>
<font size="3">Tabela x: Estrutura de Desenvolvimento do Requisito</font>
<table>
    <tr>
        <th>Versão</th>
        <th>Nome do Requisito</th>
        <th>Resolução de requisitos em conflito</th>
        <th>Verificação</th>
        <th>Correção de Defeitos</th>
        <th>Análise de impacto na evolução</th>
    </tr>
    <tr>
        <td>1.1</td>
        <td>Design responsivo que se adapta a tablets e smartphones.</td>
        <td>Este requisito não possui conflitos com outros requisitos</td>
        <td>Testes de Responsividade em dispositivos variados</td>
        <td>Correções baseadas em feedbacks de usuários e testes de usabilidade</td>
        <td>Médio: Pode exigir atualizações regulares conforme novos dispositivos são lançados</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Artefatos Gerados Pelos Requisitos Não Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>C04 - Design responsivo que se adapta a tablets e smartphones</td>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>US19 - Design Responsivo para Dispositivos Móveis</td>
        <td>Épico 2 - Acessibilidade e Usabilidade</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Compatibilidade</td>
        <td>Design</td>
        <td>Dispositivos móveis (tablets e smartphones)</td>
        <td>Elo que garante que o design do aplicativo seja responsivo e se adapte adequadamente a diferentes tamanhos de tela, incluindo tablets e smartphones.</td>
        <td>---</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>
</details>

<details>
    <summary>RNF04 Segurança de dados com criptografia de ponta-a-ponta.</summary>
        <center>
    <font size="3">Tabela x: Estrutura de Desenvolvimento do Requisito</font>
    <table>
    <tr>
        <th>Versão</th>
        <th>Nome do Requisito</th>
        <th>Resolução de requisitos em conflito</th>
        <th>Verificação</th>
        <th>Correção de Defeitos</th>
        <th>Análise de impacto na evolução</th>
    </tr>
    <tr>
        <td>1.1</td>
        <td>Segurança de dados com criptografia de ponta-a-ponta.</td>
        <td>Este requisito não possui conflitos com outros requisitos</td>
        <td>Testes de Segurança e Auditorias</td>
        <td>Correções baseadas em testes de penetração e relatórios de vulnerabilidade</td>
        <td>Alto: Necessita atualizações contínuas conforme novas vulnerabilidades são descobertas</td>
    </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Artefatos Gerados Pelos Requisitos Não Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>CON06 - O sistema deve evitar que o usuário execute atividades que possam comprometer a integridade do sistema.</td>
        <td>---</td>
        <td>---</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Elos do Requisito</font>
<table>
<tr>
    <th>Tipo de Elo</th>
    <th>Categoria</th>
    <th>Elementos Rastreáveis</th>
    <th>Descrição do ELO</th>
    <th>Requisitos Relacionados</th>
</tr>
<tr>
    <td>Segurança</td>
    <td>Desenvolvimento</td>
    <td>Algoritmos de Criptografia, Protocolos de Segurança</td>
    <td>Elo que garante a segurança dos dados transmitidos e armazenados através de criptografia de ponta-a-ponta, protegendo contra acesso não autorizado.</td>
    <td>---</td>
</tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>
</details>

<details>
    <summary>RNF05 Suporte multilíngue para facilitar o acesso por usuários não-nativos.</summary>
    <center>
            <font size="3">Tabela x: Estrutura de Desenvolvimento do Requisito</font>
    <table>
    <tr>
        <th>Versão</th>
        <th>Nome do Requisito</th>
        <th>Resolução de requisitos em conflito</th>
        <th>Verificação</th>
        <th>Correção de Defeitos</th>
        <th>Análise de impacto na evolução</th>
    </tr>
    <tr>
        <td>1.1</td>
        <td>Suporte multilíngue para facilitar o acesso por usuários não-nativos.</td>
        <td>Este requisito não possui conflitos com outros requisitos</td>
        <td>Testes de Internacionalização e Localização</td>
        <td>Correções baseadas em feedbacks de usuários e testes de localização</td>
        <td>Médio: Pode exigir a adição de novos idiomas conforme a base de usuários cresce</td>
    </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
    </center>

<center>
<font size="3">Tabela x: Artefatos Gerados Pelos Requisitos Não Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>C06 - Suporte Multilíngue para Facilitar o Acesso por Usuários Não-nativos</td>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>US06 - Suporte Multilíngue</td>
        <td>Épico 7 - Multilíngue e Internacionalização</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Internacionalização</td>
        <td>Desenvolvimento</td>
        <td>Idiomas Suportados</td>
        <td>Elo que garante que o aplicativo ofereça suporte a múltiplos idiomas, facilitando o acesso e a usabilidade para usuários não-nativos.</td>
        <td>RF22</td>
    </tr>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>
</details>

<details>
    <summary>RNF06 Tempo de resposta de busca inferior a 2 segundos.</summary>
    <center>
            <font size="3">Tabela x: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.1</td>
            <td>Tempo de resposta de busca inferior a 2 segundos.</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Testes de Desempenho e Benchmarking</td>
            <td>Correções baseadas em monitoramento de desempenho e análise de logs</td>
            <td>Médio: Pode exigir otimizações contínuas conforme o volume de dados aumenta</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
    </center>

<center>
<font size="3">Tabela x: Artefatos Gerados Pelos Requisitos Não Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>C03 - Busca por Palavras-chave</td>
        <td>---</td>
        <td>---</td>
        <td>DES06 - O sistema deve garantir um tempo de resposta não superior a 1 segundo.</td>
        <td>---</td>
        <td>---</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Desempenho</td>
        <td>Desenvolvimento</td>
        <td>Tempo de Resposta, Velocidade de Busca</td>
        <td>Elo que garante que as buscas no sistema retornem resultados em menos de 2 segundos, proporcionando uma experiência rápida e eficiente para o usuário.</td>
        <td>---</td>
    </tr>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>
</details>

<details>
    <summary>RNF07 Implementação de medidas de acessibilidade para usuários com deficiência.</summary>
        <center>
            <font size="3">Tabela x: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.1</td>
            <td>Implementação de medidas de acessibilidade para usuários com deficiência.</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Testes de Acessibilidade e Auditorias</td>
            <td>Correções baseadas em feedbacks de usuários e testes de acessibilidade</td>
            <td>Alto: Necessita atualizações contínuas conforme novas tecnologias e diretrizes de acessibilidade são desenvolvidas</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
    </center>

<center>
<font size="3">Tabela x: Artefatos Gerados Pelos Requisitos Não Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>US14 - Acessibilidade para Usuários com Deficiência Visual</td>
        <td>Épico 2 - Acessibilidade e Usabilidade</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Acessibilidade</td>
        <td>Desenvolvimento</td>
        <td>Ferramentas de Acessibilidade, Diretrizes de Acessibilidade</td>
        <td>Elo que garante a implementação de medidas de acessibilidade no aplicativo, facilitando o uso por pessoas com deficiência.</td>
        <td>RF19</td>
    </tr>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>
</details>

<details>
    <summary>RNF08 Facilidade de atualização de conteúdo pelo gestor do sistema.</summary>
    <center>
            <font size="3">Tabela x: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.1</td>
            <td>Facilidade de atualização de conteúdo pelo gestor do sistema.</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Testes de Usabilidade e Revisões pelo Gestor</td>
            <td>Correções baseadas em feedback do gestor e testes de atualização</td>
            <td>Baixo: Requer apenas ajustes menores com base em feedbacks periódicos</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
    </center>

<center>
<font size="3">Tabela x: Artefatos Gerados Pelos Requisitos Não Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>---</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Usabilidade</td>
        <td>Gestão de Conteúdo</td>
        <td>Ferramentas de Atualização de Conteúdo</td>
        <td>Elo que garante que o gestor do sistema possa atualizar o conteúdo com facilidade, mantendo a informação atualizada e relevante.</td>
        <td>---</td>
    </tr>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>
</details>

<details>
    <summary>RNF09 Suporte técnico com tempo de resposta de 24 horas.</summary>
        <center>
            <font size="3">Tabela x: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.1</td>
            <td>Suporte técnico com tempo de resposta de 24 horas.</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Monitoramento de Tempo de Resposta e Relatórios de Atendimento</td>
            <td>Correções baseadas em feedbacks de usuários e revisão dos processos de atendimento</td>
            <td>Médio: Pode exigir ajustes no processo de atendimento conforme o volume de solicitações aumenta</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
    </center>

<center>
<font size="3">Tabela x: Artefatos Gerados Pelos Requisitos Não Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>C07 - Suporte Técnico com Tempo de Resposta de 24 Horas</td>
        <td>---</td>
        <td>---</td>
        <td>
        CON05	O aplicativo deve possuir um sistema de suporte ao usuário,
        SUP03 - O sistema deve oferecer suporte ao usuário através de canais apropriados e uma equipe disponível.
        </td>
        <td>---</td>
        <td>---</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Suporte</td>
        <td>Atendimento ao Cliente</td>
        <td>Tempo de Resposta, Qualidade do Atendimento</td>
        <td>Elo que garante que o suporte técnico responda às solicitações dos usuários dentro de 24 horas, assegurando um atendimento eficiente e rápido.</td>
        <td>---</td>
    </tr>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>
</details>

<details>
    <summary>RNF10 O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar.</summary>
            <center>
            <font size="3">Tabela x: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.1</td>
            <td>O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar.</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Testes de Usabilidade e Feedbacks de Usuários</td>
            <td>Correções baseadas em testes de usabilidade e análise de feedbacks</td>
            <td>Baixo: Ajustes de interface conforme novos recursos são adicionados</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
    </center>

<center>
<font size="3">Tabela x: Artefatos Gerados Pelos Requisitos Não Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>
            USA04 - O aplicativo deve oferecer uma interface padronizada que garanta conforto visual ao usuário, seguindo os princípios de ergonomia no design de UI 3,
            DES02 - O sistema deve oferecer uma navegação fluida e sem interrupções, com caminhos organizados de forma lógica,
            DES04 - O aplicativo deve ter uma interface de design simplificado, seguindo os princípios de ergonomia no design de UI.
        </td>
        <td>US17 - Navegação Intuitiva</td>
        <td>Épico 2 - Acessibilidade e Usabilidade</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Usabilidade</td>
        <td>Interface do Usuário</td>
        <td>Layout, Navegação</td>
        <td>Elo que garante que a interface do usuário do aplicativo seja intuitiva e fácil de navegar, proporcionando uma experiência positiva ao usuário.</td>
        <td>RF24</td>
    </tr>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>
</details>

<details>
    <summary>RNF11 O aplicativo deve garantir a segurança e a privacidade dos dados dos usuários.</summary>
                <center>
            <font size="3">Tabela x: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.1</td>
            <td>O aplicativo deve garantir a segurança e a privacidade dos dados dos usuários.</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Testes de Segurança e Auditorias</td>
            <td>Correções baseadas em testes de penetração e relatórios de segurança</td>
            <td>Alto: Necessita atualizações regulares para manter a proteção contra novas ameaças e vulnerabilidades</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
    </center>

<center>
<font size="3">Tabela x: Artefatos Gerados Pelos Requisitos Não Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>US13 - Autenticação Multifatorial</td>
        <td>Épico 1 - Autenticação Segura e Gestão de Usuários</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Segurança</td>
        <td>Proteção de Dados</td>
        <td>Políticas de Privacidade, Criptografia, Controles de Acesso</td>
        <td>Elo que garante que os dados dos usuários sejam protegidos contra acesso não autorizado, utilizando práticas de segurança como criptografia e controle de acesso.</td>
        <td>RF01</td>
    </tr>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>
</details>

<details>
    <summary>RNF12 O aplicativo deve estar disponível 24/7, com exceção de períodos de manutenção programada.</summary>
                <center>
            <font size="3">Tabela x: Estrutura de Desenvolvimento do Requisito</font>
    <table>
        <tr>
            <th>Versão</th>
            <th>Nome do Requisito</th>
            <th>Resolução de requisitos em conflito</th>
            <th>Verificação</th>
            <th>Correção de Defeitos</th>
            <th>Análise de impacto na evolução</th>
        </tr>
        <tr>
            <td>1.1</td>
            <td>O aplicativo deve estar disponível 24/7, com exceção de períodos de manutenção programada.</td>
            <td>Este requisito não possui conflitos com outros requisitos</td>
            <td>Monitoramento de Disponibilidade e Relatórios de Manutenção</td>
            <td>Correções baseadas em análises de incidentes e melhorias na infraestrutura</td>
            <td>Médio: Pode exigir ajustes contínuos para garantir alta disponibilidade e mínima interrupção de serviço</td>
        </tr>
</table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
    </center>

<center>
<font size="3">Tabela x: Artefatos Gerados Pelos Requisitos Não Funcionais</font>
<table>
    <tr>
        <th>Cenário</th>
        <th>Léxico</th>
        <th>Casos de Uso</th>
        <th>Especificação Suplementar</th>
        <th>História de Usuário</th>
        <th>Backlog</th>
    </tr>
    <tr>
        <td>---</td>
        <td>---</td>
        <td>---</td>
        <td>CON01 - O sistema deve ser acessível 24 horas por dia, 7 dias por semana, ou seja, de maneira ininterrupta.</td>
        <td>---</td>
        <td>---</td>
    </tr>
</table>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>

<center>
<font size="3">Tabela x: Elos do Requisito</font>
<table>
    <tr>
        <th>Tipo de Elo</th>
        <th>Categoria</th>
        <th>Elementos Rastreáveis</th>
        <th>Descrição do ELO</th>
        <th>Requisitos Relacionados</th>
    </tr>
    <tr>
        <td>Disponibilidade</td>
        <td>Infraestrutura</td>
        <td>Monitoramento de Servidores, Planos de Contingência</td>
        <td>Elo que garante que o aplicativo esteja disponível 24/7, exceto durante manutenções programadas, assegurando uma experiência contínua para os usuários.</td>
        <td>---</td>
    </tr>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/henriqtorresl" target="_blank">Henrique Torres</a>.</p></font>
</center>
</details>

<details>
    <summary>RNF13 O aplicativo deve apresentar um tempo de resposta rápido (< 2 segundos) nas buscas.</summary>
        IS12
</details>
<details>
    <summary>RNF14 O aplicativo deve ser acessível de acordo com os padrões da WCAG 2.1.</summary>
        IS13
</details>
<details>
    <summary>RNF15 O aplicativo deve ter um mecanismo robusto de backup e recuperação de dados.</summary>
        IS14
</details>
<details>
    <summary>RNF16 O aplicativo deve ser escalável para acomodar um crescente número de usuários e documentos.</summary>
        IS15
</details>
<details>
    <summary>RNF17 O aplicativo deve oferecer suporte multilíngue para atender a uma base de usuários diversificada.</summary>
        IS16
</details>
<details>
    <summary>RNF18 Medidas de segurança robustas.</summary>
        ENT07
</details>
<details>
    <summary>RNF19 Requisitos para suporte e manutenção.</summary>
        ENT09
</details>




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
|`1.0`|15/06/2024|16/06/2024|Criação do Documento, inserção da introdução e da metodologia. | [Diego Sousa](https://github.com/DiegoSousaLeite)|[João Artur](https://github.com/joao-artl),[Luiz Gustavo](https://github.com/LuizGust4vo) e  [Henrique Torres](https://github.com/henriqtorresl)|
|`1.1`|24/06/2024|24/06/2024|Modelagem do mapeamento e tabelas das Rastreabilidades funcionais| [Douglas Marinho](https://github.com/M4RINH0)|[João Artur](https://github.com/joao-artl),[Luiz Gustavo](https://github.com/LuizGust4vo) e  [Henrique Torres](https://github.com/henriqtorresl)|
|`1.2`|24/06/2024|24/06/2024|Criando tabela dos requisitos funcionais de 19 à 26 e do requisito não funcional 1| [João Artur](https://github.com/joao-artl)|[Luiz Gustavo](https://github.com/LuizGust4vo) e  [Henrique Torres](https://github.com/henriqtorresl)|