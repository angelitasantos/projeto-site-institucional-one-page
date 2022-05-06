## Git e GitHub

<br>Tira dúvidas Git - GitHub
<br>data: 05 de maio de 2022
<br>resumo:
<br>criar um repositório local e um repositório remoto
<br>comandos aprendidos: git init, git status, git add, git commit, git log, git remote, git push, git pull

<br>Exemplo prático
- criar um repositório local
  - mkdir nomedoprojeto
  - cd nomedoprojeto
  - git init

- criar o primeiro commit
  - echo '# o que escrever' >> README.md
  - git status
  - git add README.md
  - git commit -m 'cria arquivo README.md'
  - git log


- criar um repositório remoto no Github
  - git remote add origin https://github.com/nomedousuario/nomerepositorio.git
  - git push origin nomedabranch
