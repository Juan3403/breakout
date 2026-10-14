# Breakout

Jogo de quebrar tijolos completo, feito em um único arquivo HTML com canvas. Sem instalação e sem dependências: abra o `index.html` ou jogue online.

**Jogar:** https://juan3403.github.io/breakout/

## Recursos

- **7 modos:** Clássico (15 fases), Infinito, **Frenético** (todo tijolo solta um buff, nunca um ruim), Contra o tempo, Uma vida, Desafio diário e Fase própria.
- **Tijolos especiais:** de 2 de vida, indestrutíveis, explosivos (reação em cadeia), móveis, que se regeneram e com power-up garantido.
- **Chefes** com tiros que mirram na raquete.
- **10 power-ups:** raquete larga, bola lenta, multibola, vida extra, laser, bola de fogo, ímã e escudo, além de dois ruins (raquete estreita e bola rápida).
- **Editor de fases** com compartilhamento por link.
- **2 jogadores** em cooperação.
- **Autoplay:** um bot que joga sozinho, pega power-ups, desvia dos tiros e mira o laser.
- **Velocidade 1x, 2x ou 3x.**
- Níveis de dificuldade, 3 temas (neon, retro e pôr do sol), paleta para daltônicos, ranking top 10, conquistas e suporte a gamepad.
- **PWA:** funciona offline e pode ser instalado.

## Controles

| Ação | Tecla |
|---|---|
| Mover a raquete | ← → ou mouse |
| Lançar a bola / soltar do ímã / atirar | Espaço ou clique |
| Pausar | P |
| Autoplay liga/desliga | T |
| Velocidade 1x → 2x → 3x | V |
| Som liga/desliga | M |
| Voltar | Esc |

No modo 2 jogadores, o jogador 2 usa **A / D** para mover e **W** para o laser.

Partidas em que o autoplay foi usado não entram no recorde, no ranking nem nas conquistas.

## Rodar localmente

Abra o `index.html` no navegador. Para testar o PWA e o service worker, sirva a pasta por HTTP:

```
python -m http.server 8000
```

e acesse http://localhost:8000.
