# Lima_RSR_de_sinal_AM
Descrição: Este projeto tem por objetivo criar um programa que realize o cálculo da razão sinal-ruído de um sinal AM por meio do software MATLAB.
Motivação: Os sinais de rádios AM são sempre recebidos por um demodulador com algum ruído. Calculando a RSR desses sinais antes e após a demodulação
é possivel projetar e avaliar diversos aspectos dos equipamentos moduladores, demoduladores e do prórpio sinal AM.

A user interface do MATLAB pode ser gerada com o App Designer, que é uma tool do MATLAB2019a. Com o App Designer, é possivel utilizar programação gráfica similar para,de forma similar ao Front Panel do LABVIEW, gerar a GUI. Além disso, o App Designer gera automaticamente as variáveis e o código a ser utlizado na aba de programação, tornando bem simples e rápida a programação da interface gráfica do aplicativo

IMPORTANTE:1)A versao do MATLAB utilizada foi a R2019b, outras versões podem não executar os programas corretamente
           2)Para executar o app SNR_Analyzer, é necessário que o arquivo .bin e o arquivo Sinal.m estejam na mesma pasta do
           arquivo .mlapp
           3)Algumas funcionalidades, como a escolha do nome do arquivo e a SNR antes da demodulação, ainda não foram implementadas e                estão em desenvolvimento para a versão 2.0 do app.
