# Projeto-2-Dois-displays-0-a-99
Este projeto em MicroPython utiliza dois displays de 7 segmentos para exibir números de 0 a 99 em sequência, com intervalo de 0,5 segundos entre cada número.

🔢 Contador de 7 Segmentos – Evolução do Projeto
Projeto 1 – Display Único

Exibia um único dígito de 0 a 9.

Controle de 7 GPIOs correspondentes aos segmentos A–G.

Loop simples mostrando os números em sequência com intervalo de 0,5 s.

Conceitos aplicados:

Controle digital de pinos (HIGH/LOW)

Representação de padrões binários em listas

Loop for e temporização com sleep()

Projeto 2 – Dois Displays (Contador de 0 a 99)

Evolução do projeto anterior, agora com dois displays de 7 segmentos, permitindo contar de 00 a 99.

Controle de 14 GPIOs (7 por display) para os segmentos A–G de cada display.

Mapeia cada número (00 a 99) para os segmentos correspondentes.

Loop contínuo mostrando os números em sequência, com intervalo de 0,5 s.

Conceitos aplicados:

Mesmos conceitos do projeto anterior (GPIO, listas, loops, sleep())

Adição de controle de múltiplos displays, exigindo mapeamento e atualização separados para cada display

Lógica de incremento e “overflow” do dígito da esquerda ao passar de 9

🔗 Links dos Projetos no Wokwi

Projeto 1 – Display único (0 a 9): https://wokwi.com/projects/441301444611430401

Projeto 2 – Dois displays (0 a 99): https://wokwi.com/projects/440540478769006593

💡 Resumo da evolução:
O segundo projeto é uma extensão natural do primeiro: mantém toda a lógica de controle de segmentos, mas adiciona um display extra e controle de contagem dupla, transformando um simples contador de 0 a 9 em um contador completo de 0 a 99.
