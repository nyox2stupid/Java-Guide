# Java-Guide
### Java Lernguide

#### 0. 
###Programme: Greenfoot/Eclipse
- **Greenfoot:**
  - Ideal für Anfänger, visuelle Programmierung.
- **Eclipse:**
  - Professionelle Entwicklungsumgebung, umfassende Funktionen.
    
### Seiten:
- **https://www.w3schools.com/**

#### 1. Variablen
```java
int zahl = 5;          // Ganzzahl
double kommazahl = 3.5;// Gleitkommazahl
char zeichen = 'A';    // Zeichen
boolean wahr = true;   // Wahrheitswert
String text = "Hallo"; // Zeichenkette
```

#### 2. Basic Funktionen
```java
System.out.print("Hallo");     // Ausgabe ohne Zeilenumbruch
System.out.println("Welt!");   // Ausgabe mit Zeilenumbruch
int x = 5 + 3;                  // Addition
int y = 5 * 3;                  // Multiplikation
double z = Math.sqrt(25);       // Wurzel berechnen
```

#### 3. Erweiterte Variablen
```java
int[] zahlen = {1, 2, 3, 4};    // Array
String[] namen = new String[3];// Array initialisieren
```

#### 4. Tricks
```java
// Kommentare verbessern Code-Verständnis
int a = 1;
a++;                            // Inkrement
a += 2;                         // Addition und Zuweisung
```

#### 5. Imports
```java
import java.util.Scanner;       // Import für Scanner
Scanner scanner = new Scanner(System.in);
int eingabe = scanner.nextInt();
```

#### 6. Schleifen
```java
for (int i = 0; i < 5; i++) {   // For-Schleife
    System.out.println(i);
}

while (x < 10) {               // While-Schleife
    System.out.println(x);
    x++;
}
```

#### 7. Methoden
```java
void printName(String name) {   // Methode ohne Rückgabewert
    System.out.println("Name: " + name);
}

int addiere(int a, int b) {      // Methode mit Rückgabewert
    return a + b;
}
```

#### 8. Was ist OOP?
- **Objektorientierte Programmierung (OOP):**
  - Prinzipien wie Kapselung, Vererbung, Polymorphie.
  - Klassen erstellen, Objekte instanziieren.
```java
class Auto {
    String marke;
    int baujahr;

    void fahre() {
        System.out.println("Das Auto fährt.");
    }
}

Auto meinAuto = new Auto();
meinAuto.marke = "BMW";
meinAuto.fahre();
```

**Hinweis:** Dieser Guide bietet einen knappen Überblick. Vertiefe dein Wissen durch Tutorials und Praxis. Viel Erfolg beim Lernen von Java!
