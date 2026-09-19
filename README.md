# Brincando pelo Mundo — Brasil & México

Site estático responsivo para a **Feira Cultural do Infantil 1**, unindo a UI/UX moderna com o conteúdo detalhado do projeto e os materiais visuais produzidos para a feira.

## O que foi integrado
- UI/UX responsivo, com navegação mobile, modo claro/escuro, barra de progresso, animações suaves e acessibilidade.
- Pesquisa e filtros para as 17 propostas do projeto: Brasil, México e produções artísticas.
- Modais com o conteúdo completo de cada proposta e as páginas correspondentes dos PDFs.
- Galeria com as 33 páginas dos materiais visuais.
- Seções de apresentação, México, história, cultura, brincadeiras, experiências, galeria e considerações finais.
- Responsáveis: Professora Cibele, Tia Eli e Tia Bruna.
- Nome da escola no rodapé: **Brincando e Criando**.
- PDFs originais preservados em `docs/`.

## Estrutura
- `index.html` — página principal
- `css/styles.css` — UI/UX responsivo
- `js/data.js` — conteúdo das 17 propostas
- `js/app.js` — filtros, busca, modais, galeria, menu mobile, tema e animações
- `assets/atividades/` — 33 páginas dos PDFs em WebP
- `docs/` — PDFs originais enviados

## Publicação
Pode ser publicado diretamente em Vercel, Netlify ou GitHub Pages. Não há build nem dependências de Node.

## Font Awesome
Os ícones usam Font Awesome via CDN. Para máxima estabilidade offline, o conteúdo principal continua funcionando mesmo sem os ícones externos.

## Pesquisa complementar do México
A seção geral do México foi complementada com fontes institucionais e de patrimônio cultural indicadas na própria página, incluindo INEGI, UNESCO, Secretaría de Cultura e INAH.


### Ajuste de bandeira do México
Os emojis 🇲🇽 foram substituídos por uma imagem real da bandeira do México (FlagCDN), evitando que navegadores Windows exibam as letras “MX”. A imagem é usada diretamente no HTML e nas áreas correspondentes do site.
