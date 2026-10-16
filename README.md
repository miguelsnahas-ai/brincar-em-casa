# Brincar em Casa — Landing page

Site estático (1 página) da consultoria **Brincar em Casa** + seção do grupo **Ofertas da Sil**.

## Arquivos
- `index.html` — a página completa (HTML + CSS + JS, tudo junto).
- `ofertas-da-sil-logo.png` — logo usado na seção Ofertas da Sil. Precisa ficar na mesma pasta do `index.html`.

As fontes (Quicksand + Mulish) carregam do Google Fonts automaticamente — não precisa baixar nada.

## Como publicar pelo Claude Code

1. Copie estes dois arquivos para a pasta do seu projeto no Claude Code.
2. Cole o prompt abaixo:

> Tenho um site estático de uma página só: `index.html` e a imagem `ofertas-da-sil-logo.png`, na raiz do projeto. Quero publicar online com um link público. Faça o deploy como site estático (pode ser GitHub Pages, Vercel, Netlify ou Cloudflare Pages — escolha o mais simples de configurar daqui) e, ao final, me mostre a URL pública. Não altere o conteúdo nem o visual da página, só publique.

Se quiser domínio próprio depois (ex.: `brincaremcasa.com.br`), peça ao Claude Code para configurar o DNS no serviço escolhido.

## O que ainda falta preencher (placeholders no HTML)
- **Contato da consultoria:** os botões de CTA da consultoria apontam para `#planos`. Troque pelo link real (WhatsApp/compra) quando tiver. Procure por `A definir` no HTML.
- **Instagram:** no rodapé há `@instagram (a definir)`.
- **Foto da Silvana:** a seção "Sobre" tem um espaço reservado ("foto da Silvana"). É só trocar o bloco `.portrait` por uma `<img>`.

## Já configurado
- O botão **"Entrar no grupo gratuito"** e o link do rodapé já apontam para o grupo de WhatsApp das Ofertas da Sil.
