# Como publicar as demos no GitHub Pages

1. No GitHub, crie um repositório **público** novo. Sugestão de nome: `demos`.
2. Clique em "uploading an existing file" e arraste TODO o conteúdo desta pasta
   (index.html, as pastas ferrugem, boteco e agenda, e o arquivo .nojekyll).
   Se o .nojekyll não aparecer no seu explorador de arquivos, ele é um arquivo oculto: pode pular, não é obrigatório.
   Clique em "Commit changes".
3. Vá em Settings > Pages. Em "Build and deployment", escolha "Deploy from a branch",
   branch `main`, pasta `/ (root)`, e salve.
4. Espere 1 a 2 minutos. O endereço fica: https://SEU-USUARIO.github.io/demos/
   As demos ficam em /ferrugem/, /boteco/ e /agenda/.
5. Abra o endereço no celular e teste as três demos antes de mandar para alguém.

## Antes de divulgar
- Abra `index.html` e troque [seu nome] e [seu número] na caixa de contato.
- As páginas têm `noindex`, então não aparecem no Google. Quem tem o link consegue abrir.
- Para atualizar uma demo, edite o arquivo no GitHub e faça commit. O site atualiza sozinho em 1 a 2 minutos.

## Depois (opcional)
- Domínio próprio: registre um .com.br no Registro.br e aponte para o GitHub Pages em Settings > Pages > Custom domain.
