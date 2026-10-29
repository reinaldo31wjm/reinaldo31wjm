# Otimização cinematográfica — REI

A experiência combina uma identidade medieval sombria com texto curto, movimento discreto e carregamento consciente.

## Direção visual

- Paleta carvão, vermelho escarlate e ouro envelhecido.
- Títulos grandes e composição com espaço negativo.
- Cavaleiro e cenário como foco; textos breves para não competir com a arte.
- Linguagem visual coerente entre a página e o README.

## Cinematografia

- Entrada escalonada do título e das chamadas principais.
- Camadas de sombra, vinheta e brilho vermelho para profundidade.
- Movimento atmosférico suave e partículas de brasas ascendentes.
- Revelação de conteúdo durante a rolagem e indicador de progresso.
- Respeito à preferência `prefers-reduced-motion`.

## Interação

- Botão para ligar/desligar efeitos sem recarregar a página.
- Brilho ambiente e parallax discreto em computadores compatíveis.
- Cartões com resposta visual e foco de teclado visível.
- Links para os repositórios do GitHub.

## Desempenho, acessibilidade e responsividade

- Banner principal em WebP estático de 2048 × 684 px; o poster alternativo tem 1600 × 534 px.
- Avatar em WebP animado de 260 × 220 px com 24 quadros, além de poster estático.
- Pré-carregamento do banner, decodificação assíncrona e carregamento tardio do avatar.
- Menos partículas em telas pequenas/economia de dados e pausa das animações em abas ocultas.
- Link para pular ao conteúdo, foco visível, textos alternativos e suporte a `prefers-reduced-motion`.
- Metadados de compartilhamento e idioma `pt-BR`.

## Publicação

1. Faça backup do repositório antes de substituir arquivos.
2. Envie o conteúdo deste pacote para a raiz de `reinaldo31wjm/reinaldo31wjm`.
3. Confirme que `index.html`, `readme.md`, `imgs/` e `.github/` estão na raiz.
4. Ative GitHub Pages em **Settings → Pages → Deploy from a branch → `main` → `/ (root)`**.
5. Teste a página em celular e desktop; confira navegação, links, efeitos ON/OFF e teclado.
6. Se publicar em outro caminho ou domínio, revise a URL canônica e os links.

## Critérios de pronto

- Sem dependências externas obrigatórias para a página.
- Conteúdo legível em telas pequenas.
- Interações acessíveis por teclado.
- Efeitos respeitam a preferência de movimento reduzido.
- Banner, avatar, favicon e imagens locais carregam corretamente.
- Página compatível com hospedagem estática no GitHub Pages.

Detalhes de desempenho em `docs/desempenho.md`; revisão final em `docs/acabamento-publicacao.md`.
