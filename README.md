# 🛒 my-ecommerce-react-app

Mini e-commerce moderno criado com **React**, **Vite**, **Zustand** (com persistência local), **Material UI (MUI)** e **TanStack Query**. O projeto tem foco em arquitetura clara, componentização e boas práticas para um front-end escalável.

---

## ✨ Funcionalidades previstas

- 🛍️ Listagem de produtos com imagens, títulos, preços e categorias  
- ➕ Adicionar e remover itens do carrinho  
- 💾 Persistência do carrinho via **localStorage**  
- 🎯 Filtro de produtos por categoria  
- 📊 Cálculo automático do subtotal  
- 🚀 Fetch otimizado com **TanStack Query**  
- 🌙 Modo escuro opcional  
- 🌐 Deploy automatizado na **Vercel**

---

## 📁 Estrutura de pastas (prevista)

my-ecommerce-react-app/
├─ public/
│ └─ imagens, ícones, etc.
├─ src/
│ ├─ assets/ → imagens e ícones
│ ├─ components/ → Header, Footer, ProductCard, CartDrawer
│ ├─ pages/ → Home.tsx, Product.tsx, Cart.tsx
│ ├─ store/ → Zustand com persistência (cartStore.ts)
│ ├─ hooks/ → useCart.ts, useProducts.ts
│ ├─ types/ → Product.ts, CartItem.ts
│ ├─ services/ → api.ts (fetch da API)
│ ├─ App.tsx
│ ├─ main.tsx
│ └─ vite.config.ts

---

## 🧱 Tecnologias e libs

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Zustand](https://zustand-demo.pmnd.rs/)
- [Material UI (MUI)](https://mui.com/)
- [TanStack Query](https://tanstack.com/query/latest)
- [TypeScript](https://www.typescriptlang.org/)

---

## 🧪 API de produtos

A listagem será baseada na API pública do [Fake Store API](https://fakestoreapi.com/products).

---

## 🚀 Deploy

Será feito com [Vercel](https://vercel.com/), com build automatizado via GitHub.

---

## 📌 Status

> 🟡 Projeto em desenvolvimento — ainda não iniciado oficialmente.
