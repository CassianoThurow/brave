# Next.js v12 - Brave

Este é um modelo stater para NextJS e Typescript.

### Stack

- [NextJS](https://nextjs.org) - Uma estrutura React que permite construir sites estáticos super rápidos e extremamente fáceis de usar.
- [Typescript](https://www.typescriptlang.org) - Uma linguagem de programação fortemente tipada que se baseia em JavaScript.
- [TailwindCSS](https://tailwindcss.com/) - O Tailwind CSS é um framework CSS utilitário e altamente personalizável para criar interfaces web modernas e responsivas.
- [Sass](https://sass-lang.com) - Uma linguagem de script de pré-processador que é interpretada ou compilada em CSS.
- [ESlint](https://eslint.org) - Uma ferramenta para identificar e relatar padrões encontrados no código ECMAScript/JavaScript.
- [Husky](https://www.npmjs.com/package/husky) - Hooks que permitem que scripts personalizados sejam executados em seu repositório.
- [Lint-staged](https://github.com/okonet/lint-staged) - Ajuda o [Husky](https://www.npmjs.com/package/husky) a executar linters em arquivos git.
- [Commitlint](https://commitlint.js.org/#/) - Uma ferramenta que identifica suas mensagens de commit e garante que elas sigam um conjunto de regras.

#### Versão

- NodeJS (`v16.17.0`) (Minimo)
- NextJS (`v12.3.0`)
- ReactJS (`v18.2.0`)

## Estrutura de pastas

```js
├── ...
├── public
    ├── images       # Contem coisas como (imagens, ícones, logos)
├── src
│   ├── components   # Contem componentes de UI reutilizáveis como (Header, Footer, Modal, Button, .etc)
│   ├── pages        # Contém componentes de página individuais
│   ├── styles       # Estilos globais
│   ├── fonts        # Onde é armazenada todas fontes que serão utilizadas no projeto
└── ...
```

## Começando

**1. Clone o repositório e instale as dependências**

```bash
$ git clone https://code.brave.ag/brave/development-boilerplates.git <DIRETÓRIO>
$ cd <DIRETÓRIO>
$ npm install
```

**2. Habilitar husky** (Opcional)

```bash
$ npm run prepare
```

> ⚠️ Certifique-se de ter um repositório Git, caso contrário, execute este comando: `git init`..
> Você pode ignorar este comando se você instalou pacotes antes.

**3. Desenvolvimento**

```bash
$ npm run dev
```

## Guia de uso

### Commit

- Com o husky instalado para fazer um commit, voce deve adicionar os arquivos que voce seja enviar ao git (`git add .`) e rodar apenas um `git commit`, para rodar todos os linters de código antes que seu código seja enviado ao repositório e estar habilitado a seguir o padrão de commit:
  [
    "feat",
    "fix",
    "perf",
    "refactor",
    "revert",
    "style",
  ],

### ESlint

Você deve instalar a extensão [ESlint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) no VSCode para detectar erros.
