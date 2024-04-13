# edge_CP1
Trabalho de EDEGE COMPUTING, sistema para analise de luminosidade.
EXPLICAÇÃO DO CÓDIGO:
Este código Arduino foi desenvolvido como parte do projeto Vinheria Agnello, com o objetivo de monitorar os estoques de vinho. Utilizando um Arduino e sensores, especificamente um sensor de luminosidade (LDR), o sistema é capaz de capturar informações sobre a luminosidade do ambiente onde os vinhos estão armazenados.
A funcionalidade principal do código é avaliar os níveis de luminosidade detectados pelo sensor LDR e emitir notificações visuais e sonoras correspondentes ao estado do ambiente de armazenamento. O código opera da seguinte forma:
Definição dos pinos dos LEDs e do buzzer: São definidas as variáveis para os pinos dos LEDs (verde, amarelo, vermelho) e do buzzer, que serão utilizados para indicar o estado da luminosidade.
Configuração do setup(): Inicia a comunicação serial e define os pinos como saídas.
Loop principal (loop()): Realiza a leitura da luminosidade através do sensor LDR e executa as seguintes ações com base nos valores lidos:
Se a luminosidade estiver abaixo de um limite pré-definido (indicando condições ideais), acende o LED verde.
Se a luminosidade estiver em um nível intermediário (indicando atenção necessária), acende o LED amarelo.
Se a luminosidade estiver acima de outro limite pré-definido (indicando uma situação crítica), acende o LED vermelho e ativa o buzzer para emitir um alerta sonoro.
Saída dos dados: Os dados de luminosidade são enviados através da porta serial para monitoramento externo.
Este código proporciona um sistema de monitoramento em tempo real da luminosidade do ambiente de armazenamento dos vinhos, garantindo um controle mais eficaz dos estoques e ajudando a prevenir danos aos produtos devido a condições ambientais inadequadas.

LINK PARA O SISTEMA NO TINKERCAD: 
https://www.tinkercad.com/things/a65bIEMapmm-cp1-vinheria


