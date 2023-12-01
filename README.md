# BLE-Simulator

# Sistema para Controle de Registro Hospitalar

## Descrição
Este código simula a utilização de um BLE (Bluetooth Low Energy), juntamente com um sensor. Para isso, foi utilizado a comunicação Serial entre dois arduinos, e com isso, eles irão somando o número de pacientes conforme a entrada dos mesmo dentro de cada ala com um sensor presente.

## Funcionamento
1. O programa inicia com o número de pacientes em 1, e a cada 2s, ele acrescenta +1 paciente ao ambiente, devido as leituras feitas pelo segundo Arduino UNO.

## Variáveis
- `backlight`: Adiciona a declaração do pino backlight.
- `paciente`: Variável que armazena o número dos pacientes.

## Funções
1. `void loop()`: Realiza o processo de looping do processo.

## Integrantes
1. Marcelo Vieira de Melo - RM: 552953
2. Caio Hideki Cardenas Ishizu – RM: 553630

## Observações
- O código é um exemplo básico e pode ser estendido para atender a requisitos específicos do sistema hospitalar.
- Certifique-se de substituir os dados de login padrão por informações seguras em um ambiente de produção.

---

**Observação:** Antes de implementar ou utilizar este código, verifique se está em conformidade com as regulamentações locais e garanta que o sistema atenda aos padrões de segurança necessários.
