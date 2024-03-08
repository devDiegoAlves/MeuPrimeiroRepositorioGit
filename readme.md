# Git
(GIT = Sistema de Controle de Versão Distribuído)
## Git Init
### O que é o Git Init?
>**_Git Init_** é um Comando que inicia um repositório _"GIT"_ em um diretório (pasta) já existente ou em um novo (vazio).

### Para que serve o Git Init?
>Serve para criar um novo subdiretório chamado _.git_ (faz um a nova pasta, dentro da já existente, com o nome _.git_), tal subdiretório conterá todos os arquivos necessários para o repositório e sua manutenção.
>
>A partir dele, pode-se ter acesso a todas as versões de um mesmo código que foram armazenadas ou modificadas dentro desse mesmo repositório.
>
>**Por exemplo:** Se você tiver um código previamente armazenado num repositório e em algum momento você editar qualquer linha desse mesmo código, existe uma possibilidade de você identificar em que momento e qual linha algo foi modificado (seja por você mesmo, ou por outra pessoa, no caso de uma plataforma como o GitHub, por exemplo).

## Git Add
### O que é o Git Add?
>**_Git Add_** é um Comando que de forma básica, adiciona (como o nome sugere) conteúdo, ou seja, propõe uma mudança no _git_ — essa mudança pode ser tanto uma alteração, quanto uma remoção ou a própria adição de conteúdo. — em um arquivo local ao índice ou staging area, que terá a mudança confirmada, posteriormente, com o comando _git commit_, e finalmente enviada ao repositório remoto pelo _git push_.
>
>**Ou seja**, esse conjunto de comandos, iniciado pelo _git add_, são os responsáveis por “salvar” nossas alterações no projeto.

## Git Reset
### O que é o Git Reset?
>**_Git Reset_** é o comando que "desfaz" o erro, basicamente. Serve para desfazer as alterações (ou preparações de arquivos) realizadas e permite o fazer sem a necessidade de um _"commit"_.

## Commit
### O que é um Commit?
>Um **_commit_** adiciona as alterações mais recentes do código-fonte para o repositório, tornando essas alterações parte da revisão principal do repositório. O próprio termo _"commit"_, no inglês, significa "comprometer-se", ou seja, quando você realiza um _"commit"_, você se compromete que aquelas modificações realizadas, ficarão efetivamente salvas no repositório.

### É possível "desfazer" um Commit?
>Sim, os sistemas de controle de versão (GIT) permitem reverter facilmente para versões anteriores. Nesse contexto, um commit dentro de um _Git_ é protegido, pois é facilmente revertido, mesmo após o commit ter sido aplicado.

## Git Clone
### O que é o Git Clone?
>O **_git clone_** é usado para selecionar um repositório existente e criar um clone ou cópia do repositório de destino.
>
>Sobretudo, utiliza-se o  _"git clone"_ para apontar para um repositório existente e fazer um clone ou cópia deste repositório no novo diretório, em outro local. O repositório original pode estar localizado no sistema de arquivos local ou em protocolos com suporte a acesso por máquinas remotas. O comando _git clone_ copia um repositório do _Git_ existente.
>
>A "cópia de trabalho" é um repositório completo do _Git_ — que tem seu próprio histórico, gerencia seus próprios arquivos e é um ambiente isolado como um todo do repositório original.

## Git Fetch, Git Pull e Git Push
### O que é Git Fetch?
>O comando **_git fetch_** baixa _"commits"_, arquivos e referências de um repositório remoto para seu repositório local. Busca (_fetching_) é o que você faz quando quer ver em que todos estão trabalhando.
>
>O _Git_ isola o conteúdo buscado do conteúdo local existente e não tem efeito algum no trabalho local de desenvolvimento.
>
>Ao baixar conteúdo de um repositório remoto, os comandos _git pull_ e _git fetch_ ficam disponíveis para realizar a tarefa. Pode se considerar _"git fetch"_ a versão "segura" desses comandos. Ele vai baixar o conteúdo remoto, mas não vai atualizar o estado de trabalho do repositório local, deixando o trabalho atual intacto.

>**Resumindo:** Identifica alterações entre um repositório local e o remoto.

### O que é Git Pull?
>O **_git pull_** é a alternativa mais agressiva: ele vai baixar o conteúdo remoto para a ramificação ativa local e vai executar o comando _git merge_ — Mesclagem é o jeito do Git de unificar um histórico bifurcado. — imediatamente para criar um commit de merge para o novo conteúdo remoto. Mudanças pendentes em andamento podem causar conflitos e ativar o fluxo de resolução de conflitos de merge.

>**Resumindo:** Puxa as informações baixadas e adiciona no repositório local.

### O que é Git Push?
>O comando **_git push_** é usado para enviar o conteúdo do repositório local para um repositório remoto. O comando _push_ transfere commits do repositório local a um repositório remoto. 
>
>É o oposto de _"git fetch"_, que importa commits para ramificações locais, enquanto o comando _push_ exporta commits para ramificações remotas. As ramificações remotas são configuradas usando o comando _"git remote"_ — uma interface para gerenciar uma lista de entradas remotas que são armazenadas no 'arquivo ./. git/config' do repositório. — O comando _push_ tem o potencial de sobrescrever modificações e, assim, deve ser usado com cuidado.

>**Resumindo:** Envia as alterações do repositório local até o remoto (GitHub).

## Git Status
### O que é Git Status?
>O comando _**git status**_ exibe as condições do diretório de trabalho e da área de staging. Ele permite que você veja quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git.