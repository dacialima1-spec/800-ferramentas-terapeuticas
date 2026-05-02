# 800 Ferramentas Terapêuticas Aplicadas em Sessão — Página de Vendas

Projeto de página de vendas HTML estática para o produto "800 Ferramentas Terapêuticas Aplicadas em Sessão" (psicólogos e terapeutas).

## Estrutura do projeto

```
800 Ferramentas Terapêuticas/
├── index.html          ← ARQUIVO PRINCIPAL (fonte da verdade, editar aqui)
├── site-hostinger.zip  ← Zip pronto para upload na Hostinger
├── site-netlify/
│   ├── index.html      ← Cópia sincronizada do index.html principal
│   ├── netlify.toml    ← Configurações de segurança/cache do Netlify
│   └── robots.txt      ← Permite indexação pelo Google
└── CLAUDE.md           ← Este arquivo
```

## Regras importantes

- **Sempre editar `index.html`** na raiz — ele é a fonte da verdade.
- Após editar, **sincronizar** `site-netlify/index.html` (copiar o index.html para lá).
- Após sincronizar, **recriar o zip** `site-hostinger.zip` com os arquivos de `site-netlify/`.
- **Projeto totalmente separado** do projeto "Crochê PET Copa Brasil" / "Ganchillo para mascotas Argentina". Não misturar conteúdo, paleta, fontes ou copy entre eles.

## Sistema visual (do design original)

- **Paleta:**
  - Bege `#F5EFE7` (fundo principal)
  - Bege 2 `#EFE6D9`
  - Marrom `#5A2E1C` (texto forte)
  - Marrom escuro `#3B1F14` (blocos)
  - Marrom mais escuro `#2A1610`
  - Terracota `#C46A3A` / `#E08858` (destaque)
  - Verde `#2FBF71` / `#26A862` (CTA)
- **Tipografia:** Playfair Display (headlines, autoridade editorial) + Inter (corpo)
- **Ritmo visual:** dobras alternam fundo bege/marrom escuro
- **Numeração editorial italic** (i, ii, iii…) em cada dobra

## Estrutura da página (12 dobras + fechamento)

1. Hero — dor + solução + CTA principal
2. Dor — 6 pontos clínicos
3. Mecanismo — 4 abordagens base (TCC, TDC, MBCT, TN)
4. Produto — 9 frentes clínicas
5. Diferencial — "Não é só um kit"
6. Bônus — 3 bônus exclusivos
7. Transformação — 5 resultados
8. Autoridade — embasamento clínico (5 abordagens)
9. Entrega — o que está incluso
10. Oferta — preço + CTA
11. Garantia — 7 dias incondicional
12. FAQ — 6 perguntas
13. Fechamento final + footer

## Interatividade

- FAQ accordion com animação suave
- Barra de progresso de scroll no topo
- Timer regressivo decorativo na top bar
- CTAs com efeito shine + estado pressionado
- Sticky CTA fixo no mobile

## Pendências antes de publicar

- Trocar links `#` dos CTAs pelo checkout real (Hotmart/Eduzz/Kiwify)
- Adicionar pixel de tracking (Meta Pixel / Google Tag) se necessário
- Configurar Open Graph tags com imagem real do produto
- Revisar título da aba e descrição para SEO

## Deploy

- **Netlify:** arrastar a pasta `site-netlify/` em https://app.netlify.com/drop
- **Hostinger:** fazer upload do `site-hostinger.zip` no painel de hospedagem
