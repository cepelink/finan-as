# Minhas Finanças

App web (PWA) para controle mensal de recebimentos, gastos e dívidas.
Os dados ficam salvos no navegador de cada aparelho (localStorage).
Use Exportar/Importar backup para levar os dados entre aparelhos.

## Publicar no Firebase Hosting
    npm i -g firebase-tools
    firebase login
    firebase init hosting   # public dir: . | SPA: não | não sobrescrever index.html
    firebase deploy

## Subir no GitHub
    git init
    git add .
    git commit -m "Primeira versão"
    git branch -M main
    git remote add origin https://github.com/SEU-USUARIO/financas.git
    git push -u origin main
