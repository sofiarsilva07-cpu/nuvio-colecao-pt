# Nuvio Coleção Portugal — catálogos com filtros de streaming

Esta versão usa fontes TMDB Discover para que cada serviço de streaming tenha as opções de filmes e séries filtradas por categoria e ano, mantendo a paginação normal.

## Streaming

Dentro de cada serviço existem:

- `Filmes` e `Séries` sem filtro de ano ou categoria;
- opções por categoria, como `Filmes — Ação` e `Séries — Ação`;
- opções por ano, de 2010 a 2026, além de `antes de 2010`.

O Nuvio apresenta as fontes como abas/opções nativas. O ficheiro de coleções não consegue criar controlos HTML personalizados; dependendo da versão do Nuvio, estas opções podem aparecer como abas ou num selector.

## Importante

Instalar no Nuvio o `Nuvio Catalog Addon`, usado pelas coleções de descoberta, categorias e extras. As fontes de streaming desta versão usam directamente os filtros TMDB Discover e já não dependem do `AIO Metadata`.

Todos os serviços estão limitados à região `PT` e excluem conteúdos adultos. O ZIP não contém qualquer chave TMDB.
