# Meu Controle Financeiro

Aplicativo pessoal em HTML, CSS e JavaScript, pronto para GitHub Pages.

## Publicar
1. Abra **Settings → Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)`, depois salve.
4. Aguarde a publicação e abra o endereço informado pelo GitHub Pages.
5. No Android/Chrome, menu ⋮ → **Adicionar à tela inicial** ou **Instalar app**.

## Armazenamento
Os dados financeiros ficam no IndexedDB local do navegador, no banco `meu-controle-financeiro`, object store `appState`. Nenhum dado financeiro é enviado ao GitHub. O armazenamento é específico deste navegador/aparelho; exporte ou faça backup antes de limpar os dados do navegador ou trocar de aparelho.

## Arquivos
- `index.html`: aplicação e regras de cálculo.
- `manifest.webmanifest`: configuração PWA.
- `sw.js`: cache para abertura offline após a primeira visita.
- `icon.svg`: ícone do aplicativo.
