# Nuvio Coleção Portugal — catálogos

Esta versão usa `catalogSources` do Nuvio para permitir paginação normal dos add-ons.

## Importante

Instalar no Nuvio:

1. `AIO Metadata`, para os catálogos de Netflix, Prime Video, Disney+, Max e Apple TV+.
2. `Nuvio Catalog Addon`, para categorias, descoberta, tendências, avaliações e família.

Os catálogos addon são pagináveis e não têm o limite artificial de 20/40 itens que existia nas fontes estáticas. As pastas de streaming têm apenas duas fontes: Filmes e Séries.

O filtro dinâmico Ano/Categoria é fornecido pelo catálogo/add-on, não pelo ficheiro `collections.json`. O Nuvio mostra os filtros disponíveis no catálogo instalado. Para filtros simultâneos de serviço + ano + género, é necessário instalar/configurar um catálogo TMDB Discover+ ou equivalente; o ZIP não contém uma chave TMDB.

Os serviços SkyShowtime, Filmin e RTP Play permanecem com as fontes TMDB originais porque o AIO Metadata não publica IDs estáveis verificados para esses três catálogos.
