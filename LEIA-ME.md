# Site "O Jesus Esquecido? Resposta"

O site é o `index.html` mais a pasta `images/` (147 ilustrações). Os dois precisam ir juntos para o GitHub, na mesma pasta.

## Publicar no GitHub Pages
1. Crie um repositório (por exemplo `jesus-esquecido`) e envie o `index.html` e a pasta `images/` inteira.
2. No repositório: Settings > Pages > Source: "Deploy from a branch", branch `main`, pasta `/ (root)`.
3. O site fica em `https://SEU-USUARIO.github.io/jesus-esquecido/`.
4. Para abrir direto em turco: `.../jesus-esquecido/?lang=tr`. Em português: `?lang=pt`.
   Sem isso, o site abre sempre em turco e no modo escuro (o botão ☀ troca para o modo claro).

## IA
- Já vem configurada: Claude Opus 5.5, esforço alto, com a sua chave.
- Responde com todo o conhecimento teológico e histórico, no seu estilo, e no fim diz se o assunto está no documento (e em que parte).
- O histórico de perguntas fica salvo no aparelho de cada pessoa (botão "Histórico").
- A chave está dentro do `index.html`, dividida em pedaços (procure `AI_CONFIG`). Para trocar a chave, substitua esses pedaços pela chave nova.

## Atualizar o texto
O conteúdo vem dos dois arquivos .txt (PT e TR). Quando mudar o texto, peça para gerar o `index.html` de novo.
