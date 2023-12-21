## And
**Definição:** Verifica se ambos os argumentos são TRUE e retorna TRUE se isso se confirmar. Caso contrário, retorna false.  <br><br>

**Sintaxe:**  
```dax
AND(<logical1>,<logical2>)
```
**Exemplo:**  
```dax
= IF(AND(10 > 9, -10 < -1), "All true", "One or more false")
```
