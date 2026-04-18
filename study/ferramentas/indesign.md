# Adobe InDesign

InDesign é o software padrão para diagramação editorial — livros, revistas, catálogos, jornais, relatórios, zines e qualquer material com múltiplas páginas. É onde texto longo e imagens são combinados em layouts estruturados, prontos para impressão profissional ou publicação digital.

---

## Quando Usar InDesign

- Qualquer projeto com **mais de 2 páginas**
- Material para impressão profissional que exige controle preciso de tipografia
- Publicações com padrão consistente entre páginas (cabeçalho, rodapé, numeração)
- Livros, revistas, relatórios anuais, catálogos, cardápios elaborados
- Zines, lookbooks, apresentações editoriais

**Quando NÃO usar InDesign:**
- Logos e ícones (use Illustrator)
- Interfaces digitais (use Figma)
- Edição de fotos (use Photoshop)
- Flyers simples de página única (pode usar Illustrator)

---

## Conceitos Fundamentais

### Master Pages (Páginas Mestras)
Templates aplicados a múltiplas páginas. Tudo o que está na Master Page aparece em todas as páginas que a utilizam (cabeçalho, número de página, logo, grid). Altere a Master e todas as páginas atualizam automaticamente.

### Text Frames
No InDesign, o texto vive dentro de caixas de texto. Caixas podem ser vinculadas — quando o texto transborda de uma caixa, continua automaticamente na próxima.

### Paragraph Styles e Character Styles
Estilos de parágrafo definem a aparência de cada nível de texto (título, subtítulo, corpo, legenda). Criar estilos e aplicá-los consistentemente é o trabalho central do InDesign. Altere um estilo e todo o texto que usa aquele estilo atualiza de uma vez.

### Baseline Grid
Linhas horizontais que garantem que o texto de todas as colunas fique alinhado horizontalmente — fundamental para qualidade editorial.

### Preflight
Verificação automática antes de exportar que aponta problemas: imagens com baixa resolução, fontes faltando, cores RGB em documento de impressão, caixas de texto com overflow (texto que não cabe).

### Sangria (Bleed)
Área extra além da borda do documento para que elementos que vão "até a borda" sejam cortados corretamente na gráfica, sem deixar fios brancos. Padrão: **3mm** de sangria em todos os lados para impressão profissional.

---

## Roteiro de Aprendizado

**Semana 1 — Interface e documentos**
- [ ] Criar um documento com múltiplas páginas, margens, colunas e sangria
- [ ] Entender o painel de Pages
- [ ] Criar e navegar entre Master Pages
- [ ] Criar caixas de texto e de imagem
- [ ] Colocar imagens: File > Place (⌘D / Ctrl+D)

**Semana 2 — Tipografia editorial**
- [ ] Character panel e Paragraph panel
- [ ] Criar Paragraph Styles (H1, H2, body text, caption)
- [ ] Aplicar estilos a todo o documento
- [ ] Trabalhar com Baseline Grid
- [ ] Texto em múltiplas colunas com vinculação de caixas

**Semana 3 — Imagens e layout**
- [ ] Place de imagens (TIFF, PSD com camadas, PDF, PNG)
- [ ] Fit Content Proportionally vs. Fill Frame Proportionally
- [ ] Wrap Text (texto que contorna imagens)
- [ ] Criar tabelas
- [ ] Trabalhar com guides e grids

**Semana 4 — Publicação e impressão**
- [ ] Preflight: verificar erros antes de exportar
- [ ] Exportar PDF para impressão (PDF/X-1a ou PDF/X-4)
- [ ] Exportar PDF interativo para digital
- [ ] Exportar EPUB (publicação digital)
- [ ] Preparar arquivos com Package (reúne fontes e imagens)

---

## Atalhos Essenciais

| Ação | Atalho (Mac) | Atalho (Windows) |
|------|-------------|-----------------|
| Selection Tool | V (ou Esc) | V (ou Esc) |
| Direct Selection | A | A |
| Type Tool | T | T |
| Place (importar) | ⌘D | Ctrl+D |
| Zoom | ⌘+/- | Ctrl+/- |
| Fit page in window | ⌘0 | Ctrl+0 |
| Guides visíveis | ⌘; | Ctrl+; |
| Baseline grid visível | ⌘⌥' | Ctrl+Alt+' |
| Visualizar sem guides | W | W |
| Paragraph Styles panel | F11 | F11 |

---

## Fluxo de Trabalho com Outros Softwares

InDesign não existe em isolamento — ele recebe arquivos de outros programas:

- **Illustrator (.ai / .pdf):** logos e gráficos vetoriais colocados via Place
- **Photoshop (.psd):** fotos e composições colocadas via Place (com camadas preservadas)
- **Fontes:** instaladas no sistema e disponíveis em todos os softwares Adobe

**Regra:** nunca cole diretamente imagens no InDesign. Sempre use File > Place para que o link seja mantido. Assim, se você editar a imagem no Photoshop, o InDesign atualiza automaticamente.

---

## Vídeos Recomendados

- **Canal Adobe Creative Cloud** (`youtube.com/@AdobeCreativeCloud`) — série *"InDesign for Beginners"*; ponto de partida oficial
- **Canal Yes I'm a Designer** — busque *"InDesign tutorial"*; projetos completos passo a passo
- **Canal Dansky** (`youtube.com/@dansky`) — busque *"InDesign magazine layout"*; foco em layout editorial
- **Canal Envato Tuts+** (`youtube.com/@tutsplus`) — busque *"InDesign"*; tutoriais variados incluindo zines, catálogos e revistas

## Artigos e Documentação

- **Adobe InDesign Tutorials** (`helpx.adobe.com/indesign/tutorials.html`) — tutoriais oficiais
- **InDesign Secrets** (`indesignsecrets.com`) — blog especializado com dicas avançadas

---

## Projeto de Prática Sugerido

Crie um zine de 8 páginas (A5 dobrado = A4) com tema livre:
1. Configure o documento com 8 páginas, tamanho A5, 3mm de sangria
2. Crie uma Master Page com número de página e cabeçalho
3. Crie Paragraph Styles para título, subtítulo, corpo e legenda
4. Diagramme conteúdo misto (texto + imagem) em todas as páginas
5. Faça o Preflight e exporte um PDF para impressão
