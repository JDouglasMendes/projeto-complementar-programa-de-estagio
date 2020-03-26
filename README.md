# Projeto complemtar para o programa de estágio da LG Lugar de Gente.

Projeto complementar para os estagiários da LG Lugar de Gente que teve interesse em praticar de forma individual os tópicos vistos durante o  curso ministrado por **Douglas Mendes**.

## Projeto para Estacionamento

#### Um shopping começará a cobrar pelo uso do estacionamento, os preços serão:
**Motocicleta**
* Primeira hora R$ 1.50
* Após a primeira hora R$ 1 por hora adicional.

**Carro de passeio**
* Primeira hora R$ 3
* Após a primeira R$ 1.50 por hora adicional.

**Caminhonetes**
* Primeira hora R$ 3
* Após a primeira R$ 1.50 por hora adicional.

_Para cada veículo que faz uso do estacionamento terá as seguintes informações mantidas._
* Placa do veículo
* Tipo de veículo {Motocicleta, Carro, Camionetes}
* Data e hora de entrada.
* Data e hora de saída.
* Valor pago

**Regras de exceção:**

* Caso o veículo fique menos de 15 minutos não será cobrado.
* Quando o veículo utilizar o estacionamento pela 3ª vez, a próxima utilização será grátis.

**Relatórios gerados pela aplicação:**

* Relatórios de veículos que utilizaram o estacionamento em uma determinada data(Parâmetro).
* Relatório de todos os veículos que já utilizaram o estacionamento agrupador por tipo e ordenados por placa.
* Relatório agrupado por quantidade de veículos e data de uso, Exemplo:

Data      | Motocicletas | Carros | Caminhonetes
----------|--------------|--------|----------------------
01/01/2020| 1            | 2      | 0
02/01/2020| 0            | 3      | 5

* Tempo médio de cada tipo de veículo no estacionamento.

