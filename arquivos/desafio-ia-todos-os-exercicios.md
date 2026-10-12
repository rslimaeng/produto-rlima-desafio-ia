# Desafio Relatório, Planilha e Slides com IA em 7 Dias
Os 25 exercícios, para usar sem internet. Cada um: Traga · Cole · Confira.
Funciona em qualquer IA de chat. Uma conversa nova por exercício, salvo quando o cartão diz o contrário.


---

# Dia 1 · O mesmo pedido, dois jeitos


## Exercício 1 · O teste do raso

`Delegar` · `Trabalho fechado` · ~20 min

**A situação:** você pega um mês que já fechou. Pede o relatório do seu jeito de sempre, depois pelo cartão, e compara os dois com o que você entregou.



### Traga
- **Os números do mês**, colados como texto: a tabela, a planilha copiada ou os totais.
- **Três respostas curtas:**
  - quem lê o relatório;
  - o que essa pessoa faz depois de ler;
  - o que aconteceu de diferente naquele mês.
- **O relatório que você entregou,** aberto ao lado. Ele é o seu gabarito. **Cole na conversa só depois da primeira resposta** (rodada 2, abaixo): se a IA vir o relatório antes, ela copia, e não sobra nada para comparar.

**Já tem um pedido que você usa para esse relatório?** Ele serve no lugar do cartão se tiver os 4 sinais:
- diz **quem lê**;
- diz **o que essa pessoa faz depois de ler**;
- diz **o que não pode** (inventar número, explicar causa que não está no dado);
- diz **quando está pronto**.

Faltou algum? Use o cartão, ou acrescente ao seu a linha que falta.

Tire nome de cliente, de pessoa e valor sensível antes de colar. Trocar por "Cliente A" basta.


### Cole
**Conversa A, nova.** Peça do seu jeito de sempre, como faria numa terça qualquer. Se não tiver um jeito, use:

```
Faz um relatório com estes números.
[cole os números]
```

**Conversa B, outra conversa nova.** Cole o pedido abaixo e troque o que está entre colchetes:

```
Sou [seu cargo] e todo mês preparo o relatório de [assunto] para [quem lê]. Os números de [mês e ano] estão abaixo, entre as etiquetas <numeros>. Neste mês, [o que aconteceu de diferente, em uma linha].

O que eu preciso: um relatório de uma página. No topo, os 3 números que mais mudaram em relação ao mês anterior ou à meta. Depois, o que precisa de decisão de [quem lê]. O resto em poucas linhas no fim.

Restrições: use apenas os números abaixo. Não estime valor que estiver faltando. Não explique causa que não está nos números; se achar uma provável, escreva como hipótese.

Na dúvida: se um número parecer errado, estiver faltando ou aparecer duas vezes, liste o que encontrou e me pergunte antes de usar.

Está pronto quando [quem lê] consegue decidir o que fazer lendo só esta página, sem abrir a planilha.

<numeros>
[cole aqui os números do mês]
</numeros>
```


### Confira
**O que deve voltar:**
- **A conversa A volta boa e longa,** mas resolve sozinha o número que não fecha e não diz o que fazer. É isso o raso: não serve para quem decide.
- A conversa B começa pelo que mudou e pelo que precisa de decisão.
- Em B, nenhuma causa aparece como fato se ela não está nos números.
- Se havia número estranho, B perguntou em vez de usar.

**Agora o gabarito.** Abra o relatório que você entregou e anote 3 diferenças:

| | O que eu pus no relatório | O que a conversa B pôs |
|---|---|---|
| O que está no topo | | |
| Um número que saiu diferente: quem está certo? | | |
| Uma coisa que eu resolvi de cabeça e ela perguntou (ou inventou) | | |

**Se B voltou longa:** `Corte para uma página, e deixe no topo só o que exige decisão de [quem lê].`

**Rodada 2, opcional · o seu relatório como modelo.** Na mesma conversa B, depois de anotar as 3 diferenças:

```
Abaixo está o relatório que eu entreguei com estes mesmos números. Use-o como modelo de formato e de tom, e refaça o seu. Não copie as conclusões: se a sua leitura dos números for diferente da minha, mostre onde.

<meu_relatorio>
[cole o relatório que você entregou]
</meu_relatorio>
```

**O que deve voltar:** o seu formato, com os números conferidos por ela, e os pontos em que a leitura dela difere da sua. É aqui que o resultado costuma melhorar mais.

> **Guarde a conversa A.** Ela é o material do exercício 2.


## Exercício 2 · O defeito diz o que mexer

`Delegar` · ~10 min

**A situação:** a resposta voltou ruim. Em vez de pedir de novo até sair uma que agrade, você descobre o defeito e conserta numa rodada só.



### Traga
- **A resposta da conversa A** do exercício 1, ou qualquer resposta que te decepcionou esta semana.
- **A conversa onde ela está.** O conserto vai na mesma conversa.


### Cole
Leia a resposta e ache o defeito na tabela. Cole **só a frase daquele defeito**, completando os colchetes.

| A resposta veio… | O que faltou no pedido | Cole |
|---|---|---|
| **Servia para qualquer empresa** | a sua situação | `Isto serviria para qualquer empresa. A nossa situação é: [2 ou 3 fatos: números, prazo, o que já foi decidido]. Refaça usando só o que vale para o nosso caso.` |
| **Rasa:** tem o que você pediu, sem profundidade | a tarefa estava larga | `Está raso em [o ponto]. Aprofunde só esse ponto: [o que você quer saber], com um exemplo do nosso caso.` |
| **No tom errado** | quem vai ler | `Quem vai ler é [quem], que espera um texto [direto, formal, sem termo técnico]. Reescreva nesse tom, sem mudar o conteúdo.` |
| **Certa, mas difícil de usar** | o formato | `O conteúdo está certo, o formato não. Refaça em [tabela com as colunas X e Y, ou lista de até 5 itens], com no máximo [tamanho].` |
| **Longa demais** | o que é "pronto" | `[Quem lê] tem 5 minutos. Corte para [uma página ou 10 linhas], deixando no topo só o que exige decisão.` |


### Confira
**O que deve voltar:**
- A mesma resposta, consertada numa rodada.
- O defeito que você apontou sumiu.
- O que já estava certo continua lá.

**Se o defeito não sumiu,** o problema era outro: volte à tabela e escolha a linha seguinte. **Não peça "tenta de novo".** Cada rodada é um novo sorteio de palavras (slide 6): sempre aparece uma que agrada, até quando todas estão erradas.

**Se nenhuma linha resolve,** talvez o problema não seja o pedido:
- a informação não existe escrita em lugar nenhum;
- a IA não teve acesso ao material;
- a decisão é sua.


## Exercício 3 · Delegar ou pensar junto, o mesmo material

`Delegar + Pensar junto` · ~15 min

**A situação:** o relatório está pronto para sair. Na mesma conversa, você faz dois pedidos sobre ele: um que confere pelo seu critério, outro que pergunta o que você não está vendo.



### Traga
- **O relatório da conversa B** do exercício 1, ou um relatório seu que está para sair.
- **Os números** que ele usa.
- **O seu critério, em 2 ou 3 linhas:** o que você confere hoje antes de mandar um relatório. Exemplos:
  - cada número bate com a planilha;
  - toda variação acima de 10% tem explicação;
  - nenhuma pendência fica sem dono.


### Cole
**Uma conversa nova.** Primeiro o material e o critério:

```
Vou te pedir duas coisas sobre o relatório abaixo, uma de cada vez. Ainda não faça nada: só confirme que leu.

O meu critério, que eu uso quando confiro na mão: [o seu critério, em 2 ou 3 linhas].

<relatorio>
[cole o relatório]
</relatorio>

<numeros>
[cole os números]
</numeros>
```

**Pedido 1 · Delegar.** Começa por uma ordem e leva o seu critério:

```
Confira o relatório contra os números, usando o meu critério e nenhum outro.

O que eu preciso: uma tabela com uma linha por item do critério, a situação de cada um e o que ficou pendente separado no fim.

Restrições: não decida nada que eu não tenha deixado decidido. Não preencha buraco por estimativa.

Na dúvida: se um caso não se encaixar no critério, marque para eu conferir em vez de escolher por mim.

Está pronto quando eu sei, item por item, o que pode sair e o que eu preciso olhar.
```

**Pedido 2 · Pensar junto.** Na mesma conversa, termina em pergunta:

```
Agora outra coisa. O meu critério está descrito acima.

O que eu preciso: três coisas que a minha conferência não pegaria neste relatório, e o que eu deveria olhar em cada uma. Não me dê a decisão: me dê o que falta entrar nela.

Restrições: não repita o que o meu critério já confere. Cada ponto vem com o motivo pelo qual ele escapa do meu critério.

Na dúvida: se faltar contexto para avaliar algum ponto, pergunte antes de supor.

Está pronto quando eu tenho 3 perguntas que eu não teria feito sozinho.
```


### Confira
**O que deve voltar:**
- Duas respostas que não se parecem.
- **Pedido 1:** uma tabela, nada decidido por ela e os casos de fora marcados para você. É a resposta que economiza a tarde.
- **Pedido 2:** pontos que o seu critério não cobre, cada um com o motivo, e nenhuma decisão. Mostra o que faltava entrar na decisão.
- **O que o pedido 2 aponta é hipótese:** confira na fonte antes de mudar o relatório.
- **Algo que contraria o que você pensava.** Se tudo concordou, desconfie: a IA tende a concordar com quem pergunta.

**Se o pedido 1 decidiu por você:** `Você decidiu [o quê]. Volte esse item e marque para eu conferir.`

**Se o pedido 2 veio como recomendação:** `Não me dê a decisão. Me dê só o que falta entrar nela, com o motivo de cada ponto.`


---

# Dia 2 · Planilha


## Exercício 4 · Raio-X antes de perguntar

`Delegar` · ~10 min

**A situação:** uma planilha de outra área chegou, e você ainda não sabe o que ela responde.



### Traga
- **A planilha.** Selecione as células, copie e cole como texto. Se a sua IA aceita anexo, anexar também serve.
- **Para que você vai usar,** em uma frase: a pergunta que te trouxe até ela.
- **Conte as linhas você mesmo,** antes de colar. É o gabarito mais barato do dia.

Tire nome de cliente, de pessoa e valor sensível antes de colar.


### Cole
**Conversa nova:**

```
Sou [seu cargo] e recebi esta planilha de [área]. Vou usá-la para [a pergunta que te trouxe até ela]. Ela está abaixo, entre as etiquetas <planilha>.

Antes de qualquer conta, faça um raio-x dela:
1. Quantas linhas e quantas colunas.
2. Para cada coluna: o nome, o tipo (número, data, texto livre ou categoria) e o que você acha que ela quer dizer. Marque como suposição o que não estiver escrito na planilha.
3. Células vazias, valores estranhos (texto onde deveria haver número, o mesmo item escrito de dois jeitos) e linhas que parecem total ou subtotal.
4. Três perguntas que esta planilha responde bem e três que ela não responde, pensando no meu uso. Perguntas que estes dados respondem, não perguntas gerais de negócio.

Restrições: não calcule nada ainda. Não invente coluna que não existe.

Na dúvida: se encontrar um problema que muda as contas, pare aqui e me avise.

Está pronto quando eu sei o que esta planilha consegue me dizer, sem precisar abri-la.

<planilha>
[cole aqui a planilha]
</planilha>
```


### Confira
**O que deve voltar:**
- **O número de linhas bate com a sua contagem.** Se não bateu, ela não leu tudo, e nada do resto vale.
- Cada coluna com o tipo, e com **suposição marcada** onde o nome não diz.
- Os estranhos listados com **onde estão**: a coluna e a linha.
- 3 perguntas que ela responde e 3 que não, **citando as colunas**. E nenhuma conta de resultado: conferir se o total da planilha fecha vale, e costuma achar o erro.

**Se ela já calculou o resultado:** `Você calculou antes do raio-x. Volte: só a estrutura e os problemas, sem nenhum número.`

**Se as perguntas serviam para qualquer planilha:** `Essas perguntas serviriam para qualquer planilha. Refaça só com perguntas que estas colunas respondem, e cite a coluna em cada uma.`

> **Guarde a conversa.** O exercício 5 continua nela.


## Exercício 5 · Arrumar antes de pedir

`Delegar` · ~20 min · **na mesma conversa do exercício 4**

**A situação:** o raio-x mostrou célula mesclada, total no meio da tabela, o mesmo nome escrito de dois jeitos.



### Traga
- **A conversa do exercício 4,** aberta.
- **O que você já sabe:** quais nomes parecidos são a mesma coisa, se souber.


### Cole
**Primeiro, a lista:**

```
Agora, a arrumação. Liste os problemas desta planilha que atrapalham uma conta, nesta ordem: células mescladas, linhas de total ou subtotal no meio dos dados, o mesmo nome escrito de jeitos diferentes, número guardado como texto, datas em formatos diferentes e cabeçalhos que não dizem o que a coluna guarda.

Para cada problema: onde está (coluna e linha), o que ele faria com a conta e o conserto que você propõe. Numere os consertos.

Restrições: não conserte nada ainda. Nomes parecidos, mostre como estão escritos e não junte.

Na dúvida: se não souber se dois nomes são a mesma coisa, pergunte.

Está pronto quando eu consigo dizer "pode" ou "não" para cada conserto, um por um.
```

**Depois, o seu "pode":**

```
Pode aplicar os consertos [números]. O [número] não. Devolva a tabela limpa: uma linha por registro, sem linhas de total, cada dado na sua célula.
```


### Confira
**O que deve voltar:**
- A lista dos problemas, cada um com **onde está**.
- **Nada consertado** antes do seu "pode".
- Nomes parecidos mostrados **como estão**, sem juntar.
- Na tabela limpa, **o número de registros é o mesmo** de antes, menos as linhas de total. Conte.

**Se ela juntou nomes sozinha:** `Você juntou [os nomes] sem me perguntar. Desfaça, liste os nomes exatamente como estão na planilha e me pergunte quais são a mesma coisa.`

**Para a próxima vez:** o conserto definitivo é na sua planilha original, antes de colar. A lista de hoje é o seu checklist.


## Exercício 6 · O número e de onde ele saiu

`Delegar` · ~15 min · **na mesma conversa**

**A situação:** você precisa levar 2 ou 3 números para a reunião, e alguém vai estar com a planilha aberta.



### Traga
- **A tabela limpa** do exercício 5, na mesma conversa.
- **Os 2 ou 3 números** que a reunião vai perguntar.


### Cole
```
Com a tabela limpa, preciso destes números para a reunião: [número 1], [número 2], [número 3].

Antes de calcular, diga qual coluna e qual regra você vai usar em cada um. Se houver mais de um jeito defensável de calcular (somar tudo e dividir, ou tirar a média das médias, por exemplo), mostre os dois e espere eu escolher.

Depois, para cada número, traga:
- o número direto, sem arredondar para ficar bonito;
- a coluna de onde ele saiu;
- quais linhas entraram na conta, e quantas;
- qualquer suposição que você fez.

Restrições: nunca use uma coluna que não existe. Se a pergunta pedir causa ("por que caiu?"), responda como hipótese, não como fato.

Na dúvida: se você não conseguir calcular sobre todas as linhas, diga que estimou.

Está pronto quando eu consigo refazer cada número na planilha, sozinho, em um minuto.
```


### Confira
**O que deve voltar:**
- **O método dito antes do número.** Se havia dois jeitos de calcular, ela mostrou os dois.
- Cada número com **o endereço:** a coluna, as linhas que entraram e quantas.
- Suposição marcada como suposição.
- **Refaça um número na mão,** na planilha. Se bateu, o resto ganha crédito. Se não bateu, pare aqui.

**A IA também prevê número (slide 6): sem fazer a conta, escreve o valor provável. Antes de levar algum à reunião:** `Antes de eu usar esse número: você executou um cálculo sobre todas as linhas, ou estimou olhando uma parte? Diga quantas linhas entraram na conta e quais colunas você usou.`


## Exercício 7 · A planilha que você monta na mão

`Delegar` · `Trabalho fechado` · ~15 min · **conversa nova**

**A situação:** toda semana (ou todo mês) você monta à mão o mesmo controle, com as mesmas colunas e os mesmos filtros.



### Traga
- **As colunas do seu controle** e o que cada uma guarda.
- **Os filtros ou separações** que você faz toda vez.
- **Onde ele vive:** Excel ou Google Planilhas.
- **De 3 a 10 linhas de uma semana já fechada,** e o resultado que você levou naquela semana. É o gabarito.


### Cole
```
Toda semana eu monto à mão um controle de [nome do controle], no [Excel ou Google Planilhas]. Quero montá-lo uma vez, com fórmulas, e depois só colar os dados novos.

As colunas que eu uso, e o que cada uma guarda:
[coluna: o que guarda]
Os filtros ou separações que eu faço toda vez: [por exemplo, só o que venceu na semana, separado por responsável].
O que eu levo no fim: [o total, a lista ou o indicador].

O que eu preciso:
1. A estrutura: as colunas na ordem, quais eu preencho e quais são calculadas.
2. A fórmula de cada coluna calculada, escrita para o [Excel ou Google Planilhas], já com os nomes das minhas colunas.
3. Como fazer o filtro ou o resumo (filtro, tabela dinâmica ou fórmula), passo a passo.
4. O teste: aplique as fórmulas nas linhas abaixo, de uma semana já fechada, e mostre o resultado.

Restrições: use só funções que existem no [Excel ou Google Planilhas]. Não crie coluna que eu não pedi sem dizer para que ela serve.

Na dúvida: se uma regra minha estiver ambígua, pergunte antes de escrever a fórmula.

Está pronto quando o teste com a semana já fechada der o mesmo resultado que eu levei naquela semana: [o resultado que você conhece].

<semana_fechada>
[cole aqui as linhas]
</semana_fechada>
```


### Confira
**O que deve voltar:**
- A estrutura, com **as fórmulas escritas para as suas colunas**.
- **O teste bate com o resultado** que você levou naquela semana.
- Cole uma das fórmulas na sua planilha de verdade. Ela roda sem erro.

**Se o teste não bateu:** `O teste deu [o que deu], e o certo é [o que você levou]. Mostre linha a linha onde a fórmula faz diferente do que eu faço à mão.`

**Se a fórmula deu erro na sua planilha:** `A fórmula da coluna [qual] deu este erro no [Excel ou Google Planilhas]: [cole o erro]. Corrija só ela, sem mudar o resto.`


---

# Dia 3 · Relatório com pesquisa


## Exercício 8 · O que aconteceu × por que aconteceu

`Pensar junto` · ~10 min · **conversa nova**

**A situação:** os números caíram, e todo mundo quer saber por quê.



### Traga
- **Os números de dois períodos,** colados como texto.
- **O que você já sabe** que mudou no período, ou "nada".


### Cole
```
Sou [seu cargo]. Os números abaixo mostram que [o indicador] [caiu ou subiu] em [período], e vão me perguntar por quê. O que eu já sei que mudou no período: [o que você sabe, ou "nada"].

O que eu preciso, em duas partes separadas:
1. O que aconteceu: o fato, com o número e a comparação (de quanto para quanto, e onde a mudança se concentrou). Só o que está nos números.
2. Por que pode ter acontecido: de 3 a 5 causas possíveis, cada uma marcada como [HIPÓTESE]. Para cada uma: o que nos números aponta para ela, o que a derrubaria e onde eu verifico (um dado interno, uma pessoa ou uma fonte de fora).

Restrições: nenhuma causa entra na parte 1. Não escreva "devido a" nem "puxado por" sem a marca [HIPÓTESE]. Se uma causa depende de dado que só a empresa tem, marque [BUSCAR INTERNAMENTE].

Na dúvida: se os números não bastam nem para o fato, diga o que falta.

Está pronto quando eu sei o que aconteceu, e qual hipótese testar primeiro. No fim, me diga qual você testaria primeiro, e por quê.

<numeros>
[cole aqui os números]
</numeros>
```


### Confira
**O que deve voltar:**
- **O fato com o número e a comparação,** e nenhuma causa nessa parte.
- Cada causa marcada como hipótese, **com o que a derrubaria.**
- Onde verificar cada uma: dado interno, pessoa ou fonte de fora.
- **Escolha uma hipótese de fora.** Ela vai para o exercício 9.

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se uma causa entrou como fato:** `Você pôs uma causa na parte do fato: "[o trecho]". Mova para as hipóteses, com a marca, e diga o que a derrubaria.`

**Se as causas serviam para qualquer queda:** `Essas causas serviriam para qualquer queda. Refaça só com hipóteses que estes números sustentam, citando o número que aponta para cada uma.`


## Exercício 9 · Pesquisa com hipótese, em vez de mil abas

`Pensar junto` · ~15 min · **conversa nova**

**A situação:** para explicar o número, você precisa de contexto de fora: o mercado, o setor, uma regra.



### Traga
- **A hipótese de fora** que você escolheu no exercício 8, escrita como afirmação.
- **A decisão** que essa pesquisa vai apoiar.
- **O modo de pesquisa da sua IA,** se ela tiver. O nome muda de uma para outra: pesquisa aprofundada, *deep research*. Se não tiver, a busca comum serve.


### Cole
```
Sou [seu cargo] em [setor]. Esta pesquisa vai apoiar a decisão de [a decisão].

A minha hipótese, como afirmação: [a hipótese].
O que eu quero: [confirmar, derrubar ou mapear]. Se for confirmar, traga também o melhor argumento contra.

Fontes que valem: autor ou instituição identificada, publicadas nos últimos dois anos, sem texto de quem vende a solução. Dado de outro país ou de empresa de outro porte entra marcado.
Ruído a ignorar: opinião sem autor, fórum, material de vendas.

Antes de escrever, liste as incertezas: o que poderia contradizer a hipótese.

Como eu quero receber, em uma página: se a hipótese se sustenta, cai ou fica em aberto; as 3 evidências mais fortes, a favor e contra; o que eu ainda preciso verificar.

Marque cada afirmação com uma etiqueta:
[DE MEMÓRIA] o que você sabe do que leu antes, sem fonte para mostrar agora;
[BUSCADO] o que você encontrou nesta pesquisa, com o link e o trecho que diz isso;
[PRECISA VERIFICAR] número, data, regra ou nome que eu devo conferir antes de usar.
Não dê porcentagem nem valor sem fonte. Se não tiver a fonte, diga onde eu poderia procurar.

Está pronto quando eu sei se a hipótese aguenta, e o que eu confiro antes de levar adiante.
```


### Confira
**O que deve voltar:**
- **Um veredito:** a hipótese se sustenta, cai ou fica em aberto. "Fica em aberto" é um resultado certo.
- **Toda afirmação com etiqueta.** Todo `[BUSCADO]` com o link e o trecho.
- **A evidência contra** apareceu, e não só a que confirma.
- Nenhuma porcentagem sem fonte.

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se a sua IA não busca na internet,** tudo vai sair `[DE MEMÓRIA]`, isto é, previsto do que ela leu, não consultado (slide 6). A etiqueta fez o trabalho dela: avisou.

**Se faltou etiqueta:** `Esta afirmação não tem etiqueta: "[o trecho]". Etiquete todas, e o que não tiver fonte vira [PRECISA VERIFICAR].`

**Se só veio o que confirma:** `Você só trouxe o que confirma a hipótese. Traga a melhor evidência contra ela, com a fonte.`


## Exercício 10 · As fontes passam no teste?

`Pensar junto` · ~20 min

**A situação:** a pesquisa voltou com links. Antes de usar, você abre e lê.



### Traga
- **Os links** que mais sustentam a resposta do exercício 9.
- **15 minutos para abrir cada um.** Fique com **no máximo 3**. Link que não abre, ou que não diz o que a pesquisa disse, sai.


### Cole
**Dois caminhos, à sua escolha:**
- **No NotebookLM** (indicação; ferramenta do Google que responde só com os arquivos que você sobe): crie um caderno, suba as 3 fontes pelo link e cole as perguntas abaixo, uma de cada vez. Ele responde só com o que está nas fontes e mostra o trecho.
- **Na sua IA,** numa conversa nova: cole o texto das 3 fontes entre as etiquetas `<fonte1>`, `<fonte2>` e `<fonte3>`, e depois as perguntas.

**Primeiro:**

```
Vou te fazer três perguntas sobre estas fontes, uma de cada vez. Responda olhando só para elas. Está pronto quando eu souber quanto posso confiar nelas: onde brigam, o que falta e quem não foi ouvido.

1. Mostre onde as fontes discordam entre si: afirmações conflitantes e dados que não batem. Para cada ponto, cite a fonte e o trecho. Se elas forem consistentes, diga isso claramente.
```

**Depois, uma de cada vez:**

```
2. Com base nessas fontes, que pontos importantes sobre [o tema] ficaram de fora ou foram tratados por cima? Não invente detalhes: só descreva o que falta.
```

```
3. Há pontos de vista contrários, ou menos conhecidos, sobre [o tema] que provavelmente não estão nessas fontes? Descreva em linhas gerais e diga que tipo de fonte eu precisaria buscar para encontrá-los.
```


### Confira
**O que deve voltar:**
- **Cada discordância com a fonte e o trecho.** Ou um "são consistentes", dito com todas as letras.
- O que falta, **sem detalhe inventado.**
- Quem não foi ouvido, e onde procurar.
- **Clique numa citação** (ou procure o trecho na fonte). Ele diz o que a resposta afirma? A citação mostra o trecho, mas não confere a conclusão.

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se um trecho citado não está na fonte:** `Não encontrei este trecho na [fonte]: "[o trecho]". Mostre o trecho literal de onde saiu isso. Se não houver, retire a afirmação.`


## Exercício 11 · Uma página para quem tem 5 minutos

`Delegar` · `Trabalho fechado` · ~20 min · **conversa nova**

**A situação:** junte os números do exercício 8 e o que passou no teste do exercício 10.



### Traga
- **Os números** do exercício 8.
- **O que a pesquisa trouxe,** só com as fontes que passaram no exercício 10.
- **Um relatório seu já entregue,** como gabarito de formato e de tamanho.
- **Um design system,** o guia de cores, letras e formatos de uma marca, para o relatório sair em HTML (a página que abre no navegador e vira PDF): o da Jangada Eletro, no material de exemplo, ou o da sua empresa.


### Cole
```
Sou [seu cargo] e preciso levar [o tema] para [quem lê], que tem 5 minutos. Abaixo estão os números e o que a pesquisa trouxe, só com as fontes que eu conferi. Se eu colar um relatório meu já entregue, use como modelo de formato.

O que eu preciso: um relatório de uma página, nesta ordem:
- Título e período.
- Situação: o que aconteceu, em 2 linhas, com o número principal e a comparação.
- Interpretação: por que, com a fonte de cada afirmação. O que ainda é hipótese aparece como hipótese.
- Risco: o que acontece se nada mudar, em no máximo 3 pontos.
- A decisão que eu peço a [quem lê], em uma frase.

Restrições: use só os números e as fontes abaixo. Não invente comparação com períodos que eu não dei. Tom direto, sem rodeio.

Antes de me entregar, faça a conferência e me mostre: de onde saiu cada número; qual fonte sustenta cada afirmação de fora; e o que você procurou e não encontrou, marcado [buscar internamente] ou [verificar antes da reunião].

Está pronto quando [quem lê] consegue decidir lendo só esta página.

<numeros>
[cole os números]
</numeros>
<pesquisa>
[cole o que passou no teste das fontes]
</pesquisa>
<meu_relatorio>
[opcional: um relatório seu já entregue]
</meu_relatorio>
```

**Depois, na mesma conversa · o relatório em HTML.** Com o texto aprovado, cole:

```
Agora transforme este relatório num arquivo HTML de uma página, pronto para imprimir em A4 retrato. Use o design system abaixo: as cores, as letras e as peças dele, sem inventar outras. Não mude nenhum texto nem número do relatório. Deixe a conferência de fora: ela é para mim, não para [quem lê].

Está pronto quando eu imprimo em PDF e sai uma página, com a decisão em destaque.

<design_system>
[cole o design system]
</design_system>
```

**Para virar PDF:** abra o HTML no navegador e use Ctrl+P (no Mac, Cmd+P) → Salvar como PDF.


### Confira
**O que deve voltar:**
- **Uma página,** com a decisão pedida em uma frase.
- Cada número com a origem, e cada afirmação de fora com a fonte.
- **O que era hipótese continua hipótese.** Entre uma etapa e outra, o aviso costuma sumir e a hipótese vira fato.
- **Ponha ao lado do relatório que você entregou:** o tamanho é parecido? A decisão está tão clara quanto?
- **No HTML, o texto e os números são os mesmos da versão em texto,** e o PDF sai em uma página.

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se a hipótese virou fato:** `A hipótese "[qual]" virou fato no relatório. Volte a marca de hipótese, como estava na pesquisa.`

**Se passou de uma página:** `[Quem lê] tem 5 minutos. Corte para uma página e ponha a decisão pedida no topo.`

**Se o HTML mudou o texto:** `Você mudou o texto ao montar o HTML: "[o trecho]". Volte ao texto do relatório, palavra por palavra, e mude só a aparência.`


---

# Dia 4 · Apresentação e documento


## Exercício 12 · Títulos que já dizem a conclusão

`Delegar` · `Trabalho fechado` · ~10 min · **conversa nova**

**A situação:** uma apresentação que você já fez, com títulos de assunto: "Resultados", "Vendas por estado", "Próximos passos".



### Traga
- **Os títulos, na ordem,** e **2 ou 3 linhas do conteúdo de cada slide.** É de onde vão sair os números do título.
- **O que a plateia decidiu** depois da apresentação. É o gabarito.


### Cole
```
Abaixo estão os títulos e o conteúdo dos slides de uma apresentação que eu fiz para [quem assistiu].

Leia só os títulos, em sequência, sem o conteúdo de nenhum slide.
1. Escreva em três linhas o que alguém entenderia só por eles: qual é o problema, qual é a causa e o que vai ser feito.
2. Aponte todo título que diz só o assunto (como "Análise de X", "Resultados" ou "Próximos passos").
3. Reescreva esses títulos para que digam a conclusão do slide, com um número, uma comparação ou uma consequência que já esteja no conteúdo dele.

Restrições: não invente número para caber no título. Se o conteúdo do slide não tem nenhuma conclusão, diga isso em vez de criar uma.

Está pronto quando, lendo só os títulos novos, alguém que não estava na sala entende o problema, a causa e o que fazer.

<slides>
[cole os títulos e o conteúdo de cada slide]
</slides>
```


### Confira
**O que deve voltar:**
- As 3 linhas do que se entende hoje pelos títulos. Costuma ser quase nada.
- Os títulos de assunto apontados, um por um.
- Cada título novo com **número, comparação ou consequência que está no conteúdo do slide.**
- **O gabarito:** lendo os títulos novos, alguém chegaria à decisão que a plateia tomou?

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se apareceu número que não está no slide:** `O título do slide [N] traz um número que não está no conteúdo dele: [o número]. Use só número que está no slide, ou mostre a conta que fez.`

**Se o título continua de assunto:** `O título do slide [N] ainda diz só o assunto. Reescreva com um número, uma comparação ou uma consequência do conteúdo.`


## Exercício 13 · Do relatório ao roteiro, com os dados da pesquisa

`Delegar` · ~20 min · **conversa nova**

**A situação:** o relatório do dia 3 vira 5 minutos de apresentação. Primeiro o argumento, em texto; depois a aparência.



### Traga
- **O relatório de uma página** do exercício 11, com o dado de fora e a fonte.
- **Quem vai assistir,** e quanto tempo você tem.
- **Informar ou pedir aprovação?** Se o próximo passo depende de alguém aprovar, é pedir aprovação.
- **O design system** do exercício 11: o da Jangada Eletro ou o da sua empresa.


### Cole
```
Abaixo está um relatório que eu vou apresentar para [quem assiste] em [tempo]. O objetivo é [informar o resultado / pedir a aprovação de: o quê].

O que eu preciso: o roteiro da apresentação, em texto, com no máximo 7 slides. Para cada slide:
- um título que já diz a conclusão, com um número, uma comparação ou uma consequência;
- até 3 linhas de conteúdo;
- o tipo de gráfico ou visual sugerido.

Um dos slides traz o dado de fora que a pesquisa trouxe, com a fonte no próprio slide.
Se o objetivo é pedir aprovação, o primeiro slide é a resposta: o que eu peço e por quê. Os seguintes constroem o argumento.
No fim, a fala do primeiro minuto da apresentação, do jeito que eu falaria.

Restrições: use só os números do relatório. Se faltar um, escreva [FALTA: o quê] no lugar. Nada de "Introdução", "Agenda" ou "Obrigado" como slide.

Está pronto quando, lendo só os títulos em sequência, [quem assiste] entende o problema, a causa e o que eu proponho.

<relatorio>
[cole o relatório do exercício 11]
</relatorio>
```

**Depois, na mesma conversa · os slides em HTML.** Com o roteiro aprovado, cole:

```
Agora transforme o roteiro aprovado em slides, num arquivo HTML: uma capa e um slide por item do roteiro, no formato 16:9 (338,667 × 190,5 mm, o tamanho do slide do PowerPoint), com um slide por página quando eu imprimir em PDF. Use o design system abaixo, sem inventar cor nem letra. Mantenha os títulos e os números do roteiro exatamente como estão. A fala do primeiro minuto não entra nos slides.

Está pronto quando eu imprimo em PDF e sai um slide por página, com os títulos do roteiro.

<design_system>
[cole o design system]
</design_system>
```

**Para virar PDF:** abra o HTML no navegador e use Ctrl+P (no Mac, Cmd+P) → Salvar como PDF. **Para virar PPT:** se a sua IA gera arquivo, peça "agora gere um .pptx com estes slides, com o mesmo texto"; se não gera, converta o PDF. **Prefere Canva, Gamma ou PowerPoint?** Cole o roteiro lá e peça para **manter o texto como está.** O trabalho dessa etapa é a forma, não o conteúdo.


### Confira
**O que deve voltar:**
- **No máximo 7 slides,** e os títulos passam no teste do exercício 12.
- **O dado de fora aparece com a fonte** no slide.
- Se é pedido de aprovação, **a resposta abre** a apresentação.
- A fala do primeiro minuto **cabe em um minuto, lida em voz alta.** Cronometre.
- **No PDF, um slide por página,** com os títulos do roteiro sem palavra trocada.

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se a ferramenta de slides mexeu no texto** (ela costuma reescrever título e cortar número): `Compare o texto destes slides com o roteiro que eu aprovei, abaixo. Liste todo título que mudou e todo número que sumiu ou mudou de valor. Depois devolva o texto dos slides com os títulos e os números do roteiro restaurados.`

**Se apareceu número que não estava no relatório:** `Releia o roteiro frase por frase e compare com o relatório. Para cada frase com número, diga se ele está no relatório com o mesmo valor, se mudou ou se não está.`


## Exercício 14 · O documento longo em uma página

`Delegar` · ~10 min · **conversa nova**

**A situação:** chegou um documento longo, e a reunião é daqui a uma hora.



### Traga
- **O documento.** Anexar o PDF é melhor, porque a página fica. Se colar o texto, a referência vira a seção.
- **O seu papel na reunião:** você decide, opina ou executa?
- **Do que trata a reunião,** em uma frase.


### Cole
```
Tenho uma reunião sobre [o assunto] daqui a uma hora, e o meu papel nela é [decidir / opinar / executar]. O documento está [anexado / abaixo].

O que eu preciso, em uma página (no máximo 400 palavras):
1. Do que o documento trata, em 3 linhas.
2. O que importa para quem [decide / opina / executa], e não o resumo do documento inteiro.
3. O que eu preciso fazer esta semana, com o prazo que o documento dá.
4. O que o documento não diz e eu deveria perguntar na reunião.

Restrições: cada ponto vem com a página (ou a seção) de onde saiu. Se o documento não diz algo, escreva "não informado"; não complete. Se duas partes do documento se contradizem ou não se encaixam, aponte.

Está pronto quando eu entro na reunião sabendo o que importa para mim e o que fazer esta semana, sem ter lido o documento inteiro.
```


### Confira
**O que deve voltar:**
- **Uma página, do ponto de vista do seu papel.**
- **Cada ponto com a página** de onde saiu. **Abra duas das páginas citadas** e confira.
- Os prazos desta semana, com a data do documento.
- O que o documento não diz, como pergunta. Melhor ainda se ela cruzou duas partes que não se encaixam.

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se a página citada não diz aquilo:** `Na página [N] não encontrei: "[o trecho]". Mostre o trecho literal de onde saiu. Se não houver, retire o ponto.`

**Se veio o resumo do documento inteiro:** `Isso é o resumo do documento inteiro. Refaça só com o que importa para quem [o seu papel], e com o que eu faço esta semana.`


## Exercício 15 · O que esta proposta assume?

`Pensar junto` · ~10 min · **conversa nova**

**A situação:** uma proposta de fornecedor ou de outra área espera o seu ok.



### Traga
- **A proposta,** colada ou anexada.
- **O que você já confere** numa proposta dessas: o seu critério de sempre.
- **O que está em jogo:** o valor, o prazo e o problema que essa compra deveria resolver.


### Cole
```
Recebi a proposta abaixo para [finalidade]. Ela deveria resolver [o problema], e o valor em jogo é [valor]. Quando eu leio uma proposta dessas, eu confiro [o seu critério de sempre].

Não me dê a decisão. O que eu preciso:
1. O que está claro e o que está vago.
2. O que ela dá como certo sem provar: números sem fonte, promessas sem condição, premissas que ela não escreve. Cite o trecho.
3. O que não está na proposta e deveria estar. O que faltar, marque "não informado".
4. Três perguntas para fazer antes de aprovar, que a minha conferência de sempre não faria.

Restrições: não repita o que o meu critério já confere. Não recomende aprovar nem recusar.

Na dúvida: se faltar contexto para avaliar um ponto, pergunte antes de supor.

Está pronto quando eu tenho as perguntas que não teria feito sozinho. Que pergunta eu ainda não fiz?
```


### Confira
**O que deve voltar:**
- O claro e o vago, separados.
- **O que a proposta assume sem provar, com o trecho.** O mais valioso costuma ser a premissa que nem está escrita.
- O que falta, como "não informado": custo total, multa, prazo.
- **3 perguntas que o seu critério não faria,** e nenhuma recomendação.
- **Algo que contraria o que você pensava.** Se tudo concordou, desconfie: a IA tende a concordar com quem pergunta.

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se veio uma recomendação:** `Não me dê a decisão. Me dê só o que falta entrar nela, com o trecho da proposta em cada ponto.`

**Se uma premissa não está na proposta:** `Onde a proposta diz "[o trecho]"? Cite o trecho. Se ela não diz, separe: o que é da proposta e o que é leitura sua.`


---

# Dia 5 · Reunião e ata


## Exercício 16 · Da anotação bagunçada à ata

`Delegar` · `Trabalho fechado` · ~15 min · **conversa nova**

**A situação:** as anotações de uma reunião que já tem ata. A ata real fica fora da conversa: é o gabarito.



### Traga
- **As anotações,** do jeito que estão, com abreviação e tudo.
- **Quem estava,** com o papel de cada um, e **a data.**
- **A ata real,** aberta ao lado. **Não cole na conversa.**

**Se a anotação é uma transcrição longa** (reunião gravada), use uma conversa só para ela. Conversa longa piora a resposta sem avisar.


### Cole
```
Abaixo estão as minhas anotações de uma reunião sobre [o assunto], em [data], com [participantes e o papel de cada um]. Estão do jeito que eu anotei.

O que eu preciso: a ata, com
- cabeçalho: data, assunto e participantes;
- as decisões tomadas, separadas do que só foi discutido;
- uma tabela de pendências: o que fazer | quem | até quando;
- a próxima reunião, se foi marcada.

Restrições: use só o que está nas anotações. Não crie pendência nem decisão que não está lá. Se uma pendência não tem dono ou prazo nas anotações, deixe a célula vazia e marque [sem dono] ou [sem prazo]. Se deduzir uma data (por exemplo, "sexta"), diga que deduziu. Abreviação que você não entendeu, mostre como está e pergunte.

Na dúvida: se não der para saber se algo foi decidido ou só sugerido, ponha em "discutido" e marque [confirmar].

Está pronto quando quem não estava na reunião sabe o que foi decidido, o que cada um faz e até quando.

<anotacoes>
[cole aqui as anotações]
</anotacoes>
```

**Antes de abrir o Confira:** escreva 2 sinais que a resposta precisa ter para servir. Depois compare com os de baixo.


### Confira
**O que deve voltar:**
- **Decisões separadas do que só foi discutido.**
- Cada pendência com dono e prazo, **ou marcada [sem dono] e [sem prazo].**
- Data deduzida, dita como deduzida. Abreviação estranha, perguntada.
- **Agora o gabarito:** ponha a ata da IA ao lado da real. Tem pendência numa que não está na outra? **Nenhuma pendência inventada.**

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se apareceu pendência que não está nas anotações:** `A pendência "[qual]" não está nas minhas anotações. De onde ela saiu? Se não saiu de lá, retire.`

**Se a IA preencheu um dono ou prazo que não estava lá (é o padrão do slide 6: o nome mais provável):** `Você pôs "[o que pôs]" em "[a pendência]", mas as anotações não dizem isso. Deixe vazio e marque [sem dono] ou [sem prazo].`


## Exercício 17 · A pauta que cabe no tempo

`Delegar` · ~10 min · **conversa nova**

**A situação:** uma reunião de 30 a 60 minutos, com 2 ou 3 objetivos, que você vai conduzir.



### Traga
- **Os objetivos,** 2 ou 3, e **o tempo** da reunião.
- **Quem vai,** e o que cada pessoa sabe.
- **O que precisa sair decidido,** e quem decide.


### Cole
```
Vou conduzir uma reunião de [tempo] com [quem vai, com o papel de cada um e o que cada um sabe].

Os objetivos:
1. [objetivo]
2. [objetivo]
3. [objetivo, se houver]
O que precisa sair decidido: [a decisão]. Quem decide: [quem].

O que eu preciso: a pauta em tabela (horário | item | quem conduz | a pergunta que abre o assunto | tempo). No fim, "o que cada pessoa traz": o que cada participante precisa ler ou levar.

Restrições: a soma dos tempos cabe em [tempo], com 5 a 10 minutos no fim para repassar decisões, donos e prazos. O item que exige decisão não fica por último. A abertura de cada item é uma pergunta, não um assunto.

Na dúvida: se os objetivos não cabem no tempo, diga qual tirar, em vez de apertar todos.

Está pronto quando eu posso mandar a pauta hoje e cada pessoa sabe o que trazer.
```

**Antes de abrir o Confira:** escreva 2 sinais que a resposta precisa ter para servir. Depois compare com os de baixo.


### Confira
**O que deve voltar:**
- **A soma dos tempos cabe,** com o encerramento.
- **O item da decisão não está por último.**
- Cada item abre com **uma pergunta que pede resposta,** e não "Discussão sobre X".
- O que cada pessoa traz, por papel. Se não cabia tudo, **a IA disse o que tirar.**

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se a soma não cabe:** `A soma dá [x] minutos, e a reunião tem [y]. Corte, e me diga o que saiu e por quê.`

**Se a abertura é um assunto:** `A abertura do item [N] é um assunto, não uma pergunta. Reescreva como uma pergunta que pede resposta na reunião.`


## Exercício 18 · As perguntas difíceis

`Pensar junto` · ~10 min · **conversa nova**

**A situação:** você apresenta o relatório do dia 3 amanhã.



### Traga
- **O relatório** do exercício 11, ou o roteiro do exercício 13.
- **Quem vai estar na sala,** e o que cada um costuma cobrar.


### Cole
```
Amanhã eu apresento o relatório abaixo para [quem vai estar na sala]. [Papel] costuma cobrar [o quê]; [papel] costuma cobrar [o quê].

Pense como quem vai estar na sala. Quais as 3 perguntas mais incômodas que eles fariam depois da apresentação? As que eu menos gostaria de ouvir, não as óbvias.

Para cada pergunta:
- quem faria, e por quê;
- uma linha de resposta, só com o que está no relatório;
- se o relatório não responde, o que eu precisaria levar.

Restrições: não invente número para responder. Não suavize a pergunta.

Está pronto quando eu tenho as perguntas que não tinha previsto, e sei o que falta levar. No fim, me diga: qual delas eu deveria responder logo na abertura, antes que perguntem?

<relatorio>
[cole o relatório]
</relatorio>
```

**Antes de abrir o Confira:** escreva 2 sinais que a resposta precisa ter para servir. Depois compare com os de baixo.


### Confira
**O que deve voltar:**
- **Pelo menos uma pergunta que você não tinha previsto.**
- Cada uma com quem faria e uma linha de resposta **tirada do relatório.**
- Onde o relatório não responde, **o que levar,** sem número inventado.
- Uma pergunta para responder na abertura.
- **Algo que contraria o que você pensava.** Se tudo concordou, desconfie: a IA tende a concordar com quem pergunta.

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se as perguntas eram as óbvias:** `Essas eu já tinha previsto. Me dê 3 que um [papel] cético faria e que não estão aí.`

**Se a resposta trouxe número novo:** `A resposta da pergunta [N] usa um número que não está no relatório. Diga o que eu precisaria levar, sem estimar.`


---

# Dia 6 · E-mail e mensagem


## Exercício 19 · O e-mail do dia seguinte

`Delegar` · ~10 min · **conversa nova**

**A situação:** a ata do dia 5 existe, e ninguém mandou os combinados.



### Traga
- **A ata** do exercício 16.
- **Para quem vai:** só quem estava, ou também quem não foi.


### Cole
```
Abaixo está a ata de uma reunião de ontem. Ninguém mandou os combinados ainda. Escreva o e-mail para [quem vai receber], que vai sair no meu nome.

O que eu preciso:
- Assunto: o tema da reunião e a palavra "combinados".
- Primeira linha: para que serve o e-mail, em uma frase.
- As decisões, em lista.
- Quem faz o quê e até quando, em lista, pelo papel de cada um.
- Uma linha pedindo que avisem até [quando] se algo estiver errado.

Restrições: no máximo 10 linhas no corpo. Sem "Venho por meio deste", "Conforme alinhado" nem "Espero que estejam bem". Só o que está na ata: pendência sem prazo na ata continua sem prazo no e-mail, com um pedido para o dono informar.

Está pronto quando cada pessoa sabe, lendo só o e-mail, o que ela faz e até quando.

<ata>
[cole aqui a ata]
</ata>
```

**Antes de abrir o Confira:** escreva 2 sinais que a resposta precisa ter para servir. Depois compare com os de baixo.


### Confira
**O que deve voltar:**
- **No máximo 10 linhas,** começando pelo que importa.
- As decisões, e quem faz o quê até quando.
- **Sem abertura formal,** como "Venho por meio deste".
- **Pendência sem prazo continua sem prazo,** com o pedido para o dono informar.

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se veio cerimônia:** `Tire a abertura e o fechamento de cortesia. Comece pela primeira decisão.`

**Se uma pendência ganhou prazo:** `A pendência "[qual]" estava sem prazo na ata e ganhou prazo no e-mail. Volte para sem prazo e peça ao dono que informe.`


## Exercício 20 · Revisar antes de enviar

`Delegar` · ~10 min · **conversa nova**

**A situação:** um e-mail escrito, com o tom inseguro, que você ainda não mandou.



### Traga
- **O e-mail,** do jeito que está.
- **Para quem vai,** e **o que você quer que a pessoa faça** depois de ler.


### Cole
```
Vou mandar o e-mail abaixo para [quem]. O que eu quero que a pessoa faça depois de ler: [a ação]. Eu sinto o texto inseguro.

O que eu preciso:
1. A versão revisada: mais [direta / firme / gentil], no meu jeito de escrever. Corrija o português e melhore a clareza, sem mudar o que eu estou dizendo.
2. A lista do que você mudou, e por quê, em uma linha cada.
3. O que deveria estar no e-mail e não está, para a pessoa conseguir [a ação] sem precisar me perguntar nada.

Restrições: não mude o sentido. Não acrescente informação que eu não dei: o que faltar, marque [FALTA: o quê] em vez de completar. Se não entender a intenção de um trecho, pergunte.

Está pronto quando a pessoa consegue [a ação] lendo só o e-mail, sem me responder com uma pergunta.

<email>
[cole aqui o e-mail]
</email>
```

**Antes de abrir o Confira:** escreva 2 sinais que a resposta precisa ter para servir. Depois compare com os de baixo.


### Confira
**O que deve voltar:**
- **O pedido logo no começo.** Sumiram o "desculpa incomodar" e o "acho que talvez".
- A lista do que mudou, com o porquê.
- **O que falta, apontado como `[FALTA: …]`,** e não completado por ela: quantidade, prazo, número.
- O sentido é o seu, e o jeito também.

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se apareceu informação que você não deu:** `Você pôs "[o que pôs]", que eu não dei. Volte para [FALTA: o quê] e me deixe completar.`

**Se ficou mais duro do que você fala:** `Ficou mais duro do que eu falo. Mantenha a firmeza, mas no meu jeito. Uma frase minha, para referência: "[cole uma frase sua]".`


## Exercício 21 · Cobrar sem queimar a relação

`Delegar` · ~10 min · **conversa nova**

**A situação:** uma pendência já cobrada duas vezes, com alguém com quem a relação importa.



### Traga
- **A pendência,** a data original e **as duas cobranças:** quando e por onde.
- **O prazo que importa agora,** e por quê.
- **O que acontece se não vier.** Um fato, não uma ameaça.


### Cole
```
Preciso cobrar [quem] pela terceira vez sobre [a pendência]. A relação importa: [por quê].
- O que está pendente: [descreva]
- O prazo original: [data]
- As cobranças anteriores: [datas e por onde]
- O prazo que importa agora, e por quê: [data e motivo]
- O que acontece se não vier até lá: [a consequência real]

O que eu preciso: o e-mail, com
- assunto que diga a pendência e o prazo;
- uma frase de abertura, sem rodeio;
- o que está pendente e desde quando;
- o novo prazo, com o motivo;
- o que acontece se não vier, dito como fato, não como ameaça;
- um fechamento cordial.

Restrições: no máximo 10 linhas. Sem pedir desculpa por cobrar ("desculpe incomodar", "perdão pela insistência"). Sem ameaça. Não ofereça flexibilidade que eu não autorizei.

Está pronto quando [quem] sabe o que mandar, até quando e o que acontece se não mandar, e a relação continua de pé.
```

**Antes de abrir o Confira:** escreva 2 sinais que a resposta precisa ter para servir. Depois compare com os de baixo.


### Confira
**O que deve voltar:**
- **O prazo no assunto e no corpo.**
- **Sem pedido de desculpa por cobrar.**
- A consequência dita **como fato:** o que acontece, e não o que você vai fazer.
- Cordial no fechamento. E nenhum prazo extra que você não deu.

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se veio pedindo desculpa:** `Tire o pedido de desculpa por cobrar. Cobrar o combinado não é incômodo.`

**Se soou como ameaça:** `A frase "[o trecho]" soa como ameaça. Diga a mesma consequência como fato: o que acontece com o calendário, e não o que eu vou fazer.`


## Exercício 22 · Responder quem chegou irritado

`Delegar` · ~10 min · **conversa nova**

**A situação:** uma reclamação de cliente, por escrito, para hoje.



### Traga
- **A reclamação,** sem o nome do cliente. Iniciais bastam.
- **Por onde ela chegou:** e-mail, avaliação pública ou WhatsApp.
- **O que você pode oferecer, e o que não pode prometer.** É a linha mais importante do cartão.


### Cole
```
Recebi a reclamação abaixo por [canal]. Preciso responder hoje.

O que eu posso oferecer: [o que está ao seu alcance, com prazo].
O que eu não posso prometer: [o que não depende de você, ou não está autorizado].

O que eu preciso: a resposta, que
- reconhece o incômodo da pessoa com o fato concreto que ela contou;
- não admite culpa, nem entra em quem errou;
- diz o próximo passo concreto, com prazo;
- leva a conversa para o privado: [telefone, e-mail ou WhatsApp].

Restrições: no máximo 120 palavras. Sem frases prontas como "sua opinião é muito importante para nós". Sem ser defensivo. Não prometa nada fora do que eu disse que posso oferecer. Sem nome de funcionário.

Está pronto quando a pessoa lê, sente que foi ouvida e sabe o próximo passo, e a resposta não promete o que eu não posso cumprir.

<reclamacao>
[cole aqui a reclamação]
</reclamacao>
```

**Antes de abrir o Confira:** escreva 2 sinais que a resposta precisa ter para servir. Depois compare com os de baixo.


### Confira
**O que deve voltar:**
- **Reconhece com o fato que o cliente contou,** e não com uma frase que serviria para qualquer cliente.
- Sem admitir culpa, sem acusar ninguém.
- **O próximo passo com data,** e o caminho para o privado.
- **Nada prometido além do que você pode.** Até 120 palavras.

**Antes das frases prontas:** sinal falhou? Escreva você a frase de conserto. Depois compare com as de baixo.

**Se prometeu o que você não pode:** `A resposta promete "[o quê]", e isso eu não posso cumprir. Tire, e ofereça só [o que pode].`

**Se ficou fria e formal:** `Ficou formal demais. Comece pelo que aconteceu com ela, em uma frase, antes de qualquer outra coisa.`


---

# Dia 7 · O seu pedido


## Exercício 23 · A IA te entrevista primeiro

`Pensar junto` · ~15 min · **conversa nova**

**A situação:** a tarefa que mais consome a sua semana ainda não tem cartão. É o melhor lugar para começar: ela se repete toda semana, e você sabe quanto tempo custa.



### Traga
- **A tarefa,** em uma frase.
- **Quantas vezes por semana** ela chega, e **quanto tempo** leva.
- **Paciência para responder** uma rodada de perguntas por vez.


### Cole
```
Quero montar um cartão para a tarefa que mais consome a minha semana: [a tarefa, em uma frase]. Ela chega [quantas vezes] por semana e leva [quanto tempo].

Antes de escrever qualquer coisa, me entreviste. Faça no máximo 4 perguntas por rodada, de preferência com opções para eu escolher, e sempre com uma opção "outro". Pergunte até entender: o que eu recebo para fazer a tarefa; para quem é o resultado e o que essa pessoa faz com ele; o que não pode sair errado; e como eu sei que ficou pronto. Pergunte também se eu já sei como a resposta certa deveria sair (aí o pedido delega) ou se ainda preciso enxergar alguma coisa (aí o pedido pensa junto).

No fim, me devolva o cartão em três partes:
TRAGA: o que eu separo antes, e as respostas curtas que o pedido precisa.
COLE: o pedido pronto, com [colchetes] onde entra o que muda a cada vez, terminando em "Está pronto quando…".
CONFIRA: de 2 a 4 sinais do que deve voltar, e uma frase de conserto para o erro mais provável.

Restrições: não escreva o cartão antes de terminar a entrevista. Só entra no pedido a linha que muda a resposta. Não invente etapa da minha tarefa que eu não contei.

Está pronto quando eu consigo usar o cartão na próxima vez que a tarefa chegar, sem reescrever nada.
```


### Confira
**O que deve voltar:**
- **Perguntas antes do cartão,** em rodadas curtas, com opção "outro".
- Uma pergunta sobre **delegar ou pensar junto.**
- **O cartão nas três partes:** Traga · Cole · Confira.
- O Cole termina em **"Está pronto quando…"**, e nada nele é etapa que você não contou.

**Se ela escreveu o cartão cedo demais:** `Você escreveu o cartão antes de terminar a entrevista. Volte às perguntas: ainda falta entender [o quê].`

**Se apareceu etapa que você não contou:** `O cartão tem uma etapa que eu não contei: "[o trecho]". Tire, ou me pergunte se ela existe.`


## Exercício 24 · O cartão passa no teste?

`Delegar` · `Trabalho fechado` · ~20 min · **conversa nova, mais de uma vez**

**A situação:** você roda o cartão do exercício 23 num trabalho dessa tarefa que já entregou. Ele é o gabarito.



### Traga
- **O cartão** do exercício 23.
- **O material de um trabalho já entregue:** o que você tinha na mão antes de fazer.
- **O trabalho que você entregou,** aberto ao lado. **Não cole na conversa.**


### Cole
**1. Numa conversa nova,** cole o Cole do seu cartão, preenchido com o material do trabalho já entregue.

**2. Compare** o que voltou com o que você entregou, e anote de 1 a 3 diferenças.

**3. Numa outra conversa nova,** transforme as diferenças em linhas do pedido:

```
Rodei o pedido abaixo num trabalho que eu já tinha entregue e comparei o resultado com o que eu entreguei. As diferenças estão listadas.

O que eu preciso: para cada diferença, a linha que eu acrescento ou mudo no pedido para ela não acontecer de novo, e em que parte do pedido ela entra (o que eu preciso, restrições, na dúvida ou "está pronto quando").

Restrições: uma linha por diferença. Não reescreva o pedido inteiro. Não acrescente linha que não venha de uma das diferenças.

Está pronto quando eu tenho o pedido novo, com as linhas novas marcadas, para rodar de novo no mesmo trabalho.

<pedido>
[cole o Cole do seu cartão]
</pedido>

<diferencas>
1. [o que veio diferente do que eu entreguei]
2. [outra diferença, se houver]
</diferencas>
```

**4. Rode o pedido novo,** de novo numa conversa nova, no mesmo trabalho.


### Confira
**O que deve voltar:**
- **Uma linha por diferença,** e o resto do pedido como estava.
- **Na segunda rodada, a diferença sumiu.** Se não sumiu, ajuste a linha e rode de novo.
- **A régua de cada linha:** se eu apagar esta linha, a resposta muda? Se não muda, a linha sai.
- **Se depois de 2 ou 3 ajustes a diferença não some,** o teste respondeu outra pergunta: essa tarefa não é para delegar, pelo menos não desse jeito. É um resultado tão útil quanto o outro, e saiu barato.

**Se ela reescreveu o pedido inteiro:** `Você reescreveu o pedido inteiro. Volte ao meu pedido e mude só as linhas que vêm das diferenças.`


## Exercício 25 · O antes × depois do fim

`Delegar` · ~10 min · **conversa nova**

**A situação:** você refaz o pedido do exercício 1, sem olhar o cartão. É a sua prova, do mesmo jeito que o PDF começou com a minha.



### Traga
- **Os números** do exercício 1.
- **A conversa A** do exercício 1: o seu pedido de 7 dias atrás e o que ele trouxe.


### Cole
**1. Numa conversa nova, sem olhar nenhum cartão,** escreva do seu jeito o pedido do relatório do exercício 1, com os mesmos números. Rode. Se ela perguntar algo antes de montar, responda na mesma conversa até a página sair: só depois compare.

**2. Numa outra conversa nova,** compare os dois:

```
Abaixo estão dois pedidos meus para a mesma tarefa, feitos com 7 dias de diferença, e a resposta que cada um trouxe.

O que eu preciso: uma tabela com o que o pedido B diz que o pedido A não dizia, e o efeito de cada diferença na resposta. No fim, uma linha: o que ainda falta no pedido B.

Restrições: compare só o que está escrito. Não reescreva os pedidos.

Está pronto quando eu vejo, linha por linha, o que eu aprendi a escrever.

<pedido_A>
[o seu pedido do exercício 1, conversa A, e a resposta]
</pedido_A>

<pedido_B>
[o seu pedido de hoje, e a resposta]
</pedido_B>
```


### Confira
**O que deve voltar:**
- **O seu pedido de hoje tem os 4 sinais do exercício 1:** diz quem lê, o que essa pessoa faz depois, o que não pode e quando está pronto.
- A resposta de hoje começa pelo que exige decisão.
- A tabela mostra, linha por linha, **o que você escreve hoje e não escrevia.**
- **O que ainda falta** vira a próxima linha do seu cartão.

**Se ela reescreveu os pedidos:** `Você reescreveu os pedidos. Compare só o que está escrito em cada um, do jeito que está.`


---

# Materiais de exemplo (dados fictícios)



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



# Design system de exemplo · exercícios 11 e 13

**Dados fictícios.** A rede de eletroportáteis que atravessa o desafio ganha nome e cara: a
**Jangada Eletro**, uma marca inventada.

**O que é um design system:** o jeito de a empresa aparecer no papel, escrito de um modo que a IA
consegue seguir. Cores, letras, o tamanho da página e as peças que se repetem (o número grande, a
caixa da decisão, o selo de hipótese). Com ele colado no pedido, o relatório e os slides saem com
a mesma cara toda vez. Sem ele, cada conversa inventa uma.

**Como usar:**
1. Faça primeiro o conteúdo em texto (o relatório do exercício 11, o roteiro do exercício 13).
   **O conteúdo vem antes da aparência.**
2. Na mesma conversa, peça o arquivo HTML e cole o design system abaixo (o pedido está no cartão).
3. Veja o resultado: no Claude ele aparece ao lado da conversa; no ChatGPT e no Gemini, abra no
   Canvas. Se a sua IA só mostrar o código, copie, salve como `relatorio.html` e abra no navegador.
4. **Para virar PDF:** com o HTML aberto no navegador, Ctrl+P (no Mac, Cmd+P) → Salvar como PDF.
5. **Para virar PPT:** se a sua IA gera arquivo, peça "agora gere um .pptx com estes slides, com o
   mesmo texto". Se não gera, abra o PDF num conversor de PDF para PowerPoint.

**Veja o resultado com e sem design:** na página do desafio, nos exercícios 11 e 13, estão o mesmo
relatório e a mesma apresentação gerados duas vezes, uma sem e uma com este design system.

```
DESIGN SYSTEM · JANGADA ELETRO (marca fictícia)

USO
Relatório (A4 retrato, uma página) e apresentação (slides 16:9).
Gere um único arquivo HTML, com o CSS dentro dele. Nada externo.

CORES (use só estas; cada uma tem uma função)
--mar          #1d4f73  títulos, links, a cor da marca
--mar-escuro   #143a56  fundo da capa, com texto branco por cima
--mar-claro    #e8f0f6  fundo da caixa da decisão
--vela         #d9822b  só filete, barra de gráfico e detalhe. Nunca letra
--vela-texto   #9a5413  quando a cor da vela precisa virar letra
--tinta        #1c2430  texto principal
--tinta-suave  #55606d  texto secundário, fonte, rodapé
--papel        #ffffff  fundo
--areia        #f5f3ee  fundo de cartão
--linha        #e3e0d8  filetes e bordas
Estados, sempre num selo de uma palavra:
  ok #3d6b4a sobre #e9f2ec · atenção #8a6218 sobre #faf2dd · crítico #8e3728 sobre #faeee9

LETRA
Títulos: Cambria, Georgia, serif, peso 700
Texto: Calibri, Carlito, Arial, sans-serif
(são as letras do Office: o arquivo vira PPT sem trocar a fonte)
Slide: título 34px, texto 20px, rodapé 12px.
Relatório: título 22pt, texto 10,5pt.

FORMATO
Slide: 338,667 × 190,5 mm, o tamanho exato do slide do PowerPoint.
  @page { size: 338.667mm 190.5mm; margin: 0 } e um slide por página na impressão.
Relatório: @page { size: A4; margin: 16mm }, tudo em uma página.

O SLIDE TEM 5 PARTES, NESTA ORDEM
1. sobretítulo: 1 ou 2 palavras, caixa alta, cor vela-texto
2. título: a conclusão em uma frase, cor mar
3. linha de apoio: por que o slide existe (some se não precisar)
4. miolo: tabela (quando o valor exato importa), barras (quando a comparação
   importa) ou cartões
5. rodapé: "Jangada Eletro" à esquerda, o número do slide à direita
A capa: fundo mar-escuro, título branco, um filete vela.

PEÇAS
- número grande: o número principal em 48px, cor mar, com a comparação
  embaixo em tinta-suave
- caixa da decisão: fundo mar-claro, filete mar à esquerda, a decisão em uma frase
- selo de estado: uma palavra em caixa alta, nas cores de estado
- hipótese: sempre com o selo "HIPÓTESE" (cor de atenção). Fato não leva selo
- fonte: logo abaixo do dado de fora, em tinta-suave, 12px:
  "Fonte: quem, onde, quando"
- gráfico de barras: barras em mar; a barra que importa em vela; o valor
  escrito na ponta de cada barra

REGRAS
- No máximo 2 elementos em vela por página. Cor que não significa nada gasta
  a cor que significa.
- Sem sombra, sem degradê, sem ícone decorativo, sem emoji.
- Não mude nenhum texto nem número do conteúdo que eu entregar.
```

---

## Crie o seu · o pedido em que a IA te entrevista

Use numa conversa nova. Cole o design system da Jangada Eletro onde está indicado: ele é o modelo
do formato. Se tiver um relatório ou slide que a sua empresa já usa, anexe junto.

```
Quero montar o design system da minha empresa (ou da minha área) para colar nos meus pedidos de relatório e de apresentação em HTML. O modelo do formato está abaixo, entre as etiquetas <modelo>.

Antes de escrever qualquer coisa, me entreviste. Faça no máximo 4 perguntas por rodada, com opções para eu escolher e sempre uma opção "outro". Pergunte até entender: o nome que aparece no rodapé; as cores que já usamos (o código, se eu souber, ou tiradas de um material que eu anexar); as letras; para quem são os documentos; e o que nunca pode aparecer. Se eu anexar um relatório ou slide nosso, tire dele as cores e o estilo e me pergunte se está certo.

No fim, me devolva o design system no mesmo formato do modelo, preenchido com o meu caso.

Restrições: não escreva o design system antes de terminar a entrevista. Não invente cor nem letra que eu não confirmei. Toda cor de texto precisa ter contraste de pelo menos 4,5:1 com o fundo em que vai cair; se uma cor nossa não passar, me diga e proponha uma versão mais escura. Se a nossa letra não for do Office, avise que ela pode mudar quando o arquivo virar PPT.

Está pronto quando eu colo o design system num pedido de relatório e o HTML sai com a cara da minha empresa, sem eu precisar explicar mais nada.

<modelo>
[cole aqui o design system da Jangada Eletro]
</modelo>
```

**Confira o que voltou:**
- **Perguntas antes do design system,** em rodadas curtas, com opção "outro".
- **As mesmas partes do modelo:** uso, cores, letra, formato, as 5 partes do slide, peças, regras.
- **Nenhuma cor que você não confirmou,** e um aviso se alguma não passou no contraste.

**Se ela inventou uma cor:** `A cor "[qual]" eu não confirmei. Tire, ou me pergunte se ela existe.`



# Números de exemplo · dia 3

**Dados fictícios.** A mesma rede de eletroportáteis do dia 2, agora com agosto ao lado de
setembro. Use nos exercícios 8 a 11 se você não tiver números seus à mão.

**A situação:** a rede vendeu menos em setembro, e a diretoria quer saber por quê.

```
VENDAS POR ESTADO · AGOSTO × SETEMBRO 2026
Estado	Agosto	Setembro
Ceará	R$ 15.100	R$ 15.300
Pernambuco	R$ 13.480	R$ 10.905
Rio Grande do Norte	R$ 8.610	R$ 8.724
Rede	R$ 37.190	R$ 34.929

PERNAMBUCO POR PRODUTO · AGOSTO × SETEMBRO 2026
Produto	Agosto	Setembro
Air fryer	R$ 6.380	R$ 3.591
Cafeteira	R$ 3.150	R$ 3.237
Liquidificador	R$ 2.590	R$ 2.646
Ventilador	R$ 1.360	R$ 1.431
```

**O que a gerência já sabe que mudou em setembro:** nada fora do comum. Mesmo número de lojas,
mesma equipe, sem reforma.

**Para o exercício 9 (a pesquisa é real, na internet):** uma hipótese de fora que dá para
pesquisar é *"as vendas de air fryer no Brasil estão desacelerando porque o mercado já está
abastecido"*. Use a sua, se o exercício 8 trouxer uma melhor.

---

## Gabarito do exercício 8 · abra só depois

**O fato, com o número:**

| Estado | Agosto | Setembro | Variação |
|---|---|---|---|
| Ceará | R$ 15.100 | R$ 15.300 | +1,3% |
| Pernambuco | R$ 13.480 | R$ 10.905 | -19,1% |
| Rio Grande do Norte | R$ 8.610 | R$ 8.724 | +1,3% |
| **Rede** | R$ 37.190 | R$ 34.929 | -6,1% |

| Pernambuco · produto | Agosto | Setembro | Variação |
|---|---|---|---|
| Air fryer | R$ 6.380 | R$ 3.591 | -43,7% |
| Cafeteira | R$ 3.150 | R$ 3.237 | +2,8% |
| Liquidificador | R$ 2.590 | R$ 2.646 | +2,2% |
| Ventilador | R$ 1.360 | R$ 1.431 | +5,2% |

- A rede caiu R$ 2.261. **A queda está em Pernambuco**; Ceará e Rio Grande do Norte subiram.
- Dentro de Pernambuco, **a air fryer sozinha caiu R$ 2.789**, mais do que a queda da rede inteira.

**O que é hipótese, e não fato, aqui:** qualquer "por quê". Os números não dizem se foi
concorrente, estoque, preço, mercado ou sazonalidade. Uma resposta que escreva "a queda foi
puxada por…" sem a marca de hipótese errou o exercício.

**Hipóteses que os números sustentam** (cada uma com o que a derrubaria):
- **Faltou air fryer nas lojas de PE** `[buscar internamente]`: cai se o estoque de setembro estava normal.
- **Concorrente ou loja online com preço menor em PE** `[buscar fora]`: cai se a queda também aparecer onde não houve promoção.
- **O mercado de air fryer está desacelerando** `[buscar fora]`: enfraquece porque no RN a air fryer foi o produto que mais vendeu em setembro (R$ 5.985 de R$ 8.724).



# Documento longo de exemplo · exercício 14

**Dados fictícios.** O manual de campanha que a mesma rede de eletroportáteis mandou para os
gerentes de loja. São 8 páginas, marcadas com `[página N]` para a IA poder citar de onde saiu
cada ponto.

**A situação:** você é gerente da Loja Boa Viagem (Pernambuco). A reunião de alinhamento é
hoje, terça-feira, 3 de novembro, daqui a uma hora. O seu papel na campanha: **executar**.

```
MANUAL DA CAMPANHA BLACK FRIDAY 2026
Rede de lojas de eletroportáteis · Diretoria Comercial · versão de 30/10/2026

[página 1]
1. Por que esta campanha
A Black Friday responde por cerca de 14% da venda anual da rede. Em 2025, a campanha cresceu
abaixo da meta por dois motivos que a diretoria quer evitar em 2026: falta de produto nas lojas
na sexta-feira e descontos dados no balcão acima do previsto, que derrubaram a margem.
Este manual reúne o que cada loja precisa fazer, em que data e com quem falar. Ele substitui
todas as orientações anteriores sobre a campanha, inclusive as enviadas por mensagem.
A campanha vai de quinta-feira, 26 de novembro, a domingo, 29 de novembro. A sexta-feira, 27,
é o dia principal.

[página 2]
2. Os números da campanha
Meta da rede para os quatro dias: R$ 180.000 em vendas.
Meta por estado: Ceará R$ 78.000; Pernambuco R$ 62.000; Rio Grande do Norte R$ 40.000.
A meta de cada loja será enviada pelo gerente regional até 13 de novembro.
O indicador acompanhado diariamente durante a campanha é a venda por loja, comparada com a
meta do dia. A margem será acompanhada só no fechamento, em 30 de novembro.
Produtos em destaque: air fryer, cafeteira, liquidificador e ventilador. A air fryer é o
produto-âncora: é ela que aparece nos anúncios.

[página 3]
3. Preço e desconto
Os preços de campanha de cada produto chegam no sistema de caixa em 25 de novembro, às 22h.
Nenhuma loja altera preço manualmente.
O desconto no balcão, além do preço de campanha, fica limitado a 5%. Qualquer desconto acima
disso, ou qualquer desconto acima de 20% sobre o preço cheio somando tudo, segue o fluxo de
exceções.
O parcelamento máximo é de 10 vezes sem juros para compras acima de R$ 300.
Brindes: não haverá brinde nesta campanha.

[página 4]
4. Vitrine e comunicação na loja
O material de vitrine chega às lojas entre 16 e 20 de novembro. A loja confere o kit no
recebimento e informa ao regional o que faltou em até 24 horas.
A troca das etiquetas de preço acontece na noite de 25 de novembro, depois que o preço de
campanha entra no sistema. A loja fecha no horário normal nesse dia.
As redes sociais são responsabilidade do marketing central. Nenhuma loja publica oferta própria.

[página 5]
5. Estoque e reposição
Cada loja faz o pedido de reposição para a campanha pelo sistema de pedidos até sexta-feira,
6 de novembro, às 18h. Pedido feito depois dessa data entra só na reposição normal, que não
chega antes da campanha.
O pedido deve considerar a venda dos quatro dias da campanha de 2025, mais 20%.
Cotas de air fryer por loja: até 30 unidades. As lojas de Pernambuco recebem cota de até 20
unidades, por causa do estoque disponível no centro de distribuição de Recife. Lojas que
precisarem de mais devem justificar no próprio pedido.
A entrega da reposição de campanha acontece entre 18 e 23 de novembro.

[página 6]
6. Equipe
Cada loja envia ao regional a escala da equipe para os quatro dias até sábado, 7 de novembro.
A escala deve ter pelo menos duas pessoas no caixa na sexta-feira, das 10h às 20h.
Treinamento da campanha: obrigatório para todos os vendedores, on-line, em 10 de novembro, das
8h às 9h, antes da abertura das lojas. A inscrição de cada vendedor é feita pelo gerente até
quinta-feira, 5 de novembro.
Horas extras na campanha precisam de aprovação prévia do regional.

[página 7]
7. Durante a campanha
Cada loja envia ao regional, até as 21h de cada dia da campanha, o fechamento do dia: venda
total, produtos que acabaram e principais reclamações de clientes.
Produto que acabar na loja não pode ser prometido para entrega futura sem confirmação do
centro de distribuição.
Trocas de produtos comprados na campanha seguem a política normal de trocas.

[página 8]
8. Depois da campanha
Fechamento da campanha: 30 de novembro. Cada loja envia o inventário dos produtos em destaque
até 2 de dezembro.
O resultado por loja será apresentado na reunião de gerentes de 4 de dezembro.
As lojas que baterem a meta do período recebem o bônus de campanha, conforme a política de
bônus vigente.
Dúvidas sobre este manual: com o gerente regional.
```

---

## Gabarito · abra só depois

**O que importa para quem executa, na Loja Boa Viagem:**
- **Prazos desta semana (3 a 7 de novembro):**
  - **5/11, quinta:** inscrever cada vendedor no treinamento do dia 10 (página 6).
  - **6/11, sexta, até 18h:** pedido de reposição da campanha. Depois disso, o estoque não chega a tempo (página 5).
  - **7/11, sábado:** escala dos quatro dias para o regional, com 2 pessoas no caixa na sexta, das 10h às 20h (página 6).
- **A cota de air fryer em Pernambuco é de 20 unidades, não 30.** Para pedir mais, é preciso justificar no próprio pedido (página 5). Com a queda de setembro (dia 3), esta é a linha que mais importa para essa loja.
- **Desconto no balcão é de no máximo 5%,** e ninguém mexe em preço manualmente (página 3).

**O que o documento não diz (e vira pergunta na reunião):**
- **Quem aprova o "fluxo de exceções"** do desconto, e em quanto tempo (página 3). O documento cita o fluxo, mas não diz quem aprova.
- **A meta da loja,** que só chega em 13 de novembro (página 2), depois do prazo do pedido de reposição (página 5). Como pedir estoque sem saber a meta?
- **O que conta como "justificar"** o pedido acima da cota (página 5).

**Sinal de leitura de verdade:** a IA percebe que a meta da loja chega **depois** do prazo do
pedido de estoque. Isso não está escrito em nenhuma página; aparece cruzando as páginas 2 e 5.



# Proposta de exemplo · exercício 15

**Dados fictícios.** Depois da queda de setembro em Pernambuco (dia 3), um fornecedor mandou
uma proposta de sistema de estoque para a rede. A diretoria pediu a sua leitura antes de
aprovar.

**O que você já confere numa proposta dessas:** o preço mensal, o prazo de contrato e se o
fornecedor atende outras redes do mesmo tamanho.

```
PROPOSTA COMERCIAL Nº 2026-118
Sistema de reposição inteligente de estoque · para a rede de lojas de eletroportáteis
Validade da proposta: 15 dias

1. O que propomos
Um sistema que acompanha o estoque de cada loja em tempo real e faz o pedido de reposição
sozinho, antes de o produto acabar. Com ele, a ruptura (o produto que falta na prateleira)
cai até 40% já no primeiro trimestre.

2. Como funciona
O sistema lê as vendas do caixa de cada loja e calcula o ponto de reposição de cada produto.
A integração com o sistema de caixa atual é simples e feita pela nossa equipe.
O painel de acompanhamento mostra, por loja, o que está para acabar e o que já foi pedido.

3. Implantação
Implantação rápida, em todas as 6 lojas ao mesmo tempo.
Treinamento da equipe incluído.

4. Investimento
Mensalidade: R$ 1.900 por mês para a rede inteira (6 lojas).
Contrato de 36 meses.
Reajuste anual conforme o mercado.

5. Suporte
Suporte completo, em horário comercial, por e-mail e telefone.

6. Por que nós
Atendemos mais de 200 varejistas em todo o Brasil, com 98% de satisfação.
O retorno do investimento vem nos primeiros meses, pela venda que deixa de ser perdida.
```

---

## Gabarito · abra só depois

**O que está claro:** a mensalidade (R$ 1.900 para 6 lojas), o prazo de contrato (36 meses), a
validade da proposta (15 dias) e o que o sistema faz (lê o caixa e pede reposição).

**O que está vago:**
- "Implantação rápida": em quantos dias?
- "Integração simples": com qual sistema de caixa? Já fizeram com o que a rede usa?
- "Reajuste conforme o mercado": qual índice?
- "Suporte completo": qual o prazo de resposta? E fora do horário comercial, como na noite de 25 de novembro, quando os preços da Black Friday entram no sistema (exercício 14)?
- "Treinamento incluído": para quantas pessoas, e em quantas horas?

**O que ela dá como certo sem provar:**
- **"A ruptura cai até 40% já no primeiro trimestre."** Medido onde, em que tipo de loja, contra o quê? "Até" inclui zero.
- **"O retorno vem nos primeiros meses."** Não há conta nenhuma na proposta.
- **"Mais de 200 varejistas, 98% de satisfação."** Sem nome, sem fonte, sem dizer de que tamanho.
- **A premissa maior, que não está escrita:** que a queda de Pernambuco foi falta de estoque.
  A rede ainda não sabe disso (dia 3: é hipótese, a confirmar com o estoque). Se a causa for
  preço do concorrente, o sistema não resolve o problema que motivou a compra.

**O que não está na proposta (não informado):** o custo de implantação, a multa de rescisão
antes dos 36 meses, de quem são os dados das lojas e o que acontece se a integração com o caixa
não funcionar.

**3 perguntas antes de aprovar:**
1. Qual o custo total no primeiro ano, com implantação, treinamento e integração, e não só a mensalidade?
2. Qual a multa se a rede sair antes dos 36 meses?
3. Podem mostrar uma rede de 5 a 10 lojas que usa o sistema, com o antes e o depois da ruptura?

**Sinal de pensar junto de verdade:** a IA aponta que a proposta assume que o problema é
estoque. A sua conferência de sempre (preço, prazo, referências) não pegaria isso.



# Títulos de exemplo · exercício 12

**Dados fictícios.** A apresentação que a gerência da rede de eletroportáteis levou à
diretoria sobre setembro. Os títulos estão como foram apresentados, e o conteúdo de cada
slide vem embaixo, para a IA não precisar inventar número.

**O que a diretoria decidiu depois da reunião:** pedir ao comercial de Pernambuco o estoque de
air fryer de setembro, loja por loja, antes de qualquer outra ação.

```
Slide 1 · Resultados de setembro
- A rede vendeu R$ 34.929 em setembro, contra R$ 37.190 em agosto (-6,1%).

Slide 2 · Vendas por estado
- Ceará: R$ 15.100 → R$ 15.300 (+1,3%).
- Rio Grande do Norte: R$ 8.610 → R$ 8.724 (+1,3%).
- Pernambuco: R$ 13.480 → R$ 10.905 (-19,1%).

Slide 3 · Pernambuco
- A queda de Pernambuco foi de R$ 2.575.
- Air fryer: R$ 6.380 → R$ 3.591 (-43,7%). Os outros três produtos subiram um pouco.

Slide 4 · Produtos
- No RN, a air fryer foi o produto que mais vendeu em setembro (R$ 5.985 de R$ 8.724).

Slide 5 · Hipóteses
- Faltou air fryer nas lojas de Pernambuco (a confirmar com o estoque).
- Concorrente com preço menor em Pernambuco (a pesquisar).

Slide 6 · Próximos passos
- Levantar o estoque de air fryer de Pernambuco, loja por loja.
- Pesquisar preço de concorrentes em Recife.
```

---

## Gabarito · abra só depois

**O que alguém entende lendo só os títulos de hoje:** nada além de que houve uma reunião sobre
setembro. Os 6 são títulos de assunto.

**Uma versão com títulos de conclusão** (todos os números estão no conteúdo dos slides):

| # | Título de assunto | Título de conclusão |
|---|---|---|
| 1 | Resultados de setembro | A rede vendeu 6,1% menos em setembro que em agosto |
| 2 | Vendas por estado | A queda está toda em Pernambuco: -19,1%, com Ceará e RN em alta |
| 3 | Pernambuco | Só a air fryer de Pernambuco caiu R$ 2.789, mais que a queda da rede inteira |
| 4 | Produtos | No RN, a air fryer foi o produto mais vendido: o problema não é o produto |
| 5 | Hipóteses | Falta de estoque é a hipótese mais barata de testar primeiro |
| 6 | Próximos passos | Antes de qualquer ação, o estoque de air fryer de PE, loja por loja |

**Repare no título 3:** os R$ 2.789 não estão escritos no slide; saem da conta R$ 6.380 −
R$ 3.591. Se a IA trouxer esse número, pergunte de onde ele saiu. É conta certa, mas é número
novo no título.

**O teste do gabarito:** lendo só os títulos da direita, alguém chega à decisão que a
diretoria tomou? Chega: o título 6 é a própria decisão.



# Anotações de exemplo · exercício 16

**Dados fictícios.** A reunião em que a mesma rede de eletroportáteis discutiu a queda de
setembro em Pernambuco (dia 3). As anotações estão do jeito que a gerente regional fez, no
celular, durante a reunião. A ata que ela mandou depois está no gabarito: **não cole a ata na
conversa.** Ela é o seu gabarito.

**A reunião:** terça-feira, 6 de outubro de 2026, 45 minutos, por vídeo.
**Quem estava:** a gerente regional de Pernambuco (GR), o gerente da Loja Boa Viagem (GBV), a
gerente da Loja Recife Antigo (GRA), o comprador da rede (Compras) e a analista de marketing
central (MKT).

```
reuniao PE 6/10
- GR abriu c/ numeros: PE -19% set, AF -44%
- GBV: faltou AF na BV de 12 a 25/9, "cliente voltava e nao tinha"
- GRA: na RA nao faltou, mas concorrente da rua de tras c/ AF a 349 (nossa 399)
- Compras: CD Recife recebeu AF atrasada em set, fornecedor atrasou 2 sem
- decidido: levantar estoque AF set loja por loja -> Compras ate 9/10
- GRA tirar foto/print preco concorrente, mandar no grupo
- pensamos em promo AF em PE em outubro -> MKT acha cedo, ficou p/ depois da BF
- checar c/ CD se a cota de AF de PE p/ BF pode subir (hoje ta 20)
- GR leva p/ diretoria na sexta o resumo
- prox reuniao: depois do levantamento
```

---

## Gabarito · a ata que a gerente regional mandou · abra só depois

```
ATA · Queda de vendas em Pernambuco · 6/10/2026
Participantes: gerente regional PE, gerentes das lojas Boa Viagem e Recife Antigo, comprador, marketing central

O que foi apresentado
- Pernambuco vendeu 19% menos em setembro do que em agosto. A air fryer caiu 44%.

O que se ouviu
- Boa Viagem: faltou air fryer de 12 a 25 de setembro.
- Recife Antigo: não faltou produto; um concorrente próximo vende a air fryer a R$ 349, contra R$ 399 da rede.
- Compras: o centro de distribuição de Recife recebeu a air fryer com 2 semanas de atraso em setembro.

Decisões
- Antes de qualquer ação de preço, levantar o estoque de air fryer de setembro, loja por loja.
- A promoção de air fryer em Pernambuco fica para depois da Black Friday.

Pendências
| O que fazer | Quem | Até quando |
| Levantar o estoque de air fryer de setembro, por loja | Compras | 9/10 |
| Mandar foto do preço do concorrente no grupo | Gerente Recife Antigo | 7/10 |
| Consultar o CD sobre aumentar a cota de air fryer de PE na Black Friday | Compras | 16/10 |
| Levar o resumo da reunião à diretoria | Gerente regional | 9/10 |

Próxima reunião: depois do levantamento de estoque, data a marcar.
```

**Onde a ata real tem informação que as anotações não têm:**
- **O prazo da foto (7/10)** e **o dono e o prazo da consulta ao CD (Compras, 16/10)** foram
  combinados depois da reunião, por mensagem. **Nas anotações, essas duas pendências estão sem
  prazo, e a do CD está também sem dono.** A IA que preencheu esses campos inventou, mesmo que
  tenha acertado.
- **"Sexta" (levar à diretoria)** virou 9/10 na ata. Nas anotações está só "sexta". A IA pode
  deduzir 9/10 a partir da data da reunião, mas tem que dizer que deduziu.

**O que conferir na ata da IA:**
- A promoção aparece como **decisão de adiar**, e não como pendência de fazer promoção.
- "GR leva p/ diretoria" é pendência, com dono (a gerente regional).
- **As abreviações** (AF, BV, RA, CD, GR) foram perguntadas ou entendidas certo? AF é air fryer,
  BV é Boa Viagem, RA é Recife Antigo, CD é o centro de distribuição.
- **Nenhuma pendência a mais.** "Fazer promoção em outubro" como pendência é invenção.



# Reunião de exemplo · exercício 17

**Dados fictícios.** A reunião que a gerente regional de Pernambuco vai conduzir, a mesma rede
de eletroportáteis. Use estes dados para montar a pauta, se você não tiver uma reunião sua à
vista.

```
Reunião: retomada de Pernambuco para a Black Friday
Quando: quarta-feira, 4 de novembro de 2026, 45 minutos, por vídeo
Quem conduz: a gerente regional de Pernambuco

Quem vai, e o que cada um sabe:
- Gerente da Loja Boa Viagem: viveu a falta de air fryer em setembro
- Gerente da Loja Recife Antigo: acompanha o preço do concorrente
- Comprador da rede: tem o levantamento do estoque de setembro e a resposta do CD sobre a cota
- Analista de marketing central: cuida dos anúncios da Black Friday, em que a air fryer é o produto-âncora

Objetivos:
1. Ver o levantamento de estoque de setembro e fechar a causa da queda: faltou produto ou foi preço?
2. Decidir quanto pedir de air fryer para a Black Friday, já que a cota de Pernambuco é de 20 por loja e o pedido fecha na sexta, 6 de novembro, às 18h.
3. Combinar o que fazer com o preço do concorrente durante a campanha.

Quem decide o pedido de air fryer: a gerente regional, depois de ouvir o comprador.
```

---

## Gabarito · abra só depois

**Sinais de uma pauta boa para esta reunião:**
- **A soma dá 45 minutos,** com 5 a 10 de encerramento para repassar decisões, donos e prazos.
- **O objetivo 2 (o pedido) não fica por último.** Ele tem prazo na sexta e é a única decisão
  da reunião. Se o tempo acabar, acaba em outro item.
- **O objetivo 1 vem antes do 2,** porque a causa muda o pedido: se foi falta de produto, pede-se
  mais; se foi preço, mais estoque não resolve.
- **O objetivo 3 pode não caber.** O preço de campanha vem do comercial central (manual da Black
  Friday, página 3, no dia 4). A pauta boa avisa isso, em vez de espremer o assunto.
- **Cada item abre com uma pergunta:** "Faltou produto ou foi preço?", e não "Discussão sobre o
  estoque".
- **O que cada um traz:** o comprador traz o levantamento e a resposta do CD; a gerente de Recife
  Antigo traz o print do preço do concorrente.



# E-mails de exemplo · exercícios 20, 21 e 22

**Dados fictícios.** A mesma rede de eletroportáteis, nas semanas antes da Black Friday. O
exercício 19 usa a ata do exercício 16; para ele, sirva-se da ata real do material do dia 5.

---

## Exercício 20 · O e-mail inseguro

**A situação:** quarta-feira, 4 de novembro, depois da reunião da pauta (dia 5). A gerente
regional de Pernambuco escreveu para o diretor comercial e não mandou ainda.
**O que ela quer que o diretor faça:** autorizar o pedido de air fryer acima da cota, até sexta.

```
Assunto: air fryer

Oi, tudo bem? Desculpa incomodar com isso agora, sei que a semana tá corrida.

Então, a gente conversou hoje com o pessoal das lojas e o comprador sobre a Black Friday e eu acho que talvez fosse bom pedir um pouco mais de air fryer para Pernambuco do que a cota, porque em setembro faltou em uma loja e acabou que a gente perdeu venda. Não sei se faz sentido, mas queria ver contigo o que você acha.

O comprador falou que o CD consegue mandar mais se a gente justificar.

Qualquer coisa me avisa. Obrigada!
```

### Gabarito · abra só depois

**O que deveria estar e não está:**
- **O pedido, em uma frase, no começo:** "Preciso da sua autorização para pedir X air fryers para Pernambuco, acima da cota de 20 por loja."
- **Quantas unidades,** e para quais lojas. O e-mail não diz.
- **O prazo:** o pedido fecha na sexta, 6/11, às 18h (manual da Black Friday, página 5). Sem isso, a resposta pode chegar tarde.
- **O porquê com número:** em setembro, a air fryer de Pernambuco caiu 44%, e a Boa Viagem ficou sem produto de 12 a 25/9.
- **O que acontece sem a autorização:** as lojas ficam com 20 unidades cada, em uma campanha em que a air fryer é o produto-âncora.
- **O assunto:** "air fryer" não diz que é um pedido de autorização com prazo.

**O que sai:** "Desculpa incomodar", "eu acho que talvez", "Não sei se faz sentido". O pedido é legítimo e está no papel dela.

**A armadilha para a IA:** inventar a quantidade (por exemplo, "30 unidades por loja"). Ela não
está no e-mail; a revisão certa aponta `[FALTA: quantidade]`.

---

## Exercício 21 · A pendência já cobrada duas vezes

**A situação:** quarta-feira, 4 de novembro. O fornecedor de air fryer ainda não confirmou a
data de entrega da reposição da Black Friday. A rede precisa dessa data para fechar o pedido no
sistema até sexta, 6/11.

```
O que está pendente: a confirmação da data de entrega da air fryer para a Black Friday (lote de reposição)
Pedido ao fornecedor em: 14/10
Primeira cobrança: 21/10, por e-mail, sem resposta
Segunda cobrança: 28/10, por telefone; o atendente disse que "o comercial ia retornar"
A relação: fornecedor principal de air fryer da rede há 4 anos
O prazo que importa agora: quinta, 5/11, até 12h, porque o pedido da campanha fecha na sexta, 6/11, às 18h
O que acontece se não vier: a rede faz o pedido da campanha com outro fornecedor de air fryer
```

### Gabarito · abra só depois

**Sinais de uma cobrança boa:**
- **O assunto diz a pendência e o prazo:** "Data de entrega da air fryer · preciso até quinta, 5/11, 12h".
- **A primeira frase já é o pedido.** Nada de "Espero que esteja bem".
- **O histórico em uma linha,** sem tom de acusação: pedido em 14/10, cobrado em 21/10 e 28/10.
- **A consequência como fato:** "Sem a data até lá, vamos fazer o pedido da campanha com outro
  fornecedor." Não é ameaça: é o que acontece com o calendário.
- **Sem "desculpe a insistência".** E sem oferecer mais prazo que a rede não tem.

---

## Exercício 22 · A cliente que chegou irritada

**A situação:** sexta-feira, 2 de outubro. Uma cliente escreveu para o e-mail de atendimento da
rede. É sobre a falta de air fryer na Loja Boa Viagem em setembro (dia 5).

```
Fui duas vezes na loja de Boa Viagem procurar a air fryer que estava no anúncio de vocês e nas duas vezes não tinha. Na segunda vez o vendedor disse que "chegava na semana que vem" e de novo nada. Perdi duas tardes. Se anunciam um produto, tenham o produto. Vou comprar no concorrente e vou contar para todo mundo como vocês tratam o cliente.
D. S.
```

**O que a loja pode oferecer:** reservar uma air fryer no nome dela; a reposição chega na loja
na sexta, 9/10. A loja liga quando chegar.
**O que a loja não pode prometer:** desconto fora da política, nem o preço da Black Friday antes
da campanha.

### Gabarito · abra só depois

**Sinais de uma resposta boa:**
- **Reconhece com o fato dela:** as duas idas à loja e a promessa que não se cumpriu.
- **Não admite culpa,** nem entra em quem errou (o fornecedor que atrasou, o vendedor).
- **O próximo passo tem data:** a reserva, a chegada em 9/10, a ligação da loja.
- **Leva para o privado:** um telefone ou um WhatsApp da loja.
- **Não promete o que não pode:** nada de desconto, nada de preço da Black Friday.
- **Até 120 palavras,** sem "sua opinião é muito importante para nós".

**A armadilha para a IA:** oferecer um "cupom de desconto como pedido de desculpas". Não está no
que a loja pode oferecer.
