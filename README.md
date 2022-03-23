### Aula #5

##### BRANCH
- É uma versão princinpal do sistema.

##### COMMIT
- É enviar para o GITHUB as modificações que foi feito no código do sistema.

##### COMANDOS UTILIZADOS NA AULA

```js
git init
git status // verifica as alterações que houve no projeto. 
git add -A // adicionar todos os arquivos alterados ao mesmo tempo.
git add nomedoarquivo.js // adiciona um arquivo uninco.
git commit -m "Foi criado a função de login" // descrição do que foi feito no projeto.
git log // mostra as alterações que foram feitas.
```

### Aula #6
##### REVERTENDO MODIFICAÇÕES

```js

    git log  // verificar os commit já feito
    git branch // verificar todos os banch

    git reset

```

* git reset -  esse comando tem 3 tipos de decisões que podemos tomar
```js
    git reset --soft // volta o commit e deixa as modificações preparadas - não comitadas
    git reset ---mixed // Faz a mesma coisa porem não estão preparadas tera que dar o add
    git reset --hard // Ignora tudo e volta ao início

    // OBS:  É recomendado usar o soft principamente quando trabalhar em equipes.
```
![image-1-aula6](https://raw.githubusercontent.com/heudersena/curso-git-github-professor-bonieky/main/images/06/1i6.png)

### Aula #7
##### TRABALHANDO COM DIFERENTES BRANCHES

```js
    git branch test // criando uma branch chamado test
    git checkout test // Mudando de branch test

```
- Enviar push para a branch criada [ git push --set-upstream origin test ]  

### Aula 08
##### DIFERENÇA ENTRE ARQUIVOS
- verificar se os arquivos foram commitados [etc].

```js
    git diff // verificando as diferença
```