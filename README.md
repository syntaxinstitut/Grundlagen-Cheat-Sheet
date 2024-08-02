# <img src="https://github.com/devicons/devicon/blob/master/icons/swift/swift-original.svg" height="24"/> Swift Cheat Sheet

Dieses Cheat Sheet ist eine Sammlung von Swift-Konzepten mit kurzen Erklärungen und Beispielen. Hier kannst du schnell nochmal Themen oder Schlüsselwörter nachschlagen. Das Cheat Sheet beinhaltet alles, was im Modul _**Grundlagen der Programmierung mit Swift**_ gelehrt wird <ins>und noch mehr</ins>. 

Keine Sorge, du musst nicht alles auswendig können, was dieses Cheat Sheet enthält; du muss nur wissen, wie du es nachschlagen kannst.

Nutze das Cheat Sheet jederzeit als Hilfe bei der Lösung der Aufgaben oder beim Programmieren eigener Projekte. Cheat Sheets sind in der Programmierung ein beliebtes und nützliches Mittel und du findest im Internet noch zahlreiche andere Cheat Sheets zu Swift oder einem anderen Programmierthema.

Weitere sehr gute Quellen für Informationen bieten auch wie immer die [offizielle Swift-Dokumentation](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/guidedtour/) und die [offizielle Apple-Dokumentation](https://developer.apple.com/documentation/swift/).

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
- [**Closures**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#closures)
- [**Shorthand**](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#shorthand)

## Schlüsselwortverzeichnis

[`var`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#var), [`let`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#let), [`+ - * / %`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#--------), [`Int Double String Bool`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#int-double-string-bool), [`as as? as!`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#as-as-as), [`tuple`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#tuple), [`"\( )"`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#string-verkettung--interpolation), [`== != < > <= >= && || !`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#--------), [`if`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#if), [`else`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#else), [`else if`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#else-if), [`for`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#for), [`for-in`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#for-in), [`while`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#while), [`repeat`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#repeat), [`continue`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#continue), [`break`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#break), [`func`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#func), [`return`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#return), [`inout`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#inout), [`static`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#statische-elemente), [`_`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#_), [`Array`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#array), [`append`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#append), [`remove`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#remove), [`count`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#count), [`isEmpty`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#isempty), [`contains`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#contains), [`map`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#map), [`filter`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#filter), [`reduce`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#reduce), [`Dictionary`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#dictionary), [`keys`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#keys), [`values`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#values), [`Set`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#set), [`struct`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#struct), [`class`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#class), [`enum`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#enum), [`optional`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#optional), [`if let`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#if-let), [`guard let`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#guard-let),  [`do-catch`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#do-catch), [`throws`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#throws), [`try`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#try), [`try?`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#try-1), [`try!`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#try-2), [`defer`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet/tree/main?tab=readme-ov-file#defer), [`{ }`](https://github.com/syntaxinstitut/Grundlagen-Cheat-Sheet?tab=readme-ov-file#closures)

---

## Variablen und Konstanten

### `var`

Erstellt eine Variable, die sich ändern kann.

```swift
var alter: Int = 25
alter = 26
print(alter) // Ausgabe: 26
```

---

### `let`

Erstellt eine Konstante, die sich nicht ändern kann.

```swift
let name: String = "Hans"
// name = "Peter" // Fehler: Cannot assign to value: 'name' is a 'let' constant
print(name) // Ausgabe: Hans
```

---

## Rechenoperatoren

### `+`, `-`, `*`, `/`, `%`

Führt grundlegende mathematische Operationen durch.

```swift
let summe: Int = 5 + 3       // Addition
let differenz: Int = 5 - 3   // Subtraktion
let produkt: Int = 5 * 3     // Multiplikation
let quotient: Int = 6 / 3    // Division
let rest: Int = 5 % 2        // Modulo
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
let ganzeZahl: Int = Int(zahl)
print(ganzeZahl) // Ausgabe: 10

let optionalZahl: Any = 5
if let umgewandelteZahl: Int = optionalZahl as? Int {
    print(umgewandelteZahl)
}
// Ausgabe: 5
```

---

## Tupel

### `tuple`

Speichert mehrere Werte in einer einzelnen Variablen.

```swift
let person: (name: String, alter: Int) = (name: "Anna", alter: 28)
print(person.name) // Ausgabe: Anna
print(person.alter) // Ausgabe: 28
```

---

## Stringoperationen

### String-Verkettung, -Interpolation

Verkettet Strings und interpoliert Variablen in Strings.

```swift
let vorname: String = "Hans"
let nachname: String = "Müller"
let vollerName: String = vorname + " " + nachname
print(vollerName) // Ausgabe: Hans Müller

let alter: Int = 30
let begruessung: String = "Hallo, mein Name ist \(vorname) und ich bin \(alter) Jahre alt."
print(begruessung)
// Ausgabe: Hallo, mein Name ist Hans und ich bin 30 Jahre alt.
```

---

## Vergleichs- und Verknüpfungsoperationen

### `==`, `!=`, `<`, `>`, `<=`, `>=`, `&&`, `||`, `!`

Vergleicht Werte und verknüpft logische Ausdrücke.

```swift
let a: Int = 5
let b: Int = 10
print(a == b)  // Ausgabe: false
print(a != b)  // Ausgabe: true
print(a < b)   // Ausgabe: true
print(a > b)   // Ausgabe: false
print(a <= b)  // Ausgabe: true
print(a >= b)  // Ausgabe: false

let x: Bool = true
let y: Bool = false
print(x && y)  // Ausgabe: false
print(x || y)  // Ausgabe: true
print(!x)      // Ausgabe: false
```

---

## Bedingungen und Schleifen

### `if`

Führt Code aus, wenn eine Bedingung wahr ist.

```swift
let alter: Int = 20
if alter > 18 {
    print("Erwachsener")
}
// Ausgabe: Erwachsener
```

---

### `else`

Führt Code aus, wenn die Bedingung falsch ist.

```swift
let alter: Int = 16
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
let alter: Int = 18
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
let namen: [String] = ["Anna", "Bernd", "Clara"]
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
var zaehler: Int = 0
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
var zaehler: Int = 0
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

let summe: Int = addiere(a: 5, b: 3)
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

var wert: Int = 10
verdoppeln(zahl: &wert)
print(wert) // Ausgabe: 20
```

---

### Methoden

### func

Eine Funktion innerhalb einer Klasse oder Struktur nennt man Methode.

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

let person: Person = Person(name: "Hans")
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

let summe: Int = Mathe.addiere(a: 5, b: 3)
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

let namen: [String] = ["Anna", "Bernd", "Clara"]
let result: String = verbinde(strings: namen)
print(result) // Ausgabe: Anna, Bernd, Clara
```

---

## Arrays

### `Array`

Eine geordnete Sammlung von Werten.

```swift
var zahlen: [Int] = [1, 2, 3, 4, 5]
zahlen.append(6)
zahlen.remove(at: 0)
print(zahlen) // Ausgabe: [2, 3, 4, 5, 6]
```

---

### Methoden für Arrays

### `append`

Fügt ein Element an das Ende eines Arrays hinzu.

```swift
var zahlen: [Int] = [1, 2, 3]
zahlen.append(4)
print(zahlen) // Ausgabe: [1, 2, 3, 4]
```

---

### `remove`

Entfernt ein Element an einer bestimmten Position im Array.

```swift
var zahlen: [Int] = [1, 2, 3, 4]
zahlen.remove(at: 1)
print(zahlen) // Ausgabe: [1, 3, 4]
```

---

### `count`

Gibt die Anzahl der Elemente im Array zurück.

```swift
let zahlen: [Int] = [1, 2, 3, 4]
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
let zahlen: [Int] = [1, 2, 3, 4]
print(zahlen.contains(3)) // Ausgabe: true
```

---

### `map`

Wendet eine Funktion auf jedes Element des Arrays an und gibt ein neues Array zurück.

```swift
let zahlen: [Int] = [1, 2, 3, 4]
let verdoppelt: [Int] = zahlen.map { $0 * 2 }
print(verdoppelt) // Ausgabe: [2, 4, 6, 8]
```

---

### `filter`

Filtert Elemente eines Arrays basierend auf einer Bedingung.

```swift
let zahlen: [Int] = [1, 2, 3, 4]
let gerade: [Int] = zahlen.filter { $0 % 2 == 0 }
print(gerade) // Ausgabe: [2, 4]
```

---

### `reduce`

Kombiniert die Elemente eines Arrays zu einem einzelnen Wert.

```swift
let zahlen: [Int] = [1, 2, 3, 4]
let summe: Int = zahlen.reduce(0) { $0 + $1 }
print(summe) // Ausgabe: 10
```

---

## Dictionaries

### `Dictionary`

Eine ungeordnete Sammlung von Schlüssel-Wert-Paaren.

```swift
var telefonbuch: [String: String] = ["Anna": "12345", "Bernd": "67890"]
telefonbuch["Clara"] = "11223"
telefonbuch.removeValue(forKey: "Anna")
print(telefonbuch) // Ausgabe: ["Bernd": "67890", "Clara": "11223"]
```

---

### `keys`

Gibt eine Sammlung aller Schlüssel im Dictionary zurück.

```swift
let telefonbuch: [String: String] = ["Anna": "12345", "Bernd": "67890"]
print(Array(telefonbuch.keys)) // Ausgabe: ["Anna", "Bernd"]
```

---

### `values`

Gibt eine Sammlung aller Werte im Dictionary zurück.

```swift
let telefonbuch: [String: String] = ["Anna": "12345", "Bernd": "67890"]
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
let telefonbuch: [String: String] = ["Anna": "12345", "Bernd": "67890"]
print(telefonbuch.count) // Ausgabe: 2
```

---

### `contains`

Überprüft, ob ein bestimmter Schlüssel im Dictionary vorhanden ist.

```swift
let telefonbuch: [String: String] = ["Anna": "12345", "Bernd": "67890"]
print(telefonbuch.keys.contains("Anna")) // Ausgabe: true
```

---

### `remove`

Entfernt ein Schlüssel-Wert-Paar aus dem Dictionary.

```swift
var telefonbuch: [String: String] = ["Anna": "12345", "Bernd": "67890"]
telefonbuch.removeValue(forKey: "Anna")
print(telefonbuch) // Ausgabe: ["Bernd": "67890"]
```

---

### `map`

Wendet eine Funktion auf jedes Schlüssel-Wert-Paar an und gibt ein neues Array von Ergebnissen zurück.

```swift
let telefonbuch: [String: String] = ["Anna": "12345", "Bernd": "67890"]
let ergebnisse: [String] = telefonbuch.map { "\($0): \($1)" }
print(ergebnisse) // Ausgabe: ["Anna: 12345", "Bernd: 67890"]
```

---

### `filter`

Filtert Schlüssel-Wert-Paare basierend auf einer Bedingung.

```swift
let telefonbuch: [String: String] = ["Anna": "12345", "Bernd": "67890"]
let gefiltert: [String: String] = telefonbuch.filter { $0.key.contains("n") }
print(gefiltert) // Ausgabe: ["Anna": "12345", "Bernd": "67890"]
```

---

### `reduce`

Kombiniert die Schlüssel-Wert-Paare zu einem einzelnen Wert.

```swift
let telefonbuch: [String: String] = ["Anna": "12345", "Bernd": "67890"]
let ergebnis: String = telefonbuch.reduce("") { $0 + "\($1.key): \($1.value) " }
print(ergebnis) // Ausgabe: "Anna: 12345 Bernd: 67890 "
```

---

## Sets

### `Set`

Eine ungeordnete Sammlung eindeutiger Werte.

```swift
var obst: Set<String> = ["Apfel", "Banane", "Kirsche"]
obst.insert("Orange")
obst.remove("Banane")
print(obst) // Ausgabe: ["Apfel", "Kirsche", "Orange"]
```

---

### Methoden für Sets

### `contains`

Überprüft, ob ein bestimmtes Element im Set vorhanden ist.

```swift
let obst: Set<String> = ["Apfel", "Banane", "Kirsche"]
print(obst.contains("Apfel")) // Ausgabe: true
```

---

### `count`

Gibt die Anzahl der Elemente im Set zurück.

```swift
let obst: Set<String> = ["Apfel", "Banane", "Kirsche"]
print(obst.count) // Ausgabe: 3
```

---

### `isEmpty`

Überprüft, ob das Set leer ist.

```swift
let obst: Set<String> = []
print(obst.isEmpty) // Ausgabe: true
```

---

### `insert`

Fügt ein Element zum Set hinzu.

```swift
var obst: Set<String> = ["Apfel", "Banane"]
obst.insert("Kirsche")
print(obst) // Ausgabe: ["Apfel", "Banane", "Kirsche"]
```

---

### `remove`

Entfernt ein bestimmtes Element aus dem Set.

```swift
var obst: Set<String> = ["Apfel", "Banane", "Kirsche"]
obst.remove("Banane")
print(obst) // Ausgabe: ["Apfel", "Kirsche"]
```

---

### `map`

Wendet eine Funktion auf jedes Element des Sets an und gibt ein neues Array zurück.

```swift
let obst: Set<String> = ["Apfel", "Banane", "Kirsche"]
let laengen: [Int] = obst.map { $0.count }
print(laengen) // Ausgabe: [5, 6, 7]
```

---

### `filter`

Filtert Elemente eines Sets basierend auf einer Bedingung.

```swift
let obst: Set<String> = ["Apfel", "Banane", "Kirsche"]
let gefiltert: Set<String> = obst.filter { $0.hasPrefix("B") }
print(gefiltert) // Ausgabe: ["Banane"]
```

---

### `reduce`

Kombiniert die Elemente eines Sets zu einem einzelnen Wert.

```swift
let obst: Set<String> = ["Apfel", "Banane", "Kirsche"]
let ergebnis: String = obst.reduce("") { $0 + $1 + " " }
print(ergebnis) // Ausgabe: "Apfel Banane Kirsche "
```

---

## Strukturen

#### Werte-Typen

**Kopierverhalten**:

- Bei Werttypen wird eine Kopie des Wertes erstellt, wenn er einer neuen Variablen zugewiesen oder als Parameter an eine
  Funktion übergeben wird.
- Änderungen an der Kopie beeinflussen nicht den ursprünglichen Wert, da beide Variablen eine eigene Kopie enthalten.

### `struct`

Erstellt eine Struktur.

```swift
struct Punkt {
    var x: Int
    var y: Int
}

let p: Punkt = Punkt(x: 3, y: 4)
print(p.x, p.y) // Ausgabe: 3 4
```

---

## Klassen

#### Referenz-Typen

**Kopierverhalten**:

- Bei Referenztypen wird eine Referenz auf denselben Speicherort kopiert, wenn das Objekt einer neuen Variablen
  zugewiesen oder als Parameter an eine Funktion übergeben wird.
- Änderungen an der Referenz beeinflussen das ursprüngliche Objekt, da beide Variablen auf dasselbe Objekt zeigen.

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

let person: Person = Person(name: "Hans", alter: 30)
person.beschreibe() // Ausgabe: Mein Name ist Hans und ich bin 30 Jahre alt.
```

---

### Vererbung

Eine Klasse, die von einer bestehenden Klasse erbt.

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

let auto: Auto = Auto(geschwindigkeit: 120, marke: "BMW")
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

let heute: Wochentag = Wochentag.mittwoch
print(heute) // Ausgabe: mittwoch
```

---

## Optionals

### `Optional`

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
if let entpackterName: String = name {
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
    guard let name: String = optionalName else {
        print("Kein Name vorhanden.")
        return
    }
    print("Hallo, \(name)!")
}

begruessen(optionalName: "Anna") // Ausgabe: Hallo, Anna!
begruessen(optionalName: nil)    // Ausgabe: Kein Name vorhanden.
```

---

### `nil` Standardwert

Setzt einen Standardwert, wenn ein Optional nil ist.

```swift
var name: String? = nil
let begruessung: String = "Hallo, \(name ?? "Unbekannter")!"
print(begruessung) // Ausgabe: Hallo, Unbekannter!
```

---

## Fehlerbehandlung

### `do-catch`

Fängt Fehler ab und behandelt sie.

```swift
enum Fehler: Error {
    case ungueltigeEingabe
}

func teste(zahl: Int) throws {
    if zahl < 0 {
        throw Fehler.ungueltigeEingabe
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
        throw Fehler.ungueltigeEingabe
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

## Closures

### Was sind Closures?

Closures sind eigenständige Blöcke von Funktionalität, die Variablen und Konstanten aus ihrem umgebenden Kontext
erfassen und speichern können. Sie sind flexibel und ermöglichen es, Funktionen als Parameter zu übergeben oder
Codeblöcke als Rückruf (Callback) zu verwenden.

### 1. Closures als Variablen

#### Beispiel 1: Closure ohne Parameter und Rückgabewert

```swift
let simpleClosure: () -> Void = {
    print("Dies ist eine einfache Closure.")
}

simpleClosure()  // Ausgabe: Dies ist eine einfache Closure.
```

#### Beispiel 2: Closure mit Parametern und Rückgabewert

```swift
let addiereZweiZahlen: (Int, Int) -> Int = { (a: Int, b: Int) -> Int in
    return a + b
}

let ergebnis: Int = addiereZweiZahlen(3, 5)
print(ergebnis)  // Ausgabe: 8
```

### 2. Closures als Argumente von Funktionen

#### Beispiel 1: Closure als Argument einer Funktion

```swift
func fuehreOperationAus(_ operation: () -> Void) {
    operation()
}

fuehreOperationAus {
    print("Operation ausgefuehrt.")
}  // Ausgabe: Operation ausgefuehrt.
```

#### Beispiel 2: Closure mit Rückgabewert als Argument einer Funktion

```swift
func fuehreBerechnungAus(_ berechnung: (Int, Int) -> Int) {
    let ergebnis: Int = berechnung(4, 7)
    print("Berechnungsergebnis: \(ergebnis)")
}

fuehreBerechnungAus { (a: Int, b: Int) -> Int in
    return a * b
}  // Ausgabe: Berechnungsergebnis: 28
```

### 3. Closures als Rückgabewerte von Funktionen

#### Beispiel 1: Funktion gibt eine einfache Closure zurück

```swift
func erstelleBegruessung() -> () -> String {
    return {
        return "Hallo, Welt!"
    }
}

let begruessungsClosure: () -> String = erstelleBegruessung()
print(begruessungsClosure())  // Ausgabe: Hallo, Welt!
```

#### Beispiel 2: Funktion gibt eine Closure mit Parametern zurück

```swift
func erstelleAddierer(x: Int) -> (Int) -> Int {
    return { y in
        return x + y
    }
}

let addiereFuenf: (Int) -> Int = erstelleAddierer(x: 5)
print(addiereFuenf(10))  // Ausgabe: 15
```

### 4. Trailing Closures

#### Beispiel 1: Einfache Trailing Closure

```swift
func fuehreOperationMitTrailingClosureAus(abschluss: () -> Void) {
    print("Operation wird ausgefuehrt...")
    abschluss()
}

fuehreOperationMitTrailingClosureAus {
    print("Operation abgeschlossen.")
}  // Ausgabe: Operation wird ausgefuehrt...
   //         Operation abgeschlossen.
```

#### Beispiel 2: Trailing Closure mit Parametern und Rückgabewert

```swift
func berechnungMitTrailingClosure(a: Int, b: Int, berechnung: (Int, Int) -> Int) {
    let ergebnis: Int = berechnung(a, b)
    print("Berechnungsergebnis: \(ergebnis)")
}

berechnungMitTrailingClosure(a: 3, b: 7) { (x, y) in
    return x * y
}  // Ausgabe: Berechnungsergebnis: 21
```

### 5. Werte einfangen

#### Beispiel 1: Closure, die Werte einfängt
```swift
func erstelleInkrementierer() -> () -> Int {
    var gesamt: Int = 0
    let inkrementierer: () -> Int = {
        gesamt += 1
        return gesamt
    }
    return inkrementierer
}

let inkrementieren: () -> Int = erstelleInkrementierer()
print(inkrementieren())  // Ausgabe: 1
print(inkrementieren())  // Ausgabe: 2
```

#### Beispiel 2: Closure, die mehrere Werte einfängt

```swift
func erstelleMultiplikator(multiplier: Int) -> (Int) -> Int {
    return { zahl in
        return zahl * multiplier
    }
}

let multipliziereMitDrei: (Int) -> Int = erstelleMultiplikator(multiplier: 3)
print(multipliziereMitDrei(10))  // Ausgabe: 30
```

---

## Shorthand

### Was ist Shorthand?

Shorthand-Syntax ist eine kompakte Schreibweise für Closures, die dir hilft, Code lesbarer und kürzer zu machen. Sie
vereinfacht den Code, indem sie einige der Standard-Parameter- und Rückgabewert-Deklarationen weglässt. Shorthand
verwendet Platzhalter wie `$0`, `$1`, `$2` usw., um auf die Parameter des Closures zuzugreifen, anstatt ihnen Namen zu
geben.

### Wann nutze ich die Shorthand-Syntax?

1. **Für einfache Operationen in Closures**: Wenn du einfache Operationen durchführst, kannst du Shorthand-Syntax
   verwenden, um den Code kürzer und klarer zu gestalten.

   **Beispiel:**

```swift
   let zahlen: [Int] = [1, 2, 3]
   let verdoppelt: [Int] = zahlen.map { $0 * 2 }
   print(verdoppelt)  // Ausgabe: [2, 4, 6]
   ```
Hier wird `$0` als Platzhalter für das erste Argument des Closures verwendet.

2. **Für Funktionen wie `reduce`, `filter`, und `map`**: Diese Funktionen profitieren von Shorthand-Syntax, da du häufig
   kurze Operationen in Closures durchführst.

   **Beispiel für `reduce`:**
   ```swift
   let zahlen: [Int] = [1, 2, 3]
   let summe: Int = zahlen.reduce(0) { $0 + $1 }
   print(summe)  // Ausgabe: 6
   ```
   `$0` und `$1` repräsentieren die aktuellen und die vorherigen Werte beim Reduzieren der Liste.

3. **Für `contains` und `isEmpty`**: Shorthand-Syntax hilft, wenn du prüfen willst, ob ein Array ein bestimmtes Element
   enthält oder leer ist.

   **Beispiel für `contains`:**

```swift
   let woerter: [String] = ["Apfel", "Banane"]
   let enthaeltBanane: Bool = woerter.contains { $0 == "Banane" }
   print(enthaeltBanane)  // Ausgabe: true
```

`$0` repräsentiert jedes Element im Array während der Überprüfung.

### 1. Shorthand-Syntax für `map`

#### Beispiel 1: Verdopplung von Zahlen

```swift
let zahlen: [Int] = [1, 2, 3, 4, 5]
let verdoppelteZahlen: [Int] = zahlen.map { $0 * 2 }
print(verdoppelteZahlen)  // Ausgabe: [2, 4, 6, 8, 10]
```

#### Beispiel 2: Konvertierung von Ganzzahlen zu Strings

```swift
let zahlen: [Int] = [1, 2, 3, 4, 5]
let zahlenAlsString: [String] = zahlen.map { "\($0)" }
print(zahlenAlsString)  // Ausgabe: ["1", "2", "3", "4", "5"]
```

### 2. Shorthand-Syntax für `filter`

#### Beispiel 1: Filtern von geraden Zahlen

```swift
let zahlen: [Int] = [1, 2, 3, 4, 5, 6]
let geradeZahlen: [Int] = zahlen.filter { $0 % 2 == 0 }
print(geradeZahlen)  // Ausgabe: [2, 4, 6]
```

#### Beispiel 2: Filtern von Zahlen größer als 3

```swift
let zahlen: [Int] = [1, 2, 3, 4, 5, 6]
let grosseZahlen: [Int] = zahlen.filter { $0 > 3 }
print(grosseZahlen)  // Ausgabe: [4, 5, 6]
```

### 3. Shorthand-Syntax für `reduce`

#### Beispiel 1: Summe der Zahlen

```swift
let zahlen: [Int] = [1, 2, 3, 4, 5]
let summe: Int = zahlen.reduce(0) { $0 + $1 }
print(summe)  // Ausgabe: 15
```

#### Beispiel 2: Produkt der Zahlen

```swift
let zahlen: [Int] = [1, 2, 3, 4, 5]
let produkt: Int = zahlen.reduce(1) { $0 * $1 }
print(produkt)  // Ausgabe: 120
```

### 4. Shorthand-Syntax für `contains`

#### Beispiel 1: Überprüfen, ob ein Array eine bestimmte Zahl enthält

```swift
let zahlen: [Int] = [1, 2, 3, 4, 5]
let enthaeltDrei: Bool = zahlen.contains { $0 == 3 }
print(enthaeltDrei)  // Ausgabe: true
```

#### Beispiel 2: Überprüfen, ob ein Array ein bestimmtes Wort enthält

```swift
let woerter: [String] = ["Apfel", "Banane", "Kirsche"]
let enthaeltBanane: Bool = woerter.contains { $0 == "Banane" }
print(enthaeltBanane)  // Ausgabe: true
```

### 5. Shorthand-Syntax für `map` mit mehr Parametern

#### Beispiel 1: Multiplizieren von Zahlen und Addieren von 10

```swift
let zahlen: [Int] = [1, 2, 3]
let ergebnisse: [Int] = zahlen.map { $0 * 2 + 10 }
print(ergebnisse)  // Ausgabe: [12, 14, 16]
```

#### Beispiel 2: Formatieren von Datumswerten zu Strings

```swift
let daten: [Date] = [Date(), Date().addingTimeInterval(86400)] // Heute und morgen
let formatierteDaten: [String] = daten.map { "\($0)" }
print(formatierteDaten)  // Ausgabe: z.B. ["2024-08-01 00:00:00 +0000", "2024-08-02 00:00:00 +0000"]
```

---
