# 🌹 POMBAGIRAS.COM | Conhecimento Sagrado & Arte Visceral

> *O olho que tudo vê nas encruzilhadas do mundo. Desmistificando o feminino proibido através da tecnologia e da ancestralidade.*

---

## ⚡ Visão Geral

Landing page de página única dedicada ao universo das **Pombagiras** — entidades femininas da Umbanda e Quimbanda que guardam as encruzilhadas, os ciclos da vida e a força transformadora do feminino sagrado.

**Estética:** Gótico-Abyssal / Dark-Chic  
**Paleta:** Vermelho, Roxo, Preto  
**Tecnologias:** HTML5 + CSS3 puro (Glassmorphism, Mobile First, Hover Filter Effect)  
**JavaScript:** Geração dinâmica de cards, modais informativos, FAQ, glossário e bibliografia.

🔗 **Demo/Acesso:** [https://pombagiras.com](https://pombagiras.com) *(hospedagem futura)*

---

## ✨ Funcionalidades principais

- **24 cards de Pombagiras** — dados estruturados em JSON, renderização dinâmica, cada uma com imagem, nome e modal com ficha técnica detalhada.
- **Efeito Hover Filter / Color Reveal** — imagens em tons de cinza com brilho reduzido, revelando cores originais ao passar o mouse (*transition: 0.6s*).
- **Glassmorphism** — cards, modais e seções com fundo translúcido, blur e bordas rubras.
- **Responsividade total** — Mobile First, grid fluido, tipografia adaptável.
- **Modais interativos** — ao clicar em "Ficha Detalhada", abre pop-up com fatos históricos e avisos sobre a entidade.
- **FAQ** — Perguntas e respostas sobre Pombagiras (expansível via clique).
- **Glossário de Termos Sagrados** — Axé, Exu Mirim, Quimbanda, Encruzilhada, Falange, Ponto Riscado.
- **Bibliografia Recomendada** — Livros, filmes e documentários sobre o tema.
- **Redes sociais minimalistas** — 17+ links ativos (TikTok, Instagram, YouTube, Spotify, GitHub, Discord, Telegram, WhatsApp, Linktree, etc.)
- **Footer profissional** — copyright, selo de identidade, navegação simples.
- **Meta tags e SEO** — Open Graph, Twitter Card, favicon personalizado.

---

## 🧬 Estrutura do projeto

> **Nota:** Todas as imagens das entidades e banners estão hospedadas em repositórios públicos do GitHub, via links brutos (raw). Nenhum arquivo local necessário.

---

## 🖼️ Lista das 24 Pombagiras incluidas

| Nome da Pombagira | Nome da Pombagira |
|------------------|------------------|
| Pombagira Cigana | Pombagira da Lua |
| Pombagira da Figueira | Pombagira da Serra |
| Pombagira da Praia | Pombagira da Sombra |
| Dama da Noite | Pombagira das Águas Profundas |
| Maria Farrapo | Pombagira das Almas |
| Maria Mulambo | Pombagira das Trevas |
| Maria Navalha | Pombagira do Fogo |
| Maria Padilha | Sete Encruzilhadas |
| Maria Quitéria | Pombagira da Fenda |
| Menina (Pombagira Menina) | Pombagira da Calunga Profunda |
| Rosa Caveira | Pombagira da Neblina |
| Sete Saias | Pombagira das Correntes |

*(Cada uma com imagem, fatos espirituais e avisos no modal)*

---

## 🎨 Design & Interatividade

- **Filtros CSS:** `grayscale(0.8) brightness(0.7)` nas imagens, revelando cor no hover (`grayscale(0) brightness(1)`).
- **Glassmorphism:** `backdrop-filter: blur(12px)` + bordas translúcidas.
- **Tipografia:** *Playfair Display* (títulos serifados) + *Inter* (corpo sem serifa).
- **Transições suaves:** `transition: 0.6s cubic-bezier()`.
- **Grid responsivo:** `grid-template-columns: repeat(auto-fill, minmax(260px, 1fr))`.

---

## 🧠 Conteúdo Sagrado

### Curiosidades sobre Pombagiras
- Pombagira não é "diaba" — guardiã dos ciclos femininos.
- Arquétipos múltiplos: cada uma carrega uma energia única.
- Cores e oferendas: velas vermelhas, rosas, champagne.
- Maria Padilha e Sete Saias: poder feminino e sensualidade sagrada.

### FAQ (exemplos)
- O que significa Pombagira na Umbanda?
- Pombagira é a mesma coisa que Exu?
- Posso cultuar Pombagira sem ser iniciado?
- Qual a diferença entre Maria Padilha e Maria Mulambo?

### Glossário
- **Axé** — energia vital.
- **Exu Mirim** — mensageiro veloz.
- **Quimbanda** — culto às almas e exus.
- **Encruzilhada** — portal energético.
- **Falange** — grupo de entidades.
- **Ponto Riscado** — assinatura energética.

### Bibliografia Recomendada
- *Pombagira – A Face Feminina de Exu* (Alexandre Cumino)
- *Umbanda: A Proto-síntese Cósmica* (Rubens Saraceni)
- Documentário *Encruzilhadas da Alma*
- Filme *Besouro*

---

## 🔗 Redes Sociais e Links Integrados

A landing page contém **ícones minimalistas** (estilo cápsula escura) com links para:

- TikTok, Instagram, Threads, Kwai
- Spotify, Behance, Substack, YouTube
- Telegram, WhatsApp Channel, Discord
- Bio.site, Linktree, Canva
- GitHub (3 perfis: `pombagiras`, `Orgulho-Trans`, `alexialuzdeferro`)

Todos abrem em nova aba com `target="_blank"`.

---

## 📱 Responsividade & Performance

- ✅ Mobile First (media queries para desktop)
- ✅ Imagens com `loading="lazy"`
- ✅ Sem bibliotecas externas (CSS/JS puro)
- ✅ Cards gerados via JavaScript (código limpo e escalável)
- ✅ JSON embutido para fácil manutenção

---

## 🧪 Como usar

1. Copie todo o conteúdo do arquivo **`index.html`** (presente neste repositório).
2. Cole no seu editor de código ou diretamente no GitHub Pages / hospedagem.
3. Substitua os links de imagens ou textos se desejar personalizar.
4. Faça o deploy no GitHub Pages, Netlify ou qualquer servidor estático.

```bash
# Exemplo de deploy rápido com GitHub Pages:
git clone https://github.com/seu-usuario/pombagiras-landing.git
cd pombagiras-landing
# cole o index.html
git add .
git commit -m "Landing page Pombagiras"
git push origin main
# Ativar GitHub Pages nas configurações do repositório
