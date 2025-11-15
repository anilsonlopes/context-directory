# Base de Conhecimento para Agentes de IA

> Repositório de conhecimento estruturado em Markdown para consumo por agentes de IA em IDEs e ferramentas de desenvolvimento

Este repositório serve como uma **base de conhecimento centralizada** projetada
especificamente para ser consumida por agentes de IA que operam em IDEs e outras
ferramentas de desenvolvimento.

O conteúdo está organizado em arquivos Markdown estruturados, facilitando a
leitura, processamento e navegação por sistemas de IA.

## ✨ Características

- 🤖 **Otimizado para Agentes de IA** - Estrutura e formatação pensadas para facilitar processamento por IA
- 📝 **Documentação em Markdown** - Formato legível tanto para humanos quanto máquinas
- 🌳 **Estrutura Hierárquica** - Organização clara em diretórios e seções
- 🔍 **Busca Semântica** - Estrutura que facilita busca e navegação contextual
- 📚 **Conteúdo Contextual** - Explicações claras e objetivas com exemplos práticos
- 🔄 **Versionamento** - Controle de versão para rastreamento de mudanças
- 🌐 **Português do Brasil** - Todo o conteúdo em português brasileiro
- ⚡ **Fácil Manutenção** - Convenções claras para atualização e expansão do conteúdo

## 🚀 Início Rápido

```bash
# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev
```

O site de documentação estará disponível em `http://localhost:3000`

## 📁 Estrutura do Projeto

```
context-directory/
├── content/                    # Conteúdo em Markdown
│   ├── index.md               # Página inicial
│   ├── 1.getting-started/     # Seção introdutória
│   │   ├── 1.para-agentes-ia.md
│   │   ├── 2.introduction.md
│   │   └── ...
│   └── 2.essentials/          # Conteúdo essencial
│       ├── 1.markdown-syntax.md
│       └── ...
├── public/                     # Recursos estáticos
└── package.json               # Dependências e scripts
```

## ⚡ Construído com

Este repositório utiliza:

- [Nuxt 4](https://nuxt.com) - Framework web
- [Nuxt Content](https://content.nuxt.com/) - CMS baseado em arquivos
- [Nuxt UI](https://ui.nuxt.com) - Componentes de UI
- [Docus Layer](https://www.npmjs.com/package/docus) - Tema de documentação

## 📖 Documentação

Para informações sobre como agentes de IA devem consumir este repositório, consulte
a documentação em `/content/1.getting-started/1.para-agentes-ia.md`.

Para guias sobre manutenção de conteúdo, veja `/content/1.getting-started/7.manutencao-conteudo.md`.

## 🚀 Deploy

Para build de produção:

```bash
npm run build
```

Os arquivos compilados estarão no diretório `.output`, prontos para deploy em qualquer
provedor de hospedagem que suporte Node.js.

## 📄 License

[MIT License](https://opensource.org/licenses/MIT) 