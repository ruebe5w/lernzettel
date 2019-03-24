---
title: "Lernzettel Physik"
date: 2019
listings-disable-line-numbers: true
page-numbers: true
toc: true
toc-title: "Inhalt"
toc-depth: 4
---

# Lernzettel Physik
## Elektrische und Magnetische Felder 
## Schwingungen und Wellen

## Quanten und Atomphysik
### Versuche
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

![Franck-Hertz-Versuch Messschrieb](img/franck-hertz-versuch_messschrieb.jpeg){ height=250px }

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

Bei der Röntgenröhre werden Elektronen mit kinetischer Energie genutzt, um Photonen zu erzeugen. Die Energie der Elektronen wird durch Abbremsung ganz oder teilweise (in Stufen) in Photonen umgesetzt. Hierbei entsteht die sogenannte [Bremsstrahlung](#bremsstrahlung).

#### #Beugung am Gitter
#### Vakuum Photozelle
##### Aufbau
![Vakuum Photozelle](img/Vakuum-Photozelle.png){ height=250px }

Eine Anodenring und eine Kathode werden innerhalb eines Vakuumgefäßes platziert. Zusätzlich wird eine Photonenquelle benötigt, welche monoenergetisch sein sollte und genügend Anzahl von Photonen zur Verfügung stellen muss. Hierzu wird eine Hg-Dampflampe eingesetzt. Mit sehr schmalbandigen Filtern wird jeweils eine Spektrallinie des Hg-Linienspektrums ausgefiltert.

##### Theorie
Treffen Photonen auf eine Metalloberfläche, so können sie ihre Energie an Elektronen im Metall abgeben. Ist die Energie größer als die Austrittsarbeit $W_A$, so können die Elektronen die Metalloberfläche verlassen. Sie lagern sich im Anodenring an, der sich dadurch negativ auf die Spannung U auflädt und ein E-Feld zwischen Anodenring und Kathode aufbaut. Die weitere Aufladung findet solange statt, bis die kinetische Energie $E_{kin}$ der Elektronen beim Austritt aus der Oberfläche nicht mehr ausreicht, um gegen das E-Feld anzukommen. Die Elektronen haben im Anodenring gegenüber der Kathode die potentielle Energie
$$E_{pot}=\text{e}\cdot\text{U}=E_{kin}$$

Eine Energiebilanz liefert: $\text{e}\cdot\text{U}=h\cdot f-W_A$

Werden $f$ und $\text{U}$ gemessen, so sind das Wirkungsquantum $h$ und die Austrittsarbeit $W_A$ des verwendeten Metalls bestimmbar.

##### Diagramm

![Vakuum Photozelle](img/Vakuum-Photozelle-Diagramm.png){ height=250px }



#### Fluoreszenz an Kunststoffplatte
Beobachtungen beim Durchgang und Streuung von Photonen an einer transparenten Kunststoffplatte, die fluoreszierende Farbstoffe enthält.

##### Aufbau
![Fluoreszenz an Kunststoffplatte](img/Fluoreszenz&#32;an&#32;Kunststoffplatte.png){ height=250px }

##### Diagramme
![Fluoreszenz Spektrum](img/Fluoreszenz-Spektrum.png){ height=250px }

##### Deutung
In der Platte nimmt der Leuchtstoff kurzwellige Photonen auf und strahlt mittels [Fluoreszenz](#fluoreszenz) langwellige Photonen ab. Die Emission erfolgt in beliebige Richtungen, so dass die Photonen die Platte auch seitlich verlassen können.


#### Michelson-Interferometer
##### Aufbau
![Michelson-Interferometer](img/Michelson-Interferometer.png){ height=250px }

##### Ablauf
Beim Michelson-Interferometer trifft das Licht der Lichtquelle als erstes auf den halbdurchlässigen Spiegel, an dem es sich aufteilt. Ein Teil der des Licht durchläuft den Spiegel (rot), der andere wird reflektiert (mit Einfallswinkel = Ausfallswinkel)(blau). Beide werden dann jeweils nocheinmal von einem undurchlässigen Spiegel reflektiert und treffen wieder auf den halbdurchlässigen Spiegel, wobei sie ihn wieder so durchlaufen, dass sie in Richtung des Detektors parallel verlaufen. Beide Wellen haben jetzt einen gewissen Weg zurückgelegt. Ist die Differenz beider Wege ein vielfaches der Wellenlänge, kommt es zur [konstruktiven Interferenz](#interferenz).

Das Michelson-Interferometer kann somit genutzt werden, um die Wellenlänge der Lichtquelle zu bestimmen.

Für die Wegdifferenz $\Delta x$ und zwei benachbarten Maxima gilt:

$$\Delta x = \dfrac{\lambda}{2}$$

Dieser Zusammenhang gilt, da bei Verschiebung eines einzelnen Spiegels die Welle den Wegunterschied der beiden Spiegel $\Delta x$ doppelt durchlaufen muss (Hin- und Rückweg). Somit beträgt die Wellenlängenänderung/Gangunterschied $2\cdot \Delta x$.

#### He-Ne-Laser
Laser steht für light amplification by stimulated emission of radiation.
Ein Laser stahlt mithilfe  der [stimulierten Emission](#absorption-und-emission) ein intensives, kaum divergentes Lichtbündel aus.

##### Aufbau
![He-Ne Laser](img/He-Ne-Aufbau.png){ height=250px }

##### Optimierter Aufbau
![He-Ne Laser](img/He-Ne-Aufbau-2.png){ height=250px }

Nach einer ersten spontanen Emission in einem Gasvolumen könnte sich in einem gepumpten Medium die verstärkte Laserwelle (theoretisch) in jede beliebige Richtung ausbreiten. Damit es zu einer sehr großen Verstärkung kommt und um die Richtung der Verstärkung vorzugeben, wird das Gas in einer Kapilarröhre (kleiner Durchmesser, große Länge) zwischen zwei Spiegeln betrieben.

Die Welle bildet sich als stehende Welle zwischen den Spiegeln aus, die Photonen durchlaufen also das Medium mehrfach. Der Abstand der Endspiegel wird auf ein ganzahliges Vielfaches der Wellenlänge eingestellt, so dass konstruktive Interferenz innerhalb des Aufbaus besteht. Er wird daher auch als Resonator bezeichnet. 

Ein Endspiegel ist teildurchlässig (wenige Prozent). Hier wird das Laserlicht zur Nutzung ausgekoppelt. (Auch) Die ausgekoppelte Leistung muss durch das Pumpen ständig nachgeliefert werden.

##### Vorraussetzungen für einen Laser
Da Atome eines Gases am meisten sich im Grundzustand befinden, würde die simple Vorhandenheit eines Gases nicht viel Erfolg in einem Laser bringen. Das liegt daran, dass sich nur ein paar Atome im angeregten Zustand befinden. Wenn diese ihre Energie durch eine spontane Emission über ein Photon abgeben, ist es sehr wahrscheinlich, dass dieses von einem anderen Atom absorbiert (Resonanzabsorption) wird. Das führt dazu das die eingebrachte Energie in beliebige Richtungen abgestrahlt wird.

![Emission bei Normalbesetzung](img/He-Ne-Normalbesetzung.png){ height=250px }

Um eine möglichst hohe Wahrscheinlichkeit für eine stimulierte Emission zu erreichen, muss eine Besetzungsinversion des Gases vorhanden sein (also mehr Atome in einem höheren Energiezustand). Durch die Besetzungsinversion ist es wahrscheinlicher, dass ein Photon eine stimulierte Emission auslöst, als dass es absorbiert wird. Geht nun eine Atom in den Grundzustand, kann das emittierte Photon eine stimulierte Emission in den anderen Atomen auslösen. Da Photonen einer stimulierten Emission mit gleicher Phasenlage und Raumrichtung emittiert werden, findet eine Lichtverstärkung statt.

![Emission bei Besetzungsinversion](img/He-Ne-Besetzungsinversion.png){ height=250px }

Da eine Besetzung normalerweise nicht vorkommt, wird sie künstlich hervorgerufen, in dem das Neongas gepumpt wird.

##### Pumpen des Neongas
Im Helium-Neon Laser wird Neon als aktives (Laser-)Medium und Helium für das Pumpen genutzt, wobei etwa 5 mal so viele Heliumatome wie Neonatome im Gasvolumen vorhanden sind.

Vereinfachte Darstellung:

![He-Ne Laser - Pumpen](img/He-Ne-Pumpen.png){ height=250px }

Durch einen Elektronenstoß werden die Heliumatome auf das Anregungsniveau $E_{2, He}$=20,61eV. Dieses Niveau ist relativ langlebig, was das Helium daran hindert, durch die Emission eines Photons in den Grundzustand gelangen. Wenn nun eines dieser angeregten Heliumatome auf ein Neonatom trifft, kann es seine Energie bei der Atomkollision an das Neonatom abgeben. Diese Energie hebt das Neonatom ein den angeregten Zustand. Das Heliumatom (jetzt wieder im Grundzustand) wird dann recht schnell wieder durch einen Elektronenstoß angeregt.

Da Neon ein metastabiles Energieniveau bei $E_{3, Ne}$ hat, eignet es sich gut für Laseranwendungen. Es bleibt relativ lange in diesem Zustand, was genug Zeit von einem Photon zu einer stimulierten Emission auf das Energieniveau $E_{2, Ne}$ gesenkt zu werden. Von da aus geht das Neonatom recht schnell in den Grundzustand und kann dann wieder bei einem Zusammenstoß mit einem Helium angeregt werden.

### Themen
#### Glühelektrischer Effekt
Der glühelektrische Effekt (auch Richardson- oder Edison-Effekt) ist das Phänomen, dass eine glühende Metall- oder Halbleiteroberfläche Elektronen emittiert (Glühemission). Mit steigender Temperatur nimmt die kinetische Energie der Leitungselektronen im erhitzten Körper so weit zu, dass immer mehr von ihnen imstande sind, die Potenzialschwelle an der Oberfläche (Austrittsarbeit) zu überwinden.

#### #Interferenz
Interferenz beschreibt die Änderung der Amplitude bei der Überlagerung von zwei oder mehreren Wellen.

Bei der destruktiven Interferenz ist die Summe der Amplituden null.
Bei der konstruktiven Interferenz ist die Summe der Amplituden maximal.

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

Zur Messung wird folgender Aufbau genutzt, um das Spektrum mit der [Bragg-Reflexion](#bragg-reflexion) zu messen. Dabei wird ein Kristall mit Röntgenstrahlung bestrahlt. Die am Kristall reflektierte Röntgenstrahlung wird mit Hilfe eines Zählrohrs gemessen:

![Bragg-Reflexion an einem Kristall](img/Drehkristallmethode.jpg){ height=250px }

#### Bragg-Reflexion
In einigen Fällen beobachtet man, dass Wellen an regelmäßigen Strukturen nur unter ganz bestimmten Winkeln besonders stark reflektiert werden. Diese Winkel werden Glanzwinkel genannt, sie sind von der Wellenlänge und dem Strukturabstand abhängig. Die Bedingung wird als Bragg-Bedingung bezeichnet, die Reflexion als Bragg Reflexion. Es ist eine Interferenzerscheinung.

Typisch ist, dass Reflexion nicht nur an der Oberfläche erfolgt, sondern die Welle auch tief in das Material eindringen. Dies ist z.B. bei [Röntgenstrahlung](#bremsstrahlung) der Fall. Bragg Reflexion wird typisch bei Wellenlängen beobachtet/genutzt, die in der gleichen Größenordnung oder kleiner als die Gitterkonstante ist. Als Gitter werden Kristallgitter eingesetzt. Die Atome in Kristallen haben konstante Abstände, im einfachsten Fall in allen Richtungen die gleichen. Die Atome bilden Streuzentren für die einlaufende Welle. Das bedeutet, von jedem Atom geht in alle Richtungen eine Elementarwelle aus. Genzeichnet wurden hier aber nur die Ausbreitungsrichtungen, die für konstruktive Interferenz in Reflexionsrichtung von Bedeutung sind.

![Bragg-Reflexion](img/Bragg-Reflexion.png){ height=250px }

Zwei Bedingungen müssen erfüllt sein:

1. "Normale Reflexion":
   
    An jeder Gitterebene (z.B. Oberfläche des Kristalls) wird an jedem Atom die einlaufende Welle gestreut. FÜr die Richtung Einfallswinkel = Ausfallswinkel entsteht konstruktive Interferenz, da die Welle ausgehend keinen Gangunterschied zur Welle einlaufend hat.

2. Bragg Reflexion:

    Ein Teil der Welle dringt tiefer in den Kristall ein und wird dann an tieferliegenden Ebenen gestreut. Diese Anteile haben den Gangunterschied $2\cdot\Delta s$ gegenüber den gestreuten Anteilen aus der darüberliegenden Ebene. Konstruktive Interferenz kann nur entstehen, wenn dieser Gangunterschied ein vielfaches der Wellenlänge ist.

Treffen beide Bedingungen zu, so entsteht eine kräftige Reflexion in diese Richtung, der Winkel wird daher auch Glanzwinkel genannt. Die zusammengefasste Bedingung wird als Bragg-Beziehung bezeichnet:

$$2\cdot \Delta s=2\cdot a \cdot\sin\beta=\text{k}\cdot\lambda$$

#### Absorption und Emission
Atome besitzen nur diskrete Energieniveaus. Ein sich selbst überlassenes Atom strebt immer den niedrigsten Energiezustand an (Grundzustand). Atome mit einem erhöhten Energie zustand wird als angeregt bezeichnet

Die **Anregung** erfolgt z.B. durch Absorption eines Photons oder durch äußere Stöße z.B. mit Elektronen ([Franck-Hertz-Versuch](#franck-hertz-versuch), Entladungslampen, ...).

Die **Abregung**, also der Übergang zu einem niedrigen Energieniveau wird auch als Zerfall bezeichnet. Er erfolgt unter Emission (Aussendung) eines Photons mit der passenden Energiedifferenz.
Der energetische Zerfall erfolgt entweder (meist innerhalb kurzer Zeit, z.B. 10 s) spontan oder stimuliert. Die stimulierte Emission wird technisch z.B. beim Laser ausgenutzt.

Weil die **Energiezustände** der gebundenen Elektronen **diskret** sind, können auch nur diskrete Energien aufgenommen (Absorption) oder abgegeben (Emission) werden. Als Ausnahme hiervon muss aber die Grenzenergie beachtet werden. Wird mehr als die **Grenzenergie** zugeführt, so wird ein Elektron vollständig vom Atom abgetrennt (freies Elektron, geht ins Kontinuum über). Das Atom wird also **ionisiert**. Das freie Elektron kann (meistens, hier vereinfachte Darstellung) beliebige 'überschüssige Energie' als kinetische Energie haben.

![Emission und Absorption](img/Emission&#32;und&#32;Absorption.png){ height=250px }

Bei der **spontanen Emission** wird das Photon in **zufälliger Raumrichtung** emittiert.

Bei der **stimulierten Emission** sind beide Photonen **phasengleich** und breiten sich in die **selbe Raumrichtung** aus.

#### Fluoreszenz
(Grundlage: [Absorption und Emission](#absorption-und-emission))

Einige Stoffe neigen dazu, von einem höheren angeregten Zustand nicht direkt in den Grundzustand zu zerfallen, sondern zunächst einen weiteren vorhandenen und erlaubten Zustand einzunehmen.

![Fluoreszenz](img/Fluoreszenz.png){ height=250px }

Dazu wird der Rücksprung vom angeregten Energieniveau $E_3$ in den Grundzustand $E_1$ z.B. in zwei Sprünge aufgeteilt. Es kann also grundsätzlich nur energiereiche/kurzwellige Strahlung in energieärmere/langwellige Strahlung umgesetzt werden.

Technisch wird dies für Leuchtstoffe ausgenutzt, z.B. für "weiße LEDs".

#### #Nahfeldinterferenz
## Kernphysik