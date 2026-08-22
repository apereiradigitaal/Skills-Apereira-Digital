---
name: avoid-ai-writing
description: "Audita e reescreve textos para remover a cara de IA — travessões em excesso, negrito demais, palavras robóticas como 'utilizar', 'robusto' e 'no cenário atual', frases genéricas e conclusões vazias. Use esta skill sempre que alguém pedir para tirar a cara de IA de um texto, deixar o texto mais humano, revisar legenda ou roteiro escrito com inteligência artificial, limpar texto gerado por IA, ou humanizar conteúdo. Também aciona quando mencionarem 'parece escrito por IA', 'texto robótico', 'humanizar texto', 'tirar os vícios de IA', 'editor anti-IA', 'remover AI-isms', 'clean up AI writing', ou pedirem revisão de qualquer texto que passou por IA antes de ser publicado. Funciona para legenda de Instagram, roteiro, e-mail, artigo, página de vendas e qualquer texto em português ou inglês."
---

# Editor Anti-IA — Auditoria e Reescrita

## O que esta skill faz

Você cola um texto. Ela aponta cada trecho que denuncia "isso foi escrito por IA", explica
por quê, e devolve uma versão reescrita que soa como pessoa de verdade escrevendo.

O problema que ela resolve: você usa IA pra adiantar a legenda ou o roteiro, o texto fica
correto mas com aquele cheiro de robô — e o seu público sente. Essa skill tira o cheiro sem
tirar o conteúdo.

**Entrada:** um texto (legenda, roteiro, e-mail, artigo, página de vendas).
**Saída:** lista de problemas + versão reescrita + resumo do que mudou + segunda checagem.

---

## Fluxo de trabalho

1. **Auditar** — identificar cada vício de IA presente, citando o trecho exato
2. **Reescrever** — devolver a versão limpa, preservando conteúdo, estrutura e intenção
3. **Resumir** — listar as mudanças principais e o motivo de cada uma
4. **Rechecar** — reler a própria reescrita e caçar o que sobrou

Preservar sempre: os fatos, os números, os nomes, o argumento e a estrutura do original.
Mudar só o que as regras abaixo pedem.

---

## O que remover ou corrigir

### Formatação

**Travessões (—).** O tique mais denunciador de todos. Trocar por vírgula, ponto, parênteses,
ou quebrar em duas frases. Meta: zero. Máximo absoluto: um a cada 1.000 palavras. Vale para
títulos também, não só para o corpo do texto.

**Negrito demais.** Tirar o negrito da maior parte das expressões. No máximo um trecho em
negrito por seção grande — ou nenhum. Se é importante o bastante pra estar em negrito,
reescreva a frase começando por aquilo.

**Emoji em título.** Remover. Nada de `## 🚀 O que isso significa`. Exceção: post de rede
social pode usar um ou dois emojis, no fim da linha, nunca no meio da frase.

**Lista de bullets em excesso.** Transformar seções cheias de bullet em parágrafos corridos.
Bullet só para o que é lista de verdade: passo a passo, comparação, especificação.

### Estrutura de frase

**"Não é X — é Y" / "Isso não é sobre X, é sobre Y".** Reescrever como afirmação direta.
No máximo uma por texto, e só se ajudar o argumento.

**Intensificadores ocos.** Cortar: `genuinamente`, `verdadeiramente`, `realmente`,
`sinceramente`, `pra ser honesto`, `vamos ser claros`, `vale ressaltar que`. Só diga o fato.

**Hesitação.** Cortar: `talvez`, `pode potencialmente`, `é importante notar que`,
`é válido mencionar`. Faça a afirmação direto.

**Parágrafos sem ponte.** Cada parágrafo deve puxar do anterior. Se dá pra embaralhar a ordem
dos parágrafos e ninguém percebe, falta costura entre eles.

**Regra de três compulsiva.** Variar os agrupamentos. Use dois itens, quatro, ou uma frase
inteira no lugar do trio. No máximo um "adjetivo, adjetivo e adjetivo" por texto.

### Palavras e expressões a trocar

| Trocar | Por |
|---|---|
| utilizar | usar |
| realizar (no sentido de fazer) | fazer |
| possuir | ter |
| robusto | forte, sólido, confiável |
| abrangente | completo, amplo |
| de ponta / cutting-edge | mais novo, mais avançado |
| alavancar | usar, aproveitar |
| potencializar | melhorar, aumentar |
| impulsionar | aumentar, acelerar |
| otimizar | melhorar, ajustar |
| maximizar | aumentar ao máximo |
| fomentar | incentivar, apoiar |
| elevar (metafórico) | melhorar, aumentar |
| empoderar | permitir, dar autonomia |
| desbloquear (metafórico) | liberar, destravar |
| mergulhar fundo / aprofundar-se | ver de perto, entender |
| explorar (como enfeite) | ver, analisar |
| cenário (metafórico) | mercado, área, setor |
| universo / mundo (metafórico) | área, setor |
| paradigma | modelo, jeito de fazer |
| jornada (metafórico) | processo, caminho |
| ecossistema (metafórico) | conjunto, mercado |
| trilhar / embarcar | começar, entrar |
| pilar fundamental | base, ponto principal |
| peça-chave / fator crucial | importante, principal |
| verdadeiro divisor de águas | (diga o que mudou de fato) |
| um marco | (diga o que aconteceu) |
| revolucionar | mudar |
| transformador | (diga o que muda na prática) |
| meticuloso / minucioso | cuidadoso, detalhado |
| impecável | limpo, bem-feito |
| significativo | grande, importante (ou dê o número) |
| diversos / inúmeros | vários, muitos (ou dê o número) |
| a fim de | para |
| devido ao fato de que | porque |
| no que diz respeito a | sobre |
| em termos de | (reescrever) |
| serve como | é |
| apresenta / conta com | tem |
| se destaca por | (diga o que ele faz) |
| no atual cenário / nos dias de hoje | (cortar ou dar o contexto real) |
| na era digital | (cortar) |
| o futuro é promissor | (cortar ou dizer algo específico) |
| só o tempo dirá | (cortar) |
| vibrante / pulsante | (descrever o que acontece de fato) |
| em constante evolução | (cortar ou dizer o que mudou) |

A mesma lógica vale em inglês: `delve`, `leverage`, `robust`, `seamless`, `game-changer`,
`utilize`, `testament to`, `landscape`, `tapestry`, `empower`, `unleash`, `streamline`,
`showcasing`, `nestled`, `thriving`, `pivotal`, `foster`, `harness`, `underscores`.

### Frases de template

Construções de preencher lacuna. Se dá pra trocar o substantivo e a frase continuar
soando igual, é genérica demais.

- "um passo [adjetivo] rumo a [algo]" → diga qual capacidade ou resultado mudou
- "uma ferramenta poderosa para [qualquer coisa]" → diga o que a ferramenta faz
- "nesse conteúdo você vai entender tudo sobre X" → comece pelo conteúdo

### Conectivos a remover ou reescrever

- "Além disso" / "Ademais" / "Outrossim" → reestruture pra conexão ficar óbvia, ou use "e", "também"
- "No atual cenário" / "Numa era em que" → corte ou dê o contexto específico
- "Vale destacar que" / "Notavelmente" → só diga o fato
- "Em conclusão" / "Para resumir" → a conclusão deve ser óbvia sozinha
- "Quando se trata de" → fale da coisa direto
- "No fim das contas" → corte
- "Dito isso" → corte, ou use "mas"

### Problemas estruturais

**Parágrafos todos do mesmo tamanho.** Varie de propósito. Inclua parágrafos de uma ou duas
frases e outros mais longos. Se todos têm o mesmo peso, corrija.

**Abertura formulaica.** Se o texto começa com contexto amplo antes de chegar ao ponto
("No mundo em constante transformação do..."), reescreva começando pela informação ou pela
ideia. O contexto entra depois.

**Gramática limpa demais.** Não lixe a personalidade toda. Frase cortada, frase começando com
"E" ou "Mas", vírgula usada pra dar respiro: se é assim que a pessoa fala, mantenha.

### Inflação de importância

Frases como "marcando um momento decisivo na evolução de..." transformam evento comum em fato
histórico. Diga o que aconteceu e deixe o leitor julgar o tamanho. Teste prático: se a frase
continua funcionando depois de apagar a parte grandiosa, apague.

### Fuga do verbo simples

A IA evita "é" e "tem" trocando por verbo pomposo: "serve como", "apresenta", "conta com",
"configura-se como", "caracteriza-se por". Isso soa a release de assessoria. Use "é" e "tem",
a não ser que o verbo mais específico realmente acrescente sentido.

### Ciranda de sinônimos

A IA gira sinônimos pra não repetir palavra: "criadores... produtores... realizadores...
profissionais de conteúdo" no mesmo parágrafo. Gente repete a palavra mais clara. Se o mesmo
substantivo aparece três vezes e é a palavra certa, mantenha as três.

### Atribuição vaga

"Especialistas afirmam", "estudos mostram", "pesquisas indicam", "o mercado concorda" — sem
dizer qual especialista, qual estudo. Ou cite a fonte específica, ou corte a atribuição e faça
a afirmação direto.

### Conclusão genérica

"O futuro é promissor", "só o tempo dirá", "uma coisa é certa", "seguimos em frente" — é
enchimento fantasiado de conclusão. Corte. Se o texto precisa fechar, feche com algo específico
do argumento.

### Vícios de chatbot

"Espero ter ajudado!", "Com certeza!", "Ótima pergunta!", "Fique à vontade para perguntar",
"Qualquer dúvida, é só chamar" — são tiques de conversa de chat, não de texto publicado.
Remover. Vale também para "Neste artigo, vamos explorar..." e "Vamos lá!".

### Citação de nome por status

Empilhar referência de peso pra fabricar credibilidade: "citado na Forbes, no Valor, na Exame
e no G1". Se a fonte importa, use ela com contexto: "numa entrevista à Exame em 2024, ela
defendeu que...". Uma referência específica vale mais que quatro nomes soltos.

### Análise de gerúndio

Fileira de gerúndios fingindo análise: "consolidando a marca no mercado, refletindo anos de
investimento e demonstrando uma nova fase". Não diz nada. Troque por fato específico ou corte.

### Linguagem de folder

A IA cai em prosa de folheto turístico: "um polo vibrante de inovação", "um ecossistema
pujante", "aninhada entre montanhas". Troque por descrição simples. Se você não falaria isso
numa conversa, corte.

### Desafio formulaico

"Apesar dos desafios, a empresa segue crescendo" ou "mesmo diante das dificuldades, o setor se
mantém resiliente". Não afirma nada. Diga qual foi o desafio e qual foi a resposta, ou corte.

### Falsa amplitude

Extremos sem relação, colados pra parecer abrangente: "do algoritmo do Instagram à filosofia
grega", "das cavernas às startups". Liste os temas de verdade ou escolha o que importa.

### Lista com título repetido

Bullet em que cada item abre com um título em negrito que se repete: "**Alcance:** O alcance
aumentou em...". Tire o título e escreva o ponto direto. Se os itens precisam de título,
provavelmente deveriam ser parágrafos.

### Título em Caixa Alta Inicial

A IA capitaliza título demais: "Estratégias De Conteúdo E Parcerias Estratégicas". Em
português, use caixa normal: só a primeira letra e nomes próprios.

### Aviso de limitação

"Com base nas informações disponíveis", "até a minha última atualização", "não tenho acesso a
dados em tempo real". É limitação do modelo vazando pro texto. Ou busque a informação, ou tire
a ressalva. Nunca publicar uma frase que admite que o autor não pesquisou.

### Emoção declarada

A IA anuncia emoção como muleta: "o que mais me surpreendeu", "fiquei fascinado ao descobrir",
"o que me chamou atenção foi", "a parte mais interessante".

Dois problemas. Primeiro, é contar em vez de mostrar: se a coisa surpreende de verdade, quem
lê sente pelo conteúdo, não pelo aviso. Segundo, viraram muleta de transição e de abertura de
lista.

Isso nem sempre é IA — também é escrita humana no piloto automático. Sinalizar do mesmo jeito.
A correção não é "nunca diga que se surpreendeu". É: se você declara a emoção, o texto em volta
precisa sustentar ela. Se não sustenta, corte a declaração e mostre a coisa.

---

## Formato de saída

Responder em quatro seções:

**1. Problemas encontrados**
Lista dos vícios identificados, com o trecho exato citado entre aspas.

**2. Versão reescrita**
O texto completo reescrito. Preservar estrutura, intenção e todos os detalhes específicos.
Mudar só o que as regras pedem.

**3. O que mudou**
Resumo curto das edições principais. Não precisa listar palavra por palavra.

**4. Segunda checagem**
Reler a versão da seção 2 e caçar o que sobreviveu à primeira passada: conectivo reciclado,
inflação restante, fuga do verbo simples, enchimento. Corrigir, devolver o texto corrigido
ali mesmo e dizer o que mudou nessa passada. Se estiver limpo, dizer que está limpo.

---

## Calibragem de tom

O objetivo é texto que soa escrito por pessoa. Direto. Específico. O texto deve demonstrar
confiança, não afirmar que tem confiança.

Se o original já é bom, diga isso e faça só os cortes necessários. Não reescreva por
reescrever.

---

## Identidade visual (quando gerar arquivo)

Esta skill entrega texto por padrão. Se o usuário pedir a auditoria em arquivo:

```
Fundo:            #292929
Texto principal:  #f4f4f4
Texto secundário: #e0dbd7
Destaque:         #f1dd80
Fonte:            Arial
```

Sem logo e sem marca d'água.

---

## Como adaptar esta skill pro seu negócio

1. **Adicione as suas palavras proibidas.** Toda marca tem palavra que não usa. Acrescente as
   suas na tabela "Palavras e expressões a trocar", com a substituição que você prefere.
2. **Proteja o seu jeito de escrever.** Se você usa travessão de propósito, ou escreve tudo em
   minúscula, ou repete uma expressão que é a sua marca, escreva uma seção "Não mexer" no fim
   deste arquivo listando isso. A skill passa a respeitar.
3. **Ajuste o rigor.** Legenda de Instagram e artigo de blog pedem níveis diferentes. Você pode
   criar duas versões deste arquivo: uma mais dura pra texto longo, outra mais leve pra legenda.
4. **Cole exemplos seus.** Dois ou três textos que você escreveu e gosta, colados no fim, ensinam
   o seu tom melhor que qualquer regra.
5. **Alimente com o que passa batido.** Toda vez que você publicar e depois perceber um vício que
   escapou, adicione ele numa seção nova. O arquivo fica mais afiado a cada uso.
