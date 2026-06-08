# Versionamento - auth context no Laboratorio

Data: 2026-06-08

## Alteracao

O Laboratorio Jus 9 passou a consumir a rota central:

`https://jus9tecnologia.com.br/api/auth/context`

## Resultado

- Login Google continua centralizado no portal Jus 9.
- O painel do Laboratorio passa a exibir contexto governado resumido quando houver sessao.
- Charlie Echo e a equipe podem diferenciar ambiente de laboratorio, perfil operacional e permissoes sem expor segredo.

## Seguranca

Nenhum token, segredo, cookie, senha ou dado pessoal foi publicado.
