<div align="center">

# 🛼 Snitap - Landing Page

### *Snitap, sua vida mais saudável*

Landing page moderna e responsiva para e-commerce de patins

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-100%25-16A34A?style=for-the-badge)

[🌐 Ver Demo](#) • [🐛 Reportar Bug](https://github.com/eaidavid/snitap-landing-page/issues) • [✨ Solicitar Feature](https://github.com/eaidavid/snitap-landing-page/issues)

</div>

---

## 📋 Sobre o Projeto

Landing page desenvolvida para a **Snitap**, uma marca de patins focada em promover um estilo de vida saudável e ativo. O projeto apresenta um design clean e moderno, com foco na experiência do usuário e responsividade total.

<div align="center">

**Destaque:** *Interface intuitiva, performance otimizada e design que converte*

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%">

🎨 **Design Moderno**
- Interface limpa e atraente
- Elementos visuais impactantes
- Identidade visual consistente

📱 **Totalmente Responsivo**
- Adapta-se a todos dispositivos
- Desktop First approach
- Breakpoint único otimizado

🖼️ **Galeria de Fotos**
- Seção "#usesnitap por aí"
- Fotos reais de usuários
- Grid responsivo e elegante

</td>
<td width="50%">

🎯 **Call-to-Actions**
- Botões estratégicos
- "Comprar Agora" e "Veja em Ação"
- Conversão otimizada

🎭 **Banner Animado**
- Faixa infinita dinâmica
- Animação CSS suave
- Gradiente vibrante

🌐 **Redes Sociais**
- Links integrados
- Instagram, Facebook, YouTube, TikTok
- Acessibilidade garantida

</td>
</tr>
</table>

---

## 🎨 Design System

### Tipografia

| Font Family | Elemento | Tamanho | Line Height | Weight |
|-------------|----------|---------|-------------|--------|
| **Syne** | heading1 | 64px | 125% | Bold |
| **Syne** | heading2 | 40px | 120% | Bold |
| **Montserrat** | button label | 16px | 150% | Medium |
| **Montserrat** | span | 14px | 150% | Medium |

> 📦 Fontes disponíveis via [Google Fonts](https://fonts.google.com/)

### Paleta de Cores

#### Marca

<div align="center">

| Nome | Hexadecimal | Uso |
|---------|------|-------------|-----|
| snitap-sun | `#FFCD1E` | Botões principais |
| snitap-sky-mid | `#068BD4` | Backgrounds |
| snitap-sky-light | `#67E8F9` | Decorativos |
| snitap-joy-mid | `#DB2777` | Destaques |
| snitap-joy-light | `#F472B6` | Acentos |
| Brand Green | `#16A34A` | "saudável" |

</div>

#### Base

<div align="center">

| Nome | Hexadecimal | Uso |
|---------|------|-------------|-----|
| Text | `#000000` | Textos principais |
| Highlight | `#000000` | Destaques |
| Background | `#FAFAFA` | Fundo da página |

</div>

---

## 🛠️ Tecnologias Utilizadas

<div align="center">

| Tecnologia | Versão/Descrição |
|------------|------------------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Estrutura semântica |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Estilização avançada |
| **Flexbox** | Layout unidimensional |
| **CSS Grid** | Layout bidimensional |
| **Media Queries** | Responsividade |
| **CSS Animations** | Animações e transições |
| **CSS Variables** | Customização dinâmica |
| **Google Fonts** | Syne & Montserrat |

</div>

---

## 📁 Estrutura do Projeto

```plaintext
snitap-landing-page/
│
├── 📂 assets/
│   ├── 📂 hero/
│   │   ├── elipses.svg           # Círculo decorativo
│   │   ├── patins-image.png      # Imagem principal do produto
│   │   ├── stars-1.svg           # Estrelas decorativas (grupo 1)
│   │   └── stars-2.svg           # Estrelas decorativas (grupo 2)
│   │
│   └── 📂 icons/
│       ├── facebook.svg          # Ícone do Facebook
│       ├── instagram.svg         # Ícone do Instagram
│       ├── logo.svg              # Logotipo Snitap
│       ├── play.svg              # Ícone Play (botão CTA)
│       ├── shopping-bag.svg      # Ícone do carrinho
│       ├── tiktok.svg            # Ícone do TikTok
│       └── youtube.svg           # Ícone do YouTube
│
├── 📂 images/
│   ├── 01.png                    # Foto galeria #1
│   ├── 02.png                    # Foto galeria #2
│   ├── 03.png                    # Foto galeria #3
│   ├── 04.png                    # Foto galeria #4
│   ├── banner.svg                # Elemento do banner animado
│   └── person.png                # Imagem pessoa (se usado)
│
├── 📂 styles/
│   ├── banner.css                # Estilos do banner animado
│   ├── footer.css                # Estilos do rodapé
│   ├── gallery.css               # Estilos da galeria de fotos
│   ├── global.css                # Variáveis e reset global
│   ├── header.css                # Estilos do cabeçalho
│   ├── hero.css                  # Estilos da seção hero
│   └── style.css                 # Arquivo principal (imports)
│
├── 📄 index.html                 # Página principal
└── 📄 README.md                  # Documentação
```

---

## 🚀 Como Usar

### Pré-requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (opcional - recomendado VS Code)

### Instalação

**1️⃣ Clone o repositório**

```bash
git clone https://github.com/eaidavid/snitap-landing-page.git
```

**2️⃣ Navegue até a pasta do projeto**

```bash
cd snitap-landing-page
```

**3️⃣ Abra o arquivo index.html**

```bash
# Windows
start index.html

# MacOS
open index.html

# Linux
xdg-open index.html
```

<div align="center">

> 💡 **Dica Pro:** Use a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) do VS Code para desenvolvimento com hot reload automático!

</div>

---

## 📱 Responsividade

O projeto utiliza a abordagem **Desktop First** com **um único breakpoint** estratégico:

<div align="center">

| Dispositivo | Largura | Layout |
|-------------|---------|--------|
| 💻 **Desktop** | ≥ 768px | Multi-colunas, layout expansivo |
| 📱 **Mobile** | < 768px | Coluna única, otimizado para toque |

</div>

### Implementação

```css
/* Base: Desktop (≥ 768px) */
.element {
  width: 50%;
  display: flex;
  flex-direction: row;
  padding: 4rem;
}

/* Mobile: Ajustes para telas menores */
@media (max-width: 768px) {
  .element {
    width: 100%;
    flex-direction: column;
    padding: 2rem 1rem;
  }
}
```

### Pontos de Quebra

- **768px** → Transição de desktop para mobile
- **Breakpoint único** → Manutenção simplificada
- **Desktop First** → Otimizado para telas maiores primeiro

---

## 🎯 Seções da Página

### 1️⃣ Header

<table>
<tr>
<td>

- Logotipo **Snitap**
- Ícone de carrinho de compras
- Badge de notificação animado
- Layout fixo no topo

</td>
</tr>
</table>

### 2️⃣ Hero Section

<table>
<tr>
<td width="60%">

**Elementos:**
- 🎨 Título impactante: *"Snitap, sua vida mais saudável"*
- 🖼️ Imagem destacada do produto (patins premium)
- 🔘 Botão primário: "Comprar Agora"
- ▶️ Botão secundário: "Veja em Ação"
- ✨ Elementos decorativos (estrelas + círculo azul)

</td>
<td width="40%">

**Objetivo:**
- Capturar atenção
- Comunicar valor
- Direcionar ação
- Criar desejo

</td>
</tr>
</table>

### 3️⃣ Banner Animado

- 🎭 Animação CSS infinita e suave
- 🌈 Gradiente vibrante (azul → rosa)
- ⚡ Palavra "Patins" repetida dinamicamente
- ⭐ Estrelas decorativas

### 4️⃣ Galeria de Fotos

<table>
<tr>
<td>

**Estrutura:**
- 📸 Título: "GALERIA DE FOTOS"
- #️⃣ Hashtag: "#usesnitap por aí"
- 🖼️ Grid 2x2 com 4 fotos reais
- 📱 Layout responsivo (1 coluna → 2x2)

</td>
<td>

**Propósito:**
- Prova social
- Engajamento
- Comunidade
- Inspiração

</td>
</tr>
</table>

### 5️⃣ Footer

- 🏷️ Logo Snitap
- 🔗 Links: Sobre, Nossas Lojas, Política de Privacidade
- 📱 Redes sociais: Instagram, Facebook, YouTube, TikTok
- 📄 Informações legais

---

## 🎨 Customização

### 🎨 Alterar Cores

Edite as variáveis CSS no arquivo `styles/global.css`:

```css
:root {
  /* Cores da marca */
  --snitap-sun: #FFCD1E;
  --snitap-sky-mid: #068BD4;
  --snitap-sky-light: #67E8F9;
  --snitap-joy-mid: #DB2777;
  --snitap-joy-light: #F472B6;
  --brand-green: #16A34A;
  
  /* Cores base */
  --text: #000000;
  --highlight: #000000;
  --background: #FAFAFA;
}
```

### 🖼️ Adicionar Imagens na Galeria

**1.** Adicione a imagem na pasta `images/`

**2.** No arquivo `index.html`, localize a seção `.gallery` e adicione:

```html
<div class="gallery">
  <!-- Imagens existentes -->
  <img src="images/01.png" alt="Usuário praticando patinação">
  
  <!-- Sua nova imagem -->
  <img src="images/nova-foto.png" alt="Descrição da nova foto">
</div>
```

### ⚙️ Modificar Animação do Banner

No arquivo `styles/banner.css`:

```css
@keyframes scroll {
  from { transform: translateX(0); }
  to { transform: translateX(-50%); }
}

.banner-content {
  /* Altere a duração (20s = mais lento | 10s = mais rápido) */
  animation: scroll 20s linear infinite;
}
```

### 🔤 Trocar Fontes

No arquivo `styles/global.css`:

```css
/* Importar nova fonte do Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=SuaFonte:wght@400;700&display=swap');

body {
  font-family: 'SuaFonte', sans-serif;
}
```

---

## 📊 Performance & Otimização

<div align="center">

| Item | Status | Observação |
|------|--------|------------|
| HTML Semântico | ✅ | Tags apropriadas |
| CSS Modular | ✅ | Arquivos separados por seção |
| Imagens SVG | ✅ | Ícones vetorizados |
| Responsividade | ✅ | Desktop First |
| Animações CSS | ✅ | Hardware accelerated |
| Fontes Web | ✅ | Google Fonts otimizado |

</div>


---

## 🤝 Contribuindo

Contribuições são **muito bem-vindas**! 

<details>
<summary>📖 <b>Guia de Contribuição</b></summary>

<br>

### Como Contribuir

**1️⃣ Fork o projeto**

Clique no botão "Fork" no topo da página

**2️⃣ Clone seu fork**

```bash
git clone https://github.com/seu-usuario/snitap-landing-page.git
cd snitap-landing-page
```

**3️⃣ Crie uma branch para sua feature**

```bash
git checkout -b feature/MinhaNovaFeature
```

**4️⃣ Faça suas alterações e commit**

```bash
git add .
git commit -m 'feat: Adiciona minha nova feature incrível'
```

**5️⃣ Push para seu fork**

```bash
git push origin feature/MinhaNovaFeature
```

**6️⃣ Abra um Pull Request**

Vá até o repositório original e clique em "New Pull Request"

### 📝 Padrão de Commits

Seguimos o [Conventional Commits](https://www.conventionalcommits.org/pt-br/):

| Tipo | Descrição | Exemplo |
|------|-----------|---------|
| `feat:` | Nova funcionalidade | `feat: Adiciona filtro de produtos` |
| `fix:` | Correção de bug | `fix: Corrige layout mobile do header` |
| `docs:` | Documentação | `docs: Atualiza README com novos exemplos` |
| `style:` | Formatação de código | `style: Formata CSS com Prettier` |
| `refactor:` | Refatoração | `refactor: Melhora estrutura do hero.css` |
| `perf:` | Performance | `perf: Otimiza carregamento de imagens` |
| `test:` | Testes | `test: Adiciona testes para galeria` |
| `chore:` | Manutenção | `chore: Atualiza dependências` |



</details>

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

<details>
<summary>O que isso significa?</summary>

<br>

Você pode:
- ✅ Usar comercialmente
- ✅ Modificar
- ✅ Distribuir
- ✅ Uso privado

Sob as condições:
- 📋 Incluir a licença e copyright
- 📋 Sem garantias

</details>

---

<div align="center">

## 👨‍💻 Autor

<img src="https://github.com/eaidavid.png" width="150px" style="border-radius: 50%;" alt="David Alves"/>

### **David Alves**

*Desenvolvedor Full Stack apaixonado por criar experiências digitais incríveis* 🚀

<br>

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/eaidavid)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/odaviddev/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white)](https://eaidavid.github.io/portfolio/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/daaviid_alvees)

</div>

---

<div align="center">

## 📞 Contato

**Tem alguma dúvida, sugestão ou apenas quer bater um papo?**

📧 **Email:** [eaidavidalves@gmail.com](mailto:eaidavidalves@gmail.com)  
💼 **LinkedIn:** [David Alves](https://www.linkedin.com/in/odaviddev/)  
📱 **Instagram:** [@daaviid_alvees](https://www.instagram.com/daaviid_alvees/)

</div>

---

<div align="center">

### ⭐ Se este projeto te ajudou de alguma forma, considere dar uma estrela!

**Isso ajuda o projeto a crescer e motiva o desenvolvimento de novas features** 💛

<br>

**#usesnitap** 🛼✨

---

<sub>Feito com 🎶, ☕ e boas práticas de código</sub>

<br>

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=eaidavid.snitap-landing-page)
![GitHub stars](https://img.shields.io/github/stars/eaidavid/snitap-landing-page?style=social)
![GitHub forks](https://img.shields.io/github/forks/eaidavid/snitap-landing-page?style=social)

</div>
