
# RESUMO | Git e GitHub

Este repositório servirá como material de apoio. Sempre que quiser relembrar conceitos básicos ou algum comando para manipular seus repositórios, consulte aqui.

## ⚙ Tecnologias Requeridas
- [Git Download](https://git-scm.com/downloads)

## 💡 Termos Utilizados

| Termos | Resumos |
|-----|----------|
Branch | Ramificação do Projeto. |
Commit | "Post" da nova versão do Código. |
Marge | Comando para unificar Branch'. |
Remote | Liga o repositório local com o repositório no GitHub. |
Push | Envia as atualizações do local para o remoto. |
Pull | Puxa as atualizações do remoto para o local. |

### Branch:
- Ramificação do Projeto.
- Existe a possibilidade de fazer outras ramificações durante o desenvolvimento do código para testar, aprimorar, forçar bugs, tudo isso sem alterar a ramificação inicial.
- Isso são as Branches.

### Merge:
- Como foi dito anteriormente, os commits podem ou não ser feitos na ramificação inicial.
- Contudo, se eles estiverem em outra ramificação ou Branch, e fizer sentido unir ambas as versões do código, utiliza-se o Merge.
- Ele irá fundir Branches alternativas com a Branch principal ou (Main).

### Commit:
- É um post, literalmente você posta uma nova atualização quando você "commita".
- Seu diretório local (seu computador) não irá atualizar automaticamente com quaisquer alterações que você tenha feito.
- Para isso existe o "Commit". Junto dele, você coloca um comentário para exemplificar o que mudou naquela versão do post.

### Remote:
- Faz a ligação do seu repositório local com seu repositório no GitHub.

### Push:
- Ele serve para você enviar o "commit" que foi feito no repositório local para o repositório remoto no GitHub.
- Pois ele não vai automaticamente, então você pode "empurrar".

### Pull:
- Você puxa o que está no repositório remoto para seu repositório local (seu computador).

#### Esses são os termos mais utilizados no dia a dia. Embora autoexplicativos, podem gerar dúvidas às vezes, por isso, este material servirá como consulta.

## 💻 Resumo dos Códigos

### _git init_
- **Ao escolher ou criar uma pasta para um novo repositório, esse comando inicia um repositório local vazío.**

### _git add_ (Nome do arquivo)
- **Exemplo: git add README.md.**
- **Git add prepara o arquivo para ser "empurrado" para o repositório remoto.**

### _git add_ .
- **Git add prepara todos os arquivos para serem "empurrados" para o repositório remoto.**

### _git status_
- **Mostra o status do repositório, aqui, pra exemplificar o git status, se usado apos o git add, pode nos indicar se funcionou ou não.**

- **Funcionou: Change to be commited "Mensagem Verde".**
- **Não Funcionou: "Mensagem Vermelha".**

### _git commit -m "mensagem do commit"_
- **Irá criar o COMMIT com a respectiva mensagem.**

### _git branch -M main_
- **É necessário, antes de mais nada, mudar o nome da Brench inicial para main antes de fazer o envio para um repositório remoto.**

- **Motivo: Boas práticas.**

### _git remote add origin link do seu repositório no GitHub_
- **Esse comando faz a linkagem dos seus dois repositótios, tanto o Local (Computador) quanto o remoto (GuitHub).**

### _git push -u origin main_
- **"Empurra" o seu repositório local para o remoto de fato, esse comando terá de ser digitado todas as vezes que você quiser enviar as atualizações do projeto.**