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
