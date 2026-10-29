# auditoria visual e de animações

## Escopo

Auditoria automatizada de formatos, dimensões, quadros, durações de origem, integridade dos arquivos, referências locais e sintaxe. A verificação automatizada não substitui reprodução visual em navegadores reais.

## Melhorias aplicadas

- `banner-dragoes.gif` convertido para `banner-dragoes.webp`: 64 quadros, duração original total de 1280 ms, 382 KB → 219 KB (43% menor). Igualdade exata entre primeiro e último quadro após conversão: sim.
- `banner-final.gif` convertido para `banner-final.webp`: 48 quadros, duração original total de 960 ms, 2123 KB → 1115 KB (47% menor). Igualdade exata entre primeiro e último quadro após conversão: sim.
- `banner-principal.gif` convertido para `banner-principal.webp`: 48 quadros, duração original total de 960 ms, 2469 KB → 1270 KB (49% menor). Igualdade exata entre primeiro e último quadro após conversão: sim.
- `castelo-lua-sangrenta.gif` convertido para `castelo-lua-sangrenta.webp`: 48 quadros, duração original total de 960 ms, 1039 KB → 639 KB (38% menor). Igualdade exata entre primeiro e último quadro após conversão: sim.
- `dragao-escarlate.gif` convertido para `dragao-escarlate.webp`: 48 quadros, duração original total de 960 ms, 822 KB → 459 KB (44% menor). Igualdade exata entre primeiro e último quadro após conversão: sim.

GIFs pequenos foram mantidos quando WebP aumentava o tamanho. As animações convertidas preservam dimensões e número de quadros; a compressão WebP usa qualidade 82 e pode alterar detalhes finos. A duração deve ser conferida em reprodução real antes da publicação.

## Verificações antes de publicar

- [ ] Reproduzir as animações no Chrome Android e em desktop.
- [ ] Conferir nitidez de textos e contornos após compressão.
- [ ] Confirmar comportamento com `prefers-reduced-motion`.
- [ ] Validar o endereço final no GitHub Pages.
