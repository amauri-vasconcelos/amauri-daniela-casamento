# 💒 Daniela & Amauri — Site de Casamento

Site completo, elegante e responsivo para o casamento de **Daniela & Amauri** em **27 de junho de 2026**, Fortaleza – CE.

---

## 📁 Estrutura do Projeto

```
casamento-daniela-amauri/
├── index.html         ← Arquivo principal (tudo em um único arquivo)
└── README.md          ← Este arquivo
```

O site é 100% em HTML/CSS/JS puro, **sem dependências** externas além das fontes Google Fonts — pronto para deploy instantâneo.

---

## 🚀 Como Publicar

### Opção 1 — Vercel (recomendado)
1. Acesse [vercel.com](https://vercel.com) e crie uma conta gratuita
2. Clique em **"Add New Project"**
3. Faça upload da pasta do projeto ou conecte ao GitHub
4. A Vercel detecta automaticamente o `index.html`
5. Clique em **Deploy** — pronto!

### Opção 2 — Netlify
1. Acesse [netlify.com](https://netlify.com) e crie uma conta
2. Arraste a pasta do projeto para a área de **drag & drop** em "Sites"
3. O site é publicado automaticamente com uma URL gratuita
4. Opcionalmente, configure um domínio personalizado

### Opção 3 — GitHub Pages
1. Crie um repositório no GitHub (pode ser privado)
2. Faça upload do `index.html`
3. Vá em **Settings → Pages**
4. Selecione a branch `main` e pasta `/root`
5. O site fica disponível em `https://seu-usuario.github.io/nome-do-repo`

---

## 🖼️ Adicionar Foto do Casal

Para adicionar a foto, localize no `index.html` o trecho:

```html
<div class="photo-frame">
  <div class="photo-inner">
    <span class="photo-icon">💑</span>
    <span class="photo-text">Adicione sua foto aqui</span>
  </div>
</div>
```

Substitua por:

```html
<div class="photo-frame">
  <img src="foto-casal.jpg" alt="Daniela e Amauri" 
       style="width:100%;height:100%;object-fit:cover;border-radius:inherit">
</div>
```

Coloque o arquivo `foto-casal.jpg` na mesma pasta do `index.html`.

---

## ✏️ Personalizações Fáceis

| O que alterar | Onde encontrar |
|---|---|
| Cores | Variáveis CSS no início (`:root { --terracota: ... }`) |
| Nomes do casal | Buscar "Daniela & Amauri" |
| Data | Buscar "27 de junho de 2026" |
| Chave PIX | Buscar `da1d7878-07e3-4cf6-8758-b2d99b2bf07b` |
| Número WhatsApp | Buscar `5585988341614` |
| Link Mercado Pago | Buscar `link.mercadopago.com.br` |

---

## 📱 Funcionalidades

- ✅ Design responsivo (mobile-first)
- ✅ Contador regressivo até o casamento
- ✅ Linha do tempo interativa
- ✅ Botão WhatsApp com mensagem automática
- ✅ Modal de pagamento (PIX + Cartão)
- ✅ Cópia automática da chave PIX
- ✅ Mapas do Google Maps incorporados
- ✅ Navegação suave (scroll smooth)
- ✅ Animações de entrada ao rolar a página
- ✅ Menu responsivo para mobile
- ✅ 20 opções de presentes

---

## 🎨 Fontes Utilizadas

- **Great Vibes** — títulos românticos
- **Cormorant Garamond** — subtítulos elegantes serif
- **Jost** — texto limpo e moderno

---

*Feito com ❤️ para Daniela & Amauri*
