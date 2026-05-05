# 📘 CAPÍTULO 4 – TÉCNICAS DE TESTE (K3)

## 🎯 4.2 – Técnicas Caixa-Preta (K3)

### ✔️ Você precisa **SABER FAZER**

---

### 🔹 1. Particionamento de Equivalência (EP)

👉 Dado um cenário, você deve:

- Identificar classes válidas e inválidas  
- Criar testes representativos  

📌 **Exemplo típico:**

> Campo aceita valores de 1 a 100

✔️ **Classes:**

- Válido: 1–100  
- Inválido: < 1  
- Inválido: > 100  

👉 **Importante:** você **NÃO testa tudo** — testa representantes.

---

### 🔹 2. Análise de Valor Limite (BVA)

👉 Você precisa aplicar nos limites:

✔️ **Limites:**

- mínimo  
- máximo  
- logo abaixo  
- logo acima  

📌 **Exemplo:**

> Faixa: 1–100

✔️ **Testes:**

- 0  
- 1  
- 2  
- 99  
- 100  
- 101  

👉 **Muito cobrado em prova!**

---

### 🔹 3. Tabela de Decisão

👉 Você recebe regras e deve:

- Identificar combinações  
- Criar casos de teste  

📌 **Exemplo:**

> Se cliente VIP e saldo > 1000 → desconto

👉 Monte uma tabela com combinações:

- VIP / não VIP  
- saldo alto / baixo  

---

### 🔹 4. Transição de Estado

👉 Você deve:

- Identificar estados  
- Criar testes válidos e inválidos  

📌 **Exemplo:**

> Login bloqueia após 3 tentativas

✔️ **Testar:**

- sequência válida  
- sequência inválida  

---

## 🎯 4.3 – Técnicas Caixa-Branca (K3)

### 🔹 5. Cobertura de Código

👉 Você precisa entender e aplicar:

✔️ **Tipos:**

- Cobertura de instrução  
- Cobertura de decisão  

📌 **Exemplo:**

```python
if x > 10:
    print("A")
else:
    print("B")