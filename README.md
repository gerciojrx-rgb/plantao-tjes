# Plantão Judiciário — TJES
Sistema de Gestão de Escalas de Plantão | 1ª Região

## 🚀 Deploy rápido no Vercel

### Opção 1 — Via GitHub (recomendado)
1. Crie uma conta em github.com (gratuito)
2. Crie um repositório novo chamado `plantao-tjes`
3. Faça upload de todos estes arquivos para o repositório
4. Acesse vercel.com → "Add New Project" → importe o repositório do GitHub
5. Clique em **Deploy** — pronto!

### Opção 2 — Via Vercel CLI (requer Node.js instalado)
```bash
npm install
npm run build
npx vercel --prod
```

## 🗄️ Banco de dados
O Supabase já está configurado em São Paulo:
- URL: https://oyghivewqevznycqhdxg.supabase.co
- Tabelas: perfis, servidores, plantoes, auditoria, configuracoes
- RLS ativo em todas as tabelas

## 🔑 Credenciais iniciais
| Perfil | E-mail | Senha |
|--------|--------|-------|
| Master | master@tjes.jus.br | Master@2026! |
| Admin  | admin@tjes.jus.br  | Admin@2026   |

**Troque as senhas após o primeiro acesso!**

## 📁 Estrutura
```
plantao-tjes/
├── index.html
├── package.json
├── vite.config.js
├── vercel.json
├── public/
│   └── favicon.svg
└── src/
    ├── main.jsx
    └── App.jsx   ← sistema completo
```
