# Estratégia de conteúdo por estágio

Skill para o Claude que monta a estratégia de conteúdo de um perfil de marca pessoal (Instagram, TikTok, LinkedIn):

- descobre o **estágio** do perfil e a proporção certa entre **o que você fala, o que você faz e quem você é**;
- distribui os posts entre as **4 relações**: descoberta, autoridade, relacionamento e negócio;
- entrega o **calendário do mês** já com tema, formato e o que medir em cada post;
- revisa cada post pelo **checklist do post que é enviado** (7 perguntas);
- lê os números do mês e diz o que ganha mais espaço no seguinte.

## Como instalar

### No Claude Code

```
/plugin marketplace add raulsaint/estrategia-de-conteudo
/plugin install estrategia-de-conteudo@estrategia-de-conteudo
```

### No claude.ai (site ou app)

1. Baixe o arquivo [`estrategia-de-conteudo.zip`](estrategia-de-conteudo.zip) deste repositório.
2. No claude.ai, abra **Configurações → Capacidades → Skills** e envie o arquivo.

## Como usar

Abra uma conversa e peça, por exemplo:

- "Monta o calendário de conteúdo do meu perfil para este mês."
- "Analisa meus últimos posts e me diz o que está desequilibrado."
- "Revisa este post antes de eu publicar." (cole o texto ou a capa)

Na primeira vez, o Claude faz algumas perguntas sobre você, o seu público e o seu trabalho. Responda com calma: o plano sai a partir disso.

## O que tem aqui

```
skills/estrategia-de-conteudo/
├── SKILL.md                     passo a passo que o Claude segue
└── referencias/
    ├── metodo.md                as 4 relações, as 3 fontes, proporção por estágio, métricas
    ├── checklist-envio.md       as 7 perguntas do post que é enviado e a métrica de envios
    └── exemplo.md               um plano de mês pronto (perfil fictício)
```
