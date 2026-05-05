# 🧪 SIMULADO CTFL 4.0 – K3 (NÍVEL PROVA)

---

## 📌 Instruções

- ✔️ 1 alternativa correta  
- ✔️ Use papel se precisar  
- ✔️ 15 questões (estilo prova real)  
- ✔️ Gabarito + explicação no final  

---

## 🧠 QUESTÕES

### 1. (EP)
Um campo aceita valores de 10 a 50 (inclusive).  
Quantas classes de equivalência existem?

A) 2  
B) 3  
C) 4  
D) 5  

---

### 2. (EP)
Qual conjunto representa corretamente valores de teste usando EP?

A) 10, 20, 30, 40, 50  
B) 9, 10, 50, 51  
C) 0, 25, 100  
D) 10, 11, 49, 50  

---

### 3. (BVA)
Campo aceita valores de 1 a 100.  
Qual conjunto cobre BVA?

A) 1, 100  
B) 0, 1, 2, 99, 100, 101  
C) 1, 50, 100  
D) 2, 99  

---

### 4. (BVA)
Para uma faixa de 5 a 15, qual valor NÃO é de limite?

A) 4  
B) 5  
C) 10  
D) 16  

---

### 5. (Tabela de decisão)
Sistema:

- Se cliente é VIP → desconto  
- Se NÃO VIP → sem desconto  

Quantos casos mínimos?

A) 1  
B) 2  
C) 3  
D) 4  

---

### 6. (Tabela de decisão)
Sistema:

- VIP + saldo alto → desconto  
- VIP + saldo baixo → sem desconto  
- Não VIP → sem desconto  

Quantos casos mínimos?

A) 2  
B) 3  
C) 4  
D) 6  

---

### 7. (Transição de estado)
Sistema bloqueia usuário após 3 tentativas inválidas.  
Qual teste é válido?

A) 1 erro → login → bloqueio  
B) 3 erros → bloqueio  
C) 2 erros → bloqueio  
D) 1 erro → bloqueio  

---

### 8. (Transição de estado)
Qual cenário testa um fluxo inválido?

A) Login correto direto  
B) 3 erros → bloqueio  
C) Acesso após bloqueio  
D) 1 erro → sucesso  

---

### 9. (Cobertura de decisão)
Código:

```python
if idade >= 18:
    acesso = True
else:
    acesso = False

1. B
2. C
3. B
4. C
5. B
6. B
7. B
8. C
9. B
10. C
11. B
12. B
13. A
14. C
15. C