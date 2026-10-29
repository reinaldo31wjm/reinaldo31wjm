# Auditoria técnica do repositório

## Escopo

Foram examinados todos os arquivos do pacote: HTML, CSS embutido, JavaScript, Markdown, SVG, PNG, GIF, WebP e workflow do GitHub Actions. O pacote final contém 42 arquivos, incluindo documentação e recursos visuais; pastas não entram nessa contagem.

## Verificações automatizadas

- Todos os nomes de arquivos estão em minúsculas.
- Referências locais de HTML/CSS e links relativos em Markdown conferidos.
- IDs duplicados e âncoras internas ausentes verificados.
- JavaScript inline validado com `node --check`.
- HTML analisado com o parser da biblioteca padrão.
- PNG, GIF e WebP abertos pelo decodificador; dimensões e número de quadros inspecionados.
- SVGs analisados como XML.
- Integridade do arquivo ZIP verificada.
- Workflow de contribuições revisado quanto à estrutura e permissões declaradas.
- Arquivo de banner duplicado removido; o README agora reutiliza `imgs/banner-reino.webp`.
- Documentação de desempenho corrigida para refletir os formatos, dimensões e pesos reais dos arquivos.

## Resultado

As verificações locais executadas nesta revisão não encontraram referências locais ausentes, IDs duplicados, âncoras internas quebradas, links relativos de Markdown ausentes, imagens ilegíveis ou SVGs com XML inválido. O JavaScript passou na verificação sintática e o ZIP final passou no teste de integridade.

## Limites

Esta auditoria não confirma que serviços externos estejam disponíveis, que o GitHub Pages tenha concluído um deploy, que o workflow remoto execute com sucesso, nem mede FPS ou acessibilidade em leitores de tela. Esses pontos exigem testes reais após publicação.
