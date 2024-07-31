# Cheat Sheet

## Inhaltsverzeichnis

- [**Variablen und Konstanten**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#variablen-und-konstanten)  
- [**Rechenoperatoren**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#rechenoperatoren)
- [**Grundlegende Datentypen**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#grundlegende-datentypen)
- [**Typumwandlung**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#typumwandlung)
- [**Tupel**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#tupel)
- [**Stringoperationen**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#stringoperationen)
- [**Vergleichs- und Verknüpfungsoperationen**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#vergleichs--und-verknüpfungsoperationen)
- [**Bedingungen und Schleifen**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#bedingungen-und-schleifen)
- [**Funktionen**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#funktionen)
- [**Arrays**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#arrays)
- [**Dictionaries**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#dictionaries)
- [**Sets**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#sets)
- [**Strukturen**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#strukturen)
- [**Klassen**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#klassen)
- [**Enumerationen**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#enumerationen)
- [**Optionals**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#optionals)
- [**Fehlerbehandlung**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#fehlerbehandlung)

## Schlüsselwortverzeichnis

[`var`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#var), [`let`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#let), [`+ - * / %`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#+--*--/-%), [`Int Double String Bool`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#int-double-string-bool), [`as as? as!`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#as-as?-as!), [`tuple`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#tuple), [`String-Verkettung Interpolation`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#string-verkettung-interpolation), [`== != < > <= >= && || !`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#==-!=--<--<=-->-=--&&-||-!), [`if`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#if), [`else`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#else), [`else if`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#else-if), [`for`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#for), [`for-in`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#for-in), [`while`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#while), [`repeat`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#repeat), [`continue`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#continue), [`break`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#break), [`func`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#func), [`return`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#return), [`inout`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#inout), [`method`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#method), [`Statische Elemente`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#statische-elemente), [`_`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#_), [`Komplexe Datentypen als Parameter und Rückgabewert`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#komplexe-datentypen-als-parameter-und-rückgabewert), [`Array`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#array), [`append`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#append), [`remove`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#remove), [`count`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#count), [`isEmpty`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#isempty), [`contains`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#contains), [`map`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#map), [`filter`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#filter), [`reduce`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#reduce), [`Dictionary`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#dictionary), [`keys`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#keys), [`values`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#values), [`Set`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#set), [`struct`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#struct), [`class`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#class), [`inheritance`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#inheritance), [`enum`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#enum), [`optional`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#optional), [`if let`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#if-let), [`guard let`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#guard-let), [`nil coalescing`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#nil-coalescing), [`do-catch`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#do-catch), [`throws`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#throws), [`try`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#try), [`try?`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#try?), [`try!`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#try!), [`defer`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#defer)

---

## Variablen und Konstanten

### `var`
Erstellt eine Variable, die sich ändern kann.

```swift
var alter = 25
alter = 26
print(alter) // Ausgabe: 26
```
---
### `let`
Erstellt eine Konstante, die sich nicht ändern kann.

```swift
let name = "Hans"
// name = "Peter" // Fehler: Cannot assign to value: 'name' is a 'let' constant
print(name) // Ausgabe: Hans
```
---
## Rechenoperatoren

### `+`, `-`, `*`, `/`, `%`
Führt grundlegende mathematische Operationen durch.

```swift
let summe = 5 + 3       // Addition
let differenz = 5 - 3   // Subtraktion
let produkt = 5 * 3     // Multiplikation
let quotient = 6 / 3    // Division
let rest = 5 % 2        // Modulo
print(summe, differenz, produkt, quotient, rest)
// Ausgabe: 8 2 15 2 1
```
---
## Grundlegende Datentypen

### `Int`, `Double`, `String`, `Bool`
Vordefinierte Datentypen in Swift.

```swift
var zahl: Int = 10
var pi: Double = 3.14
var text: String = "Hallo"
var istWahr: Bool = true
print(zahl, pi, text, istWahr)
// Ausgabe: 10 3.14 Hallo true
```
---
## Typumwandlung

### `as`, `as?`, `as!`
Wandelt einen Wert in einen anderen Typ um.

```swift
let zahl: Double = 10.5
let ganzeZahl = Int(zahl)
print(ganzeZahl) // Ausgabe: 10

let optionalZahl: Any = 5
if let umgewandelteZahl = optionalZahl as? Int {
    print(umgewandelteZahl)
}
// Ausgabe: 5
```
---
## Tupel

### `tuple`
Speichert mehrere Werte in einer einzelnen Variablen.

```swift
let person = (name: "Anna", alter: 28)
print(person.name) // Ausgabe: Anna
print(person.alter) // Ausgabe: 28
```
---
## Stringoperationen

### String-Verkettung, -Interpolation
Verkettet Strings und interpoliert Variablen in Strings.

```swift
let vorname = "Hans"
let nachname = "Müller"
let vollerName = vorname + " " + nachname
print(vollerName) // Ausgabe: Hans Müller

let alter = 30
let begruessung = "Hallo, mein Name ist \(vorname) und ich bin \(alter) Jahre alt."
print(begruessung)
// Ausgabe: Hallo, mein Name ist Hans und ich bin 30 Jahre alt.
```
---
## Vergleichs- und Verknüpfungsoperationen

### `==`, `!=`, `<`, `>`, `<=`, `>=`, `&&`, `||`, `!`
Vergleicht Werte und verknüpft logische Ausdrücke.

```swift
let a = 5
let b = 10
print(a == b)  // Ausgabe: false
print(a != b)  // Ausgabe: true
print(a < b)   // Ausgabe: true
print(a > b)   // Ausgabe: false
print(a <= b)  // Ausgabe: true
print(a >= b)  // Ausgabe: false

let x = true
let y = false
print(x && y)  // Ausgabe: false
print(x || y)  // Ausgabe: true
print(!x)      // Ausgabe: false
```
---
## Bedingungen und Schleifen

### `if`
Führt Code aus, wenn eine Bedingung wahr ist.

```swift
let alter = 20
if alter > 18 {
    print("Erwachsener")
}
// Ausgabe: Erwachsener
```
---
### `else`
Führt Code aus, wenn die Bedingung falsch ist.

```swift
let alter = 16
if alter > 18 {
    print("Erwachsener")
} else {
    print("Minderjährig")
}
// Ausgabe: Minderjährig
```
---
### `else if`
Fügt eine zusätzliche Bedingung hinzu.

```swift
let alter = 18
if alter > 18 {
    print("Erwachsener")
} else if alter == 18 {
    print("Gerade erwachsen geworden")
} else {
    print("Minderjährig")
}
// Ausgabe: Gerade erwachsen geworden
```
---
### `for`
Wiederholt Code eine bestimmte Anzahl lang.

```swift
for i in 1...5 {
    print(i)
}
// Ausgabe: 1
//         2
//         3
//         4
//         5
```
---
### `for-in`
Iteriert über eine Sequenz von Elementen.

```swift
let namen = ["Anna", "Bernd", "Clara"]
for name in namen {
    print("Hallo, \(name)!")
}
// Ausgabe: Hallo, Anna!
//         Hallo, Bernd!
//         Hallo, Clara!
```
---
### `while`
Wiederholt Code, solange eine Bedingung wahr ist.

```swift
var zaehler = 0
while zaehler < 5 {
    print(zaehler)
    zaehler += 1
}
// Ausgabe: 0
//         1
//         2
//         3
//         4
```
---
### `repeat`
Wiederholt Code mindestens einmal, dann solange eine Bedingung wahr ist.

```swift
var zaehler = 0
repeat {
    print(zaehler)
    zaehler += 1
} while zaehler < 5
// Ausgabe: 0
//         1
//         2
//         3
//         4
```
---
### `continue`
Überspringt die aktuelle Iteration und fährt mit der nächsten fort.

```swift
for i in 1...5 {
    if i == 3 {
        continue
    }
    print(i)
}
// Ausgabe: 1
//         2
//         4
//         5
```
---
### `break`
Beendet die Schleife vorzeitig.

```swift
for i in 1...5 {
    if i == 3 {
        break
    }
    print(i)
}
// Ausgabe: 1
//         2
```
---
## Funktionen

### `func`
Erstellt eine Funktion.

```swift
func begruessen(name: String) {
    print("Hallo, \(name)!")
}

begruessen(name: "Anna")
// Ausgabe: Hallo, Anna!
```
---
### `return`
Gibt einen Wert aus einer Funktion zurück.

```swift
func addiere(a: Int, b: Int) -> Int {
    return a + b
}

let summe = addiere(a: 5, b: 3)
print(summe) // Ausgabe: 8
```
---
### Parameter
Eine Eingabe, die eine Funktion benötigt.

```swift
func begruessen(name: String) {
    print("Hallo, \(name)!")
}

begruessen(name: "Anna")
// Hier ist "name" der Parameter und "Anna" das Argument.
```
---
### Argument
Der tatsächliche Wert, der beim Aufruf der Funktion übergeben wird.

```swift
begruessen(name: "Bernd")
// Hier ist "Bernd" das Argument.
```
---
### `inout`
Erlaubt es, dass ein Parameter innerhalb der Funktion geändert und zurückgegeben wird.

```swift
func verdoppeln(zahl: inout Int) {
    zahl *= 2
}

var wert = 10
verdoppeln(zahl: &wert)
print(wert) // Ausgabe: 20
```
---
### Methoden

### `method`
Eine Funktion innerhalb einer Klasse oder Struktur.

```swift
class Person {
    var name: String
    init(name: String) {
        self.name = name
    }
    func begruessen() {
        print("Hallo, mein Name ist \(name).")
    }
}

let person = Person(name: "Hans")
person.begruessen() // Ausgabe: Hallo, mein Name ist Hans.
```
---
### Statische Elemente
Definiert Eigenschaften oder Methoden, die zur Klasse statt zur Instanz gehören.

```swift
class Mathe {
    static func addiere(a: Int, b: Int) -> Int {
        return a + b
    }
}

let summe = Mathe.addiere(a: 5, b: 3)
print(summe) // Ausgabe: 8
```
---
### Fortgeschrittene Funktionen

### `_`
Ignoriert Parameterbezeichner.

```swift
func druckeNachricht(_ nachricht: String) {
    print(nachricht)
}

druckeNachricht("Hallo, Welt!") // Ausgabe: Hallo, Welt!
```
---
### Komplexe Datentypen als Parameter und Rückgabewert

```swift
func verbinde(strings: [String]) -> String {
    return strings.joined(separator: ", ")
}

let namen = ["Anna", "Bernd", "Clara"]
let result = verbinde(strings: namen)
print(result) // Ausgabe: Anna, Bernd, Clara


```
---
## Arrays

### `Array`
Eine geordnete Sammlung von Werten.

```swift
var zahlen = [1, 2, 3, 4, 5]
zahlen.append(6)
zahlen.remove(at: 0)
print(zahlen) // Ausgabe: [2, 3, 4, 5, 6]
```
---
### Methoden für Arrays

### `append`
Fügt ein Element an das Ende eines Arrays hinzu.

```swift
var zahlen = [1, 2, 3]
zahlen.append(4)
print(zahlen) // Ausgabe: [1, 2, 3, 4]
```
---
### `remove`
Entfernt ein Element an einer bestimmten Position im Array.

```swift
var zahlen = [1, 2, 3, 4]
zahlen.remove(at: 1)
print(zahlen) // Ausgabe: [1, 3, 4]
```
---
### `count`
Gibt die Anzahl der Elemente im Array zurück.

```swift
let zahlen = [1, 2, 3, 4]
print(zahlen.count) // Ausgabe: 4
```
---
### `isEmpty`
Überprüft, ob das Array leer ist.

```swift
let zahlen: [Int] = []
print(zahlen.isEmpty) // Ausgabe: true
```
---
### `contains`
Überprüft, ob ein bestimmtes Element im Array vorhanden ist.

```swift
let zahlen = [1, 2, 3, 4]
print(zahlen.contains(3)) // Ausgabe: true
```
---
### `map`
Wendet eine Funktion auf jedes Element des Arrays an und gibt ein neues Array zurück.

```swift
let zahlen = [1, 2, 3, 4]
let verdoppelt = zahlen.map { $0 * 2 }
print(verdoppelt) // Ausgabe: [2, 4, 6, 8]
```
---
### `filter`
Filtert Elemente eines Arrays basierend auf einer Bedingung.

```swift
let zahlen = [1, 2, 3, 4]
let gerade = zahlen.filter { $0 % 2 == 0 }
print(gerade) // Ausgabe: [2, 4]
```
---
### `reduce`
Kombiniert die Elemente eines Arrays zu einem einzelnen Wert.

```swift
let zahlen = [1, 2, 3, 4]
let summe = zahlen.reduce(0) { $0 + $1 }
print(summe) // Ausgabe: 10
```
---
## Dictionaries

### `Dictionary`
Eine ungeordnete Sammlung von Schlüssel-Wert-Paaren.

```swift
var telefonbuch = ["Anna": "12345", "Bernd": "67890"]
telefonbuch["Clara"] = "11223"
telefonbuch.removeValue(forKey: "Anna")
print(telefonbuch) // Ausgabe: ["Bernd": "67890", "Clara": "11223"]
```
---
### `keys`
Gibt eine Sammlung aller Schlüssel im Dictionary zurück.

```swift
let telefonbuch = ["Anna": "12345", "Bernd": "67890"]
print(Array(telefonbuch.keys)) // Ausgabe: ["Anna", "Bernd"]
```
---
### `values`
Gibt eine Sammlung aller Werte im Dictionary zurück.

```swift
let telefonbuch = ["Anna": "12345", "Bernd": "67890"]
print(Array(telefonbuch.values)) // Ausgabe: ["12345", "67890"]
```
---
### Methoden für Dictionaries

### `isEmpty`
Überprüft, ob das Dictionary leer ist.

```swift
let telefonbuch: [String: String] = [:]
print(telefonbuch.isEmpty) // Ausgabe: true
```
---
### `count`
Gibt die Anzahl der Schlüssel-Wert-Paare im Dictionary zurück.

```swift
let telefonbuch = ["Anna": "12345", "Bernd": "67890"]
print(telefonbuch.count) // Ausgabe: 2
```
---
### `contains`
Überprüft, ob ein bestimmter Schlüssel im Dictionary vorhanden ist.

```swift
let telefonbuch = ["Anna": "12345", "Bernd": "67890"]
print(telefonbuch.keys.contains("Anna")) // Ausgabe: true
```
---
### `remove`
Entfernt ein Schlüssel-Wert-Paar aus dem Dictionary.

```swift
var telefonbuch = ["Anna": "12345", "Bernd": "67890"]
telefonbuch.removeValue(forKey: "Anna")
print(telefonbuch) // Ausgabe: ["Bernd": "67890"]
```
---
### `map`
Wendet eine Funktion auf jedes Schlüssel-Wert-Paar an und gibt ein neues Array von Ergebnissen zurück.

```swift
let telefonbuch = ["Anna": "12345", "Bernd": "67890"]
let ergebnisse = telefonbuch.map { "\($0): \($1)" }
print(ergebnisse) // Ausgabe: ["Anna: 12345", "Bernd: 67890"]
```
---
### `filter`
Filtert Schlüssel-Wert-Paare basierend auf einer Bedingung.

```swift
let telefonbuch = ["Anna": "12345", "Bernd": "67890"]
let gefiltert = telefonbuch.filter { $0.key.contains("n") }
print(gefiltert) // Ausgabe: ["Anna": "12345", "Bernd": "67890"]
```
---
### `reduce`
Kombiniert die Schlüssel-Wert-Paare zu einem einzelnen Wert.

```swift
let telefonbuch = ["Anna": "12345", "Bernd": "67890"]
let ergebnis = telefonbuch.reduce("") { $0 + "\($1.key): \($1.value) " }
print(ergebnis) // Ausgabe: "Anna: 12345 Bernd: 67890 "
```
---
## Sets

### `Set`
Eine ungeordnete Sammlung eindeutiger Werte.

```swift
var obst: Set = ["Apfel", "Banane", "Kirsche"]
obst.insert("Orange")
obst.remove("Banane")
print(obst) // Ausgabe: ["Apfel", "Kirsche", "Orange"]
```
---
### Methoden für Sets

### `contains`
Überprüft, ob ein bestimmtes Element im Set vorhanden ist.

```swift
let obst: Set = ["Apfel", "Banane", "Kirsche"]
print(obst.contains("Apfel")) // Ausgabe: true
```
---
### `count`
Gibt die Anzahl der Elemente im Set zurück.

```swift
let obst: Set = ["Apfel", "Banane", "Kirsche"]
print(obst.count) // Ausgabe: 3
```
---
### `isEmpty`
Überprüft, ob das Set leer ist.

```swift
let obst: Set = []
print(obst.isEmpty) // Ausgabe: true
```
---
### `insert`
Fügt ein Element zum Set hinzu.

```swift
var obst: Set = ["Apfel", "Banane"]
obst.insert("Kirsche")
print(obst) // Ausgabe: ["Apfel", "Banane", "Kirsche"]
```
---
### `remove`
Entfernt ein bestimmtes Element aus dem Set.

```swift
var obst: Set = ["Apfel", "Banane", "Kirsche"]
obst.remove("Banane")
print(obst) // Ausgabe: ["Apfel", "Kirsche"]
```
---
### `map`
Wendet eine Funktion auf jedes Element des Sets an und gibt ein neues Array zurück.

```swift
let obst: Set = ["Apfel", "Banane", "Kirsche"]
let laengen = obst.map { $0.count }
print(laengen) // Ausgabe: [5, 6, 7]
```
---
### `filter`
Filtert Elemente eines Sets basierend auf einer Bedingung.

```swift
let obst: Set = ["Apfel", "Banane", "Kirsche"]
let gefiltert = obst.filter { $0.hasPrefix("B") }
print(gefiltert) // Ausgabe: ["Banane"]
```
---
### `reduce`
Kombiniert die Elemente eines Sets zu einem einzelnen Wert.

```swift
let obst: Set = ["Apfel", "Banane", "Kirsche"]
let ergebnis = obst.reduce("") { $0 + $1 + " " }
print(ergebnis) // Ausgabe: "Apfel Banane Kirsche "
```
---
## Strukturen

### `struct`
Erstellt eine Struktur.

```swift
struct Punkt {
    var x: Int
    var y: Int
}

let p = Punkt(x: 3, y: 4)
print(p.x, p.y) // Ausgabe: 3 4
```
---
## Klassen

### `class`
Erstellt eine Klasse.

```swift
class Person {
    var name: String
    var alter: Int
    
    init(name: String, alter: Int) {
        self.name = name
        self.alter = alter
    }
    
    func beschreibe() {
        print("Mein Name ist \(name) und ich bin \(alter) Jahre alt.")
    }
}

let person = Person(name: "Hans", alter: 30)
person.beschreibe() // Ausgabe: Mein Name ist Hans und ich bin 30 Jahre alt.
```
---
### Vererbung

### `inheritance`
Erstellt eine neue Klasse, die von einer bestehenden Klasse erbt.

```swift
class Fahrzeug {
    var geschwindigkeit: Int
    
    init(geschwindigkeit: Int) {
        self.geschwindigkeit = geschwindigkeit
    }
    
    func beschreibe() {
        print("Das Fahrzeug fährt \(geschwindigkeit) km/h.")
    }
}

class Auto: Fahrzeug {
    var marke: String
    
    init(geschwindigkeit: Int, marke: String) {
        self.marke = marke
        super.init(geschwindigkeit: geschwindigkeit)
    }
    
    override func beschreibe() {
        print("Das \(marke) fährt \(geschwindigkeit) km/h.")
    }
}

let auto = Auto(geschwindigkeit: 120, marke: "BMW")
auto.beschreibe() // Ausgabe: Das BMW fährt 120 km/h.
```
---
## Enumerationen

### `enum`
Erstellt eine Enumeration.

```swift
enum Wochentag {
    case montag, dienstag, mittwoch, donnerstag, freitag, samstag, sonntag
}

let heute = Wochentag.mittwoch
print(heute) // Ausgabe: mittwoch
```
---
## Optionals

### `optional`
Erlaubt das Vorhandensein von `nil` für eine Variable.

```swift
var name: String? = "Hans"
print(name) // Ausgabe: Optional("Hans")

name = nil
print(name) // Ausgabe: nil
```
---
### `if let`
Entpackt sicher ein Optional.

```swift
var name: String? = "Hans"
if let entpackterName = name {
    print("Hallo, \(entpackterName)!")
} else {
    print("Kein Name vorhanden.")
}
// Ausgabe: Hallo, Hans!
```
---
### `guard let`
Entpackt sicher ein Optional, bricht bei `nil` aus der aktuellen Funktion aus.

```swift
func begruessen(optionalName: String?) {
    guard let name = optionalName else {
        print("Kein Name vorhanden.")
        return
    }
    print("Hallo, \(name)!")
}

begruessen(optionalName: "Anna") // Ausgabe: Hallo, Anna!
begruessen(optionalName: nil)    // Ausgabe: Kein Name vorhanden.
```
---
### `nil coalescing`
Setzt einen Standardwert, wenn ein Optional `nil` ist.

```swift
var name: String? = nil
let begruessung = "Hallo, \(name ?? "Unbekannter")!"
print(begruessung) // Ausgabe: Hallo, Unbekannter!
```
---
## Fehlerbehandlung

### `do-catch`
Fängt Fehler ab und behandelt sie.

```swift
enum Fehler: Error {
    case ungültigeEingabe
}

func teste(zahl: Int) throws {
    if zahl < 0 {
        throw Fehler.ungültigeEingabe
    }
    print("Zahl ist positiv.")
}

do {
    try teste(zahl: -1)
} catch {
    print("Fehler: Ungültige Eingabe.")
}
// Ausgabe: Fehler: Ungültige Eingabe.
```
---
### `throws`
Deklariert eine Funktion, die einen Fehler werfen kann.

```swift
func teste(zahl: Int) throws {
    if zahl < 0 {
        throw Fehler.ungültigeEingabe
    }
    print("Zahl ist positiv.")
}
```
---
### `try`
Verwendet eine Funktion, die einen Fehler werfen kann.

```swift
do {
    try teste(zahl: 1)
} catch {
    print("Fehler: Ungültige Eingabe.")
}
// Ausgabe: Zahl ist positiv.
```
---
### `try?`
Führt eine Funktion aus und gibt `nil` zurück, wenn ein Fehler auftritt.

```swift
let ergebnis = try? teste(zahl: -1)
print(ergebnis) // Ausgabe: nil
```
---
### `try!`
Führt eine Funktion aus und stürzt ab, wenn ein Fehler auftritt.

```swift
let ergebnis = try! teste(zahl: 1)
// Ausgabe: Zahl ist positiv.
```
---
### `defer`
Verzögert die Ausführung eines Codes bis zum Ende des aktuellen Blocks.

```swift
func begruessung() {
    defer {
        print("Auf Wiedersehen!")
    }
    print("Hallo!")
}

begruessung()
// Ausgabe: Hallo!
//         Auf Wiedersehen!
```
---
