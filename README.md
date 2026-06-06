# Minisite Link na Bio — Luís Henrique

Link na bio personalizado com foto, 3 botões e mockup do livro.

## Estrutura

```
minisite-luisao/
├── index.html     # Página principal
├── style.css      # Estilos (dark, azul/preto)
├── foto.jpg       # Sua foto de perfil
├── vercel.json    # Configuração do deploy
└── README.md
```

## Links configurados

| Botão | Destino |
|-------|---------|
| Aprender com Luisão | https://quizzfalaluisao.vercel.app/ |
| Palestras / Parcerias / Podcasts | WhatsApp direto |
| Livro Timidez Nunca Mais | Amazon Brasil |

## Deploy no GitHub + Vercel

### 1. Subir no GitHub

```bash
git init
git add .
git commit -m "feat: minisite link na bio"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/minisite-luisao.git
git push -u origin main
```

### 2. Deploy na Vercel

1. Acesse [vercel.com](https://vercel.com) → **Add New → Project**
2. Importe o repositório `minisite-luisao`
3. Deixe as configurações padrão (HTML estático)
4. Clique em **Deploy**

Qualquer `git push` na branch `main` faz redeploy automático.

## Personalizar

- **Foto**: substitua `foto.jpg` pela nova imagem (mantenha o mesmo nome)
- **Links**: edite os `href` no `index.html`
- **Nome/bio**: edite o `<h1>` e o `<p class="profile-bio">` no `index.html`
