# ⚔ Taverna Virtual

Sala virtual de RPG de mesa: dados, chat, fichas, inventário, combate, NPCs, telão e call de voz.

## Estrutura

```
taverna-virtual/
├── index.html     # estrutura da página
├── css/style.css  # estilos
├── js/app.js      # toda a lógica
├── .nojekyll
└── README.md
```

## Como rodar localmente

Abra o `index.html` no navegador (ou use `python3 -m http.server` na pasta).

## Observação importante

O modo **"Ao vivo"** (sincronização entre jogadores) depende do ambiente do Claude (`window.claude`).
Fora dele, o site funciona em **modo local**: os dados ficam salvos só no navegador de cada pessoa.
