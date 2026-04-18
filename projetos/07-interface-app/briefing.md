# Projeto 07 — Interface de Aplicativo

## Briefing do Cliente

**Produto fictício:** Vereda — App de Trilhas e Caminhadas
**Plataforma:** iOS (iPhone)
**Público-alvo:** Caminhantes iniciantes e intermediários, 18-45 anos, interesse em natureza e bem-estar
**Tom:** Funcional e calmo, sem excessos — como a natureza

**Sobre o produto:**
Vereda é um app de trilhas que ajuda caminhantes a descobrir novas rotas, registrar suas caminhadas e compartilhar com amigos. O diferencial é o foco em trilhas dentro e próximas a cidades brasileiras — não apenas parques nacionais, mas também áreas verdes urbanas, parques estaduais e trilhas de bairro acessíveis para iniciantes.

**Funcionalidades principais (para este projeto, apenas UI — não é necessário implementar):**
1. Tela de descoberta de trilhas próximas
2. Tela de detalhe de uma trilha específica
3. Tela de registro de uma caminhada em andamento (durante a trilha)

---

## Escopo do Projeto

Criar o **design de interface (UI)** de **3 telas** do app Vereda, com protótipo clicável básico conectando as telas.

Este projeto **não exige** programação — é design de tela, não desenvolvimento de app.

---

## Metas do Projeto

1. A interface deve ser **intuitiva** — um usuário que nunca usou o app deve entender o que fazer na primeira vez
2. Os elementos devem seguir as **diretrizes de acessibilidade** básicas: contraste suficiente, tamanhos de toque corretos (mínimo 44x44px), texto legível (mínimo 16px)
3. A identidade visual deve transmitir **natureza + tecnologia funcional** — não genérico, não excessivamente "verde"
4. O protótipo deve demonstrar o **fluxo básico**: ver trilha → abrir detalhe → iniciar caminhada

---

## As 3 Telas

### Tela 1 — Feed de Descoberta
Mostra trilhas próximas à localização do usuário.

**Elementos obrigatórios:**
- Barra de busca
- Filtros: dificuldade, distância, tempo estimado
- Cards de trilha: foto, nome, distância da localização atual, dificuldade (ícone), avaliação (estrelas)
- Mínimo de 4 cards visíveis (com scroll implícito)
- Barra de navegação inferior (tab bar)

### Tela 2 — Detalhe da Trilha
Informações completas de uma trilha específica.

**Elementos obrigatórios:**
- Foto de cabeçalho (hero image)
- Nome e localização da trilha
- Dados principais: distância total, tempo estimado, nível de dificuldade, ganho de altitude
- Mapa estático (placeholder retangular é suficiente)
- Seção de avaliações/comentários (pode ser simplificada)
- Botão principal de ação: "Iniciar Trilha"
- Botão de salvar/favoritar

### Tela 3 — Caminhada em Andamento
Interface minimalista mostrada durante a caminhada.

**Elementos obrigatórios:**
- Mapa ocupando a maior parte da tela (placeholder)
- HUD sobreposto: tempo decorrido, distância percorrida, velocidade atual
- Botão de pausar/encerrar a caminhada
- Botão de adicionar foto do momento

---

## Direção Visual Sugerida

**Sistema de cores:**
- Base: cores neutras (branco, cinza muito claro) para legibilidade
- Cor primária: um verde terroso, verde petróleo ou teal — não verde vibrante/néon
- Cor de acento: para botões de ação principal e dados de destaque

**Tipografia:**
- Sans-serif humanista ou geométrica para boa legibilidade em tela
- Sugestões: Inter, DM Sans, Outfit, Nunito — todas disponíveis no Google Fonts

**Ícones:**
- Use uma biblioteca consistente: Phosphor Icons ou Material Symbols (ambas com plugin no Figma)

**Fotos de placeholder:**
- Use imagens do Unsplash de trilhas brasileiras: busque "trail Brazil", "hiking mata atlântica", "parque nacional"

---

## Processo Sugerido

### Etapa 1 — Pesquisa e Referências (1-2 dias)
- [ ] Instalar apps de trilha reais: AllTrails, Wikiloc, TrailForks — analisar a UX deles
- [ ] Pesquisar UI de apps de outdoor no Dribbble e Behance
- [ ] Criar moodboard visual: paleta de cores, tipografias, estilo de cards

### Etapa 2 — Wireframes (1-2 dias)
- [ ] Fazer wireframes à mão (baixa fidelidade) das 3 telas — apenas layout, sem estilo
- [ ] Definir: onde fica cada elemento? Qual é a hierarquia de informação em cada tela?
- [ ] Validar: o fluxo faz sentido? Um usuário entenderia?

### Etapa 3 — Design das Telas no Figma (4-6 dias)
- [ ] Criar um Frame no tamanho iPhone 14 Pro (393x852px)
- [ ] Criar os estilos de cor e tipografia antes de começar as telas
- [ ] Criar components reutilizáveis: card de trilha, barra de navegação, botão primário
- [ ] Desenhar cada tela com atenção à hierarquia e ao espaçamento

### Etapa 4 — Prototipagem (1 dia)
- [ ] Conectar as 3 telas no Prototype Mode do Figma
- [ ] Testar o fluxo: Tela 1 → clique no card → Tela 2 → clique em "Iniciar" → Tela 3

---

## Ferramentas Sugeridas

- **Figma** (obrigatório e gratuito) — todo o projeto
- **Plugins Figma:** Unsplash (para inserir fotos direto), Iconify ou Phosphor Icons (ícones)
- **Material Design 3** (`m3.material.io`) — referência de boas práticas de UI

---

## Resultado Esperado

**Arquivos a entregar:**
- Arquivo `.fig` com as 3 telas + protótipo
- 3 frames exportados em PNG (para a apresentação)
- Link de protótipo compartilhável do Figma (gratuito)

**Apresentação no portfólio:**
- Contexto: o que é o Vereda e quem usa
- Wireframes (fotos dos rascunhos à mão ou wireframes digitais simples)
- As 3 telas com boa apresentação visual
- Decisões de design explicadas: por que essas cores? Por que esse layout?
- GIF ou vídeo do protótipo em funcionamento (Figma permite gravar)
- Mockup em iPhone (Figma Community tem templates de mockup de celular)

**Critério de sucesso:**
Alguém sem explicação prévia consegue entender o fluxo e navegar pelo protótipo sem dúvidas. Os dados são legíveis, os botões são fáceis de tocar e a interface parece consistente entre as 3 telas.

---

## Estimativa de Tempo
15 a 25 horas distribuídas em 2 a 3 semanas
