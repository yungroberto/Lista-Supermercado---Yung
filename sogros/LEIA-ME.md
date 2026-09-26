# Lista de Compras — publicar no GitHub Pages

Estes arquivos formam um app completo e independente (não depende do Claude).
Cada aparelho guarda sua própria lista, salva no próprio celular.

## Arquivos desta pasta
- `index.html` — o app (já vem com seus 246 itens do Notion)
- `manifest.json` — configuração do "app" para instalar na Tela de Início
- `icons/` — os ícones (carrinho laranja)

## Passo a passo

1. Acesse **github.com**, faça login (ou crie uma conta grátis).
2. Clique no **+** no canto superior direito → **New repository**.
3. Dê um nome, por exemplo `lista-compras`. Marque como **Public**. Clique em **Create repository**.
4. Na página do repositório, clique em **Add file → Upload files**.
5. Arraste os 3 itens desta pasta (`index.html`, `manifest.json`, e a pasta `icons`) para dentro da área de upload.
6. Role para baixo e clique em **Commit changes**.
7. Vá em **Settings** (aba do repositório) → **Pages** (menu à esquerda).
8. Em "Branch", selecione **main** e a pasta **/ (root)**. Clique em **Save**.
9. Espere cerca de 1 minuto. A página vai mostrar um link parecido com:
   `https://seu-usuario.github.io/lista-compras/`
10. Abra esse link no Safari do iPhone (seu e o da Natasha).
11. Toque no ícone de **compartilhar** (quadrado com seta pra cima) → **Adicionar à Tela de Início**.
12. Confirme — agora sim ele deve abrir em tela cheia, como um app de verdade.

## Importante
Como cada aparelho guarda a lista localmente (sem servidor), marcar um item no
seu celular **não aparece automaticamente** no da Natasha — são duas listas
independentes a partir daqui. Se algum dia vocês quiserem voltar a ter
sincronização em tempo real entre os dois, dá para reativar a versão que
mora no Claude (o link que já existia) ou montar um backend simples
(ex.: Firebase) para esta versão do GitHub — é só avisar.
