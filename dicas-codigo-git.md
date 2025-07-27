Trilha do que fazer

    1- Iniciar um repositório local
        1.1- git init

    2- Clonar um repositório
        2.1- entrar na pasta desejada
        2.2- git clone [url do repositorio desejado]

    3- Preparar (adicionar) as alterações
        3.1- git add .

    4- Commitar
        4.1- Antes, preparar as alterações com a dica 3    
        4.2- git commit -m [mensagem]

    5- Fazer o push (enviar) do repositório local para o repositório online:
        5.1- git push -u origin [nome da branch]

Outros:

    I- Mostra o histórico dos commits
        I.I- git log
        I.II- Para sair da interface desse hitórico, digite "q"

    II- Ver estado atual do repositório
        II.I- git status
    
    III- Listar todas as branchs
        III.I- git branch
    
    IV- Criar uma branch
        IV.I- git branch [nome da branch]

    IV/V- Criar uma branch e entrar nela no mesmo comando
        IV/V.I- git checkout -b [nome da branch]
    
    V- Entrar/trocar para uma branch
        V.I- git checkout [nome da branch]
    
    VI- Combinar as alterações feita numa outra branch e juntá-las
        VI.I- git merge [nome da branch]
        VI.II - Exemplo abaixo
            VI.II.I- git checkout main # 1.Vai para a branch de destino
            VI.II.II- git pull origin main # 2. Atualiza a branch local com a versão mais recente do repositório remoto (opcional, mas recomendado)
            VI.II.III- git merge feature # 3. Faz o merge da branch "feature" para "main"

    VII- Fazer o pull (receber/atualizar) do repositório online para o repositório local
        VII.I- git pull origin [nome da branch]

    VIII- Adicionar para qual repositório *remoto* (repositório do GitHub) o código está indo
        VIII.I- git remote add origin [url do repositório]

    IX- Ver qual repositório *remoto* (repositório do GitHub) o código estava indo
        IX.I- git remote -v