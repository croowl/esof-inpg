<h1 align="center">
  Faculdade INPG
</h1>

<h3 align="center">
    Engenharia de Software
</h3>

Atividade de avaliação do 5º Semestre do curso Gestão de TI da faculdade INPG, referente a disciplina de Engenharia de Software.


## :computer: Passo a passo da branch

Para chegar no resultado desta branch (tags, commits, merges) foram feitos os passos abaixo:

Deletar o arquivo arquivo2.js e criar o arquivo arquivo4.js no commit 3

```rm arquivo2.js```

```nano arquivo4.js```

```git commit -m "Commit três"```

Adicionar uma linha no arquivo arquivo1.js no commit 4

```nano arquivo1.js```

```git commit -m "Commit quatro"```

Fazer um push na branch dev

```git push origin dev --tags```

Criar a branch temp

```git branch temp```

Saltar para a branch temp...

```git checkout temp```

Deletar o arquivo arquivo4.js e alterar a 1ª linha do arquivo arquivo1.js após o commit 6 na branch temp

```rm arquivo4.js```

```nano arquivo1.js```

Fazer o merge entres as branches dev e main

```git checkout dev```

```git merge main```


O objetivo deste repositório é 100% acadêmico, para fins de entrega de ativadade \o/ sinta-se livre para editar ou estudar o funcionamento das branches e tags.
