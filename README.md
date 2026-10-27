# LeleTattoo · Estúdio de Tatuagem Autoral

> Website institucional, portfólio interativo e gerador de orçamentos para o estúdio autoral de tatuagem **Lelê Tattoo** (Vinicius Lelê), localizado em Morro Agudo – SP.

[![Licença MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Produção-success.svg)](#)
[![Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20TailwindCSS%20%7C%20Vanilla%20JS-14171f.svg)](#)

---

## ⚡ Sobre o Projeto

O **site-lele** foi concebido com foco em direção de arte editorial e visual autoral (estilo dark, sem templates clichês), traduzindo a identidade de traços firmes, blackwork sólido e projetos exclusivos desenvolvidos pelo tatuador Vinicius Lelê.

O foco central da experiência do usuário é encurtar o caminho entre a visualização das obras e o fechamento do orçamento, utilizando uma integração direta com o WhatsApp sem a necessidade de intermediários ou formulários tradicionais lentos por e-mail.

---

## ✨ Funcionalidades Principais

* **🎯 Direção de Arte & Tipografia Editorial:**
  * Tipografia display marcante (*Syne*) combinada com fonte de leitura editorial limpa (*Epilogue*).
  * Paleta escura profunda (`#0c0d10`, `#14171f`) com acentos em vermelho carmesim (`#dc2626`).
* **🖼️ Portfólio Interativo & Filtro de Categorias:**
  * Filtros dinâmicos em tempo real: *Todos*, *Blackwork & Linhas*, *Flashs Autorais* e *Coloridos & Sombras*.
  * Modal **Lightbox** de alta resolução ao clicar em qualquer peça, exibindo título, categoria, descrição do trabalho e botão para orçar a arte específica.
* **💬 Formulário Inteligente de Orçamento via WhatsApp:**
  * O cliente informa: *Nome*, *Local do corpo*, *Tamanho em cm*, *Estilo* e *Descrição da ideia*.
  * O script gera instantaneamente uma mensagem estruturada com formatação nativa do WhatsApp (`*negrito*`, divisores) e abre o chat diretamente com o artista, com o texto já pronto para envio.
* **🩺 Guia Prático de Cuidados:**
  * Acordeões interativos com orientações essenciais divididas em:
    * *Antes da Sessão* (preparação da pele, alimentação e hidratação).
    * *Primeiros 3 Dias* (filme protetor, higienização e pomada).
    * *Cicatrização Completa até 30 dias* (sol, hidratação e proteção).
* **📱 100% Responsivo (Mobile-First):**
  * Otimizado para smartphones, tablets e monitores de alta densidade (Retina/4K).
  * Botão de contato rápido flutuante no canto inferior direito.
* **💀 Identidade Visual & Favicon Exclusivo:**
  * Favicon com silhueta de caveira preta sobre círculo carmesim em múltiplos formatos: `favicon.svg` (vetorial), `favicon.png` e `favicon.ico`.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico:** Estruturação acessível e otimizada para SEO local.
* **Tailwind CSS:** Estilização utilitária rápida com extensões personalizadas de cores e fontes.
* **Vanilla JavaScript:** Lógica de filtragem da galeria, modal lightbox e montagem de URLs do WhatsApp sem dependências externas.
* **Google Fonts:** Famílias tipográficas *Syne* e *Epilogue*.

---

## 📂 Estrutura de Arquivos

```text
site-lele/
├── index.html         # Página principal da aplicação
├── favicon.svg        # Favicon vetorial (SVG)
├── favicon.png        # Favicon em alta resolução (PNG)
├── favicon.ico        # Ícone de compatibilidade (ICO)
├── images/            # Fotografias do estúdio, artista e portfólio
├── convo.md           # Notas e especificações de contexto
├── LICENSE            # Licença de uso de código aberto (MIT)
└── README.md          # Documentação do projeto
```

---

## 🚀 Como Executar Localmente

Como o projeto é estático e não requer etapas de compilação ou instalação de pacotes:

1. Clone o repositório:
   ```bash
   git clone https://github.com/lhsaia/site-lele.git
   cd site-lele
   ```

2. Abra o arquivo `index.html` diretamente em seu navegador preferido ou use um servidor local simples:

   **Com Python 3:**
   ```bash
   python -m http.server 3000
   ```
   Acesse: `http://localhost:3000`

   **Com VS Code:**
   Basta clicar com o botão direito em `index.html` e selecionar **"Open with Live Server"**.

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).

---

Feito com dedicação para **Lelê Tattoo** · Morro Agudo – SP.
