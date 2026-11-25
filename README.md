# PisoFácil — Landing Page de Restauração de Pisos de Madeira

> **"Madeira que fica. Histórias que seguem."**  
> Site institucional e de captação de orçamentos para Daniel Laranjeira, profissional autônomo de restauração de pisos de madeira em Ibiúna e região — SP.

---

## 📋 Visão Geral

**PisoFácil** é uma landing page estática desenvolvida com foco em conversão via WhatsApp. O objetivo central é apresentar os serviços de restauração e revitalização de pisos de madeira de Daniel Laranjeira de forma clara, visualmente refinada e orientada a um público de casas, sítios e chácaras na região de Ibiúna/SP.

O site foi desenvolvido com tecnologias web puras — sem frameworks ou dependências externas —, garantindo leveza, desempenho e facilidade de manutenção.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura semântica da página |
| **CSS3 (Puro)** | Estilização completa, layout e responsividade |
| **JavaScript (Puro)** | Interações dinâmicas (FAQ accordion, navegação ativa) |
| **Google Fonts** | Tipografia: `Cormorant Garamond` (serif elegante) + `Inter` (sans-serif) |
| **SVG** | Ícones e logotipo vetoriais |

> Sem frameworks CSS, sem bibliotecas JS, sem dependências de build.

---

## 🗂️ Estrutura de Arquivos

```
Piso-Fácil-Final/
│
├── index.html              # Página principal (única)
├── style.css               # Todos os estilos da página
├── app.js                  # JavaScript de interatividade
│
└── assets/                 # Mídias e ícones
    ├── hero-piso.png               # Imagem principal (hero)
    ├── comparacao-ambiente.png     # Imagem da comparação Antes/Depois
    ├── contato-ambiente.png        # Imagem da seção de contato
    ├── sobre-oficio.png            # Imagem da seção Sobre
    ├── servico-restauracao.png     # Foto do serviço Restauração
    ├── servico-revitalizacao.png   # Foto do serviço Revitalização
    ├── servico-acabamentos.png     # Foto do serviço Acabamentos
    ├── estudo-01.png a 06.png      # Estudos de ambiente (galeria)
    ├── logo-simbolo.svg            # Logo no header
    ├── logo-simbolo-footer.svg     # Logo no footer
    ├── icon-arrow-up-right.svg     # Ícone de link externo
    ├── icon-chevrons.svg           # Ícone do comparador Antes/Depois
    ├── icon-house.svg              # Ícone de casa
    ├── icon-info.svg               # Ícone de aviso
    ├── icon-leaf.svg               # Ícone sustentabilidade
    ├── icon-map-pin.svg            # Ícone de localização (pequeno)
    ├── icon-map-pin-22.svg         # Ícone de localização (médio)
    ├── icon-message-circle.svg     # Ícone WhatsApp
    ├── icon-message-circle-green.svg # Ícone WhatsApp verde
    ├── icon-minus.svg              # Ícone recolher FAQ
    ├── icon-plus.svg               # Ícone expandir FAQ
    └── icon-tree.svg               # Ícone de árvore
```

---

## 📄 Seções da Página

A página é estruturada como um fluxo narrativo em **9 seções** que guiam o visitante da apresentação ao contato:

### 1. `#inicio` — Hero (Apresentação Principal)
- Título editorial de impacto com tipografia serif
- Badge de localização: **Ibiúna e região · SP**
- Botão primário de CTA: **"Pedir orçamento no WhatsApp"**
- Link secundário para a seção Antes e Depois
- Imagem hero de ambiente com piso de madeira restaurado
- Legenda editorial sobreposta à imagem

### 2. Barra de Compromissos
- Três pilares do serviço exibidos horizontalmente:
  - 🌳 **Valorizar a madeira existente** — Preservar antes de substituir
  - 💬 **Contato direto com Daniel** — Conversa simples pelo WhatsApp
  - 🏠 **Para o seu lugar de viver** — Casas, sítios e chácaras

### 3. `#servicos` — Serviços
Grid de **3 serviços** com foto, número, tagline e descrição:

| # | Serviço | Descrição |
|---|---|---|
| 01 | **Restauração** | Pisos com desgaste, riscos ou acabamento comprometido |
| 02 | **Revitalização** | Renovação de pisos que ainda estão em boas condições |
| 03 | **Acabamentos** | Orientação sobre opções de proteção e acabamento |

### 4. `#antes-e-depois` — Galeria
- **Comparação visual** Antes/Depois com overlay estático e handle central
- **6 estudos de ambiente** em grid 3×2 com hover suave (scale)
- Aviso explícito de que as imagens são ilustrativas

### 5. `#como-funciona` — Como Pedir Orçamento
Processo em **3 etapas** simples:
1. Mostrar o piso (fotos via WhatsApp + localização)
2. Entender as possibilidades (conversa com Daniel + avaliação)
3. Decidir com clareza (serviço, valor e condições)

### 6. `#sobre` — Sobre Daniel Laranjeira
- Apresentação pessoal do profissional autônomo
- Destaque para o contato direto sem intermediários
- Informação de área de atendimento: Ibiúna e região

### 7. Banner de Preservação / Sustentabilidade
- Mensagem editorial sobre a preservação da madeira
- Argumento ambiental: restaurar antes de descartar
- Ícone de folha e blockquote de impacto

### 8. `#faq` — Perguntas Frequentes
Accordion nativo com `<details>` / `<summary>` — 5 perguntas:
- Todo piso de madeira pode ser restaurado?
- Quanto custa o serviço?
- Quanto tempo leva e quando posso usar o ambiente?
- É preciso retirar móveis? E a poeira?
- Como cuidar do piso depois?

### 9. `#contato` — Contato e Orçamento
- Imagem de ambiente acolhedor
- Sugestão de mensagem inicial para o WhatsApp
- CTA final: botão + indicação regional

---

## 🎨 Design System

### Paleta de Cores (CSS Variables)

| Variável | Valor | Uso |
|---|---|---|
| `--bg-primary` | `#F7F4ED` | Fundo principal (creme claro) |
| `--bg-sand` | `#EAE4D8` | Fundo seção galeria |
| `--bg-card` | `#FEFCF7` | Fundo de cards |
| `--color-brand` | `#254B3B` | Verde escuro principal |
| `--color-brand-hover` | `#1C3A2E` | Verde hover |
| `--color-accent-wood` | `#8D6B4D` | Marrom madeira (acentos) |
| `--color-text-dark` | `#2D3028` | Texto principal |
| `--color-text-muted` | `#66675D` | Texto secundário |
| `--color-border` | `#D5CFC2` | Bordas e divisores |
| `--color-footer-bg` | `#1E3C30` | Fundo do rodapé |

### Tipografia

| Fonte | Família | Uso |
|---|---|---|
| **Cormorant Garamond** | Serif | Títulos, quotes, nomes de serviços |
| **Inter** | Sans-serif | Corpo de texto, botões, labels |

### Layout

- Largura máxima: **1440px** (`--max-content-width`)
- Padding horizontal: **72px** (`--page-padding-x`)
- Altura do header: **100px** (`--header-height`)

---

## ⚙️ Como Usar / Configurar

### 1. Clonar o projeto

```bash
git clone <url-do-repositorio>
cd Piso-Fácil-Final
```

### 2. Abrir no navegador

Por ser uma página estática, basta abrir o arquivo diretamente:

```bash
# Opção 1: abrir direto
start index.html

# Opção 2: servir localmente (recomendado)
npx serve .
# ou
python -m http.server 8000
```

### 3. Configurar o link do WhatsApp

Substitua `https://wa.me/` pelo número completo com DDI:

```html
<!-- Exemplo com número brasileiro -->
<a href="https://wa.me/5511999999999" ...>
```

> Aparece em **5 locais** na página: header, hero, serviços, como funciona, contato e rodapé.

---

## 📱 Responsividade

O layout usa **CSS Grid e Flexbox** com breakpoints definidos em `style.css`:

| Breakpoint | Comportamento |
|---|---|
| `< 1024px` | Colunas em stack, padding reduzido |
| `< 768px` | Tipografia ajustada, hero em coluna única |
| `< 480px` | Layout mobile-first, botões full-width |

---

## 📌 Personalizações Pendentes

Itens que precisam ser atualizados antes de publicar:

- [ ] **Link WhatsApp** — inserir número real de Daniel Laranjeira em todos os CTAs
- [ ] **Imagens reais** — substituir os estudos ilustrativos por fotos de obras realizadas
- [ ] **Comparação Antes/Depois** — substituir imagem ilustrativa por foto real de projeto
- [ ] **Foto da seção Sobre** — substituir imagem de ofício por foto do Daniel
- [ ] **Área de atendimento** — confirmar cidades atendidas além de Ibiúna

---

## 📁 Deployment

Por ser um site estático (HTML + CSS + JS puros), pode ser hospedado em qualquer serviço de páginas estáticas:

- **Netlify** — Arraste a pasta ou conecte ao repositório Git
- **Vercel** — `vercel --prod`
- **GitHub Pages** — Ative nas configurações do repositório
- **Hostinger / Locaweb** — Upload via FTP

---

## 👤 Créditos

| Item | Detalhe |
|---|---|
| **Cliente** | Daniel Laranjeira — Restauração de Pisos |
| **Localização** | Ibiúna e região · SP |
| **Design** | Referência Figma · Node 4:5017 |
| **Tipografia** | Google Fonts (Cormorant Garamond + Inter) |
| **Imagens** | Ilustrativas — a substituir por fotos reais autorizadas |

---

*PisoFácil · Daniel Laranjeira — Restauração de pisos de madeira · Ibiúna e região · SP*
