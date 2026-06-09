# VERSIONAMENTO - Cadastros Governados do Laboratorio

Registrado em: 2026-06-09 07:38:28.48463

## Escopo

Cria a pagina `cadastros.html` para o Laboratorio Jus 9 registrar estudantes, pesquisadores, desenvolvedores, revisores, I.As convidadas e membros da Familia Virtual.

## Alteracoes

- Nova pagina de cadastros com login Google central.
- Novo script `assets/js/perfis-governados.js`.
- Rascunhos locais ficam no navegador.
- Com sessao autorizada, o formulario envia solicitacao governada para `/api/profile-requests`.
- Menu principal do Laboratorio recebeu link para Cadastros.

## Regra

Cadastro no Laboratorio cria solicitacao para revisao humana. Nao concede cofre, nao publica segredo e nao cria permissao sensivel automaticamente.
