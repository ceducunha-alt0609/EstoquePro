# EstoqueCP — PWA para Mobile

App de gestão de estoque para condomínios. Funciona 100% offline após a primeira carga.

## 📁 Estrutura dos arquivos

```
estoque-condo-pwa/
├── index.html      # App principal
├── manifest.json   # Configuração PWA
├── sw.js           # Service Worker (cache offline)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

---

## 🚀 Como publicar no GitHub Pages (gratuito)

### Passo 1 — Criar repositório no GitHub

1. Acesse [github.com](https://github.com) e faça login
2. Clique em **"New repository"**
3. Nome sugerido: `estoque-condo`
4. Marque **"Public"**
5. Clique em **"Create repository"**

### Passo 2 — Subir os arquivos

**Opção A — pelo navegador (mais fácil):**
1. No repositório criado, clique em **"uploading an existing file"**
2. Arraste todos os arquivos desta pasta (incluindo a pasta `icons/`)
3. Clique em **"Commit changes"**

**Opção B — via Git (terminal):**
```bash
cd estoque-condo-pwa
git init
git add .
git commit -m "EstoqueCP PWA v2"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/estoque-condo.git
git push -u origin main
```

### Passo 3 — Ativar o GitHub Pages

1. No repositório, vá em **Settings → Pages**
2. Em "Source", selecione **"Deploy from a branch"**
3. Branch: **main** / pasta: **/ (root)**
4. Clique em **Save**
5. Aguarde ~2 minutos. A URL será:
   ```
   https://SEU_USUARIO.github.io/estoque-condo/
   ```

---

## 📱 Instalar no celular

### Android (Chrome)
1. Abra a URL do GitHub Pages no Chrome
2. Aguarde carregar completamente
3. Toque nos **3 pontinhos (⋮)** no canto superior direito
4. Toque em **"Adicionar à tela inicial"**
5. Confirme — o ícone aparecerá na tela inicial

### iPhone/iPad (Safari)
1. Abra a URL no **Safari** (obrigatório, não funciona no Chrome no iOS)
2. Toque no ícone de **compartilhar (□↑)** na barra inferior
3. Role e toque em **"Adicionar à Tela de Início"**
4. Confirme o nome e toque em **"Adicionar"**

---

## ✅ Funcionalidades

- ✅ Funciona 100% offline após primeira visita
- ✅ Dados salvos localmente (localStorage)
- ✅ Instala como app nativo (sem barra do navegador)
- ✅ Ícone personalizado na tela inicial
- ✅ Tela de carregamento com a cor do app
- ✅ Compatível com Android e iOS

---

## 🔄 Atualizar o app

Para atualizar, basta substituir os arquivos no GitHub. O app baixará a nova versão automaticamente na próxima abertura com internet.
