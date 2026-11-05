# Ações Med Center

Portal responsivo para acesso às **31 pastas de ações de 2026** cadastradas no Google Drive, organizadas por mês.

## Recursos
- Meses de março a outubro de 2026.
- Pesquisa por município, mês, período e identificação da pasta.
- Filtro por estado: GO, TO ou MS.
- Acesso direto ao Drive em nova aba.
- Identificação de cópias, produção excedente e pastas com o mesmo nome.
- Funciona sem instalação ou serviços externos: basta abrir `index.html`.

## Colocar o site no ar com GitHub Pages

O arquivo `.github/workflows/deploy.yml` já está configurado para publicar automaticamente.

1. Abra **Settings → Pages** neste repositório.
2. Em **Build and deployment → Source**, selecione **GitHub Actions**.
3. Abra **Actions → Publicar site Ações Med Center**, e execute **Run workflow** caso não tenha iniciado automaticamente.

Depois que a publicação for concluída, o endereço ficará indicado em **Settings → Pages**.

> Importante: o repositório é público. Os links das pastas ficam visíveis no código do site, mas o acesso aos arquivos continua condicionado às permissões definidas em cada pasta do Google Drive.

## Atualizar ações

Edite o array `actions` no final de `index.html` para acrescentar ou ajustar pastas. A publicação será executada novamente após salvar alterações na branch `main`.
