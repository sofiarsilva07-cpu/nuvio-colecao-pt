# Nuvio Coleção Portugal — catálogos completos

Esta versão usa fontes TMDB Discover em todas as coleções, para que o conteúdo não dependa de um catálogo/add-on adicional e para manter a paginação normal.

## Streaming

Dentro de cada serviço existem:

- `Filmes` e `Séries` sem filtro de ano ou categoria;
- opções por categoria, como `Filmes — Ação` e `Séries — Ação`;
- opções por ano, de 2010 a 2026, além de `antes de 2010`.

O Nuvio apresenta as fontes como abas/opções nativas. O ficheiro de coleções não consegue criar controlos HTML personalizados; dependendo da versão do Nuvio, estas opções podem aparecer como abas ou num selector.

As restantes coleções também usam ordenação por data descendente, para mostrar primeiro o conteúdo mais recente. A pasta `Em breve` usa data ascendente, mostrando primeiro o lançamento mais próximo.

Foram acrescentadas as coleções `Explorar Filmes por ano` e `Explorar Séries por ano`, com pastas para cada ano de 2027 a 2000 e pastas por década de 1990 a 1950. Cada pasta usa um intervalo de datas exacto.

Foi também acrescentada a coleção `Explorar por Prémios`, com pastas para Óscares, Emmys, Globos de Ouro, Cannes e BAFTA.

Foi acrescentada a coleção `Ver conteúdo por País`, com opções separadas de `Filmes` e `Séries` para Japão, China, Coreia do Sul, Índia, Espanha, França, Países Nórdicos e Portugal. Todas são ordenadas pela data de lançamento mais recente.

A coleção `Mais faixas` usa agora um fundo cinematográfico próprio (`mais-faixas-background.jpg`).

As coleções `Explorar por categoria` e `Descobrir` também têm agora fundos próprios: `explorar-categorias-background.jpg` e `descobrir-background.jpg`.

As fontes TMDB Discover das secções e filtros foram separadas por ano: 2027–2000 e, depois, por décadas até 1950. A ordem das opções é da mais recente para a mais antiga, evitando resultados de anos misturados.

`Mais faixas` ficou reservado para conteúdos gerais. Os prémios e os países estão apenas nas coleções próprias `Explorar por Prémios` e `Ver conteúdo por País`.

## Fundos compatíveis com a TV

Os fundos têm URLs directos e cache-busting no JSON: `destaques-background.jpg`, `premios-background.jpg` e `descobrir-background.jpg`.

As imagens dos cartões foram convertidas de PNG para JPG para compatibilidade com televisores que não apresentam PNG remoto.

As listas de recentes, populares, em breve, tendências e mais bem avaliados não têm limite artificial de 20 ou 40 itens. Esses números foram removidos dos títulos; a navegação usa a paginação normal do TMDB.

Foram adicionadas à secção de streaming as redes CCTV, CBS, FOX, Channel 4, Fuji TV, ESPN, E!, The CW, Showtime, History e Discovery. Cada uma tem filtros de séries por ano e por década, ordenados da mais recente para a mais antiga.

Foram também adicionados Animal Planet, FX, TVI, SIC, AMC, Viki, Paramount+ e Crunchyroll, com cartões JPG compatíveis com televisores.

Foram ainda adicionados iQIYI, Syfy, Starz, Showcase, Hulu, TVE e Atreseries.

Foram também adicionados Youku, WeTV, Tencent Video, YouTube, ZDF, Das Erste, BBC One e BBC Two.

O ficheiro `collections-github-main.js` é a cópia pronta para substituir a versão antiga no GitHub. A TV deve usar esse ficheiro atualizado; ele já aponta para JPG, usa UTF-8 correto e inclui os 42 serviços/redes.

## Importante

Não é necessário instalar o `Nuvio Catalog Addon` nem o `AIO Metadata` para resolver as fontes deste pacote.

Todos os serviços estão limitados à região `PT` e excluem conteúdos adultos. O ZIP não contém qualquer chave TMDB.
