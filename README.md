---
title: Desafio de Projeto de Criação de Repositório Git/GitHub da DIO 
tags: desafio-dio-primeiro-repositorio
author: Therlyton Fonteles
---

# Git/GitHub básico: Resumo Dos Tópicos Abordados


### A estrutura do git é dividida em três tipos de componentes, que sejam:

- As blobs
- As trees
- E os commits

---
### Blobs
No git, cada arquivo é armazenado como um objeto tipo _blob_ por meio de uma sequência de 40 caracteres chamada hash.
A _blob_ possui como metadados o tipo, o tamanho do arquivo, uma barra e um zero e o conteúdo do arquivo: seja em texto, seja binário etc. Contudo, não possuirá o nome do arquivo.

---

### Trees
A _tree_ é como um conjunto de entradas de diretórios; um snapshot do diretório de trabalho. Ela mostra o modo, o tipo, o hash e o nome do arquivo.
Os modos são 3: 
- 100644 (arquivo normal)
- 100755 (arquivo executável)
- 120000 (link simbólico)
>Tipos: blobs, trees

---


### Commits
Os commits englobam toda a estrutura fazendo referência a árvore hierarquicamente mais elevada, ao commit imediatamente anterior,
além de metadados como autor, mensagem e timestamp. Ele serve para agregar as referências a todos os componentes e inclui uma mensagem explicativa sobre qualquer mudança no cenário do último commit.

![esquema do git](https://krishnabiradar.com/blogs/deconstructing-a-git-commit/img/commit-graph.png)

[fonte](https://krishnabiradar.com/blogs/deconstructing-a-git-commit/)

---


## Ciclo de Vida do Status dos Arquivos
#### Estados:
- Untracked
- Tracked
- Staged

Os arquivos rastreados do git (tracked) se subdividem em **inalterado** (unmodified), **alterado** (modified) e **preparado** (staged). Logo que um arquivo é criado pode ser classificado como _untracked_ . Após a execução do comando `git add`, ele é transferido para o Diretório Stage (Staging Directory) na forma de um arquivo de Índice e passa, então a ser *tracked*.

*O Git Index é um diretório entre o diretório de trabalho e o repositório*

![git-Index](https://static.javatpoint.com/tutorial/git/images/git-index.png)

[fonte](https://www.javatpoint.com/git-index)


Tendo em conta que à área de _tracked_ correspondem os estados _unmodified_, _modified_ e _staged_, depois do _commit_ o estado do arquivo passa para _tracked_ e _unmodified_ :




![stackoverflow-areas](https://i.stack.imgur.com/QaeAZ.png)
[fonte](https://pt.stackoverflow.com/questions/326086/quais-as-diferenças-entre-os-estados-dos-arquivos-do-git-untracked-unmodified)

![Lifecicle](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQe8rADT1vmU62AUGKmyKoVxet78a99YMsxlw&usqp=CAU)

[fonte](https://expertiza.csc.ncsu.edu/images/f/fc/)

---
## Passos Para Conectar o Git ao GitHub

1. Verificar ssh keys
  1.1 Criar ssh keys
  1.2 Adicionarr ssh public key no GitHub

2. Criar repositório no GitHub
3. Abrir code menu
4. Copiar ssh public key
5. Abrir diretório de trabalho local
6. Criar novo diretório
7. Abrir novo diretório
8. Iniciar git bash
9. Digitar git clone 
10. Colar ssh public key
11. Executar git clone
12. Inserir frase de passe
13. Confirmar frase de passe

![wikia](https://upload.wikimedia.org/wikipedia/commons/4/44/Git_data_flow_simplified.svg)

[fonte](https://commons.m.wikimedia.org/wiki/File:Git_data_flow_simplified.svg)

---

---

🧑‍💻
:octocat:
💻 
🗃️
🚥 
💡
🚀

---
