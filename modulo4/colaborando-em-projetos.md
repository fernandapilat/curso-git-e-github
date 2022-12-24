# **Colaborando em projetos de outras pessoas**

No GitHub, um **“fork”** é simplesmente o mesmo projeto no seu namespace, permitindo que você faça alterações publicamente em um projeto como uma forma mais aberta de contribuir.

## **Atualizando um fork**

Passo a passo para atualizar os commits localmente.

1. **git remote add upstream http//: repositório forkado**.
2. **git fetch upstream:** parecido com o pull.
3. **git rebase upstream/master:** a partir da perspectiva de conteúdo, o rebase é o processo de alterar a base da ramificação do commit para outra, fazendo parecer como se você criou a ramificação a partir de um commit diferente. De um jeito intrínseco, o Git realiza isso criando novos commits e aplicando-os à base especificada.

