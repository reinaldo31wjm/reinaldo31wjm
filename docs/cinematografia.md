# Cinematografia

A experiência REI combina uma abertura de marca, névoa em camadas, passagem de luz discreta e movimento atmosférico suave.

## Recursos

- Abertura com a marca REI, filete dourado e texto curto.
- Botão **Pular abertura** e tecla `Escape` para entrar diretamente no site.
- A abertura aparece uma vez por sessão; há alternativa caso o navegador bloqueie `sessionStorage`.
- Névoa animada em camadas, com deslocamento lento.
- Passagem de luz em ciclo longo para evitar flashes ou cortes bruscos.
- O controle de efeitos pausa as animações decorativas principais.
- A preferência `prefers-reduced-motion` desativa a abertura e reduz o movimento.
- Efeitos secundários são reduzidos em telas pequenas e em economia de dados.

## Arquivos

- `index.html` — página, estilos e comportamento.
- `docs/cinematografia.md` — este guia.
- `docs/identidade-visual.md` — paleta, tipografia e direção de arte.

## Teste recomendado

1. Abra `index.html` em um navegador atualizado.
2. Confirme que a abertura desaparece automaticamente após cerca de 2,8 segundos.
3. Teste o botão **Pular abertura** e a tecla `Escape`.
4. Recarregue a página na mesma sessão e confirme que a abertura não reaparece.
5. Ative/desative **Efeitos** e confira a névoa e as partículas.
6. Teste no celular e com a preferência de sistema por movimento reduzido.

A sintaxe do JavaScript pode ser verificada com `node --check`. A aparência e a acessibilidade final ainda precisam de testes em navegadores reais.
