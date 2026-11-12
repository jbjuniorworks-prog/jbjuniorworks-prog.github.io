# Portfólio · José Batista

Portfólio pessoal de **José Batista** — desenvolvedor full-stack (Python + TypeScript).

**Ao vivo:** https://jbjuniorworks-prog.github.io

---

## Sobre

Página única para recrutadores e clientes de freela. Seções, na ordem da página:

1. **Dois projetos do trabalho** como estudos de caso, no formato *o que é · meu papel · como foi feito*:
   - **Plataforma SaaS de licenciamento ambiental** (govtech): multitenant, Clean Architecture (ports & adapters), IA em produção e uma auditoria de segurança do repositório inteiro.
   - **Marketplace local com entrega em tempo real**: monorepo com três apps mobile (consumidor, lojista, entregador), rastreamento ao vivo e assistente de compras com IA.
2. **Projetos pessoais**: Brasa (delivery multi-loja, código privado), [Rota de Entregas](https://github.com/jbjuniorworks-prog/rota-entregas) (roteirizador para entregadores) e [Martelo](https://github.com/jbjuniorworks-prog/verzel-leiloes) (casa de leilões com lances ao vivo).
3. **Freelas**: o que eu faço para clientes e como funciona um projeto.
4. **Stack**, **como eu trabalho**, **experiência e formação** e **contato**.

> Os projetos do trabalho aparecem sem o nome dos produtos e dos clientes.

## Como o site é feito

Uma única página **HTML autocontida** — sem build, sem dependências, sem framework:

- HTML + CSS com custom properties e **tema claro/escuro automático** (segue o sistema do visitante)
- JavaScript puro: *reveal on scroll* (IntersectionObserver) e botão de **copiar e‑mail**
- Mockups (moldura de browser, celulares e as ilustrações dos projetos pessoais) desenhados em **CSS/SVG**, sem imagens
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

O GitHub Pages publica o que está na branch `main`. Por isso as mudanças entram por uma branch e um Pull Request: o merge na `main` é o que publica.

A versão publicada até novembro de 2026 está marcada com a tag `v2026-07`.

## Contato

- **E‑mail:** jb.juniorworks@gmail.com
- **LinkedIn:** [in/josé-batistafullstack](https://www.linkedin.com/in/jos%C3%A9-batistafullstack/)
- **GitHub:** [@jbjuniorworks-prog](https://github.com/jbjuniorworks-prog)

---

<sub>© 2026 · José Batista</sub>
