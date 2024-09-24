# Exercícios if e switch

### 01-hello-world
- Escreva o programa que gere o seguinte output:
  ```
  Hello, World!
  ```

### 02-special-chars
- Escreva o programa que gere o seguinte output:
```
A Linguagem 'C' = "cool"?
Claro, porque:
\n representa a mudanca de linha
\\ representa o simbolo \
\t representa a tabulacao

That's All Folks!!!
```

### 03-arithmetic-operators

- Escreva o programa que gere o seguinte output depois de pedidos dois inteiros.(Resultado para exemplo com input 11 e 3).

```
11 + 3 = 14
11 - 3 = 8
11 * 3 = 33
11 / 3 = 3
11 % 3 = 2

11 / 3 = 3.67
```

### 04-if-statement

Escreva um programa que permita saber qual a taxa de imposto a aplicar a um determinado estado civil, usando apenas instruções *if* para determinar o valor da taxa.

Supõe-se que o estado civil é sempre introduzido corretamente e pode ser introduzido em minúsculas ou maiúsculas, mas o "*case*" do estado civil é indiferente para o cálculo da taxa.

 As regras a aplicar são as seguintes: 

| **Estado Civil**        | **Taxa**                                 |
| ----------------------- | ---------------------------------------- |
| Solteiro (s ou S)       | 1%                                       |
| Divorciado (d ou D)     | Taxa associada aos solteiros +4%         |
| Viúvo (v ou V)          | Taxa associada aos divorciados + 3%      |
| Casado (c ou C)         | Taxa associada aos viúvos + 2.5%         |
| União de facto (u ou U) | Taxa igual à taxa associada aos casados. |

O output gerado deverá ser do tipo: 
​	Estado: **«char»** | Taxa : **«float com 2 casas decimais»**

```
Estado: s | Taxa: 1.00
ou
Estado: V | Taxa: 8.00
ou
Estado: U | Taxa: 10.50
```

### 05-switch-statement

Escreva um programa que permita saber qual a taxa de imposto a aplicar a um determinado estado civil, usando apenas a instrução ***switch (com breaks)*** para determinar o valor da taxa a aplicar.

Supõe-se que o estado civil é sempre introduzido corretamente e pode ser introduzido em minúsculas ou maiúsculas.

 As regras a aplicar são as seguintes: 

| **Estado Civil**        | **Taxa**                                 |
| ----------------------- | ---------------------------------------- |
| Solteiro (s ou S)       | 1%                                       |
| Divorciado (d ou D)     | Taxa associada aos solteiros +4%         |
| Viúvo (v ou V)          | Taxa associada aos divorciados + 3%      |
| Casado (c ou C)         | Taxa associada aos viúvos + 2.5%         |
| União de facto (u ou U) | Taxa igual à taxa associada aos casados. |

O output gerado será sempre do tipo: 
​	Estado: **«char»** | Taxa : **«float com 2 casas decimais»**

```
Estado: s | Taxa: 1.00
ou
Estado: V | Taxa: 8.00
ou
Estado: U | Taxa: 10.50
```

### 06-switch-statement (sem *break*s)

Escreva um programa que permita saber qual a taxa de imposto a aplicar a um determinado estado civil, usando apenas a instrução *switch* ***<u>sem usar qualquer break</u>*** para determinar o valor da taxa.

Supõe-se que o estado civil é sempre introduzido corretamente e pode ser introduzido em minúsculas ou maiúsculas.

 As regras a aplicar são as seguintes: 

| **Estado Civil**        | **Taxa**                                 |
| ----------------------- | ---------------------------------------- |
| Solteiro (s ou S)       | 1%                                       |
| Divorciado (d ou D)     | Taxa associada aos solteiros +4%         |
| Viúvo (v ou V)          | Taxa associada aos divorciados + 3%      |
| Casado (c ou C)         | Taxa associada aos viúvos + 2.5%         |
| União de facto (u ou U) | Taxa igual à taxa associada aos casados. |

O output gerado será sempre do tipo: 
​	Estado: **«char»** | Taxa : **«float com 2 casas decimais»**

```
Estado: s | Taxa: 1.00
ou
Estado: V | Taxa: 8.00
ou
Estado: U | Taxa: 10.50
```

