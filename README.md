Criando o meu primeiro repositorio

### Comando básicos do Git

*pwd - Present Work Directory msotra o caminho de onde você está
*cd - change directory usado para se locomover entre pastas
*cd ~ - volta para a pasta raiz
*cd . - volta uma pasta acima
*cd nome-da-pasta - para entrar em uma pasta (para conseguir enxergar essa pasta quando listar os arquivos)
*whoiam - identifica o usuário que está mexendo no sistema
*git confi --global user.name - Faz login do usuario
*git config --global user.email - mostra o email do usuario
*git clone url-que-vc-esta-usando  - Para clonar a url do repositorio, copiar a url(ctr+c) e inserir após esse comando(shift+insert)
*git init - comando p avisar que o Git vai começar a versionar na pasta que foi selecionada
*git add ou git add caminho-do-arquivo - adiciona no repositorio via linha de comando, todos os arquivos de uma vez
*git commit -m - escreve uma msg para indicar o que vocÊ modificou/adicionou nos arquivos/cria um historico do arquivo
*git remote add origin url-que-vcs-copiaram-do-github
*git remote -v vai mostrar as urls
*git pull origin master - o comando PULL pega a versão do arquivo que está no repositório remoto e cria uma cópia no seu computador
*git push origin master - envia as modificações para o repositório remoto 