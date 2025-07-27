
# 📌 O que é uma instância do problema?

## 🧠 Definição teórica:
Uma instância de um problema é um caso específico, com dados concretos, que satisfaz os requisitos do problema.

Ou seja, é quando você pega um problema genérico (por exemplo, ordenar uma lista) e dá uma entrada específica para que ele seja resolvido.

---

## ✅ Exemplo prático de instância do problema:

**Problema:** Ordenar uma lista de números em ordem crescente.  
**Instância:** ordenar `[31, 41, 59, 26, 41, 58]`.

Esse vetor é uma instância concreta do problema de ordenação.

Outro exemplo:

**Problema:** encontrar a soma de dois números.  
**Instância:** somar 7 e 13.

```python
def soma(a, b):
    return a + b

print(soma(7, 13))  # 20
```

Aqui, `(7, 13)` é uma instância do problema de soma.

---

## ❌ Exemplo de algo que não é uma instância válida:

Vamos supor que o problema seja **"ordenar uma lista de inteiros positivos"**.

Então o seguinte **não é uma instância válida**:

```python
entrada = ["banana", "abacaxi", "laranja"]  # strings em vez de inteiros
entrada = [4, -3, 2]                        # -3 não é um inteiro positivo
entrada = None                              # entrada inválida
```

Essas entradas violam as restrições do problema, então não são instâncias válidas.