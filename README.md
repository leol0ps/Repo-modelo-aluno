# Repo-modelo-aluno

Este reposiório é um repositório base para que os professores criem o repositório modelo para os alunos.

- Configure os diretórios de forma que para cada exercicio (.zip) no repositório de soluções tenha uma pasta dentro da pasta problemas/ deste repositório.

-  é necessário fazer mudanças no arquivo **trigger.yml**, siga as instruções abaixo:
  - linha 70: if [ "$GITHUB_ACTOR" = "bot" ] || [ "$GITHUB_ACTOR" = "insira aqui o usuario do repositório hub" ]; then
  - linha 86: se renomeou o repositório hub de outro nome, modificar para tal nome
  - linha 87: modifique para seu usuario
  - linha 97: se renomeou o repositório hub de outro nome, modificar para tal nome
  - linha 98: modifique para seu usuario

Após isso transforme este repositório em um repositório template para que os alunos possam utilizar. Peça para que os alunos mudem a configuração de privacidade do repositório para privado e que façam um convite para que a conta do repositório hub seja um colaborador.


