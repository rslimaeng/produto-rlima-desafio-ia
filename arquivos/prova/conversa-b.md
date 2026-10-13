### Você

```
Sou analista comercial e todo mês preparo o relatório de vendas para o diretor comercial. Os números de agosto de 2026 estão abaixo, entre as etiquetas <numeros>. Neste mês, teve a campanha do Dia dos Pais, de 1 a 9 de agosto.

O que eu preciso: um relatório de uma página. No topo, os 3 números que mais mudaram em relação ao mês anterior ou à meta. Depois, o que precisa de decisão do diretor comercial. O resto em poucas linhas no fim.

Restrições: use apenas os números abaixo. Não estime valor que estiver faltando. Não explique causa que não está nos números; se achar uma provável, escreva como hipótese.

Na dúvida: se um número parecer errado, estiver faltando ou aparecer duas vezes, liste o que encontrou e me pergunte antes de usar.

Está pronto quando o diretor comercial consegue decidir o que fazer lendo só esta página, sem abrir a planilha.

<numeros>
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
</numeros>
```

### Claude

Antes de montar a página, achei uma divergência. Como você pediu, ainda não usei o número.

**Rede em julho: o total de R$ 36.510 não bate com as partes**

- Os três estados somam R$ 36.150 (13.900 + 12.950 + 9.300).
- Os quatro produtos também somam R$ 36.150 (14.200 + 9.400 + 7.150 + 5.400).
- A linha “Rede” de julho diz R$ 36.510, uma diferença de R$ 360. Parece dois dígitos trocados, mas isso é só palpite meu.

Em agosto está tudo certo: estados e produtos somam R$ 37.190, igual à linha Rede, e a meta de R$ 37.500 também fecha.

Isso muda só uma coisa: o crescimento da Rede sobre julho. Com R$ 36.510 fica +R$ 680 (+1,9%), e com R$ 36.150 fica +R$ 1.040 (+2,9%). A distância da meta (−R$ 310, −0,8%) e os três números do topo não dependem disso.

Qual valor uso para a Rede em julho: R$ 36.150 (o que estados e produtos somam), R$ 36.510 (como está na linha Rede), ou você confere na planilha original e me diz?

Assim que você responder, monto a página.

### Você

```
Confirmo $36.150, pode seguir.
```

### Claude

Vou montar o relatório de uma página usando R$ 36.150 como total da Rede em julho, e abrir como documento.

### Documento · Relatório de vendas — agosto de 2026

## Os 3 números que mais mudaram

A air fryer cresceu R$ 3.780 e foi o único produto a subir; ventilador e cafeteira juntos perderam R$ 2.480.

| Produto | Julho | Agosto | Variação | Leitura |
|---|---|---|---|---|
| Air fryer | R$ 14.200 | R$ 17.980 | +R$ 3.780 (+26,6%) | Passou de 39,3% para 48,3% das vendas da Rede |
| Ventilador | R$ 5.400 | R$ 3.770 | −R$ 1.630 (−30,2%) | Maior queda percentual; foi de 14,9% para 10,1% das vendas da Rede |
| Cafeteira | R$ 9.400 | R$ 8.550 | −R$ 850 (−9,0%) | Segunda maior queda em reais, depois do ventilador |

Critério: maior variação percentual sobre julho, considerando produtos e estados.

## O que precisa de decisão do diretor comercial

A Rede fechou R$ 310 abaixo da meta (−0,8%); o Ceará, R$ 600 acima da sua, evitou uma distância maior. Há três decisões em aberto.

1. **Ventilador e cafeteira: agir em setembro ou aceitar a queda?** Os três produtos que caíram (ventilador, cafeteira e liquidificador) perderam R$ 2.740, o equivalente a 72% do ganho da air fryer. Excluindo a air fryer, as vendas da Rede caíram 12,5% (R$ 21.950 → R$ 19.210). **Hipótese**, não confirmada pelos números: a campanha do Dia dos Pais (1 a 9/8) concentrou a demanda na air fryer.
2. **Pernambuco e Rio Grande do Norte: qual das duas lacunas atacar primeiro?** Juntas somam R$ 910 contra a meta. PE ficou R$ 520 abaixo (−3,7%), mas subiu 4,1% sobre julho. O RN ficou R$ 390 abaixo (−4,3%) e é o único estado que caiu sobre julho (−R$ 690, −7,4%).
3. **Repetir uma ação nos moldes do Dia dos Pais?** A air fryer subiu 26,6%, mas a Rede cresceu só 2,9% e fechou abaixo da meta. Os números trazem apenas totais mensais: faltam as vendas por dia (1 a 9/8 contra o resto do mês) e o custo da campanha para medir o retorno.

## O resto

- **Rede:** R$ 37.190, +R$ 1.040 (+2,9%) sobre julho (R$ 36.150) e −R$ 310 (−0,8%) sobre a meta de R$ 37.500.
- **Ceará:** R$ 15.100, +8,6% sobre julho e +R$ 600 (+4,1%) sobre a meta; é o único estado acima da meta.
- **Liquidificador:** R$ 6.890, −R$ 260 (−3,6%) sobre julho.
- **Dado ajustado:** julho da Rede = R$ 36.150, soma dos estados e dos produtos; a linha "Rede" da planilha trazia R$ 36.510 (diferença de R$ 360).
- **Sem dados para afirmar:** meta por produto (não dá para dizer se algum cumpriu a meta) e vendas por produto em cada estado (não dá para dizer o que puxou a queda do RN).

### Claude

Estrutura no ar; agora escrevendo os 3 números do topo.
