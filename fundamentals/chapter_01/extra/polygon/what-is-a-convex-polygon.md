# 📌 O que é um polígono convexo?
Um polígono convexo é aquele em que nenhuma linha entre dois pontos dentro da figura sai para fora da figura.

### ✅ Características:
- Todos os ângulos internos são menores que 180°
- Se você traçar uma reta entre quaisquer dois pontos dentro dele, a reta fica totalmente dentro do polígono
- Não tem "reentrâncias" (curvas para dentro)

---

## 📌 O que é um polígono não convexo (ou côncavo)?
Um polígono côncavo tem pelo menos um ângulo interno maior que 180° e reentrâncias, ou seja, "dobras para dentro".

### ❌ Características:
- Você pode traçar uma linha entre dois pontos dentro do polígono e essa linha sair fora dele
- Tem "buracos" ou "entradas"
- Parece um "polígono mordido"

---

# 🎨 Exemplos visuais e descrições

## ✅ Polígonos Convexos

### 🔺 Triângulo (3 lados)
```text
    ●
   / \
  /   \
 ●-----●
```
- Todo triângulo é convexo

### ◼️ Quadrado (4 lados, ângulos retos)
```text
 ●--------●
 |        |
 |        |
 ●--------●
```
- Ângulos de 90° (todos < 180°)

### 🔷 Hexágono regular (6 lados iguais)
```text
   ●-----●
  /       \
 ●         ●
  \       /
   ●-----●
```
- Figura típica de colmeia de abelha
- Nenhuma reentrância

---

## ❌ Polígonos NÃO convexos (Côncavos)

### 🔻 "Seta" ou "flecha"
```text
    ●
   / \
  /   \
 ●     ●
  \   /
   \ /
    ●---●
```
- A parte de baixo da flecha entra para dentro do polígono
- Reentrância => não é convexo

### 📐 "L em 2D"
```text
 ●-----●
 |      
 |      
 ●-----●-----●
              |
              |
              ●
```
- O canto inferior direito forma um ângulo maior que 180°
- Parece uma letra "L", com uma "mordida" - isso quebra a convexidade

### 🧩 Polígono com "dente":
```text
   ●-----●
  /       \
 ●         ●
  \   ●   /
   \ / \ /
    ●   ●
```
- Aquele ponto no meio de baixo entra na figura, formando uma "entrada" ou "buraco"
- Portanto, não é convexo

---

## 🧪 Teste visual simples: "linha interna"

 - Polígono Convexo: A reta nunca sai para fora da borda. Todos os ângulos < 180°.
 - Polígono Côncavo: A reta pode sair da figura. Algum ângulo interno > 180°

---

# 🧠 Dica prática para lembrar:
- **Convexo:** Se nenhum dos lados da figura "entra para dentro"
- **Côncavo:** Se parece que alguém mordeu a figura ou ela tem um buraco para dentro