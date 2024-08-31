# Guia Básico de Git

## Configuração Inicial

### Instalação:
    - Baixe e instale o Git no seu computador.

### Configuração Global:
    - git config --global user.name "Seu Nome" (Definir nome de usúario)
    - git config --global user.email "seu@email.com" (Definir email do usúario)

# Comandos Essenciais
### Inicialização e Clonagem:
    - git init (Inicializa um novo repositório Git).
    - git clone <URL> (Clona um repositório existente).

## Controle de Versão:

    - git add <arquivo>: Adiciona um arquivo ao índice.
    - git commit -m "Mensagem do commit": Cria um novo commit.
    - git status: Exibe o status do repositório.
    - git log: Mostra o histórico de commits.
    - git pull: Atualiza o repositório local com as alterações remotas.
    - git push: Envia commits locais para o repositório remoto.

## Ramificações (Branches)
### Gerenciamento de Ramificações:

    - git branch: Lista as ramificações.
    - git checkout <nome-branch>: Alterna para uma ramificação específica.
    - git merge <nome-branch>: Combina alterações de uma ramificação com outra.

## Colaboração
### Sincronização com Repositórios Remotos:
    - git remote add origin <URL>: Conecta o repositório local a um repositório remoto.
    - git fetch: Busca as alterações remotas.
    - git pull origin <nome-branch>: Atualiza o repositório local com as alterações remotas.
    - git push origin <nome-branch>: Envia commits para o repositório remoto.

### Ignorando Arquivos
    - Crie um arquivo .gitignore para listar os arquivos que devem ser ignorados pelo Git.

## Comandos Básicos de Linux e Mac
### Navegação e Manipulação de Arquivos:
    - cd: Navega entre diretórios.
    - cd ..: Volta para o diretório anterior.
    - ls: Lista arquivos e pastas.
    - mkdir <nome-pasta>: Cria uma nova pasta.
    - echo "Olá mundo!" > arquivo.txt: Cria um arquivo com conteúdo.
    - cat arquivo.txt: Exibe o conteúdo do arquivo.
    - nano arquivo.txt: Edita o arquivo usando o editor de texto nano.

## Padrões de Nomenclatura para Commits
### Tipos de Commits:

####  Chore: Pequena tarefa. Exemplo:   
    - git commit -m "chore: removendo arquivo.txt"

#### Fix: Correções. Exemplo:
    - git commit -m "fix: correção cálculo de médias"

####  Feat: Inclusão de funcionalidade. Exemplo:
    - git commit -m "feat: inclusão de função para calcular médiana"

#### Docs: Atualização de documentação. Exemplo:
    - git commit -m "docs: atualização da documentação"

### Licença
## Este projeto está licenciado sob a Licença MIT.

