<div align="center">

# 🔥 Team Bela Vista | Academia

**Treino pesado, ambiente intenso e uma equipe que puxa você até o próximo nível.**

Landing page oficial da academia Team Bela Vista, feita em HTML, CSS e JavaScript puro.

<br>

[![Ver site online](https://img.shields.io/badge/🌐_Ver_site_online-ff2a1a?style=for-the-badge)](https://academia-okanharenans-projects.vercel.app/)


![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)
![Status](https://img.shields.io/badge/status-online-brightgreen)

</div>

<!--
  Para exibir um print do site aqui:
  1. Salve a imagem em docs/preview.png
  2. Descomente a linha abaixo

  <p align="center"><img src="docs/preview.png" alt="Prévia do site Team Bela Vista" width="800"></p>
-->

---

## 📖 Sobre

O **Team Bela Vista** é um projeto de landing page para uma academia de bairro com foco em comunidade. O site apresenta a estrutura, o time de professores e os planos, e leva o visitante direto para a matrícula pelo WhatsApp.

É um site **100% estático**: sem build, sem frameworks, sem dependências e sem backend.

## ✨ Destaques

- 🎨 Visual escuro com vermelho neon, inspirado no ambiente da academia
- 📱 Responsivo, pensado primeiro para celular
- 🎠 Carrossel do time com botões, miniaturas, swipe no celular e troca automática
- 🌀 Animações de entrada ao rolar a página (`IntersectionObserver`)
- ♿ Respeita `prefers-reduced-motion` e usa `aria-label` nos controles
- 💬 Botão flutuante de WhatsApp sempre visível
- 🏋️ Aceita **Wellhub** e **Gympass**

## 🧩 Seções

| Seção | Conteúdo |
| --- | --- |
| Hero | Apresentação e modalidades: Musculação, Step, Yoga, Pilates e Fit Dance |
| Estrutura de peso | Máquinas de carga, ambiente neon, acompanhamento e comunidade |
| Mais que academia | O espírito do #TeamBelaVista |
| Quem treina com você | Carrossel com os professores e seus lemas |
| Planos | Mensal, Trimestral (mais escolhido) e Anual |
| Contato | WhatsApp e telefone |

## 🛠️ Tecnologias

- **HTML5** semântico
- **CSS3** com variáveis, grid e media queries
- **JavaScript** puro (vanilla)
- **Google Fonts**: Barlow e Barlow Condensed
- **Vercel** para hospedagem

## 📁 Estrutura

```
.
├── index.html   # Página principal (imagens em base64 e script embutidos)
├── style.css    # Estilos
└── README.md
```

## 🚀 Como rodar

```bash
# 1. Clone o repositório
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git

# 2. Entre na pasta
cd NOME-DO-REPOSITORIO

# 3. Abra o index.html no navegador
```

Ou, se preferir um servidor local:

```bash
python3 -m http.server 3000
# ou
npx serve .
```

Acesse `http://localhost:3000`.

## ☁️ Deploy

O projeto está publicado na Vercel, com deploy automático a cada push na branch principal:

👉 **https://academia-okanharenans-projects.vercel.app/**

Configuração usada: *Framework Preset* **Other**, sem *Build Command* e sem *Output Directory*.

## 🎨 Personalização

| O que alterar | Onde |
| --- | --- |
| Cores (`--bg`, `--red`, `--tx`, `--mut`) | variáveis no `style.css` |
| Textos, planos e professores | `index.html` |
| Link do WhatsApp | `href="https://wa.me/..."` no `index.html` |
| Telefone | `href="tel:..."` no `index.html` |
| Tempo do carrossel | `setInterval(..., 7000)` no script (milissegundos) |

## 🌐 Link do site:
- Site: [academia-okanharenans-projects.vercel.app](https://academia-okanharenans-projects.vercel.app/)

---

<div align="center">

Feito com 💪 para o **#TeamBelaVista**

© Team Bela Vista. Todos os direitos reservados.

</div>
