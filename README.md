#Meu Projeto

git init 
- inicia um novo projeto no Git;

git add <nome do arquivo>/.
- adiciona os arquivos que estão prontos para serem commitados;

git commit -m "mensagem do commit"
- commita os arquivos no histórico;

git log
- mostra os ultimos commits;

git status 
- como está o estado das nossas ramificações;

git diff
- mostra o que foi alterado;
- o que tem de alteração na ramificação;

git merge 
- merge de ramificações, mescla as ramificações;

git branch 
- mostra a branch atual 

git branch -b <nome da branch>
- cria uma nova branch a partir do hitórico da branch atual;

git checkout <nome da branch>
- muda para a branch escolhida;

git remote add <nome do remote><link>
- adiciona um novo repositório no git remote escolhido (Github ou demais);

git push origin <nome do repositório>
- manda nossas atualizações locais para o repositório no Git remote escolhido;

git push origin <nome> <nome da branche>
- pega as alterações feitas no repositório remoto e traz para nossa máquina local;

git fetch 
- atualiza o histórico local de acordo com o histório do repositório remoto; 
- sincronização do local com o remoto; 