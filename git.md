Lista de comandos Git úteis, com uma breve explicação de cada um:

---

### Inicialização e Configuração

- **git init**  
  Inicia um novo repositório Git no diretório atual.

- **git config --global user.name "Seu Nome"**  
  Define o nome do usuário para os commits (configuração global).

- **git config --global user.email "seuemail@exemplo.com"**  
  Define o e-mail do usuário para os commits (configuração global).

---

### Trabalhando com Repositórios

- **git clone <URL_do_repositório>**  
  Clona um repositório remoto para o seu ambiente local.

- **git remote add origin <URL_do_repositório>**  
  Adiciona um repositório remoto com o apelido "origin".

- **git remote -v**  
  Lista os repositórios remotos configurados.

---

### Gerenciamento de Arquivos e Commits

- **git status**  
  Exibe o estado atual dos arquivos, indicando quais foram modificados, adicionados ou estão prontos para commit.

- **git add <arquivo>**  
  Adiciona um arquivo específico à área de stage.

- **git add .**  
  Adiciona todas as alterações no diretório atual à área de stage.

- **git commit -m "Mensagem do commit"**  
  Registra as alterações adicionadas à área de stage com uma mensagem descritiva.

- **git commit -a -m "Mensagem do commit"**  
  Adiciona e commita todas as alterações rastreadas (não inclui arquivos novos que ainda não foram adicionados com `git add`).

- **git log**  
  Mostra o histórico de commits do repositório.

- **git diff**  
  Exibe as diferenças entre as alterações feitas e o último commit (ou entre branches/commits especificados).

---

### Branches e Merges

- **git branch**  
  Lista todas as branches existentes.

- **git branch nome-da-branch**  
  Cria uma nova branch com o nome especificado.

- **git checkout <nome-da-branch>**  
  Muda para a branch especificada.

- **git checkout -b <nome-da-branch>**  
  Cria e muda para a nova branch em um único comando.

- **git merge <nome-da-branch>**  
  Une a branch especificada com a branch atual.

- **git branch -d <nome-da-branch>**  
  Deleta uma branch local (útil para limpeza após o merge).

---

### Atualizando o Repositório Remoto

- **git pull**  
  Busca as alterações do repositório remoto e as integra na branch atual.

- **git push**  
  Envia os commits locais para o repositório remoto.

- **git push -u origin <nome-da-branch>**  
  Envia a branch atual para o repositório remoto e a vincula à branch remota correspondente.

---

### Gerenciamento de Alterações e Históricos

- **git reset --hard <commit_id>**  
  Retorna o repositório a um estado anterior, descartando todas as alterações feitas após o commit especificado.

- **git stash**  
  Salva temporariamente alterações que não foram commitadas, permitindo trabalhar em outra branch sem perder o trabalho atual.

- **git stash apply**  
  Restaura as alterações que foram guardadas com o comando `git stash`.

- **git tag <nome-da-tag>**  
  Cria uma tag para marcar pontos importantes na história do repositório (por exemplo, versões de lançamento).

---

Esta lista serve como uma referência rápida para os principais comandos Git que os alunos podem consultar durante os estudos e a prática. É interessante incentivá-los a explorar a documentação oficial para aprofundar o conhecimento e descobrir mais comandos e opções disponíveis.
