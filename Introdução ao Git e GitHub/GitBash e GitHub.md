# Primeiros Passos com o GitHub :file_folder:



## Entendendo como funciona: :books:

* #### Conceito de Git e GitHub:

  * Ao contrário do que as pessoas pensam, git não é a mesma coisa que o GitHub, O Git é um *sistema de controle de versão distribuído* . Isso significa que se você está trabalhando em um ambiente de equipe, com outros desenvolvedores e programadores, todo o código que você e seus colegas escrevem será compartilhado entre todos vocês. 
  * Já o GitHub é um serviço de hospedagem. Ele é usado para rastrear alterações de código fonte. Embora ele forneça todas as funções do Git, o GitHub também adiciona algumas outras funcionalidades.

  De outra forma, iremos criar nossos diretórios locais na nossa máquina com o código que você está criando ou fazendo "manutenção" o Git será o responsável por verificar e "empurrar" o código para o servidor(GitHub ou outros) para que outras pessoas possam vê-lo e também ajuda-lo com sugestões e etc.

=======================================================================================

*Com isso entendemos que o Git não precisa necessariamente do GitHub, como o GitHub é apenas um serviço de hospedagem, podemos utilizar muitos outros para alocar nossos códigos, o GitHub é apenas o mais "famoso" entre as empresas digamos assim.*

=======================================================================================

Então após tudo isso é aí que entra o GitBash como o nosso "centro de comando" onde lá poderemos gerenciar nossos diretórios e envia-lo ao servidor.



* ### Principais comandos: :label:

  * **Git Init (somente caso vc tenha criado o diretório diretamente da sua máquina, caso tenha criado direto pelo GitHub e clonado esse comando n é necessário, ele é feito automaticamente)** = *Utilizado para criar um novo projeto de git.*
  * **Git Clone** = *Esse comando Git cria uma cópia exata de um repositório já existente.*
  * **Git add** = *Esse comando Git adiciona os arquivos especificados de código ao seu repositório, sejam arquivos novos ou arquivos anteriores que foram alterados. Oferece diferentes possibilidades de sintaxe.*
  * **Git commit** = É fundamental se estabelecer uma diferença entre git add e git commit:
    - *git add adiciona seus arquivos modificados à fila para serem submetidos a um commit posteriormente. Os arquivos **não** passaram por um commit.*
    - *O git commit executa o commit dos arquivos que foram adicionados e cria uma nova revisão com um log. Por outro lado, se você não adicionar nenhum arquivo, o git não fará o commit de nada.*
  
  Também é possível adicionar uma mensagem para a execução de um commit. Exemplo:
  
  ​		**git commit -m “seu comentário”**
  
  * **Git remote** = *O comando Git remote estabelece uma conexão entre seu repositório local e um repositório remoto.*
  * **Git Push** = *Esse comando serve para subir suas modificações para um repositório **remoto** conectado anteriormente com git remote.*
  * **Git Push** = *O comando Git pull baixa o conteúdo (não os metadados) do que foi alterado no repositório remoto para o seu repositório local e imediatamente atualiza seu contreúdo para a última versão.*
  * **Git Help** = *Existem inúmeros comandos no Git,  cada um com sua função, parâmetros e características. Felizmente, o próprio Git tem o comando help para trazer ajuda diretamente no terminal.*
