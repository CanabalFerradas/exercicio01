# Inicializa um repositório Git na pasta atual
git init

# Configura o nome de usuário global
git config --global user.name "rodrigo ferradas"

# Configura o email de usuário global
git config --global user.email "rodrigo.ferradas1587@gmail.com"

# Abre o arquivo readme.md no editor vi
vi readme.md 

# Mostra o status dos arquivos no repositório
git status

# Adiciona todos os arquivos ao stage
git add .

# Realiza o commit dos arquivos no stage com a mensagem "criando estrutura"
git commit -m "criando estrutura"

# Mostra o histórico de commits
git log 

# Mostra o histórico de commits em uma linha
git log --oneline

# Restaura as mudanças não salvas do arquivo readme.md
git restore readme.md

# Remove o arquivo readme.md do stage
git restore --staged readme.md

# Remove o arquivo arquivo.txt do stage
git restore --staged arquivo.txt

# Alterna para a versão do arquivo readme.md no último commit
git checkout readme.md

# Abre o arquivo .gitignore no editor vi
vi .gitignore

# Mostra o status dos arquivos no repositório
git status 

# Adiciona todos os arquivos ao stage
git add .

# Realiza o commit dos arquivos no stage com a mensagem "criando arquivo .ignore"
git commit -m "criando arquivo .ignore"

# Mostra as diferenças entre o working directory e o stage
git diff

# Adiciona todos os arquivos com extensão .py ao stage
git add *.py 

# Adiciona o arquivo arquivo.txt ao stage
git add arquivo.txt

# Mostra o status dos arquivos no repositório
git status

# Modifica o conteúdo do arquivo arquivo.txt
echo "modificando arquivo.txt" > arquivo.txt 

# Mostra as diferenças entre o stage e o último commit
git diff --staged

# Mostra as mudanças feitas no último commit
git show
