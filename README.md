# Coleção Nuvio Portugal

Pacote nativo para o Nuvio, configurado para Portugal.

Inclui capas tituladas, streaming sem limite artificial de resultados, filtros por categoria e ano dentro de cada serviço, filtros por ano nas categorias, descoberta, tendências, idiomas, décadas, sagas, anime, família e faixas adicionais.

As fontes base de Netflix, Prime Video, Disney+, Max, Apple TV+, SkyShowtime, Filmin e RTP Play não têm `voteCountGte` nem limite de itens: o Nuvio/TMDB pode continuar a paginar os resultados disponíveis.

O modo `TABBED_GRID` e a aba `Tudo` ficam definidos nas quatro colecções. No Nuvio, as fontes são apresentadas como abas; o JSON nativo não cria controlos dropdown personalizados.

## Actualização periódica

As faixas recentes, em breve, tendências e novidades usam datas fixas no JSON e devem ser actualizadas periodicamente.

A faixa `Recomendados para ti` usa uma selecção de fallback; personalização real depende do histórico do Nuvio/Trakt quando essa integração estiver disponível.
