A **função inversa** desfaz a transformação realizada por uma função.

Se:

$$  
f\rightarrow B  
$$

então sua inversa é:

$$  
f^{-1}\rightarrow A  
$$

Ou seja, **domínio e imagem trocam de papel**.

---

## Condição de existência

Uma função possui inversa quando é [[Funções Injetora, Sobrejetora e Bijetora|bijetora]].

$$  
\boxed{f\text{ é inversível}\iff f\text{ é bijetora}}  
$$

Portanto, ela deve ser:

- **Injetora** → não repete valores de $y$.
- **Sobrejetora** → todo elemento do contradomínio é atingido.

---

## Propriedade principal

A inversa desfaz a função:

$$  
\boxed{f^{-1}(f(x))=x}  
$$

Da mesma forma:

$$  
\boxed{f(f^{-1}(x))=x}  
$$

> $f^{-1}(x)$ **não significa** $\frac{1}{f(x)}$.

---

# Como encontrar a inversa

Considere:

$$  
f(x)=2x+3  
$$

### 1. Troque $f(x)$ por $y$

$$  
y=2x+3  
$$

### 2. Troque $x$ e $y$

$$  
x=2y+3  
$$

### 3. Isole $y$

$$  
x-3=2y  
$$

$$  
y=\frac{x-3}{2}  
$$

### 4. Escreva a inversa

$$  
\boxed{f^{-1}(x)=\frac{x-3}{2}}  
$$

---

# Verificando a inversa

Podemos verificar através da composição:

$$  
f^{-1}(f(x))  
$$

Como:

$$  
f(x)=2x+3  
$$

temos:

\frac{(2x+3)-3}{2}  
$$

$$  
=\frac{2x}{2}  
$$

$$  
\boxed{x}  
$$

Logo, a inversa está correta.

---

# Domínio e Imagem

Na inversão, domínio e imagem são trocados:

$$  
\boxed{Dom(f^{-1})=Im(f)}  
$$

$$  
\boxed{Im(f^{-1})=Dom(f)}  
$$

Por exemplo:

$$  
f:[0,+\infty)\rightarrow[0,+\infty)  
$$

$$  
f(x)=x^2  
$$

possui inversa:

$$  
\boxed{f^{-1}(x)=\sqrt{x}}  
$$

---

# Restrição de Domínio

Algumas funções não possuem inversa em todo o domínio, mas podem se tornar inversíveis ao **restringir o domínio**.

Por exemplo:

$$  
f(x)=x^2  
$$

em:

$$  
f:\mathbb R\rightarrow[0,+\infty)  
$$

não é injetora, pois:

$$  
f(-2)=f(2)=4  
$$

Portanto, não possui inversa nesse domínio.

Restringindo para:

$$  
f:[0,+\infty)\rightarrow[0,+\infty)  
$$

ela se torna bijetora.

Assim:

$$  
\boxed{f^{-1}(x)=\sqrt{x}}  
$$

---

# Gráfico da Função Inversa

Os gráficos de $f$ e $f^{-1}$ são **simétricos em relação à reta**:

$$  
\boxed{y=x}  
$$

Isso ocorre porque as coordenadas são trocadas:

$$  
(a,b)\rightarrow(b,a)  
$$

Se:

$$  
f(2)=5  
$$

então:

$$  
f^{-1}(5)=2  
$$

---

# Exemplo

Encontre a inversa de:

$$  
f(x)=\frac{x+4}{3}  
$$

Começamos:

$$  
y=\frac{x+4}{3}  
$$

Trocamos $x$ e $y$:

$$  
x=\frac{y+4}{3}  
$$

Multiplicando por $3$:

$$  
3x=y+4  
$$

Isolando $y$:

$$  
y=3x-4  
$$

Portanto:

$$  
\boxed{f^{-1}(x)=3x-4}  
$$

---

# Resumo

### Condição

$$  
\boxed{\text{Bijetora}\iff\text{Inversível}}  
$$

### Composição

$$  
\boxed{f^{-1}(f(x))=x}  
$$

$$  
\boxed{f(f^{-1}(x))=x}  
$$

### Domínio e imagem

$$  
\boxed{Dom(f^{-1})=Im(f)}  
$$

$$  
\boxed{Im(f^{-1})=Dom(f)}  
$$

### Gráfico

$$  
\boxed{f\text{ e }f^{-1}\text{ são simétricas em relação a }y=x}  
$$

---

## Relações

- [[Funções]]
- [[Funções Injetora, Sobrejetora e Bijetora]]
- [[Composição de Funções]]
- [[Domínio, Contradomínio e Imagem]]