Este é um repositório de teste para ensinar como o Git funciona

Comandos git:
git init = Inicia a "observação" dos arquivos dentro do diretório.

git status = Lista o status dos arquivos dentro do diretório.
git add "nome-do-arquivo" = altera o status do arquivo de modified para staged. Este arquivo pode ser commitado agora.
git commit -m "Comentário" = Commita as alterações realizadas com um comentário

git log --decorate = exibe informações sobre os commits
git log --author="Bruno" = exibe informações do autor Bruno
git log --graph = exibe em forma gráfica as alterações dos arquivos

git diff = lista as modificações
git checkout = desfaz a alterações, undo changes
git reset = reseta o estado do commit; --soft: remove o commit, mas mantém o arquivo como staged --mixed: remove o commit, volta o arquivo para modified --hard: remove o commit e modificações dos arquivos.

git remote add origin https://github.com/brunomouranascimento/github-course.git = Adiciona o repositorio local ao remoto
git push -u origin master = envia os arquivos para o repositorio remoto