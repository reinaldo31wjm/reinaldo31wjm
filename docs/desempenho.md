# Desempenho e carregamento inteligente

## Ajustes presentes nesta versão

- O banner principal é uma imagem WebP estática de 2048 × 684 px (180.736 bytes); isso evita decodificar um GIF grande no primeiro carregamento.
- O avatar é um WebP animado de 260 × 220 px (170.700 bytes, 24 quadros). Há um poster estático para quem prefere movimento reduzido.
- O banner também tem um poster estático de 1600 × 534 px, usado em preferência por movimento reduzido e em economia de dados.
- O carregamento prioritário do banner respeita a preferência de movimento do sistema.
- A quantidade de partículas é reduzida para 8 em telas pequenas/economia de dados e 18 em telas maiores.
- Animações decorativas são pausadas quando a aba fica em segundo plano.
- `content-visibility: auto` reduz o trabalho de renderização das seções abaixo da primeira dobra.
- A textura de fundo é feita com gradientes CSS, sem dependência de biblioteca externa.
- A barra superior evita o efeito de desfoque em telas pequenas para reduzir custo de renderização.

## Arquivos relevantes

- `index.html`: página, estilos, interatividade e regras de desempenho.
- `imgs/banner-reino.webp`: banner principal estático.
- `imgs/banner-reino-poster.webp`: alternativa estática mais leve para movimento reduzido/economia de dados.
- `imgs/avatar-cavaleiro.webp`: avatar animado.
- `imgs/avatar-cavaleiro-poster.webp`: alternativa estática do avatar.

## Validação realizada

- JavaScript inline validado com `node --check`.
- HTML analisado com o parser da biblioteca padrão do Python.
- Referências locais, IDs e âncoras internas verificados.
- Imagens rasterizadas abertas com o decodificador Pillow; dimensões e quadros registrados.
- SVGs analisados como XML.
- Links relativos do Markdown verificados.
- Integridade do ZIP conferida após a geração.

## Antes de publicar

A validação automatizada não mede FPS nem substitui testes em navegadores e dispositivos reais. Depois de publicar, confira abertura, rolagem, navegação por teclado, preferência de movimento reduzido, economia de dados e console do navegador em celular e computador.
