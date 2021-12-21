# Estudo: Markdown
Este repositório tem o objetivo de descrever como funciona a *síntaxe* de formatação de arquivos do tipo **markdown**

**E este trecho está todo em negrito devido o que estou aprendendo... que é o estilo de fonte.**

*E este trecho estará todo em itálico pois como foi dito anteriormente, estamos treinando.*

## O que é o GIT ?
<img src= "https://git-scm.com/images/logos/2color-lightbg@2x.png" width="100" height="90">

Git é um sistema de controle de versão distribuído gratuito e de código aberto projetado para lidar com tudo, desde projetos pequenos a muito grandes com velocidade e eficiência.

Git é fácil de aprender e ocupa uma área pequena com desempenho extremamente rápido . Ele supera as ferramentas SCM como Subversion, CVS, Perforce e ClearCase com recursos como ramificação local barata , áreas de teste convenientes e vários fluxos de trabalho .

O GIT pode ser baixado clicando <a href="https://git-scm.com/downloads">AQUI</a>

## O que é o GITHUB ?
<img src= "https://sempreupdate.com.br/wp-content/uploads/2021/08/genexus.jpg" wight="100" height="90">

GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo.

### Processo de comunicação entre repositório local e remoto

<img src="https://i.stack.imgur.com/1wPcg.png">

* git init: Cria um repositório Git vazio ou reinicializa um existente.
* git add: Adiciona o conteúdo do arquivo ao índice.
* git status: Mostra o status da árvore de trabalho.
* git commit: Grava alterações no repostório.
* git branch: Listar, criar ou excluir branches.
* git remote: Gerenciar conjunto de repositórios rastreados.
* git push: Atualizar referências remotas junto com objetos associados .

### Processo Prático

1. Acessar o repositório local e executar o git bash (terminal git) dentro deste diretório
2. No git bash executar o comando git init
3. Executar o comando git add .
4. Executar o comando git commit -m "first commit"
5. Após a criação do repositório remoto no Github, executar o comando: git branch -M main
6. Executar o comando git remote add origin "url do repositório remoto"
7. Executar o comando git push -u origin main
8. **OBS.: Para a realização dos procedimentos anteriores, é necessário a autenticação do usuário do Github no terminal do Git (user.name, user.email, token)

