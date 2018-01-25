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

| Linguagem | Partes | Tamanho | Elementos |
|-----------|---------|---------|---------|
| Potigol   | `ola = "Olá mundo".pegue(3)` <br> `mundo = "Olá Mundo".descarte(4)` | `"texto".tamanho` | `a = "Olá mundo"` <br> `a[1] # 'O'` |
| Python    | ``      | ``      | ``      |
| Java      | ``      | ``      | ``      |
| Scala     | ``      | ``      | ``      |

### Listas

| Linguagem | Literal | Preenchida |Tamanho | Vazia
|-----------|---------|---------|---------|---------|
| Potigol   | `a = [1, 2, 3, 4]` |`a = Lista(10, 0)`| `a.tamanho` | `a == []`   |
| Python    | ``      |  `` | `` | `` |
| Java      | ``      |  `` | ``      | `` |
| Scala     | ``      |  `` | ``      | `` |

| Linguagem | Ordenar | Inverter | Unir |
|-----------|---------|---------|---------|
| Potigol   | `[2, 3, 1, 4].ordene` |`[2, 3, 1, 4].inverta` | `[2, 3] +[1, 4]` |
| Python    | ``      | ``      | ``      |
| Java      | ``      | ``      | ``      |
| Scala     | ``      | ``      | ``      |

| Linguagem | Mapeamento | Filtro | Redução |
|-----------|---------|---------|---------|
| Potigol   | `a = [1, 2, 3, 4]`<br>`a.mapeie(n => n * 2)`      |`a.selecione(n => n mod 2 ==0)` | `a.reduza(0)((n,m) => n + m)` |
| Python    | ``      | ``      | ``      |
| Java      | ``      | ``      | ``      |
| Scala     | ``      | ``      | ``      |

### Função

| Linguagem | Definição linha | Definição bloco | Aplicação |
|-----------|---------|---------|---------|
| Potigol   | `soma(a, b: Inteiro) = a + b` <br><br> `pos(s: Texto, n: Inteiro) = s[n]`| `soma(a,b: Inteiro)`<br>`  c = a + b` <br> `  retorne c`<br>`fim`<br><br>`fat(n: Inteiro): Inteiro`<br>`  a = se n>1 então fat(n-1) senão 1 fim` <br>`retorne c`<br> `fim`      | `soma(2, 3)`      |
| Python    | ``      | ``      | ``      |
| Java      | ``      | ``      | ``      |
| Scala     | ``      | ``      | ``      |

#### Funções anônimas

| Linguagem | Literal | Invocação | Função como valor |
|-----------|---------|---------|---------|
| Potigol   | `(a, b: Inteiro) => a + b` | `((a, b: Inteiro) => a + b)(2,3)`      | `soma = (a, b: Inteiro) => a + b`      |
| Python    | ``      | ``      | ``      |
| Java      | ``      | ``      | ``      |
| Scala     | ``      | ``      | ``      |

### Instruções de Controle

| Linguagem | Se | Escolha |
|-----------|---------|---------|
| Potigol   | `se n==0 então`<br>` escreva "nenhum"`<br>`senãose n==1 então`<br> `escreva "um"`<br>`senão`<br>` escreva "vários"`<br>`fim`      | `escolha n`<br>` caso 0 => escreva "nenhum"`<br>` caso 1 => escreva "um"`<br>`caso _ => escreva "vários"`<br>`fim`      |
| Python    | ``      | ``      |
| Java      | ``      | ``      |
| Scala     | ``      | ``      |

#### Repetição

| Linguagem | Para | Enquanto |
|-----------|---------|---------|
| Potigol   | `para i de 1 até 10 faça`<br>` escreva i`<br>`fim` <br><br> `para i de 1 até 10 passo 2 faça`<br>` escreva i`<br>`fim`| `var i := 1`<br>`enquanto i <= 10 faça`<br>`  escreva "i"`<br>`  i  := i + 1` <br> `fim`      |
| Python    | ``      | ``      |
| Java      | ``      | ``      |
| Scala     | ``      | ``      |

### Registro

| Linguagem | Definição | Uso |
|-----------|---------|---------|
| Potigol   | `tipo Pessoa` <br> `  nome, email: Texto` <br> `var telefone: Texto`<br>`fim`      | `joao = Pessoa("Joao", "joao@email.com", "98888-8888")` <br> `escreva joao.nome`<br>`joao.telefone:="99999-9999"`      |
| Python    | ``      | ``      |
| Java      | ``      | ``      |
| Scala     | ``      | ``      |


### Classe

| Linguagem | Definição | Uso |
|-----------|---------|---------|
| Potigol   | `tipo Pessoa` <br> ` nome, email: Texto` <br> `var telefone: Texto` <br>`  ligar()` <br> `    escreva "ligando para {telenone}"` <br> `  fim` <br> `fim` | `joao = Pessoa("Joao", "joao@email.com", "98888-8888")` <br> `escreva joao.nome`<br>`joao.telefone:="99999-9999"` <br> `joao.ligar`      |
| Python    | ``      | ``      |
| Java      | ``      | ``      |
| Scala     | ``      | ``      |


