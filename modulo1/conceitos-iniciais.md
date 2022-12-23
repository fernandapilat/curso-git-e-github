# **Conceitos básicos:**

- **Versionamento:**
    - Controle de versões definido através de “numerações”.
    - Ele permite que devs saibam quais/quantas alterações foram realizadas.
- **Repositório:**
    - É a pasta de armazenamento de um projeto.
    - Arquivo .git indica que esse repositório é rastreável.
- **Commit:**
    - É um conjunto de alterações no código.
    - No commit é possível visualizar a mudança realizada, bem como uma mensagem descritiva, além de infos de autor, data, etc.
- **Branch:**
    - Separação de código.
    - É possível que várias pessoas atuem em um mesmo projeto independentemente.
    - A branch inicial é a branch master.
    - Develop: ambiente para uso em tempo de desenvolvimento.
    - Homolog: após as alterações serem validadas em ambiente de desenvolvimento, o código vai para a banch/ambiente de homologação.
- **Merge:**
    - O merge consiste em unir duas branchs/ambientes.
    - O merge é feito através de pull requests.
- **Clone:**
    - Transfere o repositório que esta no github para nossa máquina local através de uma cópia.
- **Pull:**
    - Mantém a cópia atualizada no repositório remoto/clonado.
- **Push:**
    - O comando git push **é usado para enviar o conteúdo do repositório local para um repositório remoto.**
    - O comando push transfere commits do repositório local a um repositório remoto.
    - É o oposto do comando git fetch , que importa commits para branches locais, enquanto o comando push exporta commits para branches remotos
- **Fork:**
    - Um fork **é um novo repositório que compartilha configurações de código e visibilidade com o repositório "upstream" original.**
    - Opensource são projetos que são mantidos pela comunidade *(apenas um detalhe)*.

<aside>

> 💡 **Qual é a diferença entre fork e clone?** A ideia **de** um git **clone** , é realmente clonar um repositório, ou seja, é como se você fizesse o download **de** um repositório do Github para sua máquina. A **diferença entre** ele e o **fork** , é que esse último faz o **clone** para o repositório do Github e cria uma "conexão" **entre** o que você fez **fork** e o original.


> 💡 **Git** é controle de versão, criado em 2005 por Linus.

</aside>