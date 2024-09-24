# Autograding Exercises


### 06-switch-statement (sem *break*s)

Escreva  um programa em C que lhe permita saber qual a taxa de imposto a aplicar a um determinado estado civil, usando apenas a instrução *switch* ***<u>sem usar qualquer break</u>*** para determinar o valor da taxa.

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

