# TSA Materiais & Metalurgia — publicação na Netlify

Esta pasta contém os arquivos do site TSA para substituir o conteúdo do repositório `guilhermetsa2024/engenhariarefrataria`.

- **Página inicial:** `index.html`.
- **Curso original de Engenharia de Refratários:** `cursos/engenharia-refratarios/index.html`.
- **Comparador de campanhas TSA:** `calculadora/index.html`.
- **Calculadora original preservada:** `calculadora/vida-revestimento/index.html`.
- **Análise de curvas:** `analise-curvas/index.html`.
- **Treinamentos:** `treinamentos/`.
- **Imagens e logotipos:** `assets/`.

## Como publicar com segurança

1. Confirme que o ZIP de backup do repositório foi guardado em local seguro.
2. Preferencialmente, crie uma branch de teste no GitHub antes de alterar `main`.
3. Substitua os arquivos do repositório pelo conteúdo **interno** desta pasta (não envie a pasta `TSA_PRONTA_PARA_GITHUB` como subpasta).
4. Confirme que `index.html` está na raiz do repositório e que a Netlify publica essa raiz.
5. Verifique a prévia de deploy e as páginas/links antes de promover para produção.
6. A Netlify está conectada ao GitHub e pode iniciar um novo deploy ao receber um commit na branch de produção.

**Importante:** não envie o HTML de prévia portátil como `index.html` do site; ele é apenas um visualizador.

**Atenção:** recursos externos (por exemplo, imagem de alto-forno hospedada em outro domínio e serviços de contato) dependem de acesso à internet e dos respectivos provedores.
