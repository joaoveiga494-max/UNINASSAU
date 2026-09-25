# UNINASSAU
git init                          → Inicializa um repositório Git na pasta atual
git clone <url>                   → Copia (clona) um repositório remoto para sua máquina
git status                        → Mostra o estado dos arquivos (modificados, não rastreados, etc.)
git add <arquivo>                 → Adiciona um arquivo à área de staging
git add .                         → Adiciona todos os arquivos modificados à área de staging
git commit -m "mensagem"          → Salva as mudanças da staging area como um novo commit
git log                           → Mostra o histórico de commits
git diff                          → Mostra as diferenças entre versões de arquivos
git branch                        → Lista, cria ou apaga branches
git checkout <branch>             → Troca para outra branch
git switch <branch>                → Troca para outra branch (comando mais novo)
git checkout -b <branch>          → Cria e já troca para uma nova branch
git merge <branch>                → Junta as mudanças de uma branch na branch atual
git pull                          → Baixa e mescla as mudanças do repositório remoto
git push                          → Envia seus commits locais para o repositório remoto
git remote add origin <url>       → Associa o repositório local a um repositório remoto (GitHub)
git fetch                         → Baixa as mudanças do remoto sem mesclar automaticamente
git reset                         → Desfaz mudanças (staging ou commits, dependendo da opção)
git revert <commit>               → Cria um novo commit que desfaz um commit anterior
git stash                         → Guarda temporariamente mudanças não commitadas
git config --global user.name     → Configura o nome do usuário no Git
git config --global user.email    → Configura o e-mail do usuário no Git
