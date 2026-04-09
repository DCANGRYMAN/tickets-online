# OVERGROUND — by Oziris

Plataforma premium de eventos de eletrônica do Brasil.

## Stack
- Angular 17+ (Standalone Components, Signals)
- SCSS com tema dark premium
- PWA ready

## Deploy na Vercel

### 1. Fork / clone este repositório

### 2. Instale as dependências localmente (para testar)
```bash
npm install
npm run build
npm start
```

### 3. Deploy via Vercel CLI
```bash
npm i -g vercel
vercel --prod
```

### 4. Deploy via GitHub
1. Suba o projeto para um repositório GitHub
2. Acesse [vercel.com](https://vercel.com) → "Add New Project"
3. Importe o repositório
4. Framework: **Angular**
5. Build Command: `npm run build`
6. Output Directory: `dist/overground/browser`
7. Clique em **Deploy**

## Scripts
| Comando | Descrição |
|---------|-----------|
| `npm start` | Servidor de desenvolvimento |
| `npm run build` | Build de produção |

## Estrutura
```
src/app/
├── core/
│   ├── models/         # Interfaces TypeScript
│   └── services/       # EventsService, AuthService, TicketsService
├── features/
│   ├── home/           # Página inicial (Hero + Destaques)
│   ├── events/         # Listagem com filtros
│   ├── event-detail/   # Página do evento
│   ├── checkout/       # Fluxo de compra
│   └── account/        # Login + Meus ingressos
└── shared/
    └── components/     # Nav, BottomNav, EventCard
```

## Funcionalidades
- ✅ 15 eventos mockados (SP + outras regiões)
- ✅ Filtro por estado e categoria
- ✅ Busca por nome
- ✅ Favoritar eventos (localStorage)
- ✅ Simulação de login (qualquer e-mail + senha 4+ chars)
- ✅ Checkout com PIX e Cartão (mock)
- ✅ QR Code de ingresso
- ✅ Histórico de pagamentos
- ✅ PWA (instalável)

Desenvolvido por **Oziris** — [oziris.com.br](https://oziris.com.br)
# overgound-ingressos
