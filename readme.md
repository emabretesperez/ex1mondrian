# 1exmondrian

Parte 1 - O quadro

O quadro foi desenhado num canvas de 800 x 800 píxeis, com fundo creme.

**Cores usadas (RGB)**

| Elemento | Cor |
|---|---|
| Fundo | `248, 245, 234` |
| Vermelho | `229, 26, 19` |
| Amarelo | `246, 205, 0` |
| Azul | `36, 34, 117` |
| Linhas | `51` (preto/cinzento escuro) |

**Como foi feito**

- Os blocos de cor foram desenhados com `rect(x, y, largura, altura)`, sem contorno (`noStroke()`).
- As linhas pretas foram desenhadas com `line(x1, y1, x2, y2)`, com espessuras diferentes (`strokeWeight(12)` e `strokeWeight(17)`).
- As posições usam `width` e `height` (por exemplo `width/2-33`), para ficarem relativas ao tamanho do canvas.
