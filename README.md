# csharp-m01-t02-a02

### Operadores lógicos

> Em C#, os operadores lógicos são utilizados para avaliar expressões booleanas e retornar valores booleanos (verdadeiro ou falso). Abaixo está uma lista dos operadores lógicos em C#:

- Operador E (&&): Retorna verdadeiro somente se todas as expressões avaliadas forem verdadeiras.

- Operador OU (||): Retorna verdadeiro se pelo menos uma das expressões avaliadas for verdadeira.

- Operador de negação (!): Retorna o valor oposto da expressão avaliada.

> Segue um exemplo de como utilizar os operadores lógicos em C#:

```C#
bool a = true;
bool b = false;

// Operador E:
bool resultadoE = a && b; // resultadoE = false

// Operador OU:
bool resultadoOU = a || b; // resultadoOU = true

// Operador de negação:
bool resultadoNao = !a; // resultadoNao = false
```

> Além disso, é possível utilizar parênteses para definir a ordem de avaliação das expressões. Por exemplo:

```C#
bool a = true;
bool b = false;
bool c = true;

bool resultado = (a && b) || c; // resultado = true
```

> Nesse caso, a expressão entre parênteses é avaliada primeiro (a && b), resultando em falso. Em seguida, a expressão (falso || c) é avaliada, resultando em verdadeiro.
