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
    - [Lineare Gleichungssysteme - LGS](#lineare-gleichungssysteme---lgs)

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

> CAS Vektor > norm

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

> CAS Vektor > dotP

#### Kreuzprodukt/Normalenvektor

![Kreuzprodukt](img/kreuzprodukt.png){ height=250px }

$$\vec{a}\times\vec{b}=\vec{c}$$

> CAS Vektor > crossP

#### Winkel zwischen zwei Vektoren

> CAS Vektor > angle

### Geraden
#### Geradengleichungen
Parametergleichung

![Parametergleichung](img/g-parameterform.png){ height=250px }

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
Wenn der Punkt $X$ (somit der Vektor $\vec{x}$) auf einer Gerade liegt, wird die Geradengleichung

in der Parameterform:

* einen Wert für den Geradenparameter ermöglichen

in der Normalenform:

* $0$ ergeben

#### Schnittpunkt zweier Geraden

Schneiden sich zwei Geraden $g_1$ und $g_2$, so kann der Schnittpunkt ermittelt werden, indem die beiden Gleichungen gelichgesetzt werden. Danach wird in einem LGS die Lösung für die beiden Geradenparameter gefunden. Jetzt kann der jeweilige Parameter in eine der Parameter in seine Geradengleichung eingesetzt werden, um ein Vektor $\vec{x}$ zu ermitteln.

$$g_1=g_2$$

$$\vec{a_1} + r \cdot \vec{m_1}=\vec{a_2} + s \cdot \vec{m_2}$$

##### Schnittwinkel zweier Geraden
Schnittwinkel mit den Richtungsvektoren $\vec{m_g}$ und $\vec{m_h}$ der Geraden $g$ und $h$:

$$\cos\varphi=\frac{|\vec{m_g}\cdot\vec{m_h}|}{|\vec{m_g}|\cdot|\vec{m_h}|}$$

#### Abstand Punkt von Gerade

Der Abstand zwischen einem Punkt $X$ und einer Gerade $g$ kann mithilfe einer Hilfsebene $H$ berechnet werden.

#### Schnittpunkt Gerade und Ebene
Schneidet sich eine Gerade $g$ und eine Ebene $E$, so kann der Schnittpunkt ermittelt werden, indem die Geradengleichung (in Parameterform) in die Ebendengleichung (in Koordinatenform) eingesetzt wird. Danach wird nach den Geradenparameter gelöst, welcher danach für eine Lösung für den Vektor $\vec{x}$ in die Geradengleichung eingesetzt werden muss.

$$g: \vec{x} = \vec{a} + r \cdot \vec{m}$$

$$E:ax+by+cz=d$$

$g$ in $E$

$$(a_1+r\cdot m_1) \cdot x + (a_2+r\cdot m_2) \cdot y + (a_3+r\cdot m_3) \cdot z=d$$


##### Schnittwinkel Gerade und Ebene
Schnittwinkel mit dem Richtungsvektor $\vec{m_g}$ der Geraden und dem Normalenvektor $\vec{n}$ der Ebene:

$$\sin\varphi=\frac{|\vec{n}\cdot\vec{m_g}|}{|\vec{n}|\cdot|\vec{m_g}|}$$

### Ebenen
#### Ebenengleichung

Parameterform

![Parameterform](img/E-parameterform.png){ height=250px }

$$E: \vec{x} = \vec{a} + r \cdot \vec{b}+s\cdot\vec{c}$$

* $\vec{x}$ : beliebiger Raumvektor
* $\vec{a}$ : Stützvektor/Ortsvektor
* $\vec{b},\vec{c}$ : Richtungsvektor
* $r,s$ : Ebenenparameter

Normalenform

![Normalenform](img/E-normalenform.png){ height=250px }

$$E:\vec{n}_{E}\cdot(\vec{x}-\vec{a})=0$$

* $\vec{x}$ : beliebiger Raumvektor
* $\vec{a}$ : Stützvektor/Ortsvektor
* $\vec{n}_{E}$ : Normalenvektor von $E$

Koordinatenform

$$E:ax+by+cz=d$$

* $a,b,c$ : Koordinaten des Normalenvektors
* $d$ : Skalarprodukt von $\vec{n}$ (Normalenvektor) und $\vec{a}$ (Stützvektor/Ortsvektor)

#### Schnittgerade zweier Ebenen
Schneiden sich zwei Ebenen $E_1$ und $E_2$, so kann die Schnittgerade $g$ ermittelt werden, indem eine der beiden Ebenengleichungen (in Koordinaten) in die andere (in Parameterform ) eingesetzt wird. Danach wird nach einen der zwei Parameter gelöst. Die Lösung enthält den anderen Parameter und wird dann in die Ebenengleichung in Parameterform eingesetzt. Diese Ebenengleichung hat jetzt nur noch ein Parameter und macht sie zu einer Geradengleichung.

$$E_1: \vec{x} = \vec{a} + r \cdot \vec{b}+s\cdot\vec{c}$$

$$E_2:ax+by+cz=d$$

$E_1$ in $E_2$

$$(a_1+r\cdot b_1+s\cdot c_1) \cdot x + (a_2+r\cdot b_2+s\cdot c_2) \cdot y + (a_3+r\cdot b_3+s\cdot c_3) \cdot z=d$$

resultiert in $g$

$$g: \vec{x} = \vec{a} + r \cdot \vec{m}$$

##### Schnittwinkel zweier Ebenen
Schnittwinkel mit den Normalenvektoren $\vec{n_1}$ und $\vec{n_2}$ der beiden Ebenen:

$$\cos\varphi=\frac{|\vec{n_1}\cdot\vec{n_2}|}{|\vec{n_1}|\cdot|\vec{n_2}|}$$

#### Abstand Punkt und Ebene

Der Abstand zwischen dem Punkt $X$ (Vector $\vec{x}$) und der Ebene $E$ (in Normalenform) kann mit folgender Formel berechnet werden. 

$$d(X,E)= \begin{vmatrix}\frac{\vec{n}\cdot (\vec{x}-\vec{a})}{|\vec{n}|}\end{vmatrix}$$

### Lineare Gleichungssysteme - LGS
Mit einem LGS kann man Gleichungen mit mehreren Unbekannten/Gleichungen lösen. Ein LGS kann zum Beispiel verwendet werden, wenn man überprüfen möchte, ob ein Punkt auf einer Geraden liegt.

Punkt $X(0, -1, 1)$
Gerade 
$$g: \vec{x}=
\begin{pmatrix}
    0 \\
    -2 \\
    0
\end{pmatrix}
+r\cdot
\begin{pmatrix}
    0 \\
    2 \\
    2
\end{pmatrix}
$$
LGS:
$$
\begin{cases}
    I. \thickspace 0=0+r\cdot 0 \\
    II. \thickspace -1=-2+r\cdot2 \\
    III. \thickspace 1=0+r\cdot2
\end{cases}
$$
Hieraus kann man den Wert $\frac{1}{2}$ für den Parameter r ermitteln. Somit liegt der Punkt auf der Gerade $g$