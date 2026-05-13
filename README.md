# anotacoes-JS

# JavaScript: Operadores e Condicionais

Resumo técnico dos fundamentos de manipulação de dados e controle de fluxo em JavaScript.

---

## 1. Operadores Aritméticos
*   `+` (Soma)
*   `-` (Subtração)
*   `*` (Multiplicação)
*   `/` (Divisão)
*   `%` (Resto da divisão)
*   `**` (Potência) - *Correção: No JS utiliza-se `**` para potência.*

---

## 2. Conversão de Tipos (Casting)

### Para Número
*   `Number()`: Conversão estrita. Retorna `NaN` se houver caracteres não numéricos.
*   `parseInt()`: Extrai o número inteiro (ignora decimais e textos após o número).
*   `parseFloat()`: Extrai o número mantendo as casas decimais.

### Para String e Boolean
*   `String(valor)` ou `valor.toString()`: Converte para texto.
*   `Boolean(valor)`: Converte para lógico. 
    *   **Falsy:** `0`, `""`, `null`, `undefined`, `NaN`.
    *   **Truthy:** Todo o resto.

---

## 3. Comparação e Lógica

### Operadores Relacionais
*   `===` e `!==`: **Igualdade e Diferença Estrita** (Compara valor e tipo). *Recomendado.*
*   `==` e `!=`: Igualdade solta (faz conversão implícita, pode gerar bugs).
*   `>`, `<`, `>=`, `<=`: Comparações de magnitude e ordem léxica (Unicode).

### Operadores Lógicos
*   `&&` (E): Ambas devem ser verdadeiras.
*   `||` (OU): Pelo menos uma deve ser verdadeira.
*   `!` (NÃO): Inverte o valor booleano.

---

## 4. Estruturas Condicionais

### If / Else
```javascript
if (condicao) {
  // código
} else if (outraCondicao) {
  // código
} else {
  // fallback
}

