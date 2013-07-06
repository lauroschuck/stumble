Este é um aplicativo de teste desenvolvido para o Firefox OS Hackaton ocorrido na 14ª edição do Fórum Internacional de Software Livre (FISL14), ocorrido de 3 a 6 de junho de 2013, em Porto Alegre/RS e foi desenvolvido por Lauro Feiten Schuck, e está disponível sob licença MIT (ver LICENSE.txt).

O nome da aplicação é 'Stumble' (tropeçar, "encontrar ao acaso"), e tem por objetivo avisar o usuário sobre pontos e/ou estabelecimentos de interesse dos quais ele esteja perto. Para tal, é utilizada a função de Geolocalização do dispositivo e, via uma conexão de dados (wifi ou mobile data) a Places API do Google. Inconvenientemente, para uso desta API é necessário o uso de uma API Key, a qual pode ser obtida gratuitamente. Para mais informações, leia a página da Places API:

https://developers.google.com/places/documentation/

Após informar a sua API Key na seção de configuração do aplicativo, ele estará pronto para uso. Utilize o menu para navegar até a lista de 'Interesses'. Clique no menu de adição para incluir novos interesses, e clique em interesses existentes para removê-los.

Para que o aplicativo execute, volte até a página inicial, e automaticamente todos os interesses serão pesquisados, conforme os parâmetros informados em sua criação (palavra chave, raio de busca, intervalo de pesquisa).

Note que como se trata de uma aplicação desenvolvida com o objetivo de aprender sobre o Firefox OS, o qual na época ainda se encontrava em estágio "developer preview", esta aplicação possui diversas limitações, tanto por parte das APIs disponíveis no momento quanto por parte de seu desenvolvimento rápido. A principal limitação fica por conta da incapacidade de executá-lo em 'background', ou seja, manter as pesquisas ativas enquanto o usuário utiliza outras aplicações; no momento a API encontrava-se em 'Initial proposal of API' - ver https://wiki.mozilla.org/Webapi

A aplicação pode ser testada sem o uso de um celular com Firefox OS, bastando utilizar a extensão 'Firefox OS Simulator', disponível para versões recentes do navegador Mozilla Firefox. Instruções de uso estão disponíveis no site da Mozilla e em diversos tutoriais na internet.

Para teste de localizações pelo Firefox OS Simulator, aqui estão algumas coordenadas:

 ------------------------------------------------------------
| Local                            | Latitude   | Longitude  |
|------------------------------------------------------------|
| PUC-RS / FISL                    | -30.059084 | -51.173308 |
| Av. Paulista, São Paulo/SP       | -30.033461 | -51.230672 |
| Av. Atlântica, Rio de Janeiro/RJ | -22.967033 | -43.180697 |
| 1st Avenue, Nova York/EUA        |  40.763408 | -73.959211 |
| Berlim, Alemanha                 |  52.519184 |  13.406139 |
 ------------------------------------------------------------


