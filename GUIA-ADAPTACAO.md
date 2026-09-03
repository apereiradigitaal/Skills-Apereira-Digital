# Como adaptar essas skills pro seu negócio

As três skills desse kit foram feitas de propósito com exemplos genéricos, pra funcionar em
qualquer nicho no primeiro uso. É isso que deixa elas prontas pra usar hoje — e é exatamente
isso que segura o resultado depois de duas semanas.

Uma skill genérica te dá um bom ponto de partida. Uma skill ajustada ao seu negócio te dá
conteúdo que você publica quase sem editar. A diferença entre as duas é meia hora de trabalho,
uma vez só.

Esse guia mostra como fazer essa meia hora render.

---

## Antes de começar: o que é o arquivo que você baixou

Cada skill é uma pasta com um arquivo `SKILL.md` dentro. Esse arquivo é **texto puro**. Nada de
código, nada de programa, nada escondido.

Você abre no Bloco de Notas, no TextEdit, no Google Docs, em qualquer editor. Lê tudo o que
está escrito ali — é literalmente o manual de instruções que o Claude segue quando você usa a
skill. Edita o que quiser, salva, sobe de novo.

Se você quebrar alguma coisa, baixa de novo aqui no repositório e recomeça. Não tem risco.

### As duas partes do arquivo

Abrindo o `SKILL.md`, você vê duas partes bem diferentes:

**O cabeçalho** (as primeiras linhas, entre `---` e `---`) tem o nome e a descrição. A descrição
é o que faz o Claude saber **quando** usar a skill sozinho. Se você quiser que ela dispare com
palavras que você usa no dia a dia, é aqui que você adiciona.

**O corpo** (todo o resto) é o que a skill **faz** quando é acionada. É onde ficam as regras, os
formatos de entrega e os exemplos. É aqui que mora 90% do que vale a pena personalizar.

---

## 0. O caminho mais rápido: peça pro Claude editar

Todos os passos abaixo você pode fazer abrindo o arquivo num editor. Mas dá pra fazer tudo
conversando, e costuma ser mais rápido.

1. **Anexe o arquivo no chat.** Descompacte o `.zip` e arraste o `SKILL.md` para a conversa.
   O Claude precisa ver o arquivo inteiro pra editar sem inventar.
2. **Diga o que te incomodou, com exemplo.** Pedir "melhora essa skill" não funciona, porque o
   Claude não sabe o que é melhor pra você.
3. **Entregue o seu contexto de uma vez.** Nicho, vocabulário do seu público, e o que você
   nunca fala.
4. **Peça o arquivo pronto:** "me devolve o SKILL.md completo, em arquivo, mantendo o cabeçalho
   igual".
5. **Suba a nova versão** em Configurações, Personalizar, Habilidades, Adicionar, Fazer upload
   de habilidade. Se a antiga continuar na lista, apague pra não ficar duas iguais.
6. **Teste num caso real e volte** no mesmo chat pra pedir o próximo ajuste.

### Exemplos de pedido que funcionam

> "essa skill me entregou hooks com cara de coach, tipo 'desperte seu potencial'. eu falo de um
> jeito mais seco e direto. ajusta a skill pra nunca usar esse tom e me devolve o arquivo."

> "meu nicho é nutrição pra corredores amadores. meu público fala treino longo, carbo, ritmo de
> prova. eu nunca falo de dieta restritiva nem de emagrecimento. troca os exemplos de nicho da
> skill por esses."

> "toda vez ela usa a palavra jornada e eu detesto. adiciona na lista do que evitar e me devolve
> o arquivo atualizado."

O resto deste guia diz **o que** mudar. Você escolhe se muda na mão ou pedindo no chat.

---

## 1. Comece pelo que mais dói

Não saia editando tudo. Use a skill do jeito que ela veio por três ou quatro vezes e anote onde
o resultado te decepcionou.

Quase sempre cai em uma dessas três:

- **"Não é assim que eu falo."** Problema de tom de voz. Vá pro item 2.
- **"Isso não serve pro meu público."** Problema de contexto e nicho. Vá pro item 3.
- **"Está bom, mas não é o formato que eu uso."** Problema de estrutura de entrega. Vá pro item 4.

Corrigir o que incomoda de verdade vale mais que reescrever o arquivo inteiro por perfeccionismo.

---

## 2. Ensine o seu tom de voz

Essa é a mudança que dá mais retorno, e a mais simples.

Descrever tom de voz com adjetivo quase não funciona. "Escreva de forma descontraída e próxima"
significa uma coisa pra você e outra completamente diferente pro Claude.

O que funciona é **exemplo**. Abra o `SKILL.md`, vá até uma seção de regras e cole um bloco assim:

```
## Meu tom de voz — usar como referência

Exemplos de conteúdo meu que funcionaram bem:

1. "[cole aqui uma legenda sua que performou]"
2. "[cole outra]"
3. "[cole mais uma]"

Padrões que eu sigo:
- escrevo tudo em minúscula
- uso "você" e nunca "vocês"
- não uso ponto de exclamação
- gosto de começar com pergunta
```

Três a cinco exemplos reais ensinam mais que uma página de adjetivos. E se você não tem exemplos
que gosta ainda, escreva você mesma dois parágrafos do jeito que você falaria — isso já serve.

---

## 3. Troque os exemplos de nicho pelos seus

As skills trazem nichos amplos como referência: marketing, saúde, educação, negócios, beleza.
Isso serve pra skill não travar quando não sabe nada sobre você.

Na `hooks-magneticos`, procure a seção **"Adaptação por nicho"**. Na `roteiro-pauta-quente`,
procure o **Passo 1** e o **Passo 2**.

Apague os nichos que não são seus e escreva o seu no lugar, com detalhe de verdade:

```
**Meu nicho: consultoria financeira para autônomos**

Vocabulário do público: MEI, imposto, pró-labore, reserva, fluxo de caixa, nota fiscal
Dores reais: misturar conta pessoal com conta da empresa, não saber quanto se pagar,
             medo de guardar dinheiro e precisar dele no mês seguinte
O que NÃO falar: investimento em renda variável, day trade, enriquecimento rápido
```

Repare que a última linha é tão importante quanto as outras. Dizer o que **não** entra evita
metade dos resultados ruins.

---

## 4. Fixe o formato que você já usa

Se você já grava reels num formato próprio, ou já tem uma estrutura de legenda que funciona, não
aceite o formato padrão da skill. Substitua.

Na `roteiro-pauta-quente`, o **Passo 4** tem o modelo de roteiro inteiro escrito. Apague e cole
o seu. Na `hooks-magneticos`, a seção **"Estrutura de entrega"** faz o mesmo papel.

O mesmo vale pra quantidade. Se 20 hooks é informação demais e você só quer 6, troque os "5" por
"2" na estrutura. A skill obedece o que está escrito no arquivo.

---

## 5. Alimente a lista do que evitar

Essa é a parte que quase ninguém faz, e é a que separa uma skill morna de uma skill afiada.

Toda vez que a skill entregar algo que não é a sua cara, não descarte em silêncio. Abra o arquivo
e adicione aquilo na seção "O que evitar":

```
### O que evitar
- hooks começando com "você sabia que"
- qualquer promessa com prazo ("em 7 dias")
- a palavra "jornada"
- tom de coach
```

Cinco ou seis rodadas fazendo isso e a skill para de errar naquilo pra sempre. É um acúmulo:
cada correção que você escreve vale pra todos os usos futuros.

---

## 6. Encadeie as skills num pedido só

As três funcionam juntas. Em vez de rodar uma de cada vez, peça o fluxo inteiro:

> "busca uma pauta quente sobre [seu nicho], monta o roteiro, e antes de fechar roda o editor
> anti-IA na legenda"

Três etapas viram um pedido. Você recebe pauta pesquisada, roteiro pronto e legenda já limpa.

Outra combinação que funciona bem:

> "cria hooks sobre [tema], escolhe o melhor e transforma num roteiro de 30 segundos"

---

## 7. Ajuste a identidade visual

As skills vêm com uma base de cores neutra e fonte Arial:

```
Fundo:            #292929
Texto principal:  #f4f4f4
Texto secundário: #e0dbd7
Destaque:         #f1dd80
Fonte:            Arial
```

Elas não têm logo, marca d'água nem dado de contato de ninguém. Se a sua marca tem paleta
própria, troque os códigos de cor acima pelos seus e mude a fonte. Se você quiser o seu logo nos
arquivos gerados, adicione uma linha dizendo onde ele fica.

---

## 8. Crie a sua própria skill

Depois de editar as três, o passo natural é criar uma do zero.

O critério é simples: **todo processo que você repete e explica do zero toda vez pode virar uma
skill.** Responder as mesmas dúvidas de cliente. Montar o relatório mensal. Escrever a
descrição de um produto novo no seu padrão.

O caminho mais rápido não é escrever o arquivo na mão. É pedir:

> "quero criar uma skill que [descreva o processo]. Ela precisa receber [entrada] e entregar
> [saída], seguindo essas regras: [suas regras]. Monta o arquivo SKILL.md pra mim."

Você recebe o arquivo pronto, testa, ajusta e sobe. Use os três arquivos desse kit como
referência de estrutura — eles seguem o mesmo padrão: o que faz, como usar, regras, formato de
entrega e checklist.

---

## 9. Teste, ajuste, repita

A primeira versão raramente é a definitiva, e não precisa ser.

Use por uma semana. Observe onde trava, onde soa genérico, onde você editou o resultado antes de
publicar. Cada uma dessas edições é uma regra que faltava no arquivo. Volte e escreva ela.

Skill boa é skill que passou por uso real e foi corrigida depois.

---

## Resumo em cinco linhas

1. Use do jeito que veio, umas quatro vezes, e anote o que incomodou
2. Anexe o SKILL.md num chat e peça a mudança, em vez de editar na mão
3. Cole três exemplos do seu texto pra ensinar o tom de voz
4. Troque os nichos de exemplo pelo seu, incluindo o que não falar
5. Adicione na lista "o que evitar" tudo que sair errado e repita por uma semana

---

Esse kit faz parte do **Destrave Seu Conteúdo**.
