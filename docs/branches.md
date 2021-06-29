# Política de Branches

Primeiro de tudo, sempre que for criar uma nova branch certifique-se que você está na devel e crie a branch a partir dela.

As _branches_ devem seguir o seguinte padrão:

* O nome da branch deve ser abstraído do nome da história de usuário a qual se refere.

<b>Exemplo:</b>

```
CriarLogin
```

* O nome da _branch_ deve possuir um 'tag' que é o número da issue a qual se refere.

<b>Exemplo:</b>

```
3CriarLogin
```

* A _branch_ deverá possuir o padrão CamelCase ```x-NomeDaBranch ```, em que o 'x' é o número da issue.

<b>Exemplo:</b>

```
3-CriarLogin
```

* Caso a _branch_ não esteja associada a alguma issue, não é necessario a adição da 'tag'.

<b>Exemplo:</b>

```
RefatorarLogin
```
