# GESTÃO PRO — Sistema de Gestão Comercial

Projeto web em HTML, CSS e JavaScript, preparado para publicação no GitHub Pages.

## Como executar localmente
1. Baixe ou extraia este repositório.
2. Abra `index.html` no navegador.

## Como publicar no GitHub Pages
1. Crie um repositório no GitHub.
2. Envie os arquivos deste projeto para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/(root)`, depois salve.
6. Aguarde a publicação e abra o endereço apresentado pelo GitHub Pages.

## Observações importantes
- Este pacote mantém o sistema como aplicação front-end de arquivo único (`index.html`).
- Os dados são armazenados localmente no navegador via `localStorage`; não há sincronização em nuvem ou banco de dados compartilhado neste pacote.
- Os dados locais não são transferidos automaticamente ao publicar no GitHub Pages. Faça backup antes de testar ou trocar de versão.
- Não inclua senhas, tokens, chaves privadas ou dados pessoais reais no repositório.
- O GitHub Pages publica arquivos estáticos; autenticação segura, API/backend e sincronização multiusuário exigem serviços adicionais.
