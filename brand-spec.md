# Brand Spec — Entre Eixos

> Fonte: `assets.md` (direção visual oficial do cliente). Sistema derivado para a landing page.

## Conceito em uma frase

Marca de **conhecimento clínico editorial**: ciência sem aparência hospitalar, estética sem aparência superficial, anatomia sem excesso de literalidade — "Um corpo. Múltiplos sistemas. Infinitas conexões."

## Tokens (OKLch, derivados do hex oficial)

| Token | Valor OKLch | Hex de origem | Uso |
|---|---|---|---|
| `--bg` | `oklch(0.966 0.026 94)` | `#F7F5F0` | Marfim — canvas principal |
| `--surface` | `oklch(0.992 0.010 90)` | `#FFFFFF` | Cartões / faixas elevadas |
| `--fg` | `oklch(0.133 0.021 155)` | `#202321` | Grafite — texto principal (12.2:1) |
| `--muted` | `oklch(0.287 0.050 161)` | derivado de `#91A49A` | Texto secundário/capitão (4.85:1) |
| `--border` | `oklch(0.84 0.09 82)` | `#D8CBB9` | Bege areia — hairlines estruturais |
| `--accent` | `oklch(0.284 0.118 168)` | `#30483F` | Verde profundo — ação e ênfase (4.5:1+ em texto) |
| `--salvia` | `oklch(0.656 0.09 161)` | `#91A49A` | Detalhes/ilustração (nunca texto pequeno) |
| `--gold` | `oklch(0.675 0.237 86)` | `#B7A27A` | Dourado discreto — linhas finas, divisores, ornamentos |

Estados derivados (via `oklch()`): `--accent-hover` = L +0.08; `--accent-soft` = accent com alfa; `--bg-deep` = verde profundo como faixa escura (`oklch(0.21 0.05 165)`).

## Tipografia

- **Display:** `"Marcellus", Georgia, "Times New Roman", serif` — um único peso elegante, serif de traço fino, usado em títulos e no lockup da marca.
- **Body:** `"Jost", system-ui, -apple-system, "Segoe UI", sans-serif` — geométrico, europeu, usado em texto corrido, labels e botões.
- Máximo 2 famílias no artefato. Labels em ALL CAPS com tracking ≥ 0.06em; display ≥ 32px com tracking negativo leve (-0.01 a -0.02em).

## Regras observadas da direção de arte

1. Sistema visual girando em torno de: **eixos, conexões, caixas, drops, descoberta**.
2. Anatomia estilizada e minimista — linhas finas conectando pontos, diagramas de traço fino, nunca anatomia literal de livro.
3. Texturas de papel/vidro/tecido em baixa opacidade como profundidade, nunca protagonistas.
4. Muito espaço negativo; iluminação editorial suave; "premium sem luxuosa demais".
5. Um accent funcional (verde profundo) no máximo 2× por tela; dourado apenas como detalhe decorativo.
6. Ícones lineares de traço fino (≈1.6px), nunca emoji.
7. Voz: clínica, precisa, sofisticada; microcopy como "marca de conhecimento", não "loja de aulas".