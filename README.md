
# Projeto com Sass

Este projeto é uma implementação de uma loja online com uma grid de produtos, desenvolvido como parte do meu aprendizado em Sass. A interface foi criada utilizando HTML5 e estilizada com Sass, visando praticar e aprimorar habilidades com esta poderosa ferramenta de pré-processamento CSS.

## Estrutura do Projeto

- `index.html`: Contém a estrutura HTML da página.
- `build/main.css`: Arquivo CSS gerado pelo Sass a partir dos arquivos `.scss`.
- `src/main.scss`: Arquivo Sass principal com os estilos da página.

## Tecnologias Utilizadas

- HTML5
- Sass (Syntactically Awesome Stylesheets)

## Funcionalidades

### Navegação

- **Header**: Contém a logo da loja e um menu de navegação com links para "Início" e "Produtos".

### Seções

- **Produtos**: Exibe uma grid de produtos, cada um com imagem, nome, descrição e um botão para ver detalhes.


## Como Executar o Projeto

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd nome-do-repositorio
    ```

3. Instale as dependências:
    ```bash
    npm install
    ```

4. Execute o Sass para compilar os arquivos `.scss` para `.css`:
    ```bash
    npm run sass
    ```

5. Abra o arquivo `index.html` em seu navegador de preferência.

## Personalização

### Estilos Customizados

Você pode adicionar ou modificar estilos no arquivo `src/main.scss` e recompilar o Sass para atualizar o `build/main.css`.

### Conteúdo

O conteúdo pode ser atualizado diretamente no arquivo `index.html`.

## Dependências

As dependências do projeto estão listadas no arquivo `package.json` e são instaladas via npm.

```json
{
  "name": "projeto-sass",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "sass": "sass --watch styles/main.scss build/main.css"
  },
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "sass": "^1.77.4"
  }
}
```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias.

Sinta-se à vontade para personalizar e expandir este README conforme necessário para refletir melhor os detalhes do seu projeto.
