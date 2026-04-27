# landing page Barbearia Bozzi

# Landing Page — Bozzi Barbearia

Landing page responsiva para a **Bozzi Barbearia (Teresina – PI)**, com foco em apresentação da marca, serviços, tabela de preços, avaliações e contato/WhatsApp.

---

## Deploy

**Link do deploy:** https://landing-page-bozzi.netlify.app/

---

## DOCs

**Link do docs:** https://canva.link/6r988kk56bt5qo4

---

## Tecnologias

- HTML
- CSS
- JavaScript (vanilla)

---

## Como rodar o projeto

Como é um projeto estático, você pode abrir o arquivo `Index.html` no navegador ou rodar com um servidor local.

### Opção 1 — Abrir direto no navegador
1. Vá até a pasta `src/`
2. Abra o arquivo `Index.html`

### Opção 2 — Servidor local (recomendado)
Se você tiver o VS Code:
1. Instale a extensão **Live Server**
2. Abra `src/Index.html`
3. Clique em **Go Live**

Ou com Node.js (exemplo usando `serve`):
```bash
npx serve .
```

---

## Estrutura de pastas (resumo)

- `src/Index.html` — página principal
- `src/Style.css` — estilos do site
- `script/` — scripts auxiliares (se aplicável)

---

## Principais recursos

- Botões de CTA para WhatsApp
- Seções: Início, Sobre, Serviços, Preços, Avaliações, Contato
- Menu mobile
- Animações de “reveal” ao rolar a página
- Mapa incorporado do Google Maps

---

## Personalização rápida

### Trocar imagens dos cards (Hero/Sobre)
As imagens ficam no `src/Index.html` dentro dos blocos:
- `.hero-card-img`
- `.sobre-img`

### Trocar textos e informações
Edite diretamente em `src/Index.html`:
- Títulos, descrições e endereço
- Links do WhatsApp e redes sociais
