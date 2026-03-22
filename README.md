# Local Turístico

Projeto de página web estática sobre destinos turísticos em Busan, Coreia do Sul. Desenvolvido com HTML e SCSS.

## Pré-requisitos

- [Node.js](https://nodejs.org/) (versão 18 ou superior recomendada)
- [pnpm](https://pnpm.io/) (gerenciador de pacotes)
- [Sass](https://sass-lang.com/) (compilador de SCSS)

Para instalar o pnpm globalmente:

```bash
npm install -g pnpm
```

Para instalar o Sass globalmente:

```bash
npm install -g sass
```

## Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/d3vnicolas/local-turistico.git
cd local-turistico
pnpm install
```

## Como rodar o projeto

### 1. Compilar o SCSS

Inicie o observador do Sass para compilar automaticamente as alterações nos estilos:

```bash
pnpm run sass
```

Esse comando observa o arquivo `styles/input.scss` e gera o `styles/output.css` automaticamente sempre que houver mudanças.

### 2. Abrir o projeto no navegador

Abra o arquivo `index.html` diretamente no navegador, ou utilize uma extensão como o [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) no VS Code para uma experiência com recarregamento automático.

## Estrutura do projeto

```
local-turistico/
├── index.html          # Página principal
├── styles/
│   ├── input.scss      # Arquivo fonte de estilos (SCSS)
│   ├── output.css      # CSS gerado pelo Sass (não editar manualmente)
│   └── guide.scss      # Guia de estilos auxiliar
└── public/
    └── images/         # Imagens utilizadas na página
```
