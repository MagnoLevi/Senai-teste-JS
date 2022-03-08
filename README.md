-simulação read me-

# Alteração feita no Senai-teste-JS
Uma alteração foi feita em seu código evitando conflitos

#### Por que usar Git?
Ele é usado para controlar o histórico de alterações de arquivos e principalmente de projetos de desenvolvimento de software. Ele permite mais flexibilidade no fluxo de trabalho, segurança e desempenho.

#### Commit?
Um commit é a realização de um conjunto de mudanças provisórias permanentes, marcando o fim de uma transação. Em sistemas de controle de versão, como o Git, um commit adiciona as alterações mais recentes do código-fonte para o repositório, tornando essas alterações parte da revisão principal do repositório. Os sistemas de controle de versão permitem reverter facilmente para versões anteriores.

## Passos para commitar um projeto
- git bash here (na pasta que será commitada)
- cd "nome da pasta" (caso necessario)
- git init 
- ls -a (lista documentos ocultos, ex: pasta gerencial do .git)
- git add * (adiciona o que vai ser comitado)
- git status (para checar o status do seu commit)
- git commit -m "" 

- criar um repositório no github
- git remote add origin (escreva o link oferecido do seu repositorio do github aqui)
- git remote -v (mostra a lista de repositorio(s) cadastrado)
- git push origin master

## "Baixar" um repositório para alterar o conteúdo
Em vez de baixar repoitórios de outros é melhor clonar para evitar conflitos

- git clone (escrever o link do repositório)
- cd (nome do arquvio) (para entrar no arquivo clonado)
- ls -a (mostrar repositorios ocultos)
- git remote -v (para ver para qual repositorio remoto este repositorio local que acabamos de clonar está apontado)
