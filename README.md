# Humanly × JOVI — Sprint 4

## Tecnologias utilizadas

React 19, Next.js 16, TypeScript, Tailwind CSS 4, PostCSS e Lucide React. O projeto utiliza componentes com props, rotas públicas e privadas, hooks nativos e customizados, Fetch API, API própria simulada e persistência em `localStorage`.

## Instalação das dependências

Requisitos: Node.js 22.13 ou superior e npm 10 ou superior.

Na pasta do projeto, execute:

```bash
npm ci
```

## Como executar o projeto

```bash
npm run dev
```

Acesse **http://localhost:3000**. O comando cria automaticamente o arquivo `.env.local` com a chave de sessão necessária, caso ele ainda não exista.

Para executar a versão de produção local:

```bash
npm run build
npm start
```

## Como executar o servidor / back-end

A interface e a API própria simulada são executadas pelo mesmo servidor Next.js, iniciado pelos comandos acima. Não é necessário iniciar outro servidor ou configurar banco de dados. Na Vercel, configure a variável `SESSION_SECRET` com uma chave aleatória de pelo menos 32 caracteres antes do deploy.

## Uso de inteligência artificial

Ferramentas de inteligencia artificial foram utilizadas como apoio tecnico na migração e estruturação do prototipo em componentes React, na implementação das funcionalidades solicitadas, na organização visual responsiva e na revisão do projeto. A equipe revisou, testou e validou o resultado final, sendo responsavel por compreender o codigo, as funcionalidades implementadas e as decisões apresentadas.

## Usuário e senha para teste

- E-mail: `professor@humanly.com`
- Senha: `Humanly@2026`

## Links do projeto

- Repositório GitHub: https://github.com/EduardoCraveiro/Sprint-4-WebDevelopment-FrontEnd
- Deploy na Vercel: https://sprint-4-web-development-front-end.vercel.app/
