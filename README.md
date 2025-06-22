<h1 align="center"> Como escrever um README incrível no seu Github</h1>
<p> https://www.alura.com.br/artigos/escrever-bom-readme


<h1 align="center"> Como criar um README para o seu perfil do GitHub </h1>
<p> https://www.alura.com.br/artigos/como-criar-um-readme-para-seu-perfil-github

========================
<h1 align="center"> Principais comandos Git </h1>

<h2> Inicia o git no projeto </h2>
<p> git init

<h2>  adiciona todos os arquivos ao git. para adicionar somente um arquivo especificar o nome do arquivo no lugar do "."</h2> 
<p> git add .

<h2> para salvar as alterações </h2> 
<p> git commit -m "informar alguma coisa sobre o projeto"

<h2> configuração para informar usuario do git no computador. deve solicitar somente na primeira vez que associa o usuario no git do computador </h2>
<p> git config --global user.mail "email de cadastro do git"
<p> git config --global user.name "meu nome"
<p> git branch -m main     

<h2> Sincronizar o repositorio local no github </h2>
<p> git remote add origin git@github.com:rodrigomorau/financas.git

<h2> Verificar o apelido do repositorio </h2>
<p> git remote -v

<h2> Enviar os arquivos para o github </h2>
<p> git push -u origin main

<h2> Verificar o status das alterações nos arquivos </h2>
<p> git status

<h2> Verificar commits </h2>
<p> git log

<h2> Reverter Commit: desfazer uma mudança no código sem excluir o commit anterior </h2>
<p> git revert "id commit"

<h2> apagar um commit: apaga o commit anterior </h2>
<h3> Evitar utilizar essa função após enviar as alterações para o github </h3>
<p> git reset --hard "id commit anterior"

<h2> alterar a msg de um commit </h2>
<p> git commit --amend -m "mensagem correta"


<h2> Como não enviar arquivos de senhas para o GitHub </h2>
<p> arquivo .gitignore
<p> site gitignore.io: site para criar automaticamente o arquivo gitignore informando as tecnologias e a linguagem de programação para não atualizar arquivos internos para o github

<h2> Compartilhar somente um trecho do código </h2>
<p> Não precisa criar um novo repositório
<p> New gist dentro do site do github

<h2> CRriar arquivo de log dos commits </h2>
<p> git log > logs.txt

===========================

<h2 align="center"> Controlando versões com Git e GitHub </h2>
<p> https://www.casadocodigo.com.br/pages/sumario-git-github

<p> Neste livro, Alexandre Aquiles e Rodrigo Ferreira mostrarão como utilizar o Git para controlar as versões do seu projeto. Serão ensinados comandos para criação de repositórios, trabalho local e remoto, branches, tags, conflitos, dentre outros assuntos. Além disso, será mostrado também como criar uma conta no GitHub e utilizá-la para hospedar seus repositórios

<h2 align="center"> Documentação git </h2>
<p> https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-O-B%C3%A1sico-do-Git
<p> Documentação oficial do Git, onde você encontrará informações importantes sobre comandos e funcionamento da ferramenta.

<h2 align="center"> Documentação github Conventional Commits </h2>
<p> https://www.conventionalcommits.org/pt-br/v1.0.0-beta.4/
<p> A especificação do Conventional Commits é uma convenção simples para utilizar nas mensagens de commit. Ela define um conjunto de regras para criar um histórico de commit explícito, o que facilita a criação de ferramentas automatizadas. Esta convenção segue o SemVer, descrevendo os recursos, correções e modificações que quebram a compatibilidade nas mensagens de commit.

<h2 align="center"> Ferramenta gerador de .gitignore </h2>
<p> https://www.toptal.com/developers/gitignore/
<p> Ferramenta para criar arquivos .gitignore úteis para o seu projeto.

<h2 align="center"> Ferramenta MarkDown Guide </h2>
<p> https://www.markdownguide.org/
<p> O Markdown Guide é um guia de referência gratuito e de código aberto que explica como usar o Markdown, a linguagem de marcação simples e fácil de usar que você pode usar para formatar praticamente qualquer documento.

<h2 align="center"> Markdown: como trabalhar com essa linguagem de markup? </h2>
<p> https://www.alura.com.br/artigos/como-trabalhar-com-markdown?_gl=1*j8tztu*_ga*NzU2NTAyMDMyLjE2ODcxOTg5NTE.*_ga_1EPWSW3PCS*MTcwMTI4NjgzMy4yOTAuMS4xNzAxMjg5MzM1LjAuMC4w*_fplc*ZXM3TVQzbmI1bSUyQlhHeUZNY1h6VHFIdHZsc1BidGUwV1FWbFMzUm41VGxpSjk2dGl0M1o4OUVuUkdNMVJMN1p2MEtxWE1TV1ZsdFc0Y3A3cVdPYksxcWdUQllCb25CVDZpTGpIVENaakQ0QXlBRW5BbDQ1VTBkRU1NY00wUnclM0QlM0Q
<p> Você irá entender sobre o funcionamento do Markdown, que é um formato de marcação de texto e como fazer o uso adequado dessa ferramenta.

<h2 align="center"> Introducing Github O’Reilly </h2>
<p> https://www.oreilly.com/library/view/introducing-github/9781491949801/
<p> Livro em Inglês para você, que é novo no GitHub. Este livro conciso mostra exatamente o que você precisa para começar e nada mais. É perfeito para gerentes de projetos e produtos e outros membros da equipe que desejam colaborar em um projeto de desenvolvimento, seja para revisar e comentar o trabalho em andamento ou para contribuir com mudanças específicas. Também é ótimo para desenvolvedores que estão aprendendo o GitHub.

<h2 align="center"> Learning Git O'Reilly </h2>
<p> https://www.oreilly.com/library/view/learning-git/9781098133900/?_gl=1*1k0j59z*_ga*MTc2ODczMTk1MS4xNjk4NDI5NjAw*_ga_092EL089CH*MTcwMTcxODU5OC4yLjEuMTcwMTcxODc3NS41My4wLjA.
<p> Este livro,em Inglês, ensina Git de maneira simples, visual e tangível para que você possa construir um modelo mental sólido de como funciona o controle de versão do Git. Através do uso de cores, narrativas e exercícios práticos, você aprenderá a usar essa ferramenta com confiança.
<p> As informações são introduzidas de forma incremental para que você não fique atolado em termos ou conceitos desconhecidos. Aprender Git é ideal para quem precisa usar Git para projetos pessoais ou profissionais: estudantes de bootcamp de codificação, desenvolvedores juniores, profissionais de dados e escritores técnicos, para citar apenas alguns!

============================


1. Crie uma conta no GitHub Você pode começar seguindo os passos mostrados no vídeo, preenchendo o formulário de cadastro, verificando sua conta e explorando a página inicial do GitHub. 

2. Criar um novo repositório no GitHub e fazer o upload de um projeto local para esse repositório. Você pode seguir passos mencionados na aula, como acessar as configurações do GitHub, criar um novo repositório com um nome único e escolher se ele será público ou privado. Em seguida, você pode adicionar uma descrição, um README, um `.gitignore` e uma licença ao repositório. 

3. Instalação do Git: Caso você ainda não tenha realizado a instalação, siga os passos na atividade [Faça como eu fiz: instalação do Git](https://cursos.alura.com.br/course/git-github-compartilhando-colaborando-projetos/task/144999) 

4. Para criar um repositório local você, digite o seguinte comando no terminal: git init

5. Para adicionar os arquivos no repositório local, digite no terminal o comando: git add .

6. Faça um commit com as modificações, digite no terminal o comando: git commit -m "mensagem de commit"

7. Para configurar a identidade do autor do commit, digite no terminal o comando: 
  git config --global user.email "seuemailaqui@example.com" 
  git config --global user.name "seu nome aqui"

8. Para criar a branch Main, digite no terminal o comando: 
  git branch -M main
  O comando git branch -m é usado para criar uma nova ramificação no repositório Git atual. Neste caso, criamos a branch padrão main, que representa a versão principal do código. 

9. Para realizar a conexão do seu repositório local com o remoto via SSH, digite no terminal: 
  git remote add origin git@github.com:seunomedeusuario/seu-repositorio.git
  Caso seja necessário, realize a configuração do protocolo SSH através da geração de chave, você pode acompanhar os passos em vídeo na atividade [Sincronizando repositórios](https://cursos.alura.com.br/course/git-github-compartilhando-colaborando-projetos/task/139310) 

10. Para subir as alterações no repositório local para o remoto, digite o seguinte comando no terminal: git push -u origin main 

11. Digite no terminal o comando "git status" e observe a saída. O comando "git status" é uma ferramenta essencial para gerenciar alterações no controle de versão Git. 
Ele fornece uma visão geral do estado atual do repositório, indicando quais arquivos foram modificados, adicionados ou excluídos desde o último commit. 
Essa informação é crucial para compreender o progresso do desenvolvimento e tomar decisões de gerenciamento de alterações. 
A saída do comando "git status" geralmente contém três seções principais: 
**Modificados:** Lista os arquivos que foram modificados desde o último commit, mas ainda não foram adicionados à área de preparação (Stage). 
**Adicionados:** Indica os arquivos que foram adicionados à área de preparação, mas ainda não foram confirmados no histórico de commits. 
**Modificados, adicionados ou excluídos:** Exibe os arquivos que não foram rastreados pelo Git, ou seja, que não foram adicionados ao índice de modificações (Staging Area). 
Além disso, o comando "git status" pode fornecer informações adicionais sobre as ramificações atuais, como a ramificação atual e as ramificações que estão à frente ou atrás da atual. 
O comando "git status" é uma ferramenta indispensável para qualquer desenvolvedor que utiliza Git. Ele permite monitorar as alterações no repositório, identificar o estado dos arquivos e tomar decisões de gerenciamento de commits de forma eficiente.

