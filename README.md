# somun hub

Painel de administração do somun ("somos um"): a lista de igrejas (sinal de vida de cada programa:
quando usou e a versão instalada, com uma anotação) e os relatos de problema de todos os programas.

Só a conta da administração entra — quem protege os dados são o login e as regras do Firestore
(`firestore.rules` no repositório do Diretor, coleções `sinais`, `hubNotas` e `relatos`). A
configuração do Firebase (`firebase-config.js`) é pública de propósito.

Publicado pelo GitHub Pages (`.github/workflows/pages.yml`).
