# Nuvio Coleção Portugal — catálogos completos

Pacote declarativo de colecções para o Nuvio. O catálogo usa fontes TMDB Discover e fontes TMDB Collection, sem incluir chaves ou credenciais TMDB.

## Conteúdo

- 8 colecções, 153 pastas e 13 240 fontes sem duplicados exactos;
- 42 serviços e redes na colecção `Explorar por streaming`;
- filtros de filmes e séries por serviço, categoria, ano, década, país e prémio;
- fontes com `includeAdult: false` para excluir conteúdos adultos;
- cartões e fundos em JPG, para melhor compatibilidade com televisores.

As colecções usam `TABBED_GRID`. O Nuvio apresenta as fontes como abas ou num selector, dependendo da versão instalada.

## Região e redes

As fontes de serviços de streaming usam a região `PT`. TVE e Atreseries mantêm a região `ES`, porque representam redes espanholas e filtram conteúdo original em espanhol.

As restantes redes televisivas usam `withNetworks`; nesses casos não é aplicado `watchRegion`, pois o filtro é feito pela rede TMDB e não por disponibilidade de streaming.

## Fundos e imagens

As pastas usam fundos próprios para as secções `Descobrir`, `Explorar por categoria`, `Mais faixas` e `Explorar por Prémios`. Os fundos com cache-busting usam `?v=20260812`.

As imagens referenciadas pelo catálogo são JPG e estão incluídas no pacote. Não são incluídos PNG não utilizados.

## Ficheiros do catálogo

`collections.json` é a fonte canónica. `collections-catalogos-final-main.json` e `collections-github-main.js` são cópias idênticas para manter compatibilidade com os destinos existentes.

Apesar da extensão `.js`, `collections-github-main.js` contém um documento JSON, não um módulo JavaScript executável. O Nuvio deve consumi-lo como JSON através do endereço bruto do GitHub.
