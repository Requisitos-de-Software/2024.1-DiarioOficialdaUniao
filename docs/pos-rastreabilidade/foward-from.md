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
    <summary>RF11 O aplicativo deve oferecer a funcionalidade de salvar documentos para consulta offline.</summary>
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
            <td>1.0</td>
            <td>Salvar documentos para consulta offline</td>
            <td>Resolvido</td>
            <td>Teste de Salvamento</td>
            <td>Sim</td>
            <td>Médio</td>
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
            <td>Salvamento de documentos</td>
            <td>Termos de Salvamento</td>
            <td>UC11 - Salvamento</td>
            <td>Detalhes de Salvamento</td>
            <td>Como usuário, quero salvar documentos para consulta offline</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF12 O aplicativo deve enviar notificações personalizadas sobre novas publicações relevantes.</summary>
    <center>
    <font size="3"> Tabela 23: Estrutura de Desenvolvimento do Requisito </font>
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
            <td>Notificações personalizadas</td>
            <td>Resolvido</td>
            <td>Teste de Notificação Personalizada</td>
            <td>Sim</td>
            <td>Baixo</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3"> Tabela 24: Artefatos Gerados Pelos Requisitos Funcionais</font>
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
            <td>Notificações personalizadas</td>
            <td>Termos de Notificação Personalizada</td>
            <td>UC12 - Notificação Personalizada</td>
            <td>Detalhes de Notificação Personalizada</td>
            <td>Como usuário, quero receber notificações personalizadas sobre novas publicações</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF13 O aplicativo deve oferecer acesso ao histórico de publicações legislativas.</summary>
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
            <td>1.0</td>
            <td>Acesso ao histórico de publicações legislativas</td>
            <td>Resolvido</td>
            <td>Teste de Histórico</td>
            <td>Sim</td>
            <td>Baixo</td>
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
            <td>Histórico de publicações</td>
            <td>Termos de Histórico</td>
            <td>UC13 - Histórico</td>
            <td>Detalhes de Histórico</td>
            <td>Como usuário, quero acessar o histórico de publicações legislativas</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF14 O aplicativo deve permitir o acesso a publicações legislativas por áreas temáticas.</summary>
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
            <td>1.0</td>
            <td>Acesso por áreas temáticas</td>
            <td>Resolvido</td>
            <td>Teste de Acesso Temático</td>
            <td>Sim</td>
            <td>Baixo</td>
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
            <td>Acesso por áreas temáticas</td>
            <td>Termos de Acesso Temático</td>
            <td>UC14 - Acesso Temático</td>
            <td>Detalhes de Acesso Temático</td>
            <td>Como usuário, quero acessar publicações legislativas por áreas temáticas</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF15 O aplicativo deve permitir o envio de comentários e feedbacks sobre as publicações.</summary>
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
            <td>1.0</td>
            <td>Envio de comentários e feedbacks</td>
            <td>Resolvido</td>
            <td>Teste de Comentários</td>
            <td>Sim</td>
            <td>Baixo</td>
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
            <td>Comentários e feedbacks</td>
            <td>Termos de Comentários</td>
            <td>UC15 - Comentários</td>
            <td>Detalhes de Comentários</td>
            <td>Como usuário, quero enviar comentários e feedbacks sobre as publicações</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF16 O aplicativo deve permitir a visualização de estatísticas sobre as publicações mais acessadas e comentadas.</summary>
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
            <td>1.0</td>
            <td>Estatísticas sobre publicações mais acessadas e comentadas</td>
            <td>Resolvido</td>
            <td>Teste de Estatísticas</td>
            <td>Sim</td>
            <td>Médio</td>
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
            <td>Visualização de estatísticas</td>
            <td>Termos de Estatísticas</td>
            <td>UC16 - Estatísticas</td>
            <td>Detalhes de Estatísticas</td>
            <td>Como usuário, quero visualizar estatísticas sobre as publicações mais acessadas e comentadas</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF17 O aplicativo deve permitir a configuração de alertas personalizados com base em critérios específicos.</summary>
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
            <td>1.0</td>
            <td>Configuração de alertas personalizados</td>
            <td>Resolvido</td>
            <td>Teste de Alertas</td>
            <td>Sim</td>
            <td>Baixo</td>
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
            <td>Configuração de alertas</td>
            <td>Termos de Alertas</td>
            <td>UC17 - Alertas</td>
            <td>Detalhes de Alertas</td>
            <td>Como usuário, quero configurar alertas personalizados com base em critérios específicos</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF18 O aplicativo deve permitir a exportação de documentos em formatos diferentes (PDF, DOCX, etc.).</summary>
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
            <td>Exportação de documentos</td>
            <td>Resolvido</td>
            <td>Teste de Exportação</td>
            <td>Sim</td>
            <td>Médio</td>
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
            <td>Exportação de documentos</td>
            <td>Termos de Exportação</td>
            <td>UC18 - Exportação</td>
            <td>Detalhes de Exportação</td>
            <td>Como usuário, quero exportar documentos em formatos diferentes (PDF, DOCX, etc.)</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF19 O aplicativo deve permitir a visualização de gráficos sobre o desempenho das leis ao longo do tempo.</summary>
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
            <td>1.0</td>
            <td>Visualização de gráficos de desempenho das leis</td>
            <td>Resolvido</td>
            <td>Teste de Gráficos</td>
            <td>Sim</td>
            <td>Alto</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
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
            <td>Gráficos de desempenho</td>
            <td>Termos de Gráficos</td>
            <td>UC19 - Gráficos</td>
            <td>Detalhes de Gráficos</td>
            <td>Como usuário, quero visualizar gráficos sobre o desempenho das leis ao longo do tempo</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

<details>
    <summary>RF20 O aplicativo deve fornecer um mecanismo de ajuda para os usuários.</summary>
    <center>
    <font size="3">Tabela 39: Estrutura de Desenvolvimento do Requisito</font>
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
            <td>Mecanismo de ajuda</td>
            <td>Resolvido</td>
            <td>Teste de Ajuda</td>
            <td>Sim</td>
            <td>Baixo</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>

    <center>
    <font size="3">Tabela 40: Artefatos Gerados Pelos Requisitos Funcionais</font>
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
            <td>Mecanismo de ajuda</td>
            <td>Termos de Ajuda</td>
            <td>UC20 - Ajuda</td>
            <td>Detalhes de Ajuda</td>
            <td>Como usuário, quero um mecanismo de ajuda no aplicativo</td>
            <td>Sim</td>
        </tr>
    </table>
    <font size="3"><p style="text-align: center"><b>Fonte:</b> [Douglas Marinho](https://github.com/M4RINH0).</p></font>
    </center>
</details>

## <a>Rastreabilidade dos Requisitos Não Funcionais</a>

<details>
    <summary>RNF01 Alta disponibilidade do sistema, com 99,9% de uptime.</summary>
        OBS10
</details>
<details>
    <summary>RNF02 Compatibilidade com as versões mais recentes de sistemas operacionais móveis.</summary>
        OBS11
</details>
<details>
    <summary>RNF03 Design responsivo que se adapta a tablets e smartphones.</summary>
        OBS12
</details>
<details>
    <summary>RNF04 Segurança de dados com criptografia de ponta-a-ponta.</summary>
        OBS13
</details>
<details>
    <summary>RNF05 Suporte multilíngue para facilitar o acesso por usuários não-nativos.</summary>
        OBS14
</details>
<details>
    <summary>RNF06 Tempo de resposta de busca inferior a 2 segundos.</summary>
        OBS15
</details>
<details>
    <summary>RNF07 Implementação de medidas de acessibilidade para usuários com deficiência.</summary>
        OBS16
</details>
<details>
    <summary>RNF08 Facilidade de atualização de conteúdo pelo gestor do sistema.</summary>
        OBS17
</details>
<details>
    <summary>RNF09 Suporte técnico com tempo de resposta de 24 horas.</summary>
        OBS18
</details>
<details>
    <summary>RNF10 O aplicativo deve ter uma interface de usuário intuitiva e fácil de navegar.</summary>
        IS09
</details>
<details>
    <summary>RNF11 O aplicativo deve garantir a segurança e a privacidade dos dados dos usuários.</summary>
        IS10
</details>
<details>
    <summary>RNF12 O aplicativo deve estar disponível 24/7, com exceção de períodos de manutenção programada.</summary>
        IS11
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