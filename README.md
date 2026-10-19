# Gerador de Certificados — GitHub Pages

## Publicar

1. Crie um repositório no GitHub e envie **todo o conteúdo desta pasta** para a raiz do repositório.
2. Abra **Settings → Pages → Build and deployment → Deploy from a branch**, escolha `main` e `/ (root)` e salve.
3. Abra o endereço informado pelo GitHub Pages (geralmente `https://USUARIO.github.io/REPOSITORIO/`).

## Atualizar os modelos

Substitua **`modelos.json`** na raiz do repositório. Ao atualizar a página, os modelos são carregados novamente do JSON publicado. Aguarde o deploy do GitHub Pages (pode demorar alguns minutos).

Alterações feitas na interface ficam apenas no armazenamento do navegador. Para publicá-las para todos, clique **Exportar backup**, renomeie o arquivo baixado para **`modelos.json`** e substitua o arquivo no repositório.

## Atenção à privacidade

**O GitHub Pages é público.** O JSON original inclui cadastros de empresas/CNPJs e imagens embutidas. Remova do JSON qualquer informação que não deva ser publicada antes de subir o repositório. Não inclua CPFs ou dados pessoais de colaboradores no JSON público.

## Observações

A geração de PDFs ocorre no navegador. O arquivo `ClearSans-Light.ttf` está incluído; a fonte Carelia é carregada do backup JSON original. Abra pelo endereço do GitHub Pages, não clicando no arquivo `index.html` local (o carregamento de JSON usa `fetch`).
