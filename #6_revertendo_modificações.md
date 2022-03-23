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