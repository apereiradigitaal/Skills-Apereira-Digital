---
name: roteiro-pauta-quente
description: "Pesquisa as pautas mais quentes e em alta do nicho do usuário na web, seleciona a melhor oportunidade de conteúdo e transforma em um roteiro completo pronto para gravar, entregue como arquivo .docx profissional. Use esta skill sempre que alguém pedir para buscar tendências de conteúdo, encontrar pautas em alta, descobrir o que está bombando no nicho, criar conteúdo baseado em tendências, fazer roteiro sobre assunto do momento, transformar trend em vídeo, ou pedir ideias de conteúdo atualizadas. Também aciona quando mencionarem 'pauta quente', 'trend do momento', 'o que tá em alta', 'conteúdo do dia', 'roteiro baseado em tendência', 'o que tá bombando', 'pautas trending', 'conteúdo viral', ou qualquer pedido que combine buscar tendências atuais + criar roteiro pronto para gravar. Funciona para qualquer nicho de conteúdo digital: marketing, tecnologia, IA, negócios, saúde, educação, lifestyle, etc."
---

# Roteiro Pauta Quente — Da Tendência ao Roteiro em Minutos

## O que esta skill faz

Você diz o seu nicho. Ela pesquisa na web o que está em alta agora, te mostra as 3 a 5
melhores oportunidades de conteúdo ranqueadas, e transforma a que você escolher num roteiro
completo — com a fala escrita do primeiro ao último segundo — entregue em .docx.

O problema que ela resolve: o branco de "não sei sobre o que postar hoje". Em vez de você
garimpar tendência e depois escrever roteiro, as duas etapas viram um pedido só.

**Entrada:** um nicho.
**Saída:** um arquivo .docx com hook, roteiro falado, legenda, hashtags e dicas de gravação.

### O caminho completo

1. Pesquisa tendências atuais do nicho usando busca na web
2. Filtra e ranqueia as pautas por potencial de viralização
3. Mostra as opções e você escolhe
4. Transforma a escolhida num roteiro scriptado, com hook e CTA
5. Entrega como .docx formatado, pronto pra ler no celular enquanto grava

---

## Fluxo de trabalho

### Passo 1 — Entender o nicho

Se o usuário não informou o nicho, perguntar de forma direta:

> "qual é o seu nicho de conteúdo? (ex: marketing digital, IA, fitness, culinária...)"

Se já informou, seguir direto pra pesquisa.

Informações úteis, mas não obrigatórias:

- Nicho específico (ex: "marketing para e-commerce" em vez de só "marketing")
- Plataforma principal (Instagram, TikTok, YouTube — default: Instagram)
- Tom de voz preferido (informal, profissional, divertido — default: informal e acessível)

Não travar o fluxo pedindo muita informação. Se tem o nicho, já pode rodar.

### Passo 2 — Pesquisar tendências

Usar busca na web. Fazer pelo menos 3 ou 4 buscas variadas:

1. `[nicho] tendências [mês atual] [ano]` — o que está em alta agora
2. `[nicho] polêmica OU novidade OU atualização` — assuntos que geram debate
3. `[nicho] Instagram OU TikTok viral` — o que está performando nas redes
4. `[nicho] news` ou termos do nicho em inglês — tendências globais antes de chegarem ao Brasil

**Fontes de qualidade:** portais de notícia do nicho, threads virais, newsletters
especializadas, Google Trends, lançamentos recentes de ferramentas e produtos.

### Passo 3 — Filtrar e ranquear

Selecionar 3 a 5 pautas e ranquear por estes critérios:

| Critério | Peso | O que avaliar |
|---|---|---|
| Timing | Alto | É novidade? Está no pico de atenção? |
| Potencial de opinião | Alto | Dá pra dar um ângulo próprio? Gera debate? |
| Relevância pro público | Alto | O público do nicho se importa com isso? |
| Facilidade de produção | Médio | Dá pra gravar rápido, sem muita produção? |
| Potencial de viralização | Médio | Tem curiosidade, polêmica ou surpresa? |

Apresentar as pautas ranqueadas:

```
🔥 pautas quentes do momento para [nicho]:

1. [pauta] — ⭐ potencial muito alto
   por que: [explicação em 1 linha]

2. [pauta] — ⭐ potencial alto
   por que: [explicação em 1 linha]

3. [pauta] — ⭐ potencial médio-alto
   por que: [explicação em 1 linha]

💎 minha recomendação: a pauta #1 porque [razão estratégica].

quer que eu crie o roteiro da #1 ou prefere outra?
```

Se o usuário quiser ir rápido ("tanto faz, faz o melhor"), criar direto o roteiro da
pauta #1 sem esperar confirmação.

### Passo 4 — Criar o roteiro

O roteiro precisa ser scriptado: falas escritas por extenso, não tópicos. Estrutura:

```
🎬 ROTEIRO: [título do vídeo]

📌 Pauta: [qual tendência está sendo abordada]
🎯 Ângulo: [qual o posicionamento/opinião sobre o tema]
⏱️ Duração estimada: [X segundos]
📱 Formato: reels / tiktok / stories

═══════════════════════════════════════════

📱 TELA INICIAL (copy que aparece na tela):
[frase impactante, máximo 2 linhas, lowercase]

═══════════════════════════════════════════

🎤 ROTEIRO COMPLETO:

[ABERTURA — hook falado, 3-5 segundos]
"[fala exata]"

[CONTEXTO — situar o espectador, 5-10 segundos]
"[fala exata]"

[DESENVOLVIMENTO — conteúdo principal, opinião, demonstração]
"[fala exata]"

[se aplicável: CORTA PRA TELA / DEMONSTRAÇÃO]
[narração durante a demonstração]

[VOLTA PRO APRESENTADOR]

[FECHAMENTO + CTA — 5-10 segundos]
"[fala exata com CTA claro]"

═══════════════════════════════════════════

📝 LEGENDA:
[legenda curta e direta para o post]

#️⃣ HASHTAGS:
[hashtags relevantes ao tema e nicho]

═══════════════════════════════════════════

💡 DICAS DE GRAVAÇÃO:
- [dica sobre enquadramento, ritmo ou edição]
- [dica sobre o melhor momento de publicar]
- [dica sobre como maximizar o alcance desse conteúdo]
```

### Passo 5 — Gerar o .docx

Criar o roteiro como arquivo .docx usando a biblioteca `docx` (Node.js).

```bash
npm install docx
```

Criar o script Node.js que monta o documento e salvar o arquivo na pasta de saída.

O documento precisa ter:

- Título estilizado no topo
- Seções bem divididas, com headings
- Formatação limpa e legível no celular (muita gente lê o roteiro no telefone enquanto grava)
- Corpo entre 12 e 14pt
- Espaçamento generoso entre as seções

---

## Regras de qualidade do roteiro

### Tom de voz

- Natural e conversacional, como se estivesse falando — não lendo
- Adaptar ao tom que o criador usa, se ele informou; senão, informal e acessível
- Sem jargão técnico sem explicação
- Frases curtas e diretas: lembre que é pra ser FALADO

### Sobre a pauta quente

- A pauta precisa ser atual: última semana, no máximo último mês
- Se não encontrar nada realmente quente, ser honesto e sugerir uma pauta evergreen com
  ângulo atual
- Sempre dar um ângulo ou opinião — não é notícia, é conteúdo com posicionamento
- Conectar a pauta com algo prático pro público ("e o que isso significa pra você que...")

### Sobre o hook

- É a parte mais importante do roteiro
- Precisa funcionar como texto na tela e como fala
- Gerar curiosidade ou espanto nos primeiros 3 segundos
- Em lowercase (padrão Instagram)

### Sobre o CTA

- Sempre incluir um CTA claro no final
- Sugerir uma palavra-chave de comentário ligada ao tema
- Pedir pra salvar e seguir
- Ser específico: "comenta [PALAVRA] que eu te mando [algo de valor]"

---

## Identidade visual do .docx

Formatação neutra, pronta pra qualquer pessoa usar:

```
Fundo da capa / faixas:  #292929
Texto principal:         #f4f4f4 sobre fundo escuro, #292929 sobre fundo claro
Texto secundário:        #e0dbd7
Destaque de títulos:     #f1dd80
Fonte:                   Arial (corpo 12-14pt, títulos 18-24pt)
```

Sem logo e sem marca d'água. Se quem usa tiver a própria identidade visual, é só trocar
as cores acima pelas da marca dela.

---

## Como adaptar esta skill pro seu negócio

### O caminho mais rápido: peça pro Claude editar

Você não precisa mexer no arquivo na mão.

1. Descompacte o `.zip` e arraste o `SKILL.md` para uma conversa com o Claude
2. Diga o que te incomodou, com exemplo do que saiu errado e de como você queria
3. Entregue o seu contexto de uma vez: nicho, vocabulário do seu público e o que você nunca fala
4. Termine com "me devolve o SKILL.md completo, em arquivo, mantendo o cabeçalho igual"
5. Suba a nova versão em Configurações, Personalizar, Habilidades, Adicionar, Fazer upload de habilidade
6. Teste num caso real e volte no mesmo chat pra pedir o próximo ajuste

Pedir "melhora essa skill" não funciona: o Claude não sabe o que é melhor pra você. Diga o que
saiu errado e como você queria que fosse.

### Ou edite você mesma

1. **Fixe o seu nicho.** No Passo 1, troque a pergunta "qual é o seu nicho?" por uma linha
   dizendo o seu. A skill deixa de perguntar e já vai direto pra pesquisa.
2. **Troque as fontes de pesquisa.** No Passo 2, liste os portais, perfis e newsletters que
   você realmente acompanha. A pesquisa fica muito mais precisa que uma busca genérica.
3. **Ajuste os critérios de ranqueamento.** Se o seu conteúdo não vive de polêmica, baixe o
   peso de "potencial de opinião" e suba o de "relevância pro público".
4. **Ensine o seu formato de roteiro.** Se você já grava num formato próprio, substitua o
   bloco do Passo 4 pela sua estrutura. É a mudança que gera mais diferença no resultado.
5. **Fixe o seu CTA.** Se você sempre usa a mesma chamada final, escreva ela na seção
   "Sobre o CTA" e a skill para de inventar CTA novo a cada roteiro.
6. **Mude o formato de entrega.** Não quer .docx? Troque o Passo 5 por "entregar o roteiro
   direto no chat" ou por PDF.

---

## Checklist de qualidade

Antes de entregar:

- [ ] A pauta é realmente atual e relevante?
- [ ] O hook gera curiosidade nos primeiros 3 segundos?
- [ ] O roteiro está scriptado (falas completas, não tópicos)?
- [ ] O tom é natural e parece fala, não texto?
- [ ] Tem CTA claro com palavra-chave para comentário?
- [ ] A legenda é curta e direta?
- [ ] O .docx está formatado, em Arial e legível no celular?
- [ ] O conteúdo tem um ângulo próprio (não é só notícia)?
- [ ] A duração estimada é realista para o formato?
