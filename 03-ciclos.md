# Exercícios sobre ciclos e funções

### 01-square
- Escreva um programa que leia um inteiro *n* e mostre um quadrado com *n* asteriscos de lado

  **Para input: [lado=2]  o output esperado é:**
  ```
  **
  **
  ```
    
  **Para input: [lado=5]  o output esperado é:**
  ```
  *****
  *****
  *****
  *****
  *****
  ```
  
### 02-formas geométricas simples
Implemente as seguintes funções em C

2.1. Mostra uma linha com **[n]** chars **[ch]** no ecrã e muda de linha.

   `Exemplo para n=7 e ch='*'`

   `*******`

   ```
   void line(int n, int ch)
   {
     ...
   }
   ```

2.2. Mostra um retângulo com **[rows]** linhas por **[cols]** colunas.

   `Exemplo para rows=3, cols=5 e ch='='`

   `=====`

   `=====`

   `=====`

```
void rectangle(int rows, int cols, int ch)
{
  ...
}
```

2.3. Mostra um quadrado com dimensão **[size]**.
Deve evitar repetir código levando em consideração que um quadrado é um caso particular de um retângulo.

```
void square(int size, int ch)
{
  ...
}
```

2.4. Mostra no ecrã um triângulo com dois lados com dimensão **[size]**. Um dos lados está encostado à esquerda. 

   Exemplo para size=3 e ch ='@' 
   `@`

   `@@`

   `@@@`

```
void triangle(int size, int ch)
{
  ...    
}
```

2.5. Altere a função **line** de tal forma que passe a colocar um **\n** no final da linha, apenas se o programador o indicar no parâmetro (*boolean*) **add_newLine** da função.

   `Output do seguinte programa:`

   `line(3, '@', 0); line(2, '#', 0); line(3, '@', 1); line(8, '=', 1); `

   `@@@##@@@`

   `========`

2.6. Reescreva o código das funções **rectangle**, **square** e **triangle** que escreveu no exercício anterior e ajuste-o de modo a usar a nova versão da função **line**.

2.7. Escreva a função **triangle_right** que mostra um triângulo equilátero com dimensão **size** alinhado à direita.

   `Exemplo para size=5 e ch ='$' `

   ``` 
       $
      $$
     $$$
    $$$$
   $$$$$
   ```

2.8. Escreva a função **triangle_top** que mostra um triângulo com 2 lados de dimensão **size**.

   `Exemplo para size=5 e ch ='$' `

   ``` 
       $
      $$$
     $$$$$
    $$$$$$$
   $$$$$$$$$
   ```

2.9. Escreva a função **triangle_bottom** que mostra um triângulo invertido com 2 lados de dimensão **size**.

   `Exemplo para size=5 e ch ='$' `

    ``` 
    $$$$$$$$$
     $$$$$$$
      $$$$$
       $$$
        $
    ```

2.10. Escreva a função **lozenge** que mostra um losango de dimensão **size**.

`Exemplo para size=3 e ch ='W' `

``` 
  W
 WWW
WWWWW
WWWWW
 WWW
  W
```

2.11. Escreva a função **parallelogram** que mostra um paralelograma de dimensões **rows** x **cols**.

`Exemplo para rows=5, cols=10 e ch ='&' `

``` 
&&&&&&&&&&
 &&&&&&&&&&
  &&&&&&&&&&
   &&&&&&&&&&
    &&&&&&&&&&
```
