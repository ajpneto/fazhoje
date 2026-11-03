# FazHoje — Inovação e Soluções Tecnológicas | AENTECH

Aplicação web estática em **HTML5**, **Tailwind CSS**, **Bootstrap 5** e **JavaScript**, totalmente otimizada para o **GitHub Pages**, vinculada ao domínio próprio **fazhoje.com**, com **SEO avançado para motores de busca**, **Google Analytics (GA4)** e **Open Graph completo para redes sociais e WhatsApp**.

---

## 🚀 Estrutura do Projeto & Subdomínio AENTECH

- **Landing Page Principal (`/`):**
  - Hospedada em `https://fazhoje.com/`.
  - Seção Hero de impacto destacando inovação e soluções práticas.
  - Card dedicado da **AENTECH** com imagem consistente de assistência técnica, descrição dos serviços e link para o subdomínio `/aentech/`.
  - Seção de Contato integrada via Formspree com rastreamento no Google Analytics e botões diretos de e-mail e WhatsApp.
- **Assistência Técnica AENTECH (`/aentech/`):**
  - Subdomínio/caminho dedicado em `https://fazhoje.com/aentech/`.
  - Página completa de assistência técnica de celulares e tablets em Ourinhos - SP.
  - Barra de navegação com link direto de retorno para `FazHoje.com`.
  - Diagnóstico em 1h, tabela de serviços, depoimentos e botão WhatsApp de orçamento rápido.
- **Redirecionamento SEO (`/aentec/`):**
  - Mantido redirecionamento 301/meta-refresh para manter compatibilidade e não quebrar links antigos ou indexações prévias.

---

## 🌐 Tecnologias & SEO

- **Google Analytics 4 (GA4):**
  - Tag `G-NCGCXV54CT` configurada em todas as páginas (`index.html`, `aentech/index.html`, `404.html`).
  - Eventos personalizados de conversão disparados em cliques no WhatsApp, chamadas telefônicas e envio de formulário de contato.
- **SEO & Dados Estruturados (Schema.org JSON-LD):**
  - Schema `WebSite` na página principal e `LocalBusiness` + `FAQPage` na página AENTECH.
  - `sitemap.xml` atualizado com as URLs canônicas `https://fazhoje.com/` e `https://fazhoje.com/aentech/`.
  - `robots.txt` permitindo indexação total e apontando para o sitemap.
- **Open Graph & Twitter Cards:**
  - Imagem consistente em alta resolução (`static/aentech-card.jpg`) configurada para cards e compartilhamento no WhatsApp, Facebook e Twitter.
- **PWA & Webmanifests:**
  - `site.webmanifest` na raiz e `aentech/site.webmanifest` no subdomínio.

---

## 📁 Estrutura de Arquivos

```text
├── .github/
│   └── workflows/
│       └── pages.yml       # Deploy automatizado no GitHub Pages
├── aentech/
│   ├── index.html          # Subdomínio da assistência técnica AENTECH (com link para FazHoje)
│   └── site.webmanifest    # Manifest PWA da AENTECH
├── aentec/
│   └── index.html          # Redirecionamento amigável para /aentech/
├── static/
│   ├── css/
│   │   └── style.css       # Estilos CSS
│   ├── js/
│   │   └── main.js        # Scripts JS e eventos GA4
│   ├── aentech-card.jpg    # Imagem consistente de assistência técnica de celulares
│   ├── og-brand.png        # Imagem institucional de marca
│   ├── favicon.ico
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── apple-touch-icon.png
│   ├── android-chrome-192x192.png
│   └── android-chrome-512x512.png
├── 404.html                # Página de erro 404 personalizada
├── CNAME                   # Domínio próprio (fazhoje.com)
├── index.html              # Landing page principal (Hero + Card AENTECH + Contato)
├── modern.html             # Versão espelho da landing page
├── README.md               # Documentação do projeto
├── robots.txt              # Regras para motores de busca
├── site.webmanifest        # Manifest PWA do FazHoje
└── sitemap.xml             # Sitemap XML atualizado
```
