# Git
(GIT = Sistema de Controle de Versão Distribuído)
## Git Init
### O que é o Git Init?
>_Git Init_ é um Comando que inicia um repositório _"GIT"_ em um diretório (pasta) já existente ou em um novo (vazio).

### Para que serve o Git Init?
>Serve para criar um novo subdiretório chamado _.git_ (faz um a nova pasta, dentro da já existente, com o nome _.git_), tal subdiretório conterá todos os arquivos necessários para o repositório e sua manutenção.
>
>A partir dele, pode-se ter acesso a todas as versões de um mesmo código que foram armazenadas ou modificadas dentro desse mesmo repositório.
>
>**Por exemplo:** Se você tiver um código previamente armazenado num repositório e em algum momento você editar qualquer linha desse mesmo código, existe uma possibilidade de você identificar em que momento e qual linha algo foi modificado (seja por você mesmo, ou por outra pessoa, no caso de uma plataforma como o GitHub, por exemplo).

## Git Add
### O que é o Git Add?
>_Git Add_ é um Comando que de forma básica, adiciona (como o nome sugere) conteúdo, ou seja, propõe uma mudança no _git_ — essa mudança pode ser tanto uma alteração, quanto uma remoção ou a própria adição de conteúdo. — em um arquivo local ao índice ou staging area, que terá a mudança confirmada, posteriormente, com o comando _git commit_, e finalmente enviada ao repositório remoto pelo _git push_.
>
>**Ou seja**, esse conjunto de comandos, iniciado pelo _git add_, são os responsáveis por “salvar” nossas alterações no projeto.

## Git Reset
### O que é o Git Reset?
>_Git Reset_ é o comando que "desfaz" o erro, basicamente. Serve para desfazer as alterações (ou preparações de arquivos) realizadas e permite o fazer sem a necessidade de um _"commit"_.

## Commit
### O que é um Commit?
>Um _commit_ adiciona as alterações mais recentes do código-fonte para o repositório, tornando essas alterações parte da revisão principal do repositório. O próprio termo _"commit"_, no inglês, significa "comprometer-se", ou seja, quando você realiza um _"commit"_, você se compromete que aquelas modificações realizadas, ficarão efetivamente salvas no repositório.

### É possível "desfazer" um Commit?
>Sim, os sistemas de controle de versão (GIT) permitem reverter facilmente para versões anteriores. Nesse contexto, um commit dentro de um _Git_ é protegido, pois é facilmente revertido, mesmo após o commit ter sido aplicado.