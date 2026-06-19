# Plantel de Futebol

## Descrição do Projeto

Este projeto é uma aplicação web simples desenvolvida em HTML, CSS e JavaScript puro, projetada para gerir e visualizar um plantel de jogadores de futebol. A aplicação permite listar todos os jogadores, filtrá-los por nome ou nacionalidade, e visualizar os jogadores agrupados por clube ou por país. Além disso, oferece funcionalidades básicas de CRUD (Criar, Ler, Atualizar, Apagar) para os dados dos jogadores, que são persistidos no `localStorage` do navegador.

## Funcionalidades

*   **Listagem de Jogadores:** Visualiza todos os jogadores do plantel numa tabela interativa.
*   **Pesquisa e Filtragem:** Pesquisa jogadores por nome ou nacionalidade na página principal.
*   **Visualização por Clube:** Lista os jogadores agrupados pelos seus respetivos clubes.
*   **Visualização por País:** Lista os jogadores agrupados pelas suas nacionalidades.
*   **Edição de Jogadores:** Permite editar os detalhes de um jogador existente (número, nome, nacionalidade, idade, posição, clube).
*   **Remoção de Jogadores:** Permite apagar jogadores do plantel.
*   **Persistência de Dados:** Os dados dos jogadores são guardados no `localStorage` do navegador, garantindo que as alterações são mantidas entre sessões.

## Estrutura do Projeto

O projeto é composto pelos seguintes ficheiros:

```
m7-futebol/
├── futebol/
│   ├── data.js
│   ├── index.html
│   ├── jogadores-clube.html
│   ├── jogadores-pais.html
│   ├── style.css
│   └── utils.js
└── README.md
```

*   `index.html`: A página principal que exibe a lista completa de jogadores e a funcionalidade de pesquisa.
*   `jogadores-clube.html`: Página dedicada à visualização dos jogadores organizados por clube.
*   `jogadores-pais.html`: Página dedicada à visualização dos jogadores organizados por país.
*   `style.css`: Contém todos os estilos CSS para a interface da aplicação.
*   `data.js`: Responsável por gerir os dados dos jogadores e clubes. Inclui a lista inicial de jogadores e funções para interagir com o `localStorage`.
*   `utils.js`: Contém funções utilitárias para a renderização da interface, como a criação das linhas da tabela de jogadores e a construção dos modais de edição e eliminação.

## Como Usar

Para executar esta aplicação localmente, siga os passos abaixo:

1.  **Clone o repositório** (ou descarregue o ficheiro ZIP e extraia-o).
2.  **Abra o ficheiro `index.html`** no seu navegador web preferido. Não é necessário um servidor web, pois a aplicação é totalmente cliente-side.

### Interação

*   Utilize a barra de pesquisa na página principal para filtrar jogadores.
*   Navegue entre as páginas 
através dos links de navegação para ver os jogadores por clube ou por país.
*   Clique nos botões "Editar" ou "Apagar" na tabela de jogadores para modificar ou remover um jogador.

## Tecnologias Utilizadas

*   **HTML5:** Estrutura da página web.
*   **CSS3:** Estilização e design responsivo.
*   **JavaScript (ES6+):** Lógica da aplicação, manipulação do DOM e persistência de dados via `localStorage`.
