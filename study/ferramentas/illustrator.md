# Adobe Illustrator

Adobe Illustrator é o software padrão da indústria para criação de gráficos vetoriais — logos, ícones, ilustrações, tipografia personalizada e qualquer arte que precise ser escalável sem perda de qualidade. É uma ferramenta paga (parte da assinatura Adobe Creative Cloud), mas é a mais importante para um designer gráfico que trabalha com identidade visual.

---

## Vetor vs. Raster — Por que isso importa

**Raster (bitmap):** imagem formada por pixels (Photoshop, fotos). Perde qualidade ao ampliar.
**Vetor:** imagem formada por equações matemáticas (curvas e pontos). Escala infinitamente sem perda de qualidade.

Um logo **deve ser criado em vetor** porque precisará aparecer em um cartão de visita (5cm) e em um outdoor (10 metros) com a mesma qualidade.

---

## Conceitos Fundamentais

### Ancoragem e Caminhos (Paths e Anchor Points)
Toda forma vetorial é definida por pontos de ancoragem conectados por caminhos. Dominar a manipulação de pontos é a habilidade central do Illustrator.

**Tipos de pontos:**
- **Corner point:** cria ângulos retos e vértices afiados
- **Smooth point:** cria curvas suaves e contínuas

### Pen Tool (Ferramenta Caneta) — P
A ferramenta mais importante e mais difícil de dominar. Cria caminhos vetoriais com precisão total. Pratique até dominar.

**Dica:** use o site `bezier.method.ac` para praticar a pen tool gratuitamente no navegador.

### Pathfinder
Combina formas de maneiras diferentes:
- **Unite:** une todas as formas em uma só
- **Minus Front:** subtrai a forma da frente do fundo (para criar buracos)
- **Intersect:** mantém apenas a área de sobreposição
- **Exclude:** remove a área de sobreposição

### Shape Builder Tool — Shift+M
Alternativa mais intuitiva ao Pathfinder. Arraste sobre formas para uni-las, clique com Alt para remover.

### Clipping Mask
Usa uma forma como máscara para recortar outra imagem ou grupo. Essencial para colocar imagens dentro de formas.

---

## Roteiro de Aprendizado

**Semana 1 — Interface e formas básicas**
- [ ] Criar um documento com as configurações corretas (RGB para digital, CMYK para impressão)
- [ ] Usar as ferramentas de forma: retângulo, círculo, polígono, estrela
- [ ] Entender a diferença entre Fill (preenchimento) e Stroke (contorno)
- [ ] Mover, redimensionar e rotacionar objetos
- [ ] Trabalhar com cores e gradientes

**Semana 2 — Pen Tool e caminhos**
- [ ] Praticar pen tool no `bezier.method.ac`
- [ ] Criar formas simples com a pen tool no Illustrator
- [ ] Editar pontos de ancoragem com a Direct Selection Tool (A)
- [ ] Converter pontos corner ↔ smooth

**Semana 3 — Combinação de formas**
- [ ] Pathfinder: Unite, Minus Front, Intersect
- [ ] Shape Builder Tool
- [ ] Compound Paths
- [ ] Clipping Mask

**Semana 4 — Tipografia**
- [ ] Criar e editar texto
- [ ] Texto em caminho (texto que segue uma curva)
- [ ] Converter texto em vetor (Outline Type): ⌘⇧O / Ctrl+Shift+O
- [ ] Kerning e tracking manual

**Semana 5 — Fluxo de trabalho profissional**
- [ ] Organização com layers e grupos
- [ ] Artboards (múltiplas pranchas em um documento)
- [ ] Exportar para diferentes formatos: SVG, PDF, PNG, EPS
- [ ] Preparar arquivo para impressão (sangria, marcas de corte, CMYK)

---

## Atalhos Essenciais

| Ação | Atalho (Mac) | Atalho (Windows) |
|------|-------------|-----------------|
| Selection Tool | V | V |
| Direct Selection Tool | A | A |
| Pen Tool | P | P |
| Type Tool | T | T |
| Zoom in/out | ⌘+/- | Ctrl+/- |
| Fit page | ⌘0 | Ctrl+0 |
| Agrupar | ⌘G | Ctrl+G |
| Pathfinder | ⌘⇧F9 | Ctrl+Shift+F9 |
| Outline Type | ⌘⇧O | Ctrl+Shift+O |
| Save as PDF | ⌘⇧S (Salvar como) | Ctrl+Shift+S |

---

## Formatos de Arquivo — Quando usar cada um

| Formato | Uso |
|---------|-----|
| `.ai` | Arquivo nativo do Illustrator — sempre mantenha este |
| `.svg` | Vetor para web — escala sem perda, pode ser editado com código |
| `.eps` | Compartilhar com gráficas e impressoras — padrão da indústria de impressão |
| `.pdf` | Envio para aprovação e para gráfica |
| `.png` | Exportar com fundo transparente para uso digital |
| `.jpg` | Exportar para uso digital onde transparência não é necessária |

---

## Vídeos Recomendados

- **Canal Adobe Creative Cloud** (`youtube.com/@AdobeCreativeCloud`) — série oficial *"Illustrator for Beginners"*; ponto de partida ideal
- **Canal Dansky** (`youtube.com/@dansky`) — tutoriais de logo design no Illustrator; muito práticos e diretos
- **Canal Will Paterson** (`youtube.com/@WillPaterson`) — busque *"logo design Illustrator"*; processo real de criação de logos
- **Canal Satori Graphics** (`youtube.com/@SatoriGraphics`) — busque *"Illustrator tips"* e *"pen tool"*; dicas de fluxo de trabalho
- **Canal How to Graphic Design** — busque *"Illustrator beginner"*; didático para iniciantes

**Em português:**
- **Canal Popup Design** (`youtube.com/@popupdesign`) — busque *"Illustrator"*; tutoriais em PT-BR
- **Canal Escola de Design** (`youtube.com/@EscoladeDesign`) — busque *"Adobe Illustrator tutorial"*

## Artigos e Documentação

- **Adobe Illustrator Tutorials** (`helpx.adobe.com/illustrator/tutorials.html`) — tutoriais oficiais em vídeo e texto, organizados por nível
- **Adobe Illustrator User Guide** (`helpx.adobe.com/illustrator/user-guide.html`) — documentação completa de todas as ferramentas

## Cursos

- **Udemy** — busque *"Adobe Illustrator"*; cursos com projetos reais de logo design
- **Skillshare** — boa seleção de cursos de identidade visual com Illustrator

---

## Projeto de Prática Sugerido

Crie um logo simples para uma marca fictícia usando **apenas formas geométricas e pen tool** — sem fontes decorativas. Exemplos: um ícone de folha, uma xícara estilizada, um pássaro geométrico. Exporte em `.ai`, `.svg` e `.png`.
