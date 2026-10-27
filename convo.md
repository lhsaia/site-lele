# 🎨 Planejamento de Projeto: Site para Tatuador
Documento de planejamento e especificações técnicas para criação do site de portfólio e captação de clientes.
## 🎯 Objetivos do Site
 1. **Portfólio Visual Impactante:** Destacar o trabalho do tatuador com foco visual e tema escuro (*dark aesthetic*).
 2. **Filtro de Atendimento via WhatsApp:** Reduzir o tempo gasto respondendo dúvidas repetitivas, direcionando o cliente com um orçamento já estruturado.
 3. **Autonomia:** Facilitar o envio de novos trabalhos/fotos no futuro sem necessidade de manutenção complexa.
## 📐 Estrutura das Seções do Site
 1. **Hero Banner (Apresentação):**
   * Imagem de destaque em alta qualidade.
   * Título marcante + estilo do artista.
   * Botão de Ação (CTA): *Solicitar Orçamento via WhatsApp*.
 2. **Galeria Interativa (Portfólio):**
   * Filtros por categoria: *Todos*, *Preto & Cinza (Blackwork)*, *Coloridos*, *Flashs Autorais*.
   * Modal Lightbox (zoom na imagem ao clicar).
 3. **Orçamento e Agendamento:**
   * **Formulário Inteligente:** O cliente preenche *Nome*, *Local do corpo*, *Tamanho em cm* e *Ideia/Descrição*. Ao enviar, abre o WhatsApp com os dados pré-formatados.
   * **WhatsApp Direto:** Botão de clique único para tirar dúvidas gerais.
 4. **Guia de Cuidados (Autoridade & Informação):**
   * Accordion (lista expansível) com dicas de Pré-Tattoo e Pós-Tattoo.
 5. **Rodapé & Botão Flutuante:**
   * Cidade/Estúdio, redes sociais e botão fixo de WhatsApp no canto da tela.
## 🛠️ Stack Técnica e Hospedagem
 * **Tecnologias:** HTML5, CSS3 moderno (Flexbox/Grid), JavaScript Vanilla.
 * **Hospedagem:** GitHub Pages (100% gratuito e estático).
 * **Estrutura de Arquivos Inicial:**
   ```text
   meu-repositorio/
   ├── index.html
   └── images/
       ├── tattoo-01.jpg
       ├── tattoo-02.jpg
       ├── flash-01.jpg
       └── estudio.jpg
   
   ```
## 🔄 Soluções Futuras para Gerenciamento de Fotos
| Opção | Como Funciona | Prós | Contras |
|---|---|---|---|
| **1. Upload via GitHub** | Subir arquivos na pasta /images e editar o HTML. | Sem ferramentas extras. | Exige mexer no código/GitHub. |
| **2. Decap CMS (Recomendado)** | Painel admin em /admin onde ele faz upload pelo celular/PC. | 100% visual, parece um blog, gratuito. | Requer configuração inicial de script. |
| **3. Feed do Instagram** | API/Widget puxa automaticamente posts do Instagram. | Zero trabalho manual para o tatuador. | Depende de limites da API externa. |
## 🚀 Checklist para Entrega da Surpresa
 * [ ] Criar repositório público no GitHub (ex: portfolio-tattoo).
 * [ ] Subir o código index.html gerado.
 * [ ] Baixar 6 a 12 fotos do Instagram dele e colocar na pasta images/.
 * [ ] Ativar a publicação em **Settings > Pages** no GitHub.
 * [ ] Atualizar o número do WhatsApp no código para o número dele.
 * [ ] Apresentar o protótipo e definir a melhor opção de gerenciamento futuro (Decap CMS ou Instagram).