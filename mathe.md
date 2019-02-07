# Lernzettel Mathe

- [Lernzettel Mathe](#lernzettel-mathe)
  - [Analysis](#analysis)
    - [Kurvendiskussion](#kurvendiskussion)
    - [e-Funktionen](#e-funktionen)
    - [Integration](#integration)
  - [Stochastik](#stochastik)
  - [Analytische Geometrie](#analytische-geometrie)
    - [Vektoren](#vektoren)
    - [Geraden](#geraden)
    - [Ebenen](#ebenen)

## Analysis
### Kurvendiskussion

#### 1. Symmetrie
#### 2. Nullstellen
> $f(x)=0$

#### 3. Extrema
> $f'(x)=0$
> 
> $f''(x_E) < 0 \Rightarrow$ Maximum
> 
> $f''(x_E) > 0 \Rightarrow$ Minimum
> 
> $f''(x_E) = 0 \Rightarrow$ keine Aussage

#### 4. Wendepunkte
> $f''(x)=0$  
> 
> $f'''(x_W) < 0 \Rightarrow$ Wendepunkt(L-r) 
> 
> $f'''(x_W) > 0 \Rightarrow$ Wendepunkt(R-l) 
> 
> $f'''(x_W) = 0 \Rightarrow$ keine Aussage 

### e-Funktionen
### Integration
Mit der Integration lässt sich der Flächeninhalt unter einer Funktion berechnen.

$$\int\limits_a^bf(x)dx$$


|  Name  | Bedeutung                 |
| :----: | :------------------------ |
|  $a$   | untere Integrationsgrenze |
|  $b$   | obere Integrationsgrenze  |
| $f(x)$ | Integral                  |
|  $dx$  | Differenzial              |

#### Ableiten
| $f(x)$  |      $x^n$       |
| :-----: | :--------------: |
| $f'(x)$ | $n\cdot x^{n-1}$ |

#### Aufleiten
| $f(x)$ |            $x^n$             |
| :----: | :--------------------------: |
| $F(x)$ | $\frac{1}{n+1}\cdot x^{n+1}$ |

#### Produktregel
$$f(x)=u(x)\cdot v(x)$$

$$f' = u'\cdot v +u\cdot v'$$

#### Kettenregel
## Stochastik
## Analytische Geometrie
### Vektoren
#### Betrag eines Vektors
Der Betrag eines Vektors ist die Länge eines seiner Pfeile.

Beispiel
$$ \overrightarrow{AB} = 
\begin{pmatrix}
    2 \\
    4 \\
    4
\end{pmatrix}
$$

$$|\overrightarrow{AB}|=\sqrt{2^2+4^2+4^2} = \sqrt{36} = 6$$

#### Skalarprodukt

$$ \vec{a} = 
\begin{pmatrix}
    a_{1} \\
    a_{2} \\
    a_{3}
\end{pmatrix}
,
\vec{b} = 
\begin{pmatrix}
    b_{1} \\
    b_{2} \\
    b_{3}
\end{pmatrix}
$$

$$\vec{a}\cdot\vec{b}=a_{1}b_{1}+a_{2}b_{2}+a_{3}b_{3}$$

> $\vec{a}\cdot\vec{b}$ ist eine reelle Zahl

#### Kreuzprodukt/Normalenvektor

![Kreuzprodukt](img/kreuzprodukt.png){ height=300px }

$$\vec{a}\times\vec{b}=\vec{c}$$

#### Winkel zwischen zwei Vektoren


### Geraden
#### Geradengleichungen
Parametergleichung

![Parametergleichung](img/g-parameterform.png){ height=300px }

$$g: \vec{x} = \vec{a} + r \cdot \vec{m}$$

* $\vec{x}$ : beliebiger Raumvektor
* $\vec{a}$ : Stützvektor/Ortsvektor
* $\vec{m}$ : Richtungsvektor
* $r$ : Geradenparameter

Normalenform

$$g:\vec{n}_{g}\cdot(\vec{x}-\vec{a})=0$$

* $\vec{x}$ : beliebiger Raumvektor
* $\vec{a}$ : Stützvektor/Ortsvektor
* $\vec{n}_{g}$ : Normalenvektor von $g$

#### Punkt auf der Gerade


#### Schnittpunkt zweier Geraden
##### Schnittwinkel zweier Geraden
#### Schnittpunkt Gerade und Ebene
##### Schnittwinkel Gerade und Ebene
### Ebenen
#### Ebenengleichung

Parameterform

![Parametergleichung](img/E-parameterform.png){ height=300px }

$$E: \vec{x} = \vec{a} + r \cdot \vec{b}+s\cdot\vec{c}$$

* $\vec{x}$ : beliebiger Raumvektor
* $\vec{a}$ : Stützvektor/Ortsvektor
* $\vec{b},\vec{c}$ : Richtungsvektor
* $r,s$ : Ebenenparameter

Normalenform

![Parametergleichung](img/E-normalenform.png){ height=300px }

$$E:\vec{n}_{E}\cdot(\vec{x}-\vec{a})=0$$

* $\vec{x}$ : beliebiger Raumvektor
* $\vec{a}$ : Stützvektor/Ortsvektor
* $\vec{n}_{E}$ : Normalenvektor von $E$

Koordinatenform

$$E:ax+by+cz=d$$

* $a,b,c$ : Koordinaten des Normalenvektors
* $d$ : Skalarprodukt von $\vec{n}$(Normalenvektor) und $\vec{a}$(Stützvektor/Ortsvektor)

#### Schnittgerade zweier Ebenen
#### Schnittwinkel zweier Ebenen