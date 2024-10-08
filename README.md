# Sistema de Estacionamento

Este projeto é uma aplicação simples de um sistema de estacionamento, que permite adicionar, remover e listar veículos, além de calcular o valor a ser pago pelos usuários com base no tempo de permanência e nas taxas estabelecidas.

## Funcionalidades

- **Adicionar Veículo**: O sistema permite que o usuário adicione um veículo, informando sua placa.
- **Remover Veículo**: O sistema remove um veículo do estacionamento, calculando o valor total a ser pago com base no tempo de permanência e nas taxas.
- **Listar Veículos**: O sistema exibe a lista de todos os veículos atualmente estacionados.

## Fórmula de Cálculo

O cálculo do valor total para remover um veículo é feito da seguinte maneira:

```
Valor Total = Preço Inicial + (Preço por Hora * Número de Horas)
```

Onde:
- **Preço Inicial**: É um valor fixo que é definido no momento da criação do estacionamento.
- **Preço por Hora**: É um valor fixo cobrado por cada hora que o veículo permanece estacionado.
- **Número de Horas**: É a quantidade de horas que o veículo permaneceu no estacionamento, informada pelo usuário no momento da remoção.

## Exemplo de Uso

### Adicionar um Veículo
O sistema pedirá para o usuário inserir a placa do veículo. Após a inserção, o veículo será adicionado à lista.

### Remover um Veículo
O sistema solicitará a placa do veículo e verificará se ele está estacionado. Se estiver, o sistema solicitará o número de horas que o veículo permaneceu estacionado e calculará o valor a ser pago, removendo o veículo da lista.

### Listar Veículos
O sistema exibirá a lista de veículos estacionados no momento.

## Tecnologias Utilizadas

- C#
- .NET Framework
- Visual Studio Code
