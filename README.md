# 🤵 Terno Livre v5.1

Sistema de gestão de vendas de ternos e trajes sob medida. PWA instalável, funciona offline.

## ✨ Funcionalidades

- Cadastro de clientes com modelo, cor, tamanhos, parcelas e entrada
- Controle de pagamento por parcelas (bolinhas verde/cinza)
- Busca por nome, modelo ou cor
- Card retrato para compartilhar via WhatsApp e E-mail
- Exportação em PNG
- Funciona **offline** (PWA)
- Dados salvos no navegador (localStorage)

## 📱 Tamanhos disponíveis

- **Calça:** 34 ao 64 + Sob Medida
- **Terno:** PP, P, M, G, GG, EG, EGG + 34 ao 60 + Sob Medida
- **Parcelas:** 1x a 12x

## 🚀 Publicar no GitHub Pages

### Passo a passo

1. **Crie um repositório** no GitHub (ex: `terno-livre`)

2. **Faça upload dos arquivos** — estrutura necessária:
   ```
   terno-livre/
   ├── index.html
   ├── manifest.json
   ├── sw.js
   ├── .nojekyll
   └── icons/
       ├── icon-192.png
       └── icon-512.png
   ```

3. **Ative o GitHub Pages:**
   - Vá em **Settings → Pages**
   - Em *Source*, selecione **Deploy from a branch**
   - Escolha a branch `main` e pasta `/ (root)`
   - Clique em **Save**

4. **Acesse o app** em:
   ```
   https://<seu-usuario>.github.io/<nome-do-repositorio>/
   ```

5. **Instale no celular:**
   - Abra a URL no Chrome (Android) ou Safari (iPhone)
   - Toque em **"Adicionar à tela inicial"**
   - O app funciona offline após a primeira abertura!

## 🛠 Tecnologias

- HTML5 + CSS3 + JavaScript puro (sem dependências externas obrigatórias)
- [html2canvas](https://html2canvas.hertzen.com/) para exportação em PNG
- Google Fonts (Playfair Display + Lato)
- PWA com Service Worker para uso offline

## 📦 Versão

`5.1.0` — Adicionado campo de entrada, tamanhos expandidos de calça (34–64) e terno (PP–EGG + numérico 34–60), parcelas até 12x.
