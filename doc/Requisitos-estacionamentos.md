## Requisitos / Estacionamentos

```console
Recurso será responsável por controlar as entradas e saídas de veículos.
Apenas clientes cadastrados podem estacionar.
Para estacionar o cliente deve fornecer o CPF cadastrado.
```

– `Os requisitos a seguir requerem autenticação e são restritos ao administrador`

- Ao estacionar um veículo as seguintes informações devem ser armazenadas: placa, marca,
modelo, cor, data de entrada, cpf.
- O processo de registro de um estacionamento deverá gerar um número de recibo único que será
armazenado junto ao demais dados de entrada.
- Ao deixar o estacionamento as seguintes informações devem ser registradas: data de saída, valor
do período estacionado e valor do desconto
- Uma vaga de estacionamento poderá ser ocupada por muitos veículos, desde que, não ao mesmo
tempo.
- O desconto deve ser concedido sempre após o cliente completar 10 estacionamentos (entrada e
saída).
- A porcentagem de desconto será de 30% sobre o valor a pagar do próximo estacionamento
completado (entrada e saída)
- O estacionamento deverá ser vinculado a uma vaga e ao cliente proprietário do veículo.
- Ao retirar o veículo o cliente deverá informar o número do recibo gerado na data de entrada

– `Os requisitos a seguir requerem autenticação e são acessíveis pelo administrador e/ou cliente`

- Apenas um administrador poderá realizar a operação de check-in.
- Apenas um administrador poderá realizar a operação de check-out.
- Administrador e cliente possuem permissão para localizar os dados de entrada no estacionamento
pelo número do recibo.
- O administrador poderá listar os estacionamentos pelo CPF do cliente.
- O cliente poderá listar apenas os seus próprios dados de estacionamentos.

– `O custo do estacionamento:`

1. Primeiros 15 Minutos – R$ 5.00
2. Primeiros 60 Minutos – R$ 9.25
3. A partir dos primeiros 60 Minutos iniciais, inclua no custo de R$ 9.25 a cobrança adicional
de R$ 1.75 para cada faixa de 15 Minutos adicionais aos primeiros 60 minutos
4. Use a tabela de cálculos para entender o processo

`Tabela de cálculos (exemplos):`
| Entrada | Saída | Valor
| --- | --- | ---
| 01-03-2023 13:00 | 01-03-2023 13:15 | R$ 5.00
| 01-03-2023 13:00 | 01-03-2023 14:00 | R$ 9,25
| 01-03-2023 13:00 | 01-03-2023 14:30 | R$ 12,75 (9,25 + 1,75 * 2)
| 01-03-2023 13:00 | 01-03-2023 15:00 | R$ 16,25 (9,25 + 1,75 * 4)
| 01-03-2023 13:00 | 01-03-2023 15:10 | R$ 18,00 (9,25 + 1,75 * 5)

- Documentar todos os recursos criados.
- Realizar testes de integração do tipo ponto a ponto (end-to-end) dos recursos criados.

– `Relatório em Pdf`
- O cliente poderá gerar um relatório em Pdf com sua lista de estacionamentos. 