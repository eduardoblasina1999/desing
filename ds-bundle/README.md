# ALTI Indústria - Kit de Identidade

Kit somente de identidade: cores, tipografia, formas e logo. Não há componentes de UI. Site da marca: https://www.altiindustria.com.br

## Como usar
Carregue `styles.css` (importa `tokens/*.css` e a fonte Poppins). Todo estilo deve usar as variáveis abaixo, sem hex soltos.

```html
<link rel="stylesheet" href="styles.css">
<section style="background:var(--color-bg-brand);color:var(--color-text-on-brand);padding:var(--space-6);border-radius:var(--radius-md)">
  <img src="brand/alti-logo-white.png" alt="ALTI Indústria" height="56">
  <h2 style="color:var(--color-text-on-brand)">Soluções industriais</h2>
  <a style="background:var(--color-accent);color:#fff;padding:var(--space-3) var(--space-5);border-radius:var(--radius-pill);text-decoration:none;font-weight:var(--font-weight-medium)">Fale conosco</a>
</section>
```

## Cores
Principal: branco `--alti-white` (#ffffff). Secundárias: `--alti-blue-900` (#034885) e `--alti-blue-500` (#1f7cd7).
Apoio: `--alti-blue-700`, `--alti-blue-100`, `--alti-blue-50`, `--alti-ink` (texto), `--alti-gray-600/300/100`.
Semânticas: `--color-bg`, `--color-bg-subtle`, `--color-bg-brand`, `--color-text`, `--color-text-muted`, `--color-text-on-brand`, `--color-primary`, `--color-accent`, `--color-border`, `--color-focus`.
Fundo claro: texto `--color-text`, títulos `--color-primary`. Fundo `--color-bg-brand`: texto branco e logo branco.

## Tipografia
Somente Poppins (`--font-family`), pesos 300-700 (`--font-weight-*`). Tamanhos `--font-size-xs` a `--font-size-3xl`. Rótulos em caixa alta usam `letter-spacing: var(--letter-spacing-caps)`.

## Formas
Cantos sempre arredondados: `--radius-sm` 8px, `--radius-md` 12px, `--radius-lg` 20px, `--radius-pill`. Espaçamento `--space-1` a `--space-8` (4-64px). Sombras `--shadow-sm/md` em azul.

## Logo
`brand/alti-logo.png` (cor original, para fundos claros) e `brand/alti-logo-white.png` (branco, para fundos azuis/escuros). Não deformar, não recolorir, manter margem livre mínima igual à altura do "A".
