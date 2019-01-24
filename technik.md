todo:
+ Java
  + Threads
+ Steuerungstechnik
  + Zuordnungstabelle
  + Datenblatt
  + Drahtbruchsicherheit
  + Schrittkette
+ Netzwerktechnik
  + Schwachstellen
  + Verschlüsselung
  + Datensicherheit
  + Firma Daten sichern Konzepte
  + Hardware (Raid)
  + räumlich getrennte Sicherung
  + ipv4
  + Subnetz Standard Gateway
  + Subnetze Bilden
  + Router, Switch
  + Firewall
  + DHCP
  + Feste IP bei Servern
  + MAC Adresse + freigeben
  + DNS

- [Technik](#technik)
  - [Netzwerktechnik](#netzwerktechnik)
  - [Steuerungstechnik](#steuerungstechnik)
    - [Drahtbruchsicherheit](#drahtbruchsicherheit)
  - [Java](#java)
    - [Quick-Links](#quick-links)
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
    - [Verzweigungen](#verzweigungen)
      - [if else](#if-else)
      - [if else-if](#if-else-if)
    - [Schleifen](#schleifen)
      - [for-Schleife](#for-schleife)
      - [while-schleife](#while-schleife)
    - [Netzwerk](#netzwerk)
      - [Multicast-Sender](#multicast-sender)
      - [Multicast-Receiver](#multicast-receiver)
      - [Simple-Server](#simple-server)
      - [Simple-Client](#simple-client)
    - [Threads](#threads)
    - [Frequenz zu Periodendauer](#frequenz-zu-periodendauer)

# Technik
## Netzwerktechnik
## Steuerungstechnik
### Drahtbruchsicherheit
## Java
### Quick-Links
* [Vergleichsoperatoren](#if-else)
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
Eine Methode wird deklariert indem zuerst ihr Umfang/ihre Reichweite angegeben wird. Mögliche Werte sind: `public` oder `private`.
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
```java
public void setName(String Name) {}
```

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

### Verzweigungen
#### if else
Bei einer einfachen Verzweigung wird die Bedingung überprüft. Wenn diese erfüllt ist, wird der folgende Code-Block ausgeführt, wenn nicht, dann springt das Programm in den Code-Block, welcher zu `else` gehört.
```java
if(counter > 255) {
    counter == 255
} else {
    counter++;
}
```
Bedingung lassen sich mit den folgenden Operatoren bilden

| Operator | Bedeutung      |
| :------: | :------------- |
|    ==    | ist gleich     |
|    !=    | ungleich       |
|    <     | kleiner als    |
|    >     | größer als     |
|    <=    | kleiner gleich |
|    >=    | größer gleich  |
**Hinweis:** Diese Operatoren gelten nur für Zahlen

> Die Gleichheit von *String*-Objekten wird über die Methode `equals` überprüft

```java
if(String1.equals("Hallo")) {
    ...
}
```
Bedingungen lassen sich zusätzlich durch **logische Operatoren** kombinieren.

| Operator | Bedeutung      |
| :------: | :------------- |
|    &&    | logisches und  |
|   \|\|   | logisches oder |

```java
if(zahl > 50 && zahl < 100){
    ...
}
```

#### if else-if

Falls weitere Verzweigungen benötigt werden, wird die oben erläuterte Verzweigung um ein `else if` und einer weiteren Bedingung erweitert.

```java
if(Bedingung1) {
    ...
} else if (Bedingung2) {
    ...
} else {
    ...
}
```

### Schleifen
#### for-Schleife
Eine **for-Schleife** wird verwendet wenn man z.B. eine bestimmte Anzahl an Durchgängen ausführen möchte. In diesem Falle zählt die die Schleife von 0 bis 49. Als erstes wird ein *Integer* deklariert, definiert und auf den gewünschten Startwert gesetzt(`int i=0`). Auf diese kann man danach nur im Schleifenkörper zugreifen. Oft heißt dieser `i`, Ankürzend für 'Index'. Danach folgt die Bedingung, welche die Schleife begrenzt(`i<50`). Als letztes wird der laufende Wert von `i` erhöht. Dies kann wie in diesem Falle um den Wert 1(`i++`) geschehen, aber z.B. auch bei jeden Durchgang um jeden beliebigen Wert erhöht werden.
```java
for (int i=0; i<50; i++) {
    ...
}
```

#### while-schleife
Eine **while-schleife** wird verwendet, wenn man einen bestimmten Block an Code ausführen solange eine Bedingung wahr ist. Im Gegensatz zur **for-schleife** wird dieser Wert jedoch nicht automatisch bei jeden Durchlauf erhöht.
```java
while (time < 4000) {
    ...
}
```
Eine besondere Version der **while-Schleife** ist die Endlos-Schleife, bei der der Wert der Bedingung auf den boolschen Wert `true` gesetzt wird. Somit ist die Bedingung immer erfüllt und die Schleife wird endlos lange ausgeführt.
```java
while (true) {
    ...
}
```

### Netzwerk
#### Multicast-Sender
Objekte dieser Klasse sind Mitglied in einer Multicast-Gruppe und können Informationen über ein Netzwerk gleichzeitig an alle Mitglieder der Gruppe versenden.
```java
MulticastSender mcs = new MulticastSender(ip, port);
```
> Die Adresse des MulticastSenders muss zwischen 224.0.0.0 und 239.255.255.255 liegen.

Methoden:

Mit der Methode `send()` wird der Parameter des Datentyps *String* an alle Mitglieder der Multicast-Gruppe gesendet.

Mit der Methode `close()` wird die Verbindung geschlossen.
#### Multicast-Receiver
Objekte dieser Klasse sind Mitglied in einer Multicast-Gruppe und können Informationen über ein Netzwerk von den Mitgliedern dieser Gruppe empfangen.
```java
MulticastReceiver mcs = new MulticastReceiver(ip, port);
```
> Die Adresse des MulticastSenders muss zwischen 224.0.0.0 und 239.255.255.255 liegen.

Methoden:

Mit der Methode `receive()` können Informationen vom Netzwerk empfangen werden. Die Methode gibt diese als eine Referenz auf ein Objekt der Klasse *String* zurück.
#### Simple-Server
#### Simple-Client

### Threads


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
    LampSimulator.setOn();
    Tools.delay(25);
    LampSimulator.setOff();
    Tools.delay(25);
}
```