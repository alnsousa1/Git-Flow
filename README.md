# Git-Flow

### O Git Flow é um padrão de desenvolvimento onde trabalhamos com branches e ambientes de desenvolvimento, testes e o de produção. O fluxo deve funcionar da seguinte maneira:
### Existirá a branch Master, onde estará armazenado o código de produção;
### A branch Develop, que é o ambiente de desenvolvimento e, a partir dessa branch, será criada as branches para o projeto, seja Fix, para correções ou Feat, para melhorias;
### As branches devem seguir um padrão de nomenclatura, por exemplo feat/2107-add-price-filter (prefixo Feat ou Fix / numeração do card da tarefa – nome da branch, normalmente em inglês), seguindo o mesmo padrão para Feat, trocando apenas o prefixo;
### Após a criação da branch específica e a realização da task, o desenvolvedor realizará o commit, push e o Pull Request para a branch DEVELOP. Concluindo esta etapa, o mesmo voltará para a branch DEVELOP com o comando “git checkout develop” e atualizará o código, já com ### a nova alteração, “git pull origin develop”. Dessa forma, o projeto estará seguindo o padrão de desenvolvimento e entrega do Git Flow;
