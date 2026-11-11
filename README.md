# Protec – Pedidos e Caixa

Site de pedidos e controle financeiro da Protec Corte a Laser. É um site simples (um único arquivo `index.html`), sem servidor.

## Recursos
- Cadastro de pedidos, com baixa, reabrir, excluir e "Zerar baixados".
- Financeiro com entradas, saídas e saldo total.
- Modo administrador com senha: só o administrador exclui lançamentos do financeiro.

## Importante
Os dados ficam salvos **no navegador** do aparelho em que o site é usado (localStorage). Cada aparelho tem seus próprios dados, e limpar os dados do navegador apaga tudo.

## Colocar no GitHub
1. Crie um repositório novo em https://github.com/new (pode ser privado).
2. Envie estes arquivos:
   ```
   git init
   git add .
   git commit -m "Protec pedidos e caixa"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
   git push -u origin main
   ```
   Ou use **Add file → Upload files** na página do repositório e arraste os arquivos.

## Publicar no Netlify
1. No Netlify: **Add new site → Import an existing project → GitHub** e escolha o repositório.
2. Deixe o campo de build command vazio e o publish directory como `.` (já vem do `netlify.toml`).
3. Clique em **Deploy**.

## Ou publicar no GitHub Pages
No repositório: **Settings → Pages → Deploy from a branch → main / (root)**.
