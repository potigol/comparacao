# Comparacao

Comparação da linguagem **Potigol** com outras linguagens.

### Versão

| Linguagem | Versão | Apresentar versão |
| -------   | -----: | --- |
| Potigol   | 0.9.15 | `$ potigol` |
| Python    |    3.6 | `$ python --version` |
| Java      |    9.0 | `$ java -version` |
| Scala     | 2.12.4 | `$ scala -version` |

### Execução

| Linguagem | Comando |
| --- | --- |
| Potigol | `$ potigol programa.poti` |
| Python  | `$ python programa.py` |
| Java    | `$ javac Programa.java`<br>`$ java Programa` |
| Scala   | `$ scalac programa.scala`<br>`$ scala programa` <br>*ou*<br> `$ scala programa.scala` |

### Gramática

| Linguagem | Blocos | Separador de comandos | Comentário de linha |
| --- | --- | --- | --- |
| Potigol | `faça fim` | *espaço* | `# comentário` |
| Python  | `:` *e identação* | *nova linha ou* `;` | `# comentário` |
| Java    | `{ }` | `;` | `// comentário` |
| Scala   | `{ }` | *nova linha ou* `;` | `// comentário` |

### Variáveis

| Linguagem | Variável | Constante |  |
| --- | --- | --- | --- |
| Potigol | `var x := 10` <br> `var y, z := 20, 30` | `x = 10` <br> `y, z = 20, 30` | `` |
| Python  | `x = 10` <br> `y, z = 20, 30` | `PI = 3.14` | `` |
| Java    | `int x = 10;` | `final int x = 10;` | `` |
| Scala   | `var x = 10` <br> `var y, z = 20, 30` <br> *declaração explícita do tipo:* <br>`var x: Int = 10`| `val x = 10` <br> `val y, z = 20, 30` | `` |

#### Atribuição

| Linguagem | Atribuição | Atribuição Paralela | Permutação |
| --- | --- | --- | --- |
| Potigol | `x := 10` | `x, y, z := 10, 20, 30` | `x, y := y, x` |
| Python  | `x = 10` | `x, y, z = 10, 20, 30` | `x, y = y, x` |
| Java    | `x = 10;` | *não tem* | *não tem* |
| Scala   | `x = 10` | *não tem* | *não tem* |

### Aritimática e Lógica

#### Valores lógicos

| Linguagem | Valores            | Operadores lógicos | Operadores relacionais |
|-----------|--------------------|--------------------|------------------------|
| Potigol   | `verdadeiro falso` | `e ou não`         | `== <> > < >= <=`      |
| Python    | ``                 | ``                 | ``                     |
| Java      | ``                 | ``                 | ``                     |
| Scala     | ``                 | ``                 | ``                     |

### Operações Aritiméticas

| Linguagem | Operadores aritiméticos | Potenciação | Raiz |
|-----------|-------------------------|-------------|---------------|
| Potigol   | `+ - * / div mod`       | `^`         | `raiz(2.0)` <br> `raiz(2.0, 2)` |
| Python    | ``                      | ``          | ``            |
| Java      | ``                      | ``          | ``            |
| Scala     | ``                      | ``          | ``            |


#### Operações Matemáticas

| Linguagem | Trigonometria | Aleatório | Absoluto |
|-----------|---------|---------|---------|
| Potigol   | `sen cos tg arcsen arccos arctg` | `aleatório(10)` <br> `aleatório(1,10)` <br> `aleatório(["a","e","i","o","u"])` | `abs(-2)`      |
| Python    | ``      | ``      | ``      |
| Java      | ``      | ``      | ``      |
| Scala     | ``      | ``      | ``      |

### Texto

| Linguagem | Literal | Quebra de linha | Interpolação |
|-----------|---------|---------|---------|
| Potigol   | `"texto"` | `"Isto é` <br> `um texto"`      | `x, y = 10, 20` <br> `"A soma {x} + {y} = {x + y}."`      |
| Python    | ``      | ``      | ``      |
| Java      | ``      | ``      | ``      |
| Scala     | ``      | ``      | ``      |

| Linguagem | Concatenação | Replicar | Maiúsculo / Minúsculo |
|-----------|---------|---------|---------|
| Potigol   | `"Olá " + "mundo"` | `"-" * 20` | `"Ola".maiúsculo` <br> `"Ola".minúsculo`      |
| Python    | ``      | ``      | ``      |
| Java      | ``      | ``      | ``      |
| Scala     | ``      | ``      | ``      |

| Linguagem | Parte | Replicar | Maiúsculo / Minúsculo |
|-----------|---------|---------|---------|
| Potigol   | `ola = "Olá mundo".pegue(3)` <br> `mundo = "Olá Mundo".descarte(4)` | `"-" * 20` | `"Ola".maiúsculo` <br> `"Ola".minúsculo`      |
| Python    | ``      | ``      | ``      |
| Java      | ``      | ``      | ``      |
| Scala     | ``      | ``      | ``      |

