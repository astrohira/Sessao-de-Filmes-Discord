CineNeds
O CineNeds é uma plataforma minimalista e moderna para organização de sessões de cinema em grupo, ideal para comunidades no Discord. O sistema permite buscar filmes em tempo real, agendar datas para as sessões e gerenciar uma lista dinâmica com persistência de dados.

Funcionalidades
Busca via API: Integração com o TMDB para obter pôsteres, títulos e anos de lançamento automaticamente.

Agendamento Dinâmico: Escolha de data e hora para cada sessão.

Organização Inteligente: A lista é ordenada automaticamente, mostrando os filmes com datas mais próximas primeiro.

Edição em Tempo Real: Altere a data de um filme diretamente no card sem precisar readicioná-lo.

Persistência de Dados: Utiliza o localStorage do navegador para manter sua lista salva mesmo após fechar a página.

Design Moderno: Interface inspirada no Modo Escuro do Discord, focada em usabilidade e estética limpa.

Notificações Internas: Sistema de avisos (toasts) para feedback de ações sem pop-ups intrusivos.

Como usar
Clone este repositório ou baixe os arquivos index.html, style.css e script.js.

Certifique-se de que os três arquivos estão na mesma pasta.

Abra o arquivo index.html em qualquer navegador moderno.

Tecnologias Utilizadas
HTML5: Estrutura semântica.

CSS3: Estilização avançada com variáveis, Grid, Flexbox e animações.

JavaScript (ES6+): Lógica de manipulação de DOM, integração com API assíncrona (Fetch) e persistência local.

TMDB API: Banco de dados de filmes.

Configuração da API
O projeto já conta com uma chave de API configurada no arquivo script.js. Caso deseje usar sua própria chave:

Crie uma conta em TheMovieDB.org.

Obtenha sua chave de API (v3 auth).

Substitua a constante API_KEY no topo do arquivo script.js.

Desenvolvido para as sessões do grupo CineNeds.