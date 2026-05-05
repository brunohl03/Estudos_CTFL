CAPÍTULO 4 – TÉCNICAS DE TESTE (K3)
🎯 4.2 – Técnicas Caixa-Preta (K3)
✔️ Você precisa SABER FAZER:
🔹 1. Particionamento de Equivalência (EP)

👉 Dado um cenário, você deve:

Identificar classes válidas e inválidas
Criar testes representativos
📌 Exemplo típico:

Campo aceita valores de 1 a 100

✔️ Classes:

Válido: 1–100
Inválido: <1
Inválido: >100

👉 Você NÃO testa tudo — testa representantes

🔹 2. Análise de Valor Limite (BVA)

👉 Você precisa aplicar nos limites:

✔️ Limites:

mínimo
máximo
logo abaixo
logo acima
📌 Exemplo:

Faixa: 1–100

✔️ Testes:

0
1
2
99
100
101

👉 Muito cobrado!

🔹 3. Tabela de Decisão

👉 Você recebe regras e deve:

Identificar combinações
Criar casos de teste
📌 Exemplo:

Se cliente VIP e saldo > 1000 → desconto

👉 Você monta tabela com combinações:

VIP / não VIP
saldo alto / baixo
🔹 4. Transição de Estado

👉 Você deve:

Identificar estados
Criar testes válidos e inválidos
📌 Exemplo:

Login:

Bloqueia após 3 tentativas

✔️ Testar:

sequência válida
sequência inválida
🎯 4.3 – Técnicas Caixa-Branca (K3)
🔹 5. Cobertura de Código

👉 Você precisa entender e aplicar:

✔️ Tipos:
Cobertura de instrução
Cobertura de decisão
📌 Exemplo:
if x > 10:
    print("A")
else:
    print("B")

👉 Testes mínimos:

x > 10
x ≤ 10

✔️ Para cobrir ambos caminhos

🎯 4.4 – Baseado em Experiência (K3 leve)

👉 Pode cair como cenário:

Teste exploratório
Error guessing

✔️ Você escolhe testes com base na experiência

📊 RESUMO K3 (O QUE VOCÊ PRECISA FAZER)
Técnica	O que fazer
EP	separar classes
BVA	testar limites
Decisão	combinar regras
Estado	validar fluxos
Caixa-branca	cobrir caminhos
⚠️ PEGADINHAS K3
1. Testar tudo ❌

👉 Você testa representantes

2. Confundir EP com BVA

👉 EP = grupos
👉 BVA = limites

3. Esquecer valores inválidos

👉 SEMPRE incluir inválidos

4. Cobertura incompleta

👉 1 teste não cobre tudo

🎯 PADRÃO DAS QUESTÕES K3

Eles vão te dar:

👉 Um cenário
👉 Uma regra
👉 Um código simples

E perguntar:

Quantos testes são necessários?
Quais valores escolher?
Qual cobertura foi atingida?
🧠 DICA DE OURO (K3)

Se aparecer número ou regra:

👉 PARE e modele rapidamente:

EP → quantos grupos?
BVA → quais limites?
Decisão → quantas combinações?
🚀 EXEMPLO REAL DE PROVA

Campo aceita idade de 18 a 60

Pergunta:
Qual conjunto de testes cobre BVA?

✔️ Resposta correta:
17, 18, 19, 59, 60, 61