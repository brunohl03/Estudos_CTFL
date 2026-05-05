# 🧪 SIMULADO CTFL 4.0 – K3 (NÍVEL PROVA)

## 📌 Instruções

* Apenas **1 alternativa correta** por questão
* Use papel para rascunho, se necessário
* Total de **15 questões** (estilo prova real)
* **Gabarito + explicação** ao final

---

## 🧠 QUESTÕES

### 1. (EP)

Um campo aceita valores de **10 a 50 (inclusive)**.
Quantas classes de equivalência existem?

* A) 2
* B) 3
* C) 4
* D) 5

---

### 2. (EP)

Qual conjunto representa corretamente valores de teste usando EP?

* A) 10, 20, 30, 40, 50
* B) 9, 10, 50, 51
* C) 0, 25, 100
* D) 10, 11, 49, 50

---

### 3. (BVA)

Campo aceita valores de **1 a 100**.
Qual conjunto cobre BVA?

* A) 1, 100
* B) 0, 1, 2, 99, 100, 101
* C) 1, 50, 100
* D) 2, 99

---

### 4. (BVA)

Para uma faixa de **5 a 15**, qual valor **NÃO** é de limite?

* A) 4
* B) 5
* C) 10
* D) 16

---

### 5. (Tabela de decisão)

Sistema:

* Se cliente é VIP → desconto
* Se NÃO VIP → sem desconto

Quantos casos mínimos?

* A) 1
* B) 2
* C) 3
* D) 4

---

### 6. (Tabela de decisão)

Sistema:

* VIP + saldo alto → desconto
* VIP + saldo baixo → sem desconto
* Não VIP → sem desconto

Quantos casos mínimos?

* A) 2
* B) 3
* C) 4
* D) 6

---

### 7. (Transição de estado)

Sistema bloqueia usuário após **3 tentativas inválidas**.

Qual teste é válido?

* A) 1 erro → login → bloqueio
* B) 3 erros → bloqueio
* C) 2 erros → bloqueio
* D) 1 erro → bloqueio

---

### 8. (Transição de estado)

Qual cenário testa um **fluxo inválido**?

* A) Login correto direto
* B) 3 erros → bloqueio
* C) Acesso após bloqueio
* D) 1 erro → sucesso

---

### 9. (Cobertura de decisão)

```python
if idade >= 18:
    acesso = True
else:
    acesso = False
```

Quantos testes mínimos para cobertura de decisão?

* A) 1
* B) 2
* C) 3
* D) 4

---

### 10. (Cobertura de decisão)

Qual conjunto cobre todos os caminhos?

* A) idade = 18
* B) idade = 20
* C) idade = 17 e 18
* D) idade = 18 e 19

---

### 11. (EP + BVA)

Campo aceita valores de **0 a 10**.

Qual conjunto é **MELHOR**?

* A) 0, 10
* B) -1, 0, 1, 9, 10, 11
* C) 5
* D) 0, 5, 10

---

### 12. (Tabela de decisão)

Sistema:

* Logado + admin → acesso total
* Logado + user → acesso parcial
* Não logado → sem acesso

Quantos casos mínimos?

* A) 2
* B) 3
* C) 4
* D) 6

---

### 13. (Cobertura)

```python
if x > 0:
    print("A")
print("B")
```

Quantos testes para cobertura de instrução?

* A) 1
* B) 2
* C) 3
* D) 4

---

### 14. (Estado)

Sistema possui estados:

* Ativo
* Inativo

Transições:

* Ativar
* Desativar

Qual teste cobre uma **transição inválida**?

* A) Ativo → Desativar → Inativo
* B) Inativo → Ativar → Ativo
* C) Ativo → Ativar
* D) Inativo → Ativar

---

### 15. (Experiência)

Um testador decide testar cenários inesperados baseado em experiência prévia.

Isso é:

* A) EP
* B) BVA
* C) Error guessing
* D) Caixa-branca

---

## ✅ GABARITO + EXPLICAÇÃO

1. **B** → válido + 2 inválidos
2. **C** → representa classes (baixo, válido, alto)
3. **B** → limites completos
4. **C** → não é limite
5. **B** → VIP / não VIP
6. **B** → 3 combinações
7. **B** → regra correta
8. **C** → acesso após bloqueio é inválido
9. **B** → true e false
10. **C** → cobre ambos caminhos
11. **B** → melhor cobertura (BVA completo)
12. **B** → 3 regras
13. **A** → 1 teste executa tudo
14. **C** → transição inválida
15. **C** → baseado em experiência

---
