# Breadcrumb 2.0 | Tray OpenCode

Este snippet aprimora o esquema de navegação auxiliar que revela a localização do usuário na loja virtual, diferentemente do padrão
da plataforma OpenCode este breadcrumb exibe a pagina em que o usuario se encontra ao invés de apenas exibir a pagina anterior, outra diferença
é que mesmo estando no primeiro nível da categoria o caminho será exibido.

## Instalação

1. Crie um arquivo com o nome **_breadcrumb.html_** dentro da pasta **_elements/snippets_**. 
2. Copie o codigo [deste snippet](#) e cole no arquivo recem criado. 
3. inclua a chamada abaixo no inicio do arquivo **_pages/catalog.html_**

```{% element('snippets/paginate') %})```
