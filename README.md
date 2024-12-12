<br>

# ✍️ Derivatives - Calculus I - Resolution of Mathematics Exercises
#### <p align="center"> AI Data Science - PUCSP University - Math Repository - [Professor Eric Bacconi Gonçalves](https://www.linkedin.com/in/eric-bacconi-423137/)

<br>

https://github.com/user-attachments/assets/e77310b2-7d55-48a2-96c2-f729cf434b75

<br>

Welcome to the **Derivatives - Calculus I** repository! This repository is a comprehensive guide designed to assist students, educators, and enthusiasts in mastering the resolution of mathematics exercises related to derivatives in Calculus I.


## 1. [Introduction to the Repository]()

This repository aims to provide a structured approach to learning derivatives, starting from the basic concepts to more advanced applications. Whether you're preparing for exams, brushing up on calculus, or exploring the role of calculus in data science, this resource will be invaluable.

## 2. [Fundamental Concepts]()

In this section, we cover the foundational concepts necessary for understanding derivatives, including:

- **Limits and Continuity**: The building blocks of derivatives.
- **Definition of a Derivative**: What it means and how it's calculated.
- **Basic Differentiation Rules**: Techniques such as the power rule, product rule, quotient rule, and chain rule.
- **Higher-Order Derivatives**: Understanding the second derivative and beyond.
- **Common Functions**: Differentiating functions like polynomials, exponentials, logarithms, and trigonometric functions.

## 3. [Why Derivatives are Important for AI Data Scientists]()

Derivatives are not just a mathematical curiosity; they play a crucial role in the field of data science and artificial intelligence (AI). This section discusses:

- **Optimization**: How derivatives help in finding minima and maxima, which are key in training machine learning models.
- **Gradient Descent**: The backbone of many learning algorithms, using derivatives to optimize model parameters.
- **Regularization**: Preventing overfitting by penalizing excessive complexity, guided by derivative-based techniques.
- **Neural Networks**: Backpropagation relies heavily on derivatives for updating weights and biases in deep learning models.

<br>  

### ***[Understanding these applications highlights the importance of derivatives in the development and optimization of AI models.]()***

<br>

## 4. [Exercises: Find the following derivatives]() ☟

This section provides practice exercises to help you apply the concepts you've learned. Below are the exercise solutions in LaTeX format:

## [Exercicise A:]() 

### Given function $\color{DeepSkyBlue} {\ f(x)}$ = $\color{DeepSkyBlue}  {x^2 + 3x + 2}$:

### Find the derivative of $\color{DeepSkyBlue} {\ f(x)}$ with respect to $\color{DeepSkyBlue} {( x )}$, and evaluate it at $\color{DeepSkyBlue} {( x = 1 )}$.

### Calculate, $\color{DeepSkyBlue} {\ f'(x)}$

### Substitute $\color{DeepSkyBlue} {( x = 1 )}$ into $\color{DeepSkyBlue} {\ f'(x)}$

### Solution:

### $\ f'(x)$ = $\frac{d}{dx}(x^2 + 3x + 2) = 2x + 3\$

### $\ f'(1)$ = $2(1) + 3 = 5\$

<br>

`Latex Code ☟`

```latex
\ f'(x) = \frac{d}{dx}(x^2 + 3x + 2) = 2x + 3\
```

```latex
\ f'(1) = 2(1) + 3 = 5\
```

<br>


## [Exercicise B:]() 

### Given Function: $\color{DeepSkyBlue} {\ f(x) = x \cdot e^x }$

### For this function, we use the product rule, which states that the derivative of a product of two functions is the first function times the derivative of the second, plus the second function times the derivative of the first.

### So, we have:

### $\ f'(x) = \frac{d}{dx}(x) \cdot e^x + x \cdot \frac{d}{dx}(e^x)\$

### $\ f'(x) = 1 \cdot e^x + x \cdot e^x\$

### $\ f'(x) = e^x + x \cdot e^x\$

<br>

`Latex Code ☟`

```latex
\ f'(x) = \frac{d}{dx}(x) \cdot e^x + x \cdot \frac{d}{dx}(e^x)\
```

```latex
\ f'(x) = 1 \cdot e^x + x \cdot e^x\
```

```latex
\ f'(x) = e^x + x \cdot e^x\
```

<br>

## [Exercicise C:]() 

### Given Function:  $\color{DeepSkyBlue} { f(x) = 3x + 5 \ln(x) }$


### Here, we have a linear function and the natural logarithm. The derivative of a linear function is simply the coefficient of the variable  $\color{DeepSkyBlue} {\ f(x)}$ , and the derivative of $\color{DeepSkyBlue} { ln(x)}$ is $\color{DeepSkyBlue} { \frac{1}{x} }$.

### Therefore:

### $\ f'(x) = \frac{d}{dx}(3x) + \frac{d}{dx}(5\ln(x))\$

### $\ f'(x) = 3 + 5 \cdot \frac{1}{x}\$

### $\ f'(x) = 3 + \frac{5}{x}$

<br>

`Latex Code ☟`

```latex
\ f'(x) = \frac{d}{dx}(3x) + \frac{d}{dx}(5\ln(x))\
```

```latex
\ f'(x) = 3 + 5 \cdot \frac{1}{x}\
```

```latex
\ f'(x) = 3 + \frac{5}{x}
```

<br>

## [Exercicise D:]() 

### Given Function:  $\color{DeepSkyBlue} {  f(x) = \sin(4x) }$

### For this function, we use the chain rule since we have a composite function. The derivative of $\color{DeepSkyBlue} { sin(u)}$ is $\color{DeepSkyBlue} { cos(u)}$ , and the derivative of  $\color{DeepSkyBlue} {( 4x )}$ with respect to $\color{DeepSkyBlue} { ( x )}$ is $\color{DeepSkyBlue} {4}$.


### So, we have:

### $\ f'(x) = \frac{d}{dx}(\sin(4x))\$

### $\ f'(x) = \cos(4x) \cdot \frac{d}{dx}(4x)\$

### $\ f'(x) = 4\cos(4x)\$


<br>

`Latex Code ☟`

```latex
\ f'(x) = \frac{d}{dx}(\sin(4x))\
```

```latex
\ f'(x) = \cos(4x) \cdot \frac{d}{dx}(4x)\
```

```latex
\ f'(x) = 4\cos(4x)\
```

<br>

## [Exercicise E:]() 

### Given Function: $\color{DeepSkyBlue} { f(x) = e^{3x} }$

### Here, we also apply the chain rule. The derivative of $\color{DeepSkyBlue} {  e^u}$ is $\color{DeepSkyBlue} { e^u}$, and the derivative of $\color{blue} {( 3x )}$ is 3.

### Therefore:

### $\ f'(x) = \frac{d}{dx}(e^{3x})\$

### $\ f'(x) = e^{3x} \cdot 3\$

### $\ f'(x) = 3e^{3x}\$

<br>

`Latex Code ☟`

```latex
\ f'(x) = \frac{d}{dx}(e^{3x})\
```

```latex
\ f'(x) = e^{3x} \cdot 3\
```

```latex
\ f'(x) = 3e^{3x}\
```

## [Exercicise F:]() 

### Given Function: $\ g(x)\$ = $\ sin(x)\$ + $\cos(x))^3\$

### To solve this derivative, we use the sum rule and the chain rule. The derivative of \( \sin(x) \) is \( \cos(x) \), and for the \( (\cos(x))^3 \) term, we use the chain rule.

So, we have:

$\ g'(x) = \frac{d}{dx}\sin(x) + \frac{d}{dx}(\cos(x))^3\$

$\ g'(x) = \cos(x) - 3(\cos(x))^2 \cdot \sin(x)\$

<br>

`Latex Code ☟`

```latex
\ g'(x) = \frac{d}{dx}\sin(x) + \frac{d}{dx}(\cos(x))^3\
```

```latex
\ g'(x) = \cos(x) - 3(\cos(x))^2 \cdot \sin(x)\
```


## 5. Conclusion

This repository is designed to be a comprehensive resource for mastering derivatives in Calculus I, with a special focus on their applications in AI and data science. By working through the materials provided, you'll build a strong foundation in calculus that will be essential for both academic and professional success in the fields of mathematics, engineering, and data science.



#

###### <p align="center"> [Copyright 2024 Quantum Software Development. Code released under the MIT license.](https://github.com/Quantum-Software-Development/README/blob/161b677c5a791f0ca8219b8e934f1cf353d5b85d/LICENSE)










