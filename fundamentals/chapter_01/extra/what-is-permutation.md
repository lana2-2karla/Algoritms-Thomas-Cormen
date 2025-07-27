
# 📌 O que é Permutação?

## 🧠 Definição teórica:
Uma permutação é uma reordenação dos elementos de um conjunto.

Ou seja, dados n elementos distintos, uma permutação é qualquer maneira de organizar esses elementos em uma nova ordem.

---

### Exemplo teórico:

**Conjunto:** `[1, 2, 3]`  
**Permutações possíveis:**

```
[1, 2, 3]  
[1, 3, 2]  
[2, 1, 3]  
[2, 3, 1]  
[3, 1, 2]  
[3, 2, 1]
```

No total, são `3! = 6` permutações possíveis.

---

## ✅ Exemplo de permutação válida em programação:

Suponha que temos uma lista:

```
numeros = [5, 3, 9]
```

Todas as seguintes são permutações válidas dessa lista:

```
[3, 5, 9]  
[9, 5, 3]  
[5, 9, 3]  
[3, 9, 5]  
[9, 3, 5]  
[5, 3, 9]  # A original também é uma permutação
```

Cada uma dessas é uma reordenação dos mesmos valores.

---

## ❌ Exemplo de algo que não é uma permutação:

```
[3, 5, 5]     # tem elementos repetidos diferentes do original  
[1, 2, 3]     # tem elementos que não existiam no original  
[3, 9]        # está faltando elementos  
[3, 9, 5, 7]  # está sobrando elementos
```

> **Observação:**  
> Uma permutação precisa conter **exatamente os mesmos elementos da lista original**, nem mais, nem menos, e **sem alterar o conteúdo** (só a ordem).
