## Investimentos: Uma aplicação web para pesquisa de investimentos

### Descrição

Esta aplicação web simples permite aos usuários pesquisar por investimentos a partir de um termo de busca. Os resultados da pesquisa são exibidos dinamicamente na página, com informações como título, descrição e link para mais detalhes.

### Tecnologias Utilizadas

* **HTML:** Estrutura básica da página, definindo os elementos e conteúdo.
* **CSS:** Estilização da página, definindo a aparência visual.
* **JavaScript:** Lógica da aplicação, responsável por manipular o DOM, realizar a pesquisa e exibir os resultados.

### Como funciona

1. **Interface do usuário:** O usuário digita um termo de busca no campo de texto e clica no botão "Pesquisar".
2. **Processamento:** O JavaScript captura o termo de busca, converte-o para minúsculas e busca por correspondências nos títulos e descrições dos investimentos armazenados no arquivo `dados.js`.
3. **Exibição dos resultados:** Os resultados da pesquisa são exibidos em uma seção específica da página, com cada resultado em um card contendo título, descrição e link para mais informações.
4. **Nenhum resultado:** Se nenhum resultado for encontrado, uma mensagem informativa é exibida.

### Estrutura dos arquivos

* **index.html:** Arquivo principal da aplicação, contendo a estrutura HTML da página.
* **styles.css:** Arquivo CSS com as regras de estilo da página.
* **dados.js:** Arquivo JavaScript contendo um array com os dados dos investimentos (título, descrição, link).
* **app.js:** Arquivo JavaScript com a lógica da aplicação, responsável pela pesquisa e atualização da interface.

### Como executar

1. **Clonar o repositório:** Clone este repositório para o seu computador local.
2. **Abrir em um editor de código:** Abra os arquivos em seu editor de código favorito.
3. **Abrir no navegador:** Abra o arquivo `index.html` em um navegador web.
