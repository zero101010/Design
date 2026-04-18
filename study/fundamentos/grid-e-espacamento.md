# Grid e Espaçamento

O grid é a estrutura invisível que organiza os elementos em uma página. Sem um sistema de grid, elementos parecem jogados aleatoriamente. Com ele, a composição ganha ritmo, coerência e profissionalismo — mesmo quando o resultado parece "livre" e orgânico.

---

## O que é um Grid?

Um grid é uma série de linhas horizontais e verticais que dividem o espaço em unidades regulares. Ele não aparece no resultado final, mas é a base que garante alinhamento consistente entre todos os elementos.

---

## Tipos de Grid

### Grid de Colunas
O mais comum em design editorial e web. Divide a página em colunas verticais com calhas (gutters) entre elas.

- **2 colunas:** jornais, layouts simples
- **3 colunas:** muito usado em web
- **4-6 colunas:** revistas, catálogos
- **12 colunas:** padrão em desenvolvimento web (Bootstrap, CSS Grid) — flexível, pode ser dividido em 1, 2, 3, 4 ou 6 colunas

**Anatomia do grid de colunas:**
- **Margem:** espaço entre a borda do documento e o início do conteúdo
- **Coluna:** área onde o conteúdo se posiciona
- **Calha (Gutter):** espaço entre colunas
- **Margem interna (Padding):** espaço interno de cada coluna

### Grid de Baseline
Linhas horizontais espaçadas uniformemente para alinhar o texto. Garante que textos em colunas diferentes fiquem na mesma linha horizontal — essencial em editorial.

### Grid Modular
Combina colunas e linhas de baseline, criando módulos (células). Muito usado em design de sistemas, embalagens e tabelas.

### Grid Hierárquico
Não segue regras rígidas de colunas — é organizado pela importância dos elementos. Comum em design de cartazes e páginas iniciais de sites.

---

## Regra dos Terços

Dividindo qualquer imagem ou página em 9 partes iguais (3x3), os quatro pontos de intersecção são os pontos de maior tensão visual — onde o olho naturalmente descansa.

**Uso prático:**
- Posicione o elemento principal em um desses quatro pontos, não no centro geométrico
- Em fotografia, o horizonte deve ficar no terço superior ou inferior, não no meio
- Em composições gráficas, afastar elementos do centro absoluto cria mais dinamismo

---

## Espaço em Branco (Whitespace)

O espaço vazio **não é ausência de design** — é um elemento ativo que:
- Cria hierarquia (elemento cercado de espaço = mais importante)
- Aumenta a legibilidade
- Transmite sofisticação e luxo
- Separa grupos de informação (espaçamento como pontuação visual)

**Tipos:**
- **Macro whitespace:** grandes áreas de espaço vazio em torno de seções
- **Micro whitespace:** espaço entre letras (kerning/tracking), linhas (leading) e parágrafos

**Regra:** quando em dúvida, adicione mais espaço, não menos.

---

## Sistema de 8 Pontos (8pt Grid)

O sistema de grid de 8 pontos é o padrão do design digital moderno (usado pelo Google Material Design, Apple Human Interface Guidelines, etc.).

**Como funciona:**
- Todos os espaçamentos são múltiplos de 8: 8, 16, 24, 32, 40, 48, 64, 80...
- Tamanhos de componentes e ícones seguem a mesma grade
- Cria consistência automática e facilita a comunicação com desenvolvedores

**Por que 8?** A maioria das telas tem densidades de pixel que se dividem bem por 8.

---

## Proporções Clássicas

### Proporção Áurea (1:1.618)
A proporção encontrada na natureza, em conchas, folhas e pinturas renascentistas. Cria composições naturalmente agradáveis.
- Use para dimensionar a relação entre elemento principal e secundário
- O retângulo áureo pode guiar o posicionamento de elementos

### Seção Áurea na prática
- Uma página A4 está próxima da proporção áurea
- Divida um retângulo na razão 1:1.618 para criar divisões naturalmente harmoniosas

---

## Vídeos Recomendados

- **Canal Satori Graphics** (`youtube.com/@SatoriGraphics`) — busque *"grid systems graphic design"* e *"rule of thirds design"*
- **Canal The Futur** (`youtube.com/@TheFutur`) — busque *"layout design principles"*
- **Canal Figma** (`youtube.com/@Figma`) — busque *"auto layout grid"*; mostra como usar grids no Figma na prática

**Em português:**
- **Canal Popup Design** (`youtube.com/@popupdesign`) — busque *"grid design"* e *"espaçamento"*
- **Canal Escola de Design** (`youtube.com/@EscoladeDesign`) — busque *"grid tipográfico"*

## Artigos Recomendados

- **Smashing Magazine** — busque *"grid design layout"*; artigos técnicos aprofundados
- **Material Design Guidelines** (`m3.material.io`) — a documentação do Google explica o sistema de grid para digital de forma muito didática
- **Canva Design School** — busque *"grid design"*

---

## Exercício Prático

1. No Figma (gratuito), crie um frame A4
2. Configure um grid de 3 colunas com 20px de calha e 40px de margem
3. Posicione estes elementos: título, imagem, dois blocos de texto e um botão/chamada
4. Tente duas composições: uma com o título no terço superior esquerdo, outra centralizada
5. Compare qual parece mais profissional e por quê
