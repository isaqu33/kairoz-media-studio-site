# Kairoz Media Studio · Página de apresentação

Landing page estática para apresentar o Kairoz e receber contatos de quem tem interesse em conhecer a aplicação. A ilustração usa conteúdo fictício. O aplicativo e o histórico dele ficam em outro repositório.

## Ver localmente

Abra `public/index.html` no navegador. Para testar por HTTP, rode `python3 -m http.server 8080 --bind 127.0.0.1 --directory public` na raiz e abra http://127.0.0.1:8080.

## Publicar na Vercel

1. Crie um projeto e importe este repositório.
2. Mantenha a raiz do repositório como **Root Directory**. O arquivo `vercel.json` configura a saída em `public`.
3. Se a interface pedir um preset, selecione **Other** e deixe o comando de build vazio. A página não precisa de dependências nem variáveis de ambiente.
4. Clique em **Deploy**. Use o endereço da landing como link de apresentação do Kairoz no portfólio.

[Guia de importação pela Vercel](https://vercel.com/docs/git#deploying-a-git-repository)
