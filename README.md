Componente FMX Loading. Componente para simulação de carregamento feito com base no componente TCircle e animado com o TFlaotAnimation.

Metodos:
Start; {inicia a animação}
Stop; {para a animação de loading}
Property:
Interpolation; {permite alterar a animação de loading}

Recomendações:
Utilizar o Uses Loading;
Utilizar os metodos em threading para não parar o processo principal enquanto estiver em modo Start. Ex de threading para utilizar os metodos start e stop enquando faz algum processo:

TThread.CreateAnonimousThread(
