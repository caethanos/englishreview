# Daily English A1

Aplicação estática de revisão de inglês iniciante. Não precisa de servidor nem processo de build: `index.html` pode ser publicado diretamente no GitHub Pages ou Netlify. O progresso fica no `localStorage` do navegador e, por isso, permanece naquele dispositivo e navegador.

## Publicar no GitHub Pages

1. Crie um repositório público no GitHub.
2. Envie `index.html` (e este README, se desejar) para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`, depois clique em **Save**.
6. Aguarde a publicação e abra o endereço exibido na seção Pages.

## Publicar no Netlify

1. Crie uma conta gratuita em [netlify.com](https://www.netlify.com/) e conecte o GitHub.
2. Escolha **Add new site → Import an existing project** e selecione o repositório.
3. Deixe **Build command** vazio e defina **Publish directory** como `.` (raiz).
4. Clique em **Deploy site**. O Netlify publica novamente a cada envio para a branch conectada.

Também é possível arrastar a pasta contendo `index.html` para a opção de deploy manual do Netlify.
