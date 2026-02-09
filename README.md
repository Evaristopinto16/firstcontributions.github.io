# First Contributions
#primeira contribuicao in pt

A website to help people make their first open source contribution.
Um site para ajudar as pessoas a fazerem sua primeira contribuição para projetos de código aberto.

## Features

- **Project Discovery**: Browse open source projects suitable for beginners
- **Issue Integration**: View "good first issue" and "help wanted" issues directly from GitHub
- **Bento Layout**: Modern, responsive card layout with varying heights
- **Real-time Data**: Fetches live issue data from GitHub repositories
- 
## Funcionalidades

- **Descoberta de Projetos**: Navegue por projetos de código aberto adequados para iniciantes
- **Integração de Problemas**: Veja problemas de "boa primeira tarefa" e "precisa-se de ajuda" diretamente do GitHub
- **Layout Bento**: Layout de cartão moderno e responsivo com alturas variáveis
- **Dados em Tempo Real**: Busca dados de problemas em tempo real de repositórios do GitHub

## Setup

### Prerequisites

- Node.js 18+
- npm or pnpm

### Installation

```sh
npm install
# or
pnpm install
```

### GitHub API Setup (Optional)

To enable live issue fetching, you'll need a GitHub Personal Access Token:

1. Go to [GitHub Settings > Personal Access Tokens](https://github.com/settings/tokens)
2. Generate a new token (no special permissions needed)
3. Create a `.env` file in the project root:

```env
GITHUB_TOKEN=your_token_here
```

Without a token, the site will work but won't show live GitHub issues due to rate limiting.

### Development

```sh
npm run dev
# or
pnpm dev
```

### Build

```sh
npm run build
# or
pnpm build
```

## Tech Stack

- **Astro**: Static site generator
- **TypeScript**: Type safety
- **GitHub API**: Live issue data
- **CSS**: Modern styling with glassmorphism effects
