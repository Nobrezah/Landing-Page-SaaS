# ⚡ Landing Page SaaS — FlowSaaS

Landing page de alta conversão para produto SaaS, construída com **Next.js 14**, **TypeScript** e **Tailwind CSS**.

## ✨ Funcionalidades

- Navbar com efeito de scroll (transparente → fosco)
- Hero com gradiente animado e CTAs
- Grid de funcionalidades responsivo
- Cards de preços com plano em destaque
- Formulário de contato com validação client-side
- SEO otimizado com Next.js Metadata API
- Scroll suave entre seções
- Layout 100% responsivo

## 🛠 Stack

| Tecnologia   | Uso                               |
|--------------|-----------------------------------|
| Next.js 14   | App Router, SSG, Metadata API     |
| TypeScript   | Tipagem de formulários e props    |
| Tailwind CSS | Design system e responsividade    |

## 🚀 Como rodar

```bash
npm install
npm run dev
```

Acesse [http://localhost:3000](http://localhost:3000)

## 📁 Estrutura

```
src/
├── app/
│   ├── layout.tsx          # Metadata SEO
│   └── page.tsx            # Composição das seções
└── components/sections/
    ├── Navbar.tsx          # Navbar com scroll effect
    ├── Hero.tsx            # Seção hero
    ├── Features.tsx        # Grid de funcionalidades
    ├── Pricing.tsx         # Cards de preços
    └── ContactForm.tsx     # Formulário com validação
```
