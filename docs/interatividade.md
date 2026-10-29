# Interatividade avançada

O site REI usa interações discretas sem bibliotecas externas:

- Inclinação 3D suave em cartões de habilidades e crônicas, apenas com cursor preciso.
- Reflexo de luz que acompanha o cursor dentro dos cartões.
- Resposta magnética leve nos botões principais em telas maiores.
- Indicação da seção atual na navegação.
- Compatibilidade com teclado (`tabindex`, `focus-visible`) e respeito a `prefers-reduced-motion`.
- Em dispositivos móveis, os cartões permanecem estáveis para evitar movimentos artificiais e custos de renderização.

## Teste

1. Abra `index.html` num navegador atualizado.
2. Mova o cursor sobre os cartões e os botões.
3. Navegue pelas seções e observe o item ativo no menu.
4. Teste com Tab e Shift+Tab.
5. Ative a opção **Efeitos: OFF** e confirme que os efeitos de ambiente param.
6. Teste numa tela estreita e com a preferência de sistema por movimento reduzido.

A validação automatizada de sintaxe não substitui os testes visuais em navegadores reais.
