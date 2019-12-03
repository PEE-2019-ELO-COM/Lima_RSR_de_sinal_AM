# Lima_RSR_de_sinal_AM
Descrição: Este projeto tem por objetivo criar um programa que realize o cálculo da razão sinal-ruído de um sinal AM por meio do software MATLAB.

Motivação: Os sinais de rádios AM são sempre recebidos por um demodulador com algum ruído. Calculando a RSR desses sinais antes e após a demodulação
é possivel projetar e avaliar diversos aspectos dos equipamentos moduladores, demoduladores e do prórpio sinal AM.

A user interface do MATLAB pode ser gerada com o App Designer, que é uma tool do MATLAB2019b. Com o App Designer, é possivel utilizar programação gráfica similar para,de forma similar ao Front Panel do LABVIEW, gerar a GUI. Além disso, o App Designer gera automaticamente as variáveis e o código a ser utlizado na aba de programação, tornando bem simples e rápida a programação da interface gráfica do aplicativo

IMPORTANTE:

1)A versao do MATLAB utilizada foi a R2019b, outras versões podem não executar os programas corretamente
           
2)Para executar o app SNR_Analyzer, é necessário que o arquivo .bin e o arquivo Sinal.m estejam na mesma pasta do arquivo .mlapp
           
3)Algumas funcionalidades, como a escolha do nome do arquivo e a SNR antes da demodulação, ainda não foram implementadas e                estão em desenvolvimento para a versão 2.0 do app.

4)Na caixa de texto File Name, deve ser colocado o nome do arquivo .bin a ser utilizado para obter as amostras de sinal. Os arquivos obtidos pelo Radio Definido por Software do laboratório de Comunicações Analógicas e Digitais estão dentro da pasta deste repositório.

5)A funcionalidade de cálculo de SNR antes da demodulação presente na versão 1 da GUI foi retirada pois não era prática teoricamente.

Exemplo de funcionamento do App:
![Exemplo](https://github.com/PEE-2019-ELO-COM/Lima_RSR_de_sinal_AM/blob/master/Exemplo%20de%20funcionamento%20do%20SNR%20App.PNG)

FLuxograma:
![Fluxograma](https://github.com/PEE-2019-ELO-COM/Lima_RSR_de_sinal_AM/blob/master/Fluxograma%20APP%20SNR.PNG)


GUI Versão 1:

![GUI](https://github.com/PEE-2019-ELO-COM/Lima_RSR_de_sinal_AM/blob/master/GUI%20APP%20SNR.PNG)

GUI Versão 2:

![GUI v2](https://github.com/PEE-2019-ELO-COM/Lima_RSR_de_sinal_AM/blob/master/SNR%20App%20GUI%20V2.PNG)

Diagrama de Classes e Relacionamentos(corrigido):
![Diagrama corrigido](https://github.com/PEE-2019-ELO-COM/Lima_RSR_de_sinal_AM/blob/master/Diagrama%20de%20Classes%20e%20Relacionamentos(corrigido).PNG)


