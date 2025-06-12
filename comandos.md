# Principais comandos git  
git init  
git add .
git commit -a -m ""  
git push  
git checkout -b "teste" (troca de braind de main criando a braind "teste")  
git push --set-upstream origin teste (empurra as alterações para o repositório remoto criando diretamento na braind "teste")  
git checkout main (trocando para braind "main")  
git branch (mosra a lista de branch atual)  
git merge teste (une o código da branch atual "main" com o código da branch "teste")
git pull (puxa os arquivos do repositório remoto par ao repositório local)  
git clone https://github.com/cleytondevsouza/Principais-comandos-do-Git.git  (clona o repositório remoto para o repósitório local)  
git clean -f (exclui arquivos do estágio untracked)
git checkout .\index.html (exclui a ultima alteração de um arquivo no estagio untracked aguradando para ser comitado)
git log (Motra toda a lista dos commits realizados no projeto)  
git checkout ea8369 (Retorna e Head para um commit antiror permitindo a volta no tempo para um commit mais antigo do projeto)  
git checkout main (retorna para o ultima versão do projeto desfazendo a volta ao tempo)  
git branch página-de-servicos (cria uma nova branch com o nome "página-de-servico)
git branch -m main (renomeia no nome da branch para "main" OBS: o usuario deverá estar na branch que deseja renomear)  
git push origin nova-imagem-na-pg-de-servcos (envia no repósitório remoto a branch nova-imagem-na-pg-de-servicos)