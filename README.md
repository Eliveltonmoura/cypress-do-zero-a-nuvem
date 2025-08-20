# cypress-do-zero-a-nuvem

Projeto de exemplo para demonstrar o comando customizado do Cypress `cy.dataTest`.

## Pré-requisitos

É necessário ter **Node.js** e **npm** instalados para rodar este projeto.

> Foram utilizadas as versões `2.42.1` e `9.5.0` do Node.js e npm, respectivamente.  
> Recomenda-se utilizar as mesmas ou versões mais recentes.

## Instalação

Execute o comando abaixo para instalar as dependências de desenvolvimento:

```bash
npm install
```

ou, na forma abreviada:

```bash
npm i
```

## Testes

> **Observação:** Antes de rodar os testes, crie uma cópia do arquivo `cypress.env.example.json` com o nome `cypress.env.json`.  
> Esse arquivo deve ser atualizado com credenciais válidas em um ambiente real.  
>
> O arquivo `cypress.env.json` está listado no [`.gitignore`](./.gitignore), garantindo que informações confidenciais não sejam versionadas.

Para rodar os testes em **modo headless**, use:

```bash
npm test
```

ou, de forma abreviada:

```bash
npm t
```

Para abrir o Cypress em **modo interativo**, execute:

```bash
npm run cy:open
```

## Apoie este projeto

Se este projeto foi útil para você, deixe uma ⭐.

---

Projeto criado com 💚 por [elivelton].