# DESCRIÇÃO:

Este código em Python utiliza um Raspberry Pi junto com um sensor de distância ultrassônico e um BUZZER para detectar a presença de objetos em uma certa faixa de distância.
Ele configura os pinos GPIO, mede a distância usando o sensor ultrassônico e controla o BUZZER com base nessa medição.
O programa executa em um loop infinito, atualizando continuamente a medição e ligando o BUZZER se um objeto estiver dentro da faixa de detecção.


# TUTORIAL:

1 - Conecte o sensor de distância ultrassônico e o BUZZER ao seu Raspberry Pi. Certifique-se de conectar os pinos corretamente de acordo com o código.

2 - Abra um editor de texto ou uma IDE Python em seu Raspberry Pi.

3 - Copie e cole o código fornecido na janela do editor.

4 - Salve o arquivo com uma extensão .py, por exemplo, sensor_distancia.py.

5 - Abra um terminal no Raspberry Pi.

6 - Navegue até o diretório onde você salvou o arquivo Python usando o comando cd.

7 - Execute o código Python digitando python3 nome_do_arquivo.py no terminal e pressione Enter.

8 - O programa começará a ser executado. Você verá a distância sendo impressa no terminal e o BUZZER emitirá som se um objeto estiver dentro da faixa de detecção.

9 - Para encerrar a execução do programa, pressione Ctrl + C no terminal. Isso irá interromper a execução e limpar os pinos GPIO.
