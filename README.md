# Comandos-Basicos-do-Git
Relação dos principais comandos do Git


### 1. Git config = Configurar sua identidade de usuário 
    git config --global user.name "seu nome"
    git config --global user.email "seu email"
   
#### Importante usar o mesmo nome e e-mail utilizado no GitHub 

### 2. Git init = Criar repositório 
    git init nome do repositorio
   
### 3. Git clone = Cria uma copia exata de um repositório ja existente
    git clone <URL do seu projeto>
    
### 4. Git add = Adiciona os arquivos especificados de código ao seu repositório, sejam arquivos novos ou anteriores, que foram alterados
    git add seu_arquivo (*adiciona arquivo em especifico ao repositorio*) 
    git add* (*adiciona todos os arquivos novos e/ou modificados ao repositorio*) 
    
 ### 5. Git commit = Executa o commit dos arquivos que foram adicionados e cria uma nova com um log 
      git commit
      git commit -a   
      git commit -m "seu comentario"
      
 ### 6. Git branch = É um caminho independete de desenvolvimento, uma alternativa 
      git branch (*lista todas as ramificações*)
      git branch <nome_do_branch> (*cria um branch com o nome especificado*)
      git branch d <nome_do_branch> (*deleta o brunch com o nome especificado*)
      
 ### 7. Git checkout = Pode ser utilizado para trocar de uma ramificação para outra
        git checkout <nome_do_brunch>
        
 ### 8. Git remote = Estabelece uma conexão entre seu repositório remoto
        git remote add <nomecurto> <URL>
        
 ### 9. Git push = Serve para subir suas modificações para um repositório remoto conectado anteriormente com git remote
        gitpush -u <nomecurto> <nome_do_brunch>
        
 ### 10. Git fetch = Irá receber todas as informações de commits, para avaliar, antes de aplicar essas alterações na sua versão local do repositório
         git fetch
      
      
