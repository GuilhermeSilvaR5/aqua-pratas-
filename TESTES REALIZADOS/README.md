![serviços-parte1](https://github.com/user-attachments/assets/f88e2cc6-88e4-41cc-863b-f44c304b6696)
Testes Realizados
1. Dispositivos Testados

Foram utilizados dispositivos reais para validar a experiência móvel:

Android: Google Pixel 4 (1080×2280)

iPhone: iPhone 12 (1170×2532)

Tablet: iPad 9ª geração (1620×2160)

2. Navegadores Testados

Chrome Mobile (Android e iOS)

Safari (iOS)

Firefox Mobile

3. O que foi Verificado

Funcionamento do touch em botões, links e menus;

Velocidade de carregamento do site em redes Wi-Fi, 4G e 3G;

Comportamento do layout em diferentes resoluções;

Renderização de imagens e textos;

Navegação entre páginas e retorno ao topo;

Estabilidade geral da interface.

4. Resultados dos Testes

Botões e links responderam corretamente ao toque, sem atrasos.

O site carregou rapidamente em 4G e com tempo aceitável em 3G.

O layout manteve sua estrutura em todas as resoluções testadas.

Navegação suave e sem travamentos nos navegadores analisados.

5. Problemas Encontrados e Soluções

Imagens demorando a carregar em rede mais lenta

Solução: Implementado lazy loading para otimizar o carregamento.

Elementos muito próximos em telas pequenas

Solução: Ajustado o padding e espaçamento entre áreas clicáveis no CSS.

Pequenas quebras de alinhamento em tablets

Solução: Ajustadas media queries para resoluções acima de 1200px.

6. Limitações Conhecidas

Em conexões extremamente lentas (como EDGE), algumas imagens podem levar mais tempo para exibir.

Dispositivos muito antigos apresentam leve atraso ao rolar páginas longas, devido ao volume de elementos visuais.

7. Evidências dos Testes


Prints do comportamento em 3G e 4G

Comparação entre navegadores
