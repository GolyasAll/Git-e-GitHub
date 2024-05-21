# RESUMO | Git e GitHub
## Adicionando uma nova Branch
- Ramificação do Projeto.
- Existe a possibilidade de fazer outras ramificações durante o desenvolvimento do código para testar, aprimorar, forçar bugs, tudo isso sem alterar a ramificação inicial.
- Isso são as Branches.

## 💻 Resumo dos Códigos

### _git checkout -b "Nome da nova Branch_
- **Com este comando estamos criando uma nova Branch, e com o checkout estamos saindo da nossa Branch inicial, no caso a Main.**

- **Isso significa que todas as alterações que eu fizer apartir disso, farão parte apenas da nova Branch, então elas não poderão mudar nada feito na Branch "Main".**

- **Isso facilitará fazer testes sem prejudicar o projeto.**

### _git add_ .
- **Git add prepara todos os arquivos para serem "empurrados" para o repositório remoto.**

### _git commit -m "mensagem do commit"_
- **Irá criar o COMMIT com a respectiva mensagem.**

### _git push origin Nome da nova Branch_
- **"Empurra" o seu repositório local para o remoto de fato, esse comando terá de ser digitado todas as vezes que você quiser enviar as atualizações do projeto.**

- **"Com isso você enviou um Commit para seu repositório remoto e no GitHub você pode conferir as Branchs que tem disponíveis no projeto.**

- **"Agora vamos imaginar que essa nova ramificação foi promissora, você agora quer adicionar essa atualização que no início era apenas um teste, mas agora fará parte do projeot em sí, segue abaixo as linhas de código para fazer o MERGE.**

### _git checkout main_
- **Para voltar para a Branch inicial e principal "Main".**

### _git merge Nome da Branch que Quer Juntar_
- **Para voltar para a Branch inicial e principal "Main".**

### _git push origin main_
- **"Empurra" o seu repositório local para o remoto de fato, esse comando terá de ser digitado todas as vezes que você quiser enviar as atualizações do projeto.**