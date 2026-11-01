# Recriando a Interface da PlayStation Store com Angular

Projeto desenvolvido para recriar a interface web da PlayStation Store utilizando o framework Angular, com foco em praticar o que foi visto em aula, consiste na componentização e design moderno inspirado no tema escuro da plataforma.

## O que foi feito

- **Layout e Estilização:** Aplicação de um tema escuro (Dark Theme) com efeitos de transparência e desfoque (*Glassmorphism*).
- **Componentes Modulares:** Divisão da interface em blocos reutilizáveis como barra de navegação, cards de jogos e etiquetas.
- **Interatividade:** Botões e rótulos com transições suaves e efeitos de foco/hover.
- **Controle de Versão:** Organização do código utilizando Git e um arquivo `.gitignore` otimizado para projetos Angular.

## Tecnologias Utilizadas

- Angular
- TypeScript
- HTML5
- CSS3 (Flexbox e variáveis)
- Git e GitHub

## Arquitetura de Componentes

- **MenuBar:** Barra de navegação superior da loja.
- **Home:** Página principal que organiza a estrutura da interface.
- **Card:** Estruturação dos cards de exibição dos jogos.
- **CardLabel:** Rótulo dinâmico gerenciado via `@Input()` para exibir tags.
- **CardPricing:** Seção de preços e plataformas (PS4 / PS5).

## Como Executar o Projeto

Projeto modificado do [Angular CLI](https://github.com/angular/angular-cli).

---

## Como executar.

Execute `ng serve` para iniciar um servidor de desenvolvimento. Acesse `http://localhost:4200/`. A aplicação será recarregada automaticamente caso você altere qualquer um dos arquivos de código-fonte.

## Geração de código (Scaffolding)

Execute `ng generate component nome-do-componente` para criar um novo componente. Você também pode usar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Execução.

Execute `ng build` para compilar o projeto. Os artefatos gerados serão armazenados no diretório `dist/`.

## Execução de testes unitários

Execute `ng test` para rodar os testes unitários por meio do [Karma](https://karma-runner.github.io).

## Execução de testes ponta a ponta (end-to-end)

Execute `ng e2e` para rodar os testes ponta a ponta utilizando uma plataforma de sua preferência. Para usar este comando, é necessário adicionar previamente um pacote que implemente funcionalidades de testes ponta a ponta.


Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Compilação

Execute `ng build` para compilar o projeto. Os artefatos gerados serão armazenados no diretório `dist/`.

## Execução de testes unitários

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

---

## Executando testes de ponta a ponta.
Execute `ng e2e` para realizar os testes de ponta a ponta (end-to-end) por meio de uma plataforma de sua preferência. Para utilizar este comando, é necessário primeiro adicionar um pacote que implemente funcionalidades de testes de ponta a ponta.
---
