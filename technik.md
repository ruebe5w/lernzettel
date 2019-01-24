todo:
+ Java
  + [x] Datentypen
  + [x] Klassen
  + [x] Methoden
  + [ ] Schleifen
  + [ ] Threads
  + [ ] Frequenz zu Periodendauer

- [Technik](#technik)
  - [Netzwerktechnik](#netzwerktechnik)
  - [Steuerungtechnik](#steuerungtechnik)
  - [Java](#java)
    - [Datentypen](#datentypen)
      - [einfache Datentypen](#einfache-datentypen)
      - [komplexe Datentype](#komplexe-datentype)
    - [Klassen](#klassen)
      - [Deklaration](#deklaration)
      - [Konstruktor](#konstruktor)
      - [Beispiel](#beispiel)
    - [Methoden](#methoden)
      - [Deklaration](#deklaration-1)
      - [Beispiel](#beispiel-1)
    - [Schleifen](#schleifen)
      - [for-Schleife](#for-schleife)
      - [while-schleife](#while-schleife)
    - [Verzweigungen](#verzweigungen)
    - [Frequenz zu Periodendauer](#frequenz-zu-periodendauer)


# Technik
## Netzwerktechnik
## Steuerungtechnik
## Java
### Datentypen
#### einfache Datentypen
| Name    | Größe           | Wertebereich                                                      |
| :------ | :-------------- | :---------------------------------------------------------------- |
| boolean | 1 Byte = 8 Bit  | **true**, **false**                                               |
| char    | 2 Byte = 16 Bit | **-128** bis **+127**                                             |
| int     | 4 Byte = 32 Bit | **-2.147.483.648** bis **+2.147.483.647**                         |
| long    | 8 Byte = 64 Bit | **-9.223.372.036.854.775.808** bis **+9.223.372.036.854.775.807** |
| float   | 4 Byte = 32 Bit | **-10$^{38}$** bis **+10$^{38}$**                                 |

#### komplexe Datentype
| Name       | Größe                               |
| :--------- | :---------------------------------- |
| String     | beliebig lange Zeichenketten        |
| BigInteger | beliebig große ganz Zahlen          |
| Color      | 16.777.216 Farben im RGB-Farbmodell |
| File       | beliebige Dateien                   |

### Klassen
#### Deklaration
```java
public class KlassenName {
    ...
}
```

#### Konstruktor
Der Konstruktor ist eine Methode der Klasse ohne einen Rückgabewert. Der Konstruktor einer Klasse wird aufgerufen sobald ein neues Objekt einer Klasse erzeugt wird. Die Methode muss mit dem Klassennamen deklariert.

```java
public KlassenName(datenTyp parameterName) {
    ...
}
```

#### Beispiel
```java
public class Schueler {
    private Name;
    private Vorname;

    public Schueler(String Name, String Vorname) {
        this.Name = Name;
        this.Vorname = Vorname;
    }

    public void setName(String Name) {
        this.Name = Name;
    }

    public String getName() {
        return Name;
    }
}
```

### Methoden
#### Deklaration
Eine Methode wird deklariert indem zuerst ihr Umfange/ihre Reichweite angegeben wird. Mögliche Werte sind: `public` oder `private`. 
> `public` ermöglicht es außerhalb der Klasse auf die Methode zuzugreifen und sie ausführen zu können.

> `public` limitiert den Zugriff auf nur in der eigenen Klasse.

Weiterhin muss angegeben werden, ob eine Methode `static` oder dynamisch ist. Bei einer statischen Methode muss bei der Deklaration zusaätzlich `static` nach der Reichweite angegeben werden. Ist die dynamisch, wird dies einfach weggelassen und es folgt der Rückgabewert.
> dynamische Methoden erfordern ein Objekt der Klasse um verwendet werden zu können.
> ```java
>   KlassenName referenz = new KlassenName();
>   referenz.methodenName();
> ```

> `static` Methoden können aufgerufen werden, ohne dass ein Objekt der Klasse vorhanden ist.
> ```java
>   referenz.methodenName();
> ```

Danach folgt der Rückgabewert. Hier muss der Rückgabewert der Klasse angeben werden. Dieser kann z.B. ein *Integer*, ein *String* oder auch ein eigener Datentyp sein. Wenn eine Methode ein Rückgabewert hat, muss dieser mit `return` im Methodenkörper zurückgegen werden, hat sie keinen kann dies weggelassen werden, jedoch muss in in der Deklaration `void` als Datentyp angegeben werden.

Nun folgt der Methodenname, welcher konventioneller Weise in 'camelCase' geschrieben wird, das bedeutet der Anfangsbuchstabe wird kleingeschrieben und jedes neue folgende Wort wird mit einem Großbuchstaben begonnen. Beispiel `methodenName`. Zusätzlich sollte der Name einer Methode ihre Aufgabe/Funktion möglichst genau beschreiben, wie z.B. `getVar` und `setVar`.

Parameter welche beim Aufruf der Methode an diese übergeben werden soll, werden nach dem Methodennamen in Klammer '()' führend mit ihrem Datentyp angegeben. Im folgenden Beispiel wird zum Beispiel ein Parameter mit dem Datentype *String* an die Methode weitergegeben und kann ab dann im Methodenkörper von nun mit der Referenu 'Name' drauf zugegriffen werden.
> ```java
>   public void setName(String Name) {}
> ```

#### Beispiel
dynamische, öffentliche Methode ohne Rückgabewert und mit Parameter
```java
public void setName(String Name) {
    this.Name = Name;
}
```

statische, private Methode mit Rückgabewert des Types *Integer* und ohne Parameter
```java
private static int getTime() {
    return 1548341291;
}
```

### Schleifen
#### for-Schleife
Eine **for-Schleife** wird verwendet wenn man z.B. eine bestimmte Anzahl an Durchgängen ausführen möchte.
```java
for (int i=0; i<50; i++) {
    ...
}
```

#### while-schleife

```java
while (time < 4000) {
    ...
}
```

### Verzweigungen
### Frequenz zu Periodendauer
Im Unterricht ist es öfters vorgekommen, dass die Frequenz zur Verfügung steht und man nun mit dieser Frequenz z.B. eine LED blinken zu lassen.

Um die Periodendauer zu berechnen können wir folgende Formel benutzen:

> $f$ = $\frac{1}{T}$ bzw. $T$ = $\frac{1}{f}$

Beispiel: geg.: $f$=20Hz
> $T$ = $\frac{1}{f}$ = $\frac{1}{20Hz}$ = $\frac{1}{20\frac{1}{s}}$

Mit dem Kehrwert multiplizieren;
> $T$ = $\frac{1}{20}$s = 0,050s = 50ms

Um die Aufgabe zu verfollständigen, muss man diese Zeit noch durch 2 dividieren, da wir bis jetzt nur die Dauer eines ganzen Vorgangs berechnet haben. Möchten wir aber die LED mit einer Frequenz von 20Hz blinken lassen wollen, ist zwischen den dem Ein- und Ausschalten der LED eine verzögerung von 25ms nötig.

```java
while (true) {
    Tools.delay(25);
    LampSimulator.setOn();
    Tools.delay(25);
    LampSimulator.setOff();
}
```