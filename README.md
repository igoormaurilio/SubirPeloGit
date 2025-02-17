# SubirPeloGit
Como subir um projeto no Git

1- Instalar o Git nesse link caso não tenha: https://git-scm.com/downloads

2- Iniciar o terminal (prompt de comando) 

3- Digite o seguinte comando "cd/CodeGame2" que após o "cd/" coloque o caminho do seu projeto e embaixo "git init ." que adiciona todos arquivos da sua pasta e caso não queira todos e sim um especifico, troque o "." pelo nome do arquivo que deseja 

4- Logo após confirmar, faça seu primeiro commit com o seguinte comando "git commit -m "Primeiro commit". O commit tem a função de armazenar as mudanças localmente no repo

5- Acesse o GitHub e crie um repositorio local ao repositorio remoto. OBS: não utilize o README ou .gitignore por conta dos problemas que podem ser vausados no repositório local

6- Adicione o repositório local ao remoto que foi criado. 
Exemplo: "git remote add origin https://github.com/igoormaurilio/CodeGame2.git"

7- Envie sua mudanças com o comando "git push -u origin main" caso seu github seja versão mais atualizada e seu branch for main, senão use o "master" ao invés do "main", exemplo: "git push -u origin master".

8- Vá a página do seu repo atual no github e verifique os arquivos do seu projeto

9- Caso queira atualizar seu projeto use o seguinte comando: 
"git add .
git commit -m "Mudanças no seu projeto"
git push origin main"
