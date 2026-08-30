Considere uma função:

$$  
f\rightarrow B  
$$

- $A$ → domínio
- $B$ → contradomínio
- $Im(f)$ → imagem

---

# Função Injetora

Uma função é **injetora** quando valores diferentes do domínio produzem **imagens diferentes**.

$$  
x_1 \neq x_2  
\Rightarrow  
f(x_1)\neq f(x_2)  
$$

Equivalentemente:

$$  
\boxed{f(x_1)=f(x_2)\Rightarrow x_1=x_2}  
$$

Ou seja, **dois valores diferentes de $x$ não podem chegar ao mesmo $y$**.

### Exemplo

$$  
f(x)=2x+1  
$$

Se:

$$  
f(x_1)=f(x_2)  
$$

então:

$$  
2x_1+1=2x_2+1  
$$

$$  
x_1=x_2  
$$

Logo, a função é **injetora**.

### Graficamente

Uma reta horizontal não pode cortar o gráfico em mais de um ponto.

> **Teste da reta horizontal.**

---

# Função Sobrejetora

Uma função é **sobrejetora** quando **todo elemento do contradomínio é atingido** pela função.

$$  
\boxed{Im(f)=B}  
$$

Ou seja:

> Não sobra nenhum elemento no contradomínio.

### Exemplo

Considere:

$$  
f:\mathbb{R}\rightarrow\mathbb{R}  
$$

$$  
f(x)=x^3  
$$

Para qualquer:

$$  
y\in\mathbb{R}  
$$

existe algum:

$$  
x\in\mathbb{R}  
$$

tal que:

$$  
f(x)=y  
$$

Logo, $f$ é **sobrejetora**.

---

# Função Bijetora

Uma função é **bijetora** quando é simultaneamente:

$$  
\boxed{\text{Injetora + Sobrejetora}}  
$$

Portanto:

- cada $x$ possui um único $y$;
- cada $y$ é atingido;
- nenhum $y$ é atingido por dois valores diferentes de $x$.

Existe uma correspondência **um para um** entre domínio e contradomínio.

### Exemplo

$$  
f:\mathbb{R}\rightarrow\mathbb{R}  
$$

$$  
f(x)=2x+1  
$$

Ela é:

- injetora → $x$ diferentes produzem $y$ diferentes;
- sobrejetora → todo $y\in\mathbb R$ pode ser atingido.

Logo:

$$  
\boxed{f\text{ é bijetora}}  
$$

---

# Função Inversível

Uma função possui uma **função inversa**:

$$  
f^{-1}\rightarrow A  
$$

quando $f$ é **bijetora**.

$$  
\boxed{f\text{ é inversível}\iff f\text{ é bijetora}}  
$$

A inversa desfaz a operação realizada pela função:

$$  
f^{-1}(f(x))=x  
$$

e:

$$  
f(f^{-1}(x))=x  
$$

> $f^{-1}(x)$ **não significa** $\frac{1}{f(x)}$.

---

## Encontrando a inversa

Considere:

$$  
f(x)=2x+1  
$$

### 1. Escreva como $y$

$$  
y=2x+1  
$$

### 2. Troque $x$ por $y$

$$  
x=2y+1  
$$

### 3. Isole $y$

$$  
x-1=2y  
$$

$$  
y=\frac{x-1}{2}  
$$

Portanto:

$$  
\boxed{f^{-1}(x)=\frac{x-1}{2}}  
$$

---

# Domínio e Imagem da Inversa

A função inversa troca o papel do domínio e da imagem:

$$  
Dom(f^{-1})=Im(f)  
$$

$$  
Im(f^{-1})=Dom(f)  
$$

Se $f\rightarrow B$ for bijetora:

$$  
f^{-1}\rightarrow A  
$$

---

# Gráfico da Função Inversa

Os gráficos de:

$$  
f(x)  
$$

e:

$$  
f^{-1}(x)  
$$

são simétricos em relação à reta:

$$  
\boxed{y=x}  
$$

Isso ocorre porque as coordenadas são trocadas:

$$  
(a,b)\rightarrow(b,a)  
$$

---

# Atenção ao Contradomínio

Ser sobrejetora ou bijetora **depende do contradomínio definido**.

Por exemplo:

$$  
f(x)=x^2  
$$

Se:

$$  
f:\mathbb R\rightarrow\mathbb R  
$$

não é sobrejetora, pois números negativos não são atingidos:

$$  
Im(f)=[0,+\infty)  
$$

Mas se definirmos:

$$  
f:\mathbb R\rightarrow[0,+\infty)  
$$

ela passa a ser **sobrejetora**.

Ainda assim, não é injetora, pois:

$$  
f(-2)=f(2)=4  
$$

Se restringirmos também o domínio:

$$  
f:[0,+\infty)\rightarrow[0,+\infty)  
$$

$$  
f(x)=x^2  
$$

então ela é **bijetora** e possui inversa:

$$  
\boxed{f^{-1}(x)=\sqrt{x}}  
$$

---

# Resumo

|Tipo|Condição|
|---|---|
|**Injetora**|Cada $y$ é atingido **no máximo uma vez**|
|**Sobrejetora**|Todo $y$ do contradomínio é atingido **pelo menos uma vez**|
|**Bijetora**|Todo $y$ é atingido **exatamente uma vez**|
|**Inversível**|A função é **bijetora**|

Uma forma rápida de lembrar:

$$  
\boxed{  
\begin{aligned}  
\text{Injetora} &\rightarrow \text{não repete }y\  
\text{Sobrejetora} &\rightarrow \text{não sobra }y\  
\text{Bijetora} &\rightarrow \text{não repete nem sobra}\  
\text{Inversível} &\leftrightarrow \text{Bijetora}  
\end{aligned}}  
$$

---

## Relações

- [[Funções]]
- [[Domínio, Contradomínio e Imagem]]
- [[Função Inversa]]
- [[Gráficos de Funções]]