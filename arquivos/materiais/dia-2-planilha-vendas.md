# Planilha de exemplo · dia 2

**Dados fictícios.** Uma rede inventada de lojas de eletroportáteis, vendas de setembro.
Use esta planilha nos exercícios 4, 5 e 6 se você não tiver uma à mão.

- **Para colar como texto:** copie o bloco abaixo inteiro.
- **Para anexar:** `dia-2-planilha-vendas.xlsx`, o mesmo conteúdo.

```
VENDAS · SETEMBRO 2026 · REDE FICTÍCIA DE ELETROPORTÁTEIS
Data	Loja	Estado	Produto	Qtd	Valor
01/09/2026	Loja Aldeota	CE	Liquidificador	2	378
02/09/2026	Loja Iguatemi	CE	Air fryer	2	798
03/09/2026	Loja Centro	CE	Ventilador	7	R$ 1.113,00
07/09/2026	Lj Aldeota	CE	Ventilador	3	477
08/09/2026	Loja Iguatemi	Ceará	Cafeteira	8	1992
09/09/2026	Loja Centro	CE	Liquidificador	6	1134
13/09/2026	Loja Aldeota	CE	Liquidificador	8	1512
14/09/2026	Loja Iguatemi	CE	Air fryer	3	1197
15/09/2026	Loja Centro	CE	Ventilador	4	636
19/09/2026	Lj Aldeota	CE	Ventilador	4	636
20/09/2026	Loja Iguatemi	CE	Cafeteira	5	1245
21/09/2026	Loja Centro	CE	Liquidificador	6	1134
2026-09-25	Loja Aldeota	CE	Liquidificador	6	1134
26/09/2026	Loja Iguatemi	CE	Air fryer	4	1596
27/09/2026	Loja Centro	CE	Ventilador	2	318
	Subtotal CE				15300
04/09/2026	Loja Boa Viagem	PE	Cafeteira	4	996
05/09/2026	Loja Recife Antigo	PE	Liquidificador	9	1701
10/09/2026	Loja Boa Viagem	PE	Air fryer	2	R$ 798,00
11/09/2026	Loja Recife Antigo	PE	Ventilador	2	318
16/09/2026	Loja Boa Viagem	PE	Cafeteira	2	498
17/09/2026	Loja Recife Antigo	PE	Liquidificador	5	945
22/09/2026	Loja Boa Viagem	PE	Air fryer	7	2793
23 set	Loja Recife Antigo	PE	Ventilador	7	1113
28/09/2026	Loja Boa Viagem	PE	Cafeteira	7	1743
06/09/2026	Loja Ponta Negra	RN	Air fryer	6	2394
12/09/2026	Loja Ponta Negra	RN	Cafeteira	9	2241
18/09/2026	Loja Ponta Negra	RN	Air fryer	9	3591
24/09/2026	Loja Ponta Negra	RN	Cafeteira	2	498
	TOTAL GERAL				50229
```

---

## Gabarito · abra só depois de fazer os exercícios

**Exercício 4 · o raio-x**
- **32 linhas no total:** 1 de título, 1 de cabeçalho, 28 vendas, 1 subtotal e 1 total.
- **28 registros de venda.** Se a IA disse 30, contou o subtotal e o total como vendas.
- **6 colunas.** "Valor" não diz se é o preço da unidade ou o total da venda: é o total (Qtd × preço).

**Exercício 5 · os defeitos plantados (são 6)**

| # | Defeito | Onde |
|---|---|---|
| 1 | Título em célula mesclada | linha 1 |
| 2 | Linha de subtotal no meio dos dados | "Subtotal CE", depois da última venda do Ceará |
| 3 | O mesmo nome escrito de dois jeitos | "Loja Aldeota" e "Lj Aldeota" (2 vezes) |
| 4 | O mesmo estado escrito de dois jeitos | "CE" e "Ceará" (1 vez) |
| 5 | Número guardado como texto | 2 valores escritos "R$ …" |
| 6 | Data em outro formato | "2026-09-…" e "… set" |

**E um sétimo, que não estava na lista do pedido:** o "TOTAL GERAL" está errado. Quem montou a
planilha somou o subtotal do Ceará junto, e o Ceará entrou duas vezes. Se a IA achou isso
sozinha, ela leu de verdade.

**Exercício 6 · os números certos** (sobre os 28 registros)

| Número | Valor certo | Quantos registros |
|---|---|---|
| Total vendido em setembro | **R$ 34.929,00** | 28 |
| Ceará | R$ 15.300,00 | 15 |
| Pernambuco | R$ 10.905,00 | 9 |
| Rio Grande do Norte | R$ 8.724,00 | 4 |
| Loja Aldeota (juntando "Lj Aldeota") | R$ 4.137,00 | 5 |
| O "TOTAL GERAL" da planilha | R$ 50.229,00 | está errado |

**Como cada erro aparece no número:**
- Somou a coluna Valor inteira: o subtotal e o total entram, e o número sai inflado.
- Deixou de fora os 2 valores em texto: o total sai menor.
- Separou "Lj Aldeota" de "Loja Aldeota": a Aldeota sai menor do que é.
- Confiou no "TOTAL GERAL": o Ceará foi contado duas vezes.

Por produto, para quem quiser ir além: Liquidificador R$ 7.938,00 · Cafeteira R$ 9.213,00 · Ventilador R$ 4.611,00 · Air fryer R$ 13.167,00
