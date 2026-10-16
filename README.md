# Team Bela Vista | Academia

Site institucional (landing page) da academia **Team Bela Vista**, com apresentação do time, planos e contato direto via WhatsApp.

## Tecnologias

- HTML5
- CSS3
- Google Fonts (Barlow e Barlow Condensed)

Site 100% estático: sem build, sem dependências e sem backend.

## Estrutura do projeto

```
team-bela-vista/
├── index.html   # Página principal (imagens embutidas em base64)
├── style.css    # Estilos do site

```

## Seções do site

- **Sobre**: conheça o time
- **Planos**: opções de matrícula
- **Contato**: WhatsApp e telefone

## Rodando localmente

Não precisa instalar nada. Basta abrir o `index.html` no navegador.

Se preferir um servidor local:

```bash
# com Python
python3 -m http.server 3000

# ou com Node
npx serve .
```

Depois acesse `http://localhost:3000`.

## Deploy na Vercel

1. Suba o projeto para um repositório no GitHub.
2. Na [Vercel](https://vercel.com), clique em **Add New → Project** e importe o repositório.
3. Configure:
   - **Framework Preset:** Other
   - **Build Command:** deixe em branco
   - **Output Directory:** deixe em branco
4. Clique em **Deploy**.

Cada novo commit na branch principal gera um deploy automático.

Via terminal:

```bash
npm i -g vercel
vercel          # preview
vercel --prod   # produção
```

### Domínio próprio

Em **Settings → Domains** no painel da Vercel, adicione o domínio e aponte o DNS conforme as instruções exibidas.

## Personalização

| O que alterar | Onde |
| --- | --- |
| Cores, fontes e layout | `style.css` |
| Textos, planos e seções | `index.html` |
| Link do WhatsApp | `href="https://wa.me/..."` no `index.html` |
| Telefone | `href="tel:..."` no `index.html` |

---
Link projeto: https://academia-okanharenans-projects.vercel.app/

Team Bela Vista © Todos os direitos reservados.
