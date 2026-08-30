Energia é uma grandeza física associada à **capacidade de um sistema produzir transformações ou realizar [[Trabalho]]**.

A energia pode ser **transferida** ou **transformada**, mas em um sistema isolado sua quantidade total é conservada.

---

## Unidade de medida

No SI, energia é medida em **joule**:

$$  
[E] = J  
$$

$$  
1J = 1N \cdot m  
$$

Como:

$$  
1N = 1kg \cdot m/s^2  
$$

Então:

$$  
1J = 1kg \cdot m^2/s^2  
$$

---

# Energia Cinética

Energia associada ao **movimento de um corpo**.

$$  
E_c = \frac{mv^2}{2}  
$$

- $E_c$ → energia cinética `[J]`
- $m$ → massa `[kg]`
- $v$ → velocidade `[m/s]`

A energia cinética depende do **quadrado da velocidade**:

$$  
E_c \propto v^2  
$$

Portanto, se a velocidade dobrar:

$$  
v \rightarrow 2v  
$$

$$  
E_c \rightarrow 4E_c  
$$

### Exemplo

Um corpo de $2,kg$ se move a $4,m/s$:

$$  
E_c = \frac{2 \cdot 4^2}{2}  
$$

$$  
\boxed{E_c = 16,J}  
$$

---

# Teorema da Energia Cinética

O [[Trabalho]] realizado pela **força resultante** é igual à variação da energia cinética.

$$  
\tau_R = \Delta E_c  
$$

$$  
\tau_R = E_{c_f} - E_{c_i}  
$$

Consequências:

$$  
\tau_R > 0 \Rightarrow E_c \uparrow  
$$

$$  
\tau_R < 0 \Rightarrow E_c \downarrow  
$$

$$  
\tau_R = 0 \Rightarrow E_c = \text{constante}  
$$

---

# Energia Potencial

Energia associada à **configuração ou posição de um sistema**.

As principais na Mecânica são:

- Energia Potencial Gravitacional
- Energia Potencial Elástica
- Energia Potencial Elétrica

A energia potencial está associada a **forças conservativas**.

---

## Energia Potencial Gravitacional

Próximo à superfície da Terra:

$$  
E_{pg} = mgh  
$$

- $E_{pg}$ → energia potencial gravitacional `[J]`
- $m$ → massa `[kg]`
- $g$ → aceleração gravitacional `[m/s^2]`
- $h$ → altura em relação à referência `[m]`

### Referencial

O valor de $E_{pg}$ depende do nível escolhido como:

$$  
h = 0  
$$

O que possui significado físico direto é a **variação**:

$$  
\Delta E_{pg} = mg\Delta h  
$$

### Trabalho da força peso

O trabalho realizado pelo peso é:

$$  
\tau_P = -\Delta E_{pg}  
$$

Portanto:

**Corpo descendo:**

$$  
E_{pg} \downarrow  
$$

e o peso realiza trabalho positivo.

**Corpo subindo:**

$$  
E_{pg} \uparrow  
$$

e o peso realiza trabalho negativo.

---

## Energia Potencial Elástica

Energia armazenada em uma mola deformada:

$$  
E_{pe} = \frac{kx^2}{2}  
$$

- $E_{pe}$ → energia potencial elástica `[J]`
- $k$ → constante elástica `[N/m]`
- $x$ → deformação da mola `[m]`

Na posição de equilíbrio:

$$  
x = 0  
$$

portanto:

$$  
E_{pe} = 0  
$$

A energia cresce com o quadrado da deformação:

$$  
E_{pe} \propto x^2  
$$

Se a deformação dobrar:

$$  
E_{pe} \rightarrow 4E_{pe}  
$$

### Trabalho da força elástica

$$  
\tau_{el} = -\Delta E_{pe}  
$$

---

# Forças Conservativas

Uma força é **conservativa** quando seu trabalho depende apenas das posições inicial e final, e não do caminho realizado.

Para uma força conservativa:

$$  
\tau_c = -\Delta E_p  
$$

Exemplos:

- força gravitacional
- força elástica
- força elétrica

Em um percurso fechado:

$$  
\tau_c = 0  
$$

---

# Forças Dissipativas

Forças dissipativas transformam parte da energia mecânica em outras formas de energia.

Exemplos:

- atrito
- resistência do ar
- forças de arrasto

O atrito pode transformar energia mecânica em **energia térmica**.

$$  
E_m \rightarrow E_{térmica}  
$$

Isso **não significa que energia foi destruída**.

A energia total continua conservada, mas a **energia mecânica** pode diminuir.

---

# Energia Mecânica

A energia mecânica é a soma das energias cinética e potencial:

$$  
E_m = E_c + E_p  
$$

Quando existem energia gravitacional e elástica:

$$  
E_m = E_c + E_{pg} + E_{pe}  
$$

---

# Conservação da Energia Mecânica

Quando apenas forças conservativas realizam trabalho:

$$  
E_m = \text{constante}  
$$

Portanto:

$$  
E_{m_i} = E_{m_f}  
$$

ou:
$$
E_{c_f} + E_{p_f}  
$$

A energia pode ser transformada entre diferentes formas.

### Queda livre

No alto:

$$  
E_{pg} \text{ máxima}  
$$

Durante a queda:

$$  
E_{pg} \rightarrow E_c  
$$

Próximo ao chão:

$$  
E_c \text{ máxima}  
$$

Sem resistência do ar:

$$  
E_{pg_i} = E_{c_f}  
$$

---

# Teorema da Energia Mecânica

Quando forças **não conservativas** realizam trabalho:

$$  
\tau_{nc} = \Delta E_m  
$$

ou:

$$  
\tau_{nc} = E_{m_f} - E_{m_i}  
$$

Assim:

$$  
E_{m_f} = E_{m_i} + \tau_{nc}  
$$

Se o trabalho da força não conservativa for negativo:

$$  
E_{m_f} < E_{m_i}  
$$

---

# Conservação da Energia Total

A **energia mecânica nem sempre é conservada**, mas a energia total de um sistema isolado é.

$$  
E_{total,i} = E_{total,f}  
$$

A energia apenas muda de forma:

$$  
E_c  
\leftrightarrow  
E_p  
\leftrightarrow  
E_{térmica}  
\leftrightarrow  
E_{química}  
\leftrightarrow  
\cdots  
$$

Por exemplo, com atrito:

$$  
E_{m,i} = E_{m,f} + E_{térmica}  
$$

---

# Relação entre Trabalho e Energia

[[Trabalho]] é uma forma de **transferência de energia**.

O principal teorema é:

$$  
\tau_R = \Delta E_c  
$$

Para forças conservativas:

$$  
\tau_c = -\Delta E_p  
$$

Para forças não conservativas:

$$  
\tau_{nc} = \Delta E_m  
$$

Essas três relações são fundamentais em problemas de energia.

---

# Potência

A potência mede a **rapidez com que energia é transferida ou transformada**.

$$  
P = \frac{\Delta E}{\Delta t}  
$$

Como trabalho é transferência de energia:

$$  
P = \frac{\tau}{\Delta t}  
$$

Unidade:

$$  
[P] = W  
$$

$$  
1,W = 1,J/s  
$$

> Ver também: [[Potência]]

---

# Exemplo — Queda Livre

Um corpo de $2,kg$ é abandonado de uma altura de $20,m$.

Considere:

$$  
g = 10,m/s^2  
$$

Inicialmente:

$$  
E_c = 0  
$$

$$  
E_{pg} = mgh  
$$

$$  
E_{pg} = 2 \cdot 10 \cdot 20  
$$

$$  
E_{pg} = 400,J  
$$

Portanto:

$$  
E_{m_i} = 400,J  
$$

Sem resistência do ar:

$$  
E_{m_f} = E_{m_i}  
$$

No chão:

$$  
E_{pg} = 0  
$$

Logo:

$$  
E_c = 400,J  
$$

Usando:

$$  
E_c = \frac{mv^2}{2}  
$$

$$  
400 = \frac{2v^2}{2}  
$$

$$  
v^2 = 400  
$$

$$  
\boxed{v = 20,m/s}  
$$

---

# Exemplo — Sistema com Atrito

Um corpo possui inicialmente:

$$  
E_{m_i} = 100,J  
$$

O atrito realiza:

$$  
\tau_{at} = -30,J  
$$

Pelo Teorema da Energia Mecânica:

$$  
\tau_{nc} = \Delta E_m  
$$

$$  
-30 = E_{m_f} - 100  
$$

$$  
\boxed{E_{m_f} = 70,J}  
$$

Os $30,J$ não desapareceram: foram transformados principalmente em energia térmica.

---

# Resumo das Fórmulas

### Cinética

$$  
\boxed{E_c = \frac{mv^2}{2}}  
$$

### Potencial gravitacional

$$  
\boxed{E_{pg} = mgh}  
$$

### Potencial elástica

$$  
\boxed{E_{pe} = \frac{kx^2}{2}}  
$$

### Energia mecânica

$$  
\boxed{E_m = E_c + E_p}  
$$

### Teorema da Energia Cinética

$$  
\boxed{\tau_R = \Delta E_c}  
$$

### Trabalho de força conservativa

$$  
\boxed{\tau_c = -\Delta E_p}  
$$

### Teorema da Energia Mecânica

$$  
\boxed{\tau_{nc} = \Delta E_m}  
$$

### Conservação da Energia Mecânica

$$  
\boxed{E_{m_i} = E_{m_f}}  
$$

quando apenas forças conservativas realizam trabalho.

### Conservação da Energia Total

$$  
\boxed{E_{total,i} = E_{total,f}}  
$$

para um sistema isolado.

---

## Relações

- [[Trabalho]]
- [[Potência]]
- [[Velocidade]]
- [[Aceleração]]
- [[Força]]