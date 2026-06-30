# 🏹 Taba — a resistência dos povos originários

**Taba** é um **RPG idle que roda no navegador** (HTML5, single-file, sem instalar — save em `localStorage`). Tema: a resistência dos povos originários do Brasil contra a colonização, contada em capítulos cronológicos da invasão (1500 → ~1693).

> Protótipo em desenvolvimento aberto. Inspirado na profundidade de progressão do gênero *idle RPG* (à la *TBH: Taskbar Hero*), com história, arte e sistemas próprios.

## ▶️ Como jogar / rodar
1. Clone o repositório.
2. Abra `index.html` no navegador (duplo-clique) **ou** sirva a pasta:
   ```bash
   python -m http.server 8901
   # abra http://localhost:8901
   ```
3. Deixe no **▶ Auto** — o combate é automático (idle). Bata inimigos, evolua heróis, abra baús, explore o Portal das Eras.

É tudo **vanilla JS, single-file** (`index.html`). Sem build, sem dependências de runtime.

## 🎮 O que já tem
- Combate idle em **levas** de inimigos diversos (tipos com vida/defesa/velocidade/alcance próprios — melee avançam e tankam, ranged atiram do fundo).
- 6 heróis (classes do gênero) com **níveis, 36 skills (ativa/passiva/aura), árvore de atributos**, formação melee-frente/ranged-fundo.
- **Itens** com 10 raridades, mods estilo PoE, **sockets + gemas**, **Cube** (síntese/alquimia/decoração/lapidação + nível do Cube), runas, 4 dificuldades, resistências.
- **Narrativa ramificada**: escolhas em cada capítulo movem 2 eixos (postura/união) → **múltiplos finais** + painel Crônica.
- Arte gerada por IA (FLUX/Z-Image + rembg) e **animação procedural** (impacto, telegrafo, FX de poderes, morte).

## 🤝 Quero ajuda com (contribuições bem-vindas)
- **Animação 2D** dos personagens (sprite-sheets / skeletal / rigging a partir da arte estática · juice de combate).
- **Balanceamento** (curvas de XP/dano/economia · calibragem das levas).
- **Sistemas** restantes do roadmap (Cube avançado, soulstones, QoL, mercado).
- **Mobile/UX** e performance.

Abra uma *issue* (pra discutir design, balanceamento, bugs) ou um *PR*. O roadmap e o design detalhado vão sendo publicados aos poucos — por enquanto, o melhor mapa é o próprio `index.html` (comentado) + as issues.

## 🧭 Estrutura
- `index.html` — **o jogo inteiro** (vanilla JS, comentado).
- `arte/out/sprite/` e `arte/out/bg/` — sprites e backgrounds usados pelo jogo (arte gerada por IA).

## ⚖️ Direção de conteúdo
O antagonista é **a invasão colonial**, sempre representado pela **indumentária/equipamento de época** (couraça, arcabuz, caravela, hábito, correntes) — **nunca** por etnia ou caricatura. Entidades mitológicas e fauna levam créditos de origem in-game, com respeito às culturas representadas.

## 🙏 Créditos & propósito
**Propósito pedagógico.** Taba é um projeto **público e educativo** — usa a linguagem do *idle RPG* para divulgar a **história da resistência dos povos originários do Brasil** (1500 → ~1693). Pensado para ser **expansível** (novos capítulos, regiões e fontes históricas).

**Inspiração.** O Taba é uma **homenagem ao gênero** *idle RPG*, com inspiração declarada em **TBH: Taskbar Hero**. A inspiração é de **mecânica e profundidade de progressão** — **toda a arte, história, código e os valores de balanceamento do Taba são originais e próprios**. Este repositório **não distribui** dados, tabelas, textos ou assets de terceiros; números de balanceamento foram desenhados para o Taba. Marcas e jogos citados pertencem aos seus respectivos donos.

---
*Dr. André William Feix · OAB/SC 56.213 · ecossistema Pindorama.*
