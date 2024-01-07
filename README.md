Git - Guia Rápido para Principais Comandos
O Git é um sistema de controle de versão distribuído amplamente utilizado para o gerenciamento de projetos de software. Este guia rápido fornece uma visão geral dos principais comandos Git para ajudá-lo a começar.

Configuração Inicial
Configurar Nome e Email:

bash
Copy code
git config --global user.name "Seu Nome"
git config --global user.email "seu.email@example.com"
Iniciar um Repositório:

Inicie um novo repositório:
bash
Copy code
git init
Clone um repositório existente:
bash
Copy code
git clone URL_DO_REPOSITORIO
Trabalhando com Alterações
Adicionar Alterações:

bash
Copy code
git add nome_do_arquivo
git add .  # Adicionar todas as alterações
Confirmar Alterações:

bash
Copy code
git commit -m "Mensagem do Commit"
Verificar Status:

bash
Copy code
git status
Visualizar Histórico de Commits:

bash
Copy code
git log
Ramificações (Branches)
Criar e Trocar de Ramificação:

bash
Copy code
git branch nome_da_ramificacao
git checkout nome_da_ramificacao
Criar e Trocar de Ramificação em um Único Comando:

bash
Copy code
git checkout -b nome_da_ramificacao
Fundir Ramificações:

bash
Copy code
git merge nome_da_ramificacao
Remover Ramificação:

bash
Copy code
git branch -d nome_da_ramificacao
Atualizações Remotas
Atualizar Repositório Local com Mudanças Remotas:

bash
Copy code
git pull origin nome_da_ramificacao
Enviar Commits para Repositório Remoto:

bash
Copy code
git push origin nome_da_ramificacao
Adicionar um Repositório Remoto:

bash
Copy code
git remote add nome_remoto URL_DO_REPOSITORIO
Desfazer Alterações
Desfazer Alterações não Cometidas:

bash
Copy code
git checkout -- nome_do_arquivo
Desfazer último Commit (Local):

bash
Copy code
git reset HEAD~1
Desfazer último Commit (Remoto):

bash
Copy code
git revert HEAD
Este guia abrange os principais comandos do Git, mas há muitos outros recursos e opções disponíveis. Consulte a documentação oficial do Git para obter informações mais detalhadas: Git Documentation.
