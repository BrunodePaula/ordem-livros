# Ordem de Livros

Uma aplicação web desenvolvida com SvelteKit para organizar e visualizar séries de livros, autores e livros em ordem cronológica. Permite explorar coleções de livros, biografias de autores e navegar pelas séries literárias de forma intuitiva.

## Funcionalidades

- **Listagem de Séries**: Visualize todas as séries disponíveis com descrições e imagens.
- **Detalhes de Autores**: Acesse biografias completas e informações sobre os autores.
- **Organização de Livros**: Veja os livros de cada série em ordem, com links para compra e imagens.
- **Interface Responsiva**: Desenvolvida com Tailwind CSS para uma experiência fluida em dispositivos móveis e desktop.

## Tecnologias Utilizadas

- **SvelteKit**: Framework para construção de aplicações web.
- **TypeScript**: Tipagem estática para maior robustez.
- **Tailwind CSS**: Framework CSS para estilização rápida e responsiva.
- **Vite**: Ferramenta de build e desenvolvimento rápido.
- **Marked**: Para renderização de Markdown em biografias.

## Instalação e Execução

1. Clone o repositório:
   ```bash
   git clone <url-do-repositorio>
   cd ordem-livros
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Execute o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

   Ou abra o app em uma nova aba do navegador:
   ```bash
   npm run dev -- --open
   ```

## Build para Produção

Para criar uma versão de produção:
```bash
npm run build
```

Para visualizar a build de produção:
```bash
npm run preview
```

## Estrutura do Projeto

- `src/routes/`: Páginas da aplicação (home, autores, séries).
- `src/components/`: Componentes reutilizáveis (itens de série, autor, etc.).
- `src/constants/`: Dados estáticos de autores e séries.
- `static/`: Arquivos estáticos (imagens, etc.).

## Contribuição

Sinta-se à vontade para contribuir com melhorias, correções ou novas funcionalidades. Abra uma issue ou envie um pull request.

## Licença

Este projeto é de código aberto e está sob a licença MIT.
