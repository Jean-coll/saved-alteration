# Tech Lead

1. Ajudar quando os membros da equipe estiverem com dificuldades
2. Gerenciar as tarefas no trello
3. Garantir que os padrões de git estão sendo seguidos
4. Executar tarefas 

# Membros da equipe

1. Seguir os padrões de git definidos
2. Ajudar quando os membros da equipe estiverem com dificuldades
3. Executar tarefas

# Colunas no trello

### Backlog
- Essa coluna deve ter tarefas que foram identificadas que precisam ser feitas porém ainda não estão prontas, pode ta faltando descrições e detalhamento.

### Pendente
- Essas coluna deve ter tarefas que estão prontas para que alguém pegue e coloque na coluna *Em andamento*

### Em andamento
- Essa coluna deve ter tarefas já começaram a ser feitas, deve ta assinado com o nome de alguém da equipe

### Aguardando aprovação
- Essa conluna deve ter tarefas que já estão com a pull request aberta esperando aprovação da equipe

### Concluído
- Essa coluna deve ter tarefas que já foram revisadas, aprovadas e mergeadas na branch main

# Branch

### main
- Essa branche deve ser a principal, a branch que vai atualizar o ambiente de produção. Não pode receber *git push*
diretamente, só recebe alterações através de pull requests (PR) aprovadas.
- Toda nova branch deve sair da *main*

# Fluxo de nova brach

1. git pull na *main*
2. criar nova branch
3. Fazer as alterações para finalizar tarefa
4. git add, git commit e git push
5. Abrir pull request para a branch main
6. Após a pull request ser aprovado e mergeada em staging abrir uma nova pull request da mesma branch para a branch main
