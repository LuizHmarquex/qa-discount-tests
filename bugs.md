#  Bugs encontrados

## BUG001 - Desconto acumulativo incorreto

**Descrição:**  
O sistema aplica múltiplos descontos de forma acumulativa.

**Passos para reproduzir:**
1. Inserir valor 100
2. Aplicar desconto de 10% e 20%

**Resultado atual:** valor final incorreto  
**Resultado esperado:** aplicar apenas o maior desconto  

---

## BUG002 - Valor negativo

**Descrição:**  
O sistema retorna valores negativos após desconto.

**Resultado esperado:** valor mínimo deve ser 0  
