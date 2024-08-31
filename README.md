# Versionamento de código GIT 

- Comanndo básicos Linux e Mac
    - cd
    - cd ..
    - ls
    - mkdir (Criar pastas)
    - echo "Olá mundo!" > "arquivo.txt"
    - cat "arquivo.txt"
    - nano arquivo.txt

-  GIT 
    - git init (inicia o git numa pasta vazia)
    - git  config --global user.name 
    - git config --global user.email
    - git config -- global core.editor "nano"

- Commits
    - git status
    - git commit
    - git add
    - git commit -m  "message"
    - git commit -am "message"



# Padrões de nomeclaturas para mensagens de commits 

### Chore - pequena tarefa 
git commit -m "chore: removendo arquivo.txt" 

### Fix - correções 
git commit -m "fix: correção cálculo de médias"

### Feat - inclusão de funcionalidade
git commit -m "feat: inclusão de função para cálcular médiana"

### Docs -  atualização de documentação
git commit -m "docs: atualização a documentação"