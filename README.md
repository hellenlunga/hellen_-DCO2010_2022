# Entregas para o DCO2004: LABORATÓRIO DE RÁDIO DEFINIDO POR SOFTWARE (2022.1)
## Hands-on 01
16.a. O que acontece com o sinal no tempo quanto à taxa de amostragem é pequena em relação à frequência do seno do Signal Source?
Aliasing ou foldover.

16.b. O que acontece com o sinal na frequência quanto à taxa de amostragem é pequena em relação à frequência do seno do Signal Source?
Alta frequência é medida erroneamente como sendo de frequência mais baixa. No flowgraph podemos observar uma raia centrada na frequência 0.

16.c. O que pode explicar esses fenômenos? Qual sua relação com a teoria de Nyquist?
Quando a taxa de amostragem para determinado sinal é menor que a frequência de Nyquist, ocorre um efeito chamado aliasing ou foldover. Ocorre um cruzamento entre as réplicas do sinal de modo que não é possível recuperar o sinal por amostragem.

24.a. Qual o comportamento do sinal no tempo (verifique e descreva o comportamento no osciloscópio virtual)?
Superposição ou soma linear de 2 sinais, com amplitude 2.

24.b. Qual o comportamento do sinal na frequência (verifique e descreva o comportamento no analisador de espectro virtual)?
No slowgraph podemos observar as raias centradas nas frequências de 100Hz e 5000Hz.

27.a. O que pode ser concluído ao analisar o sinal no domínio da frequência (analise em uma das bandas laterais, passando a seta do mouse sobre os picos)?
A multiplicação resultou em um AM-DSB-SC.

27.b. Existe alguma explicação matemática para esse comportamento?
A distancia entre as envoltórias varia proporcionalmente ao valor instantâneo do sinal modulante, pois as duas envoltórias tem a mesma forma mas fases opostas. 

27.c. Ao analisar o sinal de saída no tempo, mesmo que não tenhamos como distinguir bem como estão às frequências, podemos perceber certo padrão no comportamento das amplitudes que compõe o sinal. Que padrão é esse? Esse padrão equivale a qual tipo de modulação?
As envoltórias se cruzam no eixo de amplitude zero e nesse ponto de passagem o sinal composto sofre INVERSÂO de fase. Esse padrão equivale a modulação AM-DSB-SC.


