# Números de exemplo · exercício 1

**Dados fictícios.** A mesma rede de eletroportáteis que atravessa o desafio, num mês que já
fechou: agosto de 2026. Use se você não tiver um relatório seu à mão.

**A situação:** você é analista comercial da rede. Todo mês prepara o relatório de vendas para o
diretor comercial. O de agosto você já entregou, no dia 3 de setembro.

**As três respostas curtas, para o Traga:**
- **Quem lê:** o diretor comercial.
- **O que ele faz depois de ler:** decide a meta de cada estado e o pedido de estoque do mês seguinte.
- **O que aconteceu de diferente em agosto:** a campanha do Dia dos Pais, de 1 a 9 de agosto.

**Os números, para colar como texto:**

```
VENDAS POR ESTADO · JULHO × AGOSTO 2026
Estado	Julho	Agosto	Meta de agosto
Ceará	R$ 13.900	R$ 15.100	R$ 14.500
Pernambuco	R$ 12.950	R$ 13.480	R$ 14.000
Rio Grande do Norte	R$ 9.300	R$ 8.610	R$ 9.000
Rede	R$ 36.510	R$ 37.190	R$ 37.500

VENDAS DA REDE POR PRODUTO · JULHO × AGOSTO 2026
Produto	Julho	Agosto
Air fryer	R$ 14.200	R$ 17.980
Cafeteira	R$ 9.400	R$ 8.550
Liquidificador	R$ 7.150	R$ 6.890
Ventilador	R$ 5.400	R$ 3.770
```

**O relatório que você entregou** está no gabarito, abaixo. Ele só entra na conversa na rodada 2.

---

## Gabarito · abra só depois

### O relatório que a analista entregou, em 3 de setembro

```
RELATÓRIO DE VENDAS · AGOSTO DE 2026
Para: diretor comercial

NO TOPO
1. A rede vendeu R$ 37.190: +2,9% sobre julho e -0,8% contra a meta (R$ 37.500).
2. A air fryer vendeu R$ 17.980, +26,6% sobre julho, e foi 48% das vendas do mês. Agosto teve a campanha do Dia dos Pais (1 a 9/8).
3. Pernambuco e Rio Grande do Norte ficaram abaixo da meta (-3,7% e -4,3%). O Ceará passou (+4,1%).

PARA DECIDIR
- A meta de setembro de Pernambuco e do Rio Grande do Norte: manter a de agosto ou rever?
- O pedido de air fryer para setembro: agosto vendeu +26,6% sobre julho, com campanha. Setembro não tem campanha. O pedido volta ao nível de julho, ou fica no de agosto?

O RESTO
- Ventilador -30,2%, cafeteira -9,0%, liquidificador -3,6%.
- O total de julho na tabela está R$ 36.510, mas a soma dos estados dá R$ 36.150. Usei a soma.
```

### As 3 diferenças, linha por linha

| | O que a analista pôs | O que a conversa B pode pôr |
|---|---|---|
| O que está no topo | o total, a air fryer e os dois estados abaixo da meta | parecido, se o pedido pediu "os 3 números que mais mudaram" |
| Um número que saiu diferente | a rede cresceu +2,9% sobre julho | quem usou o total digitado (R$ 36.510) chega a +1,9%. **Quem está certo é a soma dos estados.** |
| Uma coisa resolvida de cabeça | a analista viu que o total de julho não fechava, e usou a soma | a conversa B, pelo "na dúvida", **pergunta antes de usar**. No teste de 04/10 (Claude), a conversa A também viu o erro, mas **decidiu sozinha**: usou a soma e pediu só "confirme na sua fonte" |

**O que a conversa A devolveu no teste de 04/10 (Claude.ai, Sonnet 5.5, conversa nova):** uma análise boa, de 740
palavras em 6 seções, com duas tabelas e as hipóteses marcadas, e **nenhuma decisão para o diretor.**
Ela termina em "pontos de atenção" e oferece montar um slide. É isso o raso: boa de ler, longa e
sem servir para decidir. Com outra IA ou outro modelo, ela pode voltar mais rasa, ou usar o total errado sem avisar.

**A armadilha para a IA:** explicar a queda do ventilador ("fim do inverno", "concorrência"). Os
números não dizem por quê. No pedido B, causa que não está nos números vem como hipótese.
