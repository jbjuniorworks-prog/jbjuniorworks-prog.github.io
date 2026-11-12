# Portfólio · José Batista

Portfólio pessoal de **José Batista** — desenvolvedor full-stack (Python + TypeScript).

**Ao vivo:** https://jbjuniorworks-prog.github.io

---

## Sobre

Página única que apresenta dois projetos recentes como estudos de caso, no formato *o que é · meu papel · como foi feito*:

- **Plataforma SaaS de licenciamento ambiental** (govtech) — multitenant, Clean Architecture (ports & adapters), IA em produção e uma auditoria de segurança do repositório inteiro.
- **Marketplace local com entrega em tempo real** — monorepo com três apps mobile (consumidor, lojista, entregador), rastreamento ao vivo e assistente de compras com IA.

> Os projetos aparecem de forma anônima, como exemplos — sem nomes de clientes.

## Como o site é feito

Uma única página **HTML autocontida** — sem build, sem dependências, sem framework:

- HTML + CSS com custom properties e **tema claro/escuro automático** (segue o sistema do visitante)
- JavaScript puro: *reveal on scroll* (IntersectionObserver) e botão de **copiar e‑mail**
- Mockups (moldura de browser + celulares) desenhados 100% em **CSS/SVG**
- Acessibilidade: foco por teclado visível, `prefers-reduced-motion` respeitado
- Hospedagem: **GitHub Pages**

## Rodar localmente

Não precisa de servidor — dois cliques no `index.html` já abre. Se preferir servir:

```bash
git clone https://github.com/jbjuniorworks-prog/jbjuniorworks-prog.github.io.git
cd jbjuniorworks-prog.github.io
python -m http.server 8000   # http://localhost:8000
```

## Atualizar

Edite o `index.html` e faça commit na branch `main` — o GitHub Pages republica automaticamente em segundos.

## Contato

- **E‑mail:** jb.juniorworks@gmail.com
- **LinkedIn:** [in/josé-batistafullstack](https://www.linkedin.com/in/jos%C3%A9-batistafullstack/)
- **GitHub:** [@jbjuniorworks-prog](https://github.com/jbjuniorworks-prog)

---

<sub>© 2026 · José Batista</sub>
