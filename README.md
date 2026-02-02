# Devlingo

O Devlingo é uma plataforma de aprendizado de idiomas que ajuda os usuários a aprender conceitos de programação com lições interativas.

## Funcionalidades

- Autenticação de usuário (cadastro e login)
- Lições interativas
- Acompanhamento de pontuação
- Status de conclusão de lição

## Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Supabase](https://supabase.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Router](https://reactrouter.com/)

## Começando

Para começar a usar o Devlingo, siga estes passos:

### Pré-requisitos

- [Node.js](https://nodejs.org/) (v18 ou superior)
- [npm](https://www.npmjs.com/)

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/Eduardoferalves/Devlingo.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd Devlingo
   ```
3. Instale as dependências:
   ```bash
   npm install
   ```
4. Crie um arquivo `.env` na raiz do projeto e adicione suas credenciais do Supabase:
   ```
    VITE_SUPABASE_URL=seu-url-supabase
    VITE_SUPABASE_ANON_KEY=sua-chave-anon-supabase
   ```
### Rodando a Aplicação
1. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```
2. Abra seu navegador e navegue até http://localhost:5173 para ver a aplicação em ação.

## Estrutura do Projeto
```
.
├── public
│   └── vite.svg
├── src
│   ├── assets
│   │   ├── images
│   │   └── react.svg
│   ├── components
│   │   ├── AnswerFeedbackPopUp.tsx
│   │   ├── Header.tsx
│   │   ├── LessonModal.tsx
│   │   ├── LessonNode.tsx
│   │   ├── LessonsPath.tsx
│   │   ├── LoadingScreen.tsx
│   │   ├── ProtectedRoute.tsx
│   │   └── UnitHero.tsx
│   ├── contexts
│   │   ├── AuthContext.tsx
│   │   └── AuthProvider.tsx
│   ├── hooks
│   │   ├── useCompletedLessons.ts
│   │   └── useUserProfile.ts
│   ├── mocks
│   │   └── lessonsData.ts
│   ├── pages
│   │   ├── Home.tsx
│   │   ├── LessonFailureScreen.tsx
│   │   ├── LessonScreen.tsx
│   │   ├── LessonSuccessScreen.tsx
│   │   ├── Login.tsx
│   │   └── SignUp.tsx
│   ├── services
│   │   ├── saveLessonsScore.ts
│   │   ├── supabase.ts
│   │   └── userProfile.ts
│   ├── styles
│   │   └── globals.css
│   ├── App.tsx
│   └── main.tsx
├── .gitignore
├── index.html
├── package.json
├── README.md
├── tsconfig.json
└── vite.config.ts
```

## Scripts Disponíveis

- `npm run dev`: Inicia o servidor de desenvolvimento.
- `npm run build`: Compila a aplicação para produção.
- `npm run lint`: Executa o linter no código.
- `npm run preview`: Inicia um servidor local para visualizar a build de produção.

## Contribuindo

Contribuições são bem-vindas! Por favor, abra uma issue ou envie um pull request com suas alterações.

## Licença

Este projeto está licenciado sob a Licença MIT.
