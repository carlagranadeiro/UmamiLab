# 🍜 Umami Lab — Menu Digital Interativo

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?logo=github)](https://carlagranadeiro.github.io/Umami-Lab/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)]()
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)]()

> **Uma imagem abre o apetite e vale mais de mil palavras.**  
> Menu digital interativo para restaurante de ramen, com fotos reais dos pratos, suporte multilingue e QR Code integrado.

---

## ✨ Funcionalidades

| Feature | Descrição |
|---------|-----------|
| 📱 **QR Code Dinâmico** | Geração automática do QR para acesso rápido via telemóvel |
| 🌍 **Multilingue** | 3 idiomas: Português 🇵🇹 · English 🇬🇧 · 日本語 🇯🇵 |
| 🌓 **Modo Escuro** | Toggle manual + deteção automática da preferência do sistema |
| 🖼️ **Fotos Reais** | Imagens autênticas de cada prato para apetecer à primeira vista |
| 🔥 **Indicador Picante** | Badge 🌶️ nos pratos com nível de picante |
| 📋 **Detalhes Completos** | Modal com ingredientes, alergénios e descrição detalhada |
| ⚡ **Filtros Rápidos** | Navegação por categorias: Todos · Classic · Specialty |
| 💾 **Persistência** | Preferências de tema guardadas entre visitas |
| 📴 **Offline-Ready** | SPA single-file, carregamento instantâneo |

---

## 🍜 Menu

### Classic Bowls
| Prato | Preço | Destaque |
|-------|-------|----------|
| Shoyu Ramen | €12.50 | Caldo à base de soja, chashu pork, ovo mollete |
| Miso Ramen | €13.00 | Caldo rico de miso, carne de porco moída, manteiga |
| Tonkotsu Ramen | €14.50 | Caldo cremoso de ossos de porco, alho negro |
| Shio Ramen | €12.00 | Caldo leve de sal, frango, rebentos de bambu |

### Specialty Bowls
| Prato | Preço | Destaque |
|-------|-------|----------|
| Spicy Tan Tanmen | €15.00 | 🌶️ Gergelim com chili, porco moído, bok choy |
| Black Garlic Ramen | €15.50 | Base tonkotsu, alho negro torrado, chalotas crocantes |
| Tokyo Chicken Ramen | €13.50 | Caldo claro de frango, frango grelhado, nori |
| Firecracker Ramen 🔥 | €14.00 | 🌶️ Caldo extra picante, chili oil, jalapeño |

---

## 🛠️ Tecnologias

- **HTML5** semântico e acessível
- **Tailwind CSS** via CDN — design mobile-first, responsivo
- **Vanilla JavaScript** — zero dependências de framework
- **QRCode.js** — geração de QR codes no cliente
- **Google Fonts** — Inter + Noto Sans JP

> *Arquitetura deliberadamente simples: um único ficheiro HTML self-contained, zero build steps, zero backend.*

---

## 🚀 Alojamento

A app está alojada em **GitHub Pages**:

```
https://carlagranadeiro.github.io/Umami-Lab/
```

### Como funciona o QR Code
O QR Code na secção inferior da app aponta automaticamente para o URL de produção. Basta imprimir essa secção e colocar nas mesas do restaurante — os clientes apontam a câmara do telemóvel e acedem instantaneamente ao menu digital.

---

## 📦 Estrutura do Projeto

```
Umami-Lab/
├── index.html          # Aplicação completa (SPA single-file)
├── README.md           # Este ficheiro
└── .github/
    └── workflows/      # (opcional) CI/CD automático
```

---

## 🎨 Design System

| Elemento | Valor |
|----------|-------|
| **Cor primária** | `#d97706` (Ramen-600) — quente, apetitosa |
| **Tipografia** | Inter (corpo) · Noto Sans JP (títulos japoneses) |
| **Breakpoints** | Mobile-first: sm(640px), md(768px), lg(1024px) |
| **Animações** | fadeIn 0.3s · slideUp 0.4s · scale 0.3s |

---

## 🔧 Desenvolvimento Local

1. Clona o repositório:
```bash
git clone https://github.com/carlagranadeiro/Umami-Lab.git
cd Umami-Lab
```

2. Abre `index.html` diretamente no browser:
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

3. Ou serve com um servidor local:
```bash
python3 -m http.server 8000
# Acede a http://localhost:8000
```

---

## 📝 Roadmap

- [ ] Integração com fotos reais do restaurante
- [ ] Modo acessibilidade (fontes grandes, alto contraste)
- [ ] Service Worker para funcionamento offline completo
- [ ] Integração com WhatsApp Business ("Chamar staff")
- [ ] Painel admin para atualização de preços via JSON
- [ ] Suporte para mais idiomas (ES, FR, DE)

---

## 👤 Autor

**Carla Granadeiro** — [@carlagranadeiro](https://github.com/carlagranadeiro)

> Desenvolvido com 🍜 e 💻 para tornar a experiência de ramen acessível a todos, independentemente da língua.

---

## 📄 Licença

MIT © 2026 Umami Lab

---

<p align="center">
  <a href="https://carlagranadeiro.github.io/Umami-Lab/">
    <img src="https://img.shields.io/badge/🍜%20Ver%20Menu%20Live-FF6B6B?style=for-the-badge" alt="Ver Menu Live">
  </a>
</p>
