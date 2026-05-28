# Episódio Emocional

> Uma ferramenta interativa de autoconhecimento para mapear, compreender e ressignificar episódios emocionais.

**Criado por [Karina Drvale](https://github.com/karinadrvale-cmd)**

---

## O que é

O **Episódio Emocional** é um guia reflexivo em formato de jornada — um formulário em 6 etapas que conduz a pessoa pelo processo de análise de uma situação emocional vivida. Ao final, gera automaticamente um **mapa visual** das conexões entre o gatilho, o padrão emocional e o comportamento.

A ferramenta é inteiramente **client-side**: roda no navegador, sem servidor, sem banco de dados, sem login. Tudo fica local.

---

## Como usar

1. Abra o arquivo `index.html` no navegador — ou acesse via GitHub Pages
2. Clique em **"Começar minha jornada"**
3. Preencha as 6 etapas com calma e honestidade
4. Clique em **"Concluir jornada"** para ver o resumo completo e o mapa do seu episódio

---

## As 6 etapas

| Etapa | Nome | O que é registrado |
|-------|------|--------------------|
| 1 | **Situação** | Condição anterior, Evento objetivo e Gatilho interno |
| 2 | **Padrão Automático** | Base de dados emocional-comportamental (padrões que se repetem) |
| 3 | **Emoções & Reações** | Emoção primária, nuances, intensidade, mudanças físicas e psicológicas |
| 4 | **Ações** | Como você reagiu e se foi uma ação construtiva ou destrutiva |
| 5 | **Reestruturação** | Nova perspectiva sobre o pensamento automático + condição posterior |
| 6 | **Insight** | O que você leva dessa experiência |

---

## Sobre o Gatilho

> **Evento** → o fato externo, objetivo, observável.
> **Gatilho** → o que aquele evento *tocou* internamente: o significado imediato, o medo ativado, a memória despertada ou a crença confirmada.

O mesmo evento pode não disparar nada em outra pessoa. O gatilho é pessoal — ele existe na interseção entre o evento e a sua história emocional. Por isso os dois campos são distintos no formulário e no mapa.

---

## Funcionalidades

- **Jornada guiada em 6 etapas** com transições suaves e barra de progresso
- **Chips de emoção primária** com ramificações de nuances (Alegria, Medo, Tristeza, Raiva, Nojo, Surpresa)
- **Slider de intensidade emocional** (0–10)
- **Padrões automáticos** selecionáveis + campo livre
- **Mapa mental SVG** gerado dinamicamente ao final, com:
  - 5 colunas de análise (Condição Anterior → Evento/Gatilho → Estado Emocional → Ações → Condição Posterior)
  - Período refratário destacado
  - Loop de feedback (ciclo de condicionamento)
  - Nós clicáveis que abrem o texto completo em popup
- **Cards de resumo** com prévia do texto e modal para leitura completa
- **Modal expansível** em todos os nós do mapa e cards de resumo
- Totalmente **responsivo** (mobile e desktop)
- **Zero dependências externas** — apenas Google Fonts

---

## Estrutura do projeto

```
episodio-emocional/
├── index.html      ← aplicação completa (HTML + CSS + JS em um único arquivo)
└── README.md
```

Toda a lógica, estilo e interatividade estão contidos em `index.html`. Não há dependências de build, npm ou frameworks.

---

## Tecnologias

- **HTML5** semântico
- **CSS3** — variáveis, animações, backdrop-filter, line-clamp
- **JavaScript** vanilla — sem frameworks
- **SVG** gerado dinamicamente via JS para o mapa mental
- **Google Fonts** — Fraunces (serif) + DM Sans (sans-serif)

---

## Deploy via GitHub Pages

1. Vá em **Settings → Pages** no seu repositório
2. Em *Source*, selecione a branch `main` e a pasta `/ (root)`
3. Salve — em alguns minutos o site estará disponível em:

```
https://<seu-usuario>.github.io/<nome-do-repositorio>/
```

---

## Licença

Uso pessoal e educacional livre. Para uso comercial, entre em contato com a autora.

---

*Criado com cuidado por Karina Drvale · 2025*
