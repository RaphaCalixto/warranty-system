# Sistema de Garantia

Sistema de gerenciamento de garantias desenvolvido com Next.js, TypeScript e Tailwind CSS.

## 🚀 Tecnologias Utilizadas

- [Next.js 15.2.4](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [PNPM](https://pnpm.io/) (Gerenciador de pacotes)

## 📋 Pré-requisitos

- Node.js (versão 18 ou superior)
- PNPM instalado globalmente
- Git

## 🔧 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/RaphaCalixto/warranty-system.git
cd warranty-system
```

2. Instale as dependências:
```bash
pnpm install
```

3. Inicie o servidor de desenvolvimento:
```bash
pnpm dev
```

4. Acesse o projeto em [http://localhost:3000](http://localhost:3000)

## 📦 Scripts Disponíveis

- `pnpm dev` - Inicia o servidor de desenvolvimento
- `pnpm build` - Cria a versão de produção
- `pnpm start` - Inicia o servidor de produção
- `pnpm lint` - Executa o linter

## 🔐 Variáveis de Ambiente

Crie um arquivo `.env.local` na raiz do projeto com as seguintes variáveis:

```env
# Exemplo de variáveis de ambiente (ajuste conforme necessário)
DATABASE_URL="sua_url_do_banco_de_dados"
NEXT_PUBLIC_API_URL="sua_url_da_api"
```

## 📁 Estrutura do Projeto

```
warranty-system/
├── app/              # Rotas e páginas da aplicação
├── components/       # Componentes reutilizáveis
├── contexts/        # Contextos do React
├── hooks/           # Custom hooks
├── lib/             # Utilitários e configurações
├── public/          # Arquivos estáticos
└── styles/          # Estilos globais
```

## 🤝 Contribuindo

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/AmazingFeature`)
3. Faça o Commit das suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Faça o Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

Raphael Calixto
- GitHub: [@RaphaCalixto](https://github.com/RaphaCalixto)
- Email: raphacalixto10@gmail.com 