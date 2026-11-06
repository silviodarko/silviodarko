# SilvOS — site público

Landing page estática do projeto SilvOS, criada para publicação por **GitHub Pages**.

## Estrutura

- index.html — conteúdo, sem dependências externas.
- styles.css — interface responsiva, efeitos Liquid Glass.
- app.js — menu acessível, animações e destaques da navegação.
- favicon.svg e social-preview.svg — identidade gráfica do site.
- .nojekyll — publicação dos arquivos diretamente, sem processamento Jekyll.

## Publicação

Este site está em /docs do repositório **público de perfil** silviodarko/silviodarko. Ele **não depende do repositório privado** de desenvolvimento do SilvOS.

Em https://github.com/silviodarko/silviodarko/settings/pages configure:

1. Source: **Deploy from a branch**.
2. Branch: **main**.
3. Folder: **/docs**.
4. Clique em **Save** e confira a execução de Pages.

Quando a configuração estiver ativa, o endereço esperado será:

https://silviodarko.github.io/silviodarko/

**Nota:** publicar código na pasta /docs, por si só, não garante que o GitHub Pages esteja ativado. Verifique a configuração e o status do deployment.

## Privacidade e manutenção

- Não há Google Analytics, cookies, formulário, trackers, CDNs, fontes externas, tokens ou qualquer acesso ao conteúdo do usuário.
- A demonstração de Jarvis é **conceitual** e não representa uma conversa real nem uma sessão conectada.
- Todo o conteúdo público sobre o estágio do SilvOS precisa continuar fiel ao [roadmap](../SILVOS_ROADMAP.md).
- Antes de anunciar uma ISO, validar pacotes, redistribuição, licenças, testes de instalação e recuperação.
- O projeto principal segue privado.

**Não inclua** configurações de autenticação, logs de mensagens, identificadores de agentes, credenciais, endereços residenciais ou arquivos internos nesta pasta.
