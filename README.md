# my-ecommerce-react-app
🛒 Mini e-commerce criado com React, Vite, Zustand e Material UI. Inclui listagem de produtos, carrinho com persistência local e UI moderna com componentes do MUI.

📦 my-ecommerce-app/
├─ public/
│  └─ (logo, ícones, etc.)
├─ src/
│  ├─ assets/               → imagens e ícones
│  ├─ components/           → Header, Footer, ProductCard, CartDrawer
│  ├─ pages/                → Home.tsx, Product.tsx, Cart.tsx
│  ├─ store/                → cartStore.ts (Zustand + persist)
│  ├─ hooks/                → useCart.ts, useProducts.ts (com TanStack Query)
│  ├─ types/                → Product.ts, CartItem.ts
│  ├─ services/             → api.ts (fetch dos produtos)
│  ├─ App.tsx
│  └─ main.tsx
├─ tailwind.config.js
├─ tsconfig.json
└─ vite.config.ts

📦 Funcionalidades principais:
🛒 Adicionar/remover do carrinho

🧠 Zustand com persistência (localStorage)

🔍 Filtro por categoria

💵 Cálculo automático de subtotal

📦 Listagem com TanStack Query (ex: consumindo https://fakestoreapi.com/products)

💅 UI com Tailwind ou Material UI

🌙 Dark mode opcional

🚀 Deploy na Vercel
