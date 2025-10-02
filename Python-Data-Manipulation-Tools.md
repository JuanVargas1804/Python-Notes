# Python - Key Takeaways (Operadores y Expresiones)

## 1. Expressions
- Una **expresión** es una combinación de valores, variables, operadores o llamadas a funciones.
- Siempre se evalúa a un valor.
- Ejemplo: `1 + 2`

## 2. Operators
- Son símbolos o palabras clave que permiten realizar operaciones sobre valores.
- Ejemplo: `*` multiplica dos valores: `x * y`

## 3. Operadores aritméticos en Python
- `+` → Suma
- `-` → Resta
- `*` → Multiplicación
- `/` → División clásica (siempre retorna `float`)
- `%` → Módulo (resto de la división)  
  Ejemplo: `5 % 2 = 1`
- `**` → Exponenciación (potencia)  
  Ejemplo: `2 ** 3 = 8`
- `//` → División entera (resultado redondeado hacia abajo)  
  Ejemplo: `3 // 2.0 = 1.0`

## 4. Unary Operator
- Operador con **un solo operando**.  
- Ejemplo: `-1`, `+3`

## 5. Binary Operator
- Operador con **dos operandos**.  
- Ejemplo: `4 + 5`, `12 % 5`

## 6. Jerarquía de prioridades (orden de evaluación)
1. `**` → Exponenciación (más alto)
2. Operadores unarios `+`, `-`  
   (ejemplo: `4 ** -1 = 0.25`)
3. `*`, `/`, `//`, `%`
4. `+`, `-` (binarios, menor prioridad)

## 7. Paréntesis
- Las subexpresiones entre **paréntesis se evalúan primero**.  
- Ejemplo: `15 - 1 * (5 * (1 + 2)) = 0`

## 8. Exponentiation (Exponenciación)
- Usa **asociatividad a la derecha** (right-sided binding).  
- Ejemplo: `2 ** 2 ** 3 = 256`
