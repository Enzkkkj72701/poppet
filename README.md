# Pop Pet Center JK — publicação do site

Este projeto é um site estático em HTML. Não precisa de `npm install`, build ou framework.

## Publicar pelo GitHub e depois pela Vercel

### 1. Colocar no GitHub
1. Entre em https://github.com e crie um repositório novo, por exemplo `pop-pet-center-jk`.
2. Deixe o repositório público ou privado, conforme sua preferência.
3. Envie os arquivos desta pasta para a raiz do repositório. O arquivo principal precisa se chamar `index.html`.
4. Confirme que `index.html` e `vercel.json` aparecem na página inicial do repositório.

### 2. Publicar na Vercel
1. Entre em https://vercel.com e escolha **Add New → Project**.
2. Conecte sua conta do GitHub, se ainda não estiver conectada.
3. Importe o repositório `pop-pet-center-jk`.
4. Como é um site HTML estático, deixe o framework como **Other** (ou sem framework).
5. Deixe o **Build Command** vazio e o **Output Directory** como `.` (raiz), se a Vercel pedir esses campos.
6. Clique em **Deploy**.

A Vercel vai gerar um endereço `*.vercel.app`. Cada novo envio de alterações para a branch principal do GitHub poderá disparar uma nova publicação.

## Antes de divulgar
- Abra o site publicado no computador e no celular.
- Teste os botões do WhatsApp e do mapa.
- Confira textos, endereço e telefone.
- As fontes do Google Fonts precisam de conexão com a internet; há fontes alternativas no CSS.
