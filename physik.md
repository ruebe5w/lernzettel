---
title: "Lernzettel Physik"
date: 2019
listings-disable-line-numbers: true
page-numbers: true
toc: true
toc-title: "Inhalt"
---



# Lernzettel Physik
* Photoeffekt: [Vakuum Photozelle](#vakuum-photozelle)
* Inverser Photoeffekt: [Röntgenstrahlung](#bremsstrahlung)
* Bragg-Reflexion am Kristall: [Bragg-Reflexion](#messung-des-spektrums)

## Elektrische und Magnetische Felder 
## Schwingungen und Wellen
## Quanten und Atomphysik
### Versuche
#### Glühelektrischer Effekt

Der glühelektrische Effekt (auch Richardson- oder Edison-Effekt) ist das Phänomen, dass eine glühende Metall- oder Halbleiteroberfläche Elektronen emittiert (Glühemission). Mit steigender Temperatur nimmt die kinetische Energie der Leitungselektronen im erhitzten Körper so weit zu, dass immer mehr von ihnen imstande sind, die Potenzialschwelle an der Oberfläche (Austrittsarbeit) zu überwinden.

#### Vakuum Photozelle


#### Wiensches Geschwindigkeitsfilter
##### Verwendung
Ein Geschwindigkeitsfilter dient hauptsächlich dazu, aus dem Teilchenstrahl einer Ionenquelle nur diejenigen Teilchen den Filter passieren zu lassen, die eine bestimmte Geschwindigkeit besitzen, während alle übrigen im Filter „hängenbleiben“ – anders gesagt, kann man damit einen Teilchenstrom mit nur einer genau definierten Geschwindigkeit „präparieren“, aber auch die Geschwindigkeit unbekannter geladener Teilchen bestimmen. Das Filter wird zum Beispiel in einem [Massenspektrometer](#massenspektrometer) genutzt.

##### Aufbau
![Wiensches Geschwindigkeitsfilter](img/wiensches&#32;geschwindigkeitsfilter.gif){ height=250px }

Im Filter stehen ein homogenes elektrisches Feld und ein homogenes magnetisches Feld senkrecht aufeinander und senkrecht zur Einschussrichtung der geladenen Teilchen. Damit ein Teilchen nach dem Passieren der Eintrittsblende in gerader Bahn die Austrittsblende erreichen kann, muss an jedem Punkt Kräftegleichgewicht $F_\text{el}=F_{\text{L}}$ herrschen:
$$
\begin{aligned}
    F_\text{el}&=F_{\text{L}}\\
    q\cdot E&=q\cdot v\cdot B\\\\
    v&=\dfrac{E}{B}
\end{aligned}
$$
Nur Teilchen mit dieser Geschwindigkeit können das Filter passieren. Alle anderen werden nach oben oder unten abgelenkt und erreichen daher die Öffnung der Ausgangsblende nicht.

#### Massenspektrometer
##### Aufbau
![Massenspektrometer](img/massenspektrometer.png){ height=250px }

##### Verwendung
Bei einem Massenspektrometer werden Teilchen eines Ionenstrahls zuerst mithilfe eines [Geschwindigkeitsfilters](#wiensches-geschwindigkeitsfilter) mit einer bekannten Geschwindigkeit rausgefiltert, um dann z.B. mittels eines Magnetfeldes die verschiedenen Massen zu trennen.

##### Bewegung von Teilchen im homogenen Feld
Die Teilchen bewegen sich auf einem Kreisbogen. Dies wird durch den Zusammenhang $F_\text{L}=F_{\text{Z}}$ beschrieben:
$$
\begin{aligned}
    F_\text{L}&=F_{\text{Z}}\\
    q\cdot v\cdot B&=\dfrac{m\cdot v^2}{r}\\\\
    r&=\dfrac{m\cdot v}{e\cdot B}
\end{aligned}
$$

Da die Geschwindigkeit $v$ und die Größe der Flussdichte $B$ bekannt sind, hängt der Radius der Kreisbahn von der Masse $m$ des Teilchens ab. Somit bewegen sich Teilchen verschiedener Massen auf verschieden Kreisbahnen. Dies wird genutzt, um Teilchen eines Ionenstrahls zu trennen.

#### Franck-Hertz-Versuch
##### Aufbau
![Franck-Hertz-Versuch](img/Franck-Hetz-Versuch.png){ height=250px }

##### Bestandteile

* $\text{U}_\text{H}$ **Heizspannung**:
  
  Die Heizspannung hat die Funktion, mittels Glühelektrischem Effekt freie Elektronen in der Röhre zur Verfügung zu stellen.

* $\text{U}_\text{B}$ **Beschleunigungsspannung**:

  Die Beschleunigungsspannung hat die Funktion, zwischen Kathode und Gitter ein elektrisches Feld zur Verfügung zu stellen, in dem Elektronen beschleunigt werden.

* $\text{U}_\text{G}$ **Gegenspannung**:

  Die Gegenspannung sorgt dafür, dass zwischen Gitter und Anode ein Gegenfeld erzeugt wird. Dadurch wird erreicht, dass nur Elektronen, die eine Mindestenergie beim Durchfliegen des  Gitters haben, die Anode erreichen und vom Strommesser gemessen werden.

* $\text{I}_\text{A}$ **Strommesser**:
  
  Das Strommessgerät misst den Anodenstrom und damit die Anzahl der Elektronen je Zeiteinheit, die die Anode erreicht.

##### Bewegung eines Elektrons in der Röhre

Elektronen treten aufgrund des [Glühelektrischen Effekts](#glühelektrischer-effekt) aus der Kathode aus. Sie werden im elektrischen Feld zwischen Kathode und Gitter beschleunigt. Dabei kommt es zu Zusammenstößen mit den Hg-Atomen (Quecksilber-Atomen). Aufgrund ihrer Trägheit durchfliegen die meisten Elektronen das Gitter und gelangen in das Gegenfeld. Nur Elektronen, die im Bereich des Gitters genügend Energie besitzen, können das Gegenfeld überwinden und die Anode erreichen. Sie fließen über die Anode ab und bilden den Anodenstrom $\text{I}_\text{A}$. Ansonsten kehren sie im Gegenfeld um und fließen über das Gitter ab.

So bildet sich ein Minimum im Messschrieb, wenn sich eine Anregungszone direkt vor dem Gitter befindet, da die Elektronen von dieser Anregungszone bis zum Gitter nicht ausreichend beschleunigt werden, um das Gegenfeld zu überwinden.

##### Diagramm

![Franck-Hertz-Versuch Messchrieb](img/franck-hertz-versuch_messschrieb.jpeg){ height=250px }

**Hinweis:** Es werden die Maxima genutzt um die Anregungsenergie festzustellen, da diese gegenüber den Minima leichter zu Identifizieren sind. Dies ist möglich, da die Maxima und Minima ungefähr den gleichen Abstand haben.

##### Stöße der Elektronen mit den Hg-Atomen

Die Elektronen stoßen ständig mit Hg-Atomen zusammen. Haben sie eine Energie bis zu 4,8eV, so sind die Zusammenstöße elastisch und die Elektronen behalten ihre Energie. Haben die Elektronen genügend Energie (bei Quecksilber ca. 4,8eV) so ist der Stoß unelastisch und die Elektronen geben ihre Energie an die Hg-Atome ab. Anschließend werden die Elektronen erneut beschleunigt.

Das Hg-Atom hat die Energie aufgenommen und befindet sich nun in einem angeregten Zustand. Dieses möchte in sein Grundzustand zurück (Abregung) und gibt die Energiedifferenz in Form eines Photons ab. Die Energiedifferenz legt die Frequenz/Wellenlänge des Photons fest:

$$
\begin{aligned}
    \text{E}_\text{Ph}&=h\cdot f \\\\
    f&=\dfrac{\text{E}}{h}
\end{aligned}
$$

##### Ergebnisse des Franck-Hertz-Versuchs

* Elektronen können bei Stößen mit Atomen nur ganz bestimmte Energieportionen abgeben
* Die Größe der Energie ist abhängig von der Atomsorte/Element
* Elektronen einer Sorte können nur diskrete Anregungszustände einnehmen
* Die möglichen Energien werden in Energieniveauschema/Termschema dargestellt

#### Röntgenröhre
##### Aufbau

![Röntgenröhre](img/roentgenroehre.jpeg){ height=250px }

##### Bestandteile

* $\text{U}_\text{H}$ **Heizspannung**:

    Die Heizspannung hat die Funktion, mittels Glühelektrischem Effekt freie Elektronen in der Röhre zur Verfügung zu stellen.

* $\text{U}_\text{B}$ **Beschleunigungsspannung**:

    Die Beschleunigungsspannung hat die Funktion, zwischen Kathode und Anode ein elektrisches Feld zur Verfügung zu stellen, in dem Elektronen beschleunigt werden. 

* **Anode**:

    Die Anode ist das Ziel der beschleunigten Elektronen, In ihr wird die Röntgenstrahlung ausgelöst.

##### Durchführung

Bei der Röntgenröhre werden Elektronen mit kinetischer Energie genutzt, um Photonen zu erzeugen. Die Energie der Elektronen wird durch Abbremsung ganz oder teilweise (in Stufen) in Photonen umgesetzt. Hierbei entsteht die sogenannte [Bremsstrahlung](#bremsstrahlung)

#### Bremsstrahlung
Die Bremsstrahlung (auch Röntgenstrahlung) entsteht bei der Erzeugung in der [Röntgenröhre](#röntgenröhre).

##### Entstehung der Bremsstrahlung
Die Elektronen werden im elektrischen Feld beschleunigt und nehmen dabei die kinetische Energie
$$\tag*{auf.}\text{E}_\text{kin}=\dfrac{1}{2}m\cdot v^2 = \text{e}\cdot\text{U}_\text{B}$$
Beim Aufprall auf die Anode werden die Elektronen sehr stark abgebremst. Ihre Energie kann dabei ganz oder teilweise auf ein Photon (Röntgenquant) übertragen werden. Das entstehende Spektrum ist kontinuierlich mit einer kürzesten Wellenlänge $\lambda_0$ bzw. $\lambda_\text{min}$ (max. Photonenenergie).

$$\text{E}_\text{Ph}=h\cdot f=\dfrac{h\cdot c}{\lambda}$$

$$\text{E}_\text{kin}= \text{e}\cdot\text{U}_\text{B}$$

Energieerhaltungssatz EES
$$\dfrac{h\cdot c}{\lambda}=\text{e}\cdot\text{U}_\text{B}$$

##### Diagramm
![Bremsstrahlung](img/bremsstrahlung.png){ height=250px }

**Hinweis:** In dieser Grafik ist auf der Querachse die Wellenlänge aufgetragen, dies ist aber nicht immer der Fall, da manchmal auch die Frequenz aufgetragen ist!

##### Messung des Spektrums

Zur Messung wird folgender Aufbau genutzt, das Spektrum mit der Bragg-Reflexion an einem Kristall zu messen:

#### Beugung am Gitter

##### Aufbau

#### Michelson-Interferometer
#### He-Ne-Laser
####
## Kernphysik