# 🚀 SideContextAI Landing Page

Esta é a página de apresentação (Landing Page) oficial e multilíngue do **SideContextAI**. Ela foi desenvolvida com HTML5 semântico, JavaScript moderno (ESModules) e Vanilla CSS puro com efeitos avançados de glassmorphism e auroras dinâmicas.

## 📁 Estrutura de Arquivos
- `index.html`: Estrutura principal da página, meta-tags de SEO e preview interativo da extensão.
- `style.css`: Estilização premium em Dark Mode, animações Scroll Reveal e efeitos de hover 3D.
- `script.js`: Lógica de internacionalização (tradução dinâmica na UI) e controle de animações.
- `messages.js`: Dicionário completo de traduções em **Português (PT-BR)**, **Inglês (EN)** e **Espanhol (ES)**.

---

## 🌎 Como publicar no GitHub Pages (Deploy)

Para hospedar esta página gratuitamente no GitHub Pages usando um repositório dedicado, siga estes passos simples:

### Passo 1: Crie um repositório no GitHub
1. Acesse o seu [GitHub](https://github.com/) e crie um novo repositório público chamado `side-context-ai` (ou o nome que preferir).
2. **Importante**: Não inicialize o repositório com README, .gitignore ou Licença (deixe-o totalmente vazio).

### Passo 2: Inicialize e envie os arquivos locais
Abra o seu terminal no diretório desta landing page (`/home/amaral/Documents/_dev/side-context-ai-landing/`) e execute os seguintes comandos:

```bash
# Inicialize o repositório Git local
git init

# Adicione todos os arquivos criados
git add .

# Crie o primeiro commit de lançamento
git commit -m "feat: first release of sidecontextai landing page"

# Renomeie a branch principal para 'main'
git branch -M main

# Vincule o repositório local ao seu repositório criado no GitHub
# (Substitua 'seu-usuario' pelo seu nome de usuário do GitHub)
git remote add origin https://github.com/seu-usuario/side-context-ai.git

# Envie os arquivos para o GitHub
git push -u origin main -f
```

### Passo 3: Ative o GitHub Pages
1. Vá até a página do seu repositório no GitHub.
2. Acesse a aba **Settings** (Configurações) no topo direito.
3. No menu lateral esquerdo, clique em **Pages** (sob a seção "Code and automation").
4. Sob **Build and deployment**:
   - Defina a **Source** como `Deploy from a branch`.
   - Em **Branch**, selecione a branch `main` e a pasta `/ (root)`.
   - Clique em **Save** (Salvar).
5. Aguarde cerca de 1 a 2 minutos. O GitHub exibirá o link público no topo da seção (ex: `https://seu-usuario.github.io/side-context-ai/`).

Pronto! Sua Landing Page premium e multilíngue estará no ar e disponível para todo o mundo!
