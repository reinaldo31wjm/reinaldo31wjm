# Acabamento final e publicação

## O que foi ajustado

- Navegação mobile volta a exibir os links das seções em duas linhas, com espaçamento adaptado a telas estreitas.
- Margem de rolagem maior no celular para que títulos não fiquem escondidos sob a barra fixa.
- Abertura cinematográfica pode ser fechada com `Escape`, além do botão de pular.
- Metadados Open Graph, Twitter Card e URL canônica para melhorar a prévia ao compartilhar o site.
- Favicon SVG próprio com a identidade REI.
- Redução de efeitos decorativos no modo de movimento reduzido.
- Recuperação e inclusão dos arquivos de imagem usados pela página, além de validação de caminhos locais.

## Publicar no GitHub Pages

1. Faça backup do repositório antes de substituir arquivos.
2. Copie o conteúdo desta pasta para a raiz de `reinaldo31wjm/reinaldo31wjm`, mantendo os diretórios `.github/` já existentes.
3. Confirme que `index.html` e a pasta `imgs/` ficaram na raiz.
4. No GitHub, abra **Settings → Pages** e selecione a branch `main` e a pasta `/(root)` se ainda não estiver configurado.
5. Aguarde o deploy terminar e abra `https://reinaldo31wjm.github.io/reinaldo31wjm/`.
6. Faça uma atualização forçada no navegador para evitar cache da versão anterior.

## Testes manuais recomendados

- [ ] Celular estreito: todos os links de navegação estão acessíveis.
- [ ] Teclado: Tab, Enter, Escape e foco visível funcionam.
- [ ] Ativar a opção `Efeitos: ON/OFF`.
- [ ] Ativar a preferência de sistema `Reduzir movimento`.
- [ ] Verificar se banner, avatar, favicon e imagens do README carregam depois do deploy.
- [ ] Conferir links externos e a prévia ao compartilhar a URL.

**Limite da validação:** os testes automatizados de arquivos e sintaxe não substituem uma conferência em navegadores reais. FPS, acessibilidade com leitor de tela e desempenho em dispositivos físicos ainda precisam ser verificados após a publicação.
