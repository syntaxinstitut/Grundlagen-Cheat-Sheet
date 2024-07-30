# Cheat Sheet

---

### `var`

Erstellt eine Variable, die sich ändern kann

```swift
var alter = 25
alter = 26
print(alter) // Ausgabe: 26
```
---
### `let`

Erstellt eine Konstante, die sich nicht ändern kann

```swift
let name = "Hans"
// name = "Peter" // Fehler: Cannot assign to value: 'name' is a 'let' constant
print(name) // Ausgabe: Hans
```
---
### `if`

Führt Code aus, wenn eine Bedingung wahr ist

```swift
let alter = 20
if (alter > 18) {
    print("Erwachsener")
}
// Ausgabe: Erwachsener
```
---
### `else`

Führt Code aus, wenn die Bedingung falsch ist

```swift
let alter = 16
if (alter > 18) {
    print("Erwachsener")
} else {
    print("Minderjährig")
}
// Ausgabe: Minderjährig
```
---
### `else if`

Fügt eine zusätzliche Bedingung hinzu

```swift
let alter = 18
if (alter > 18) {
    print("Erwachsener")
} else if (alter == 18) {
    print("Gerade erwachsen geworden")
} else {
    print("Minderjährig")
}
// Ausgabe: Gerade erwachsen geworden
```
---
### `for`

Wiederholt Code eine bestimmte Anzahl lang

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
### `while`

Wiederholt Code, solange eine Bedingung wahr ist

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

Wiederholt Code mindestens einmal, dann solange eine Bedingung wahr ist

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
### `func`

Erstellt eine Funktion

```swift
func begruessen(name: String) {
    print("Hallo, \(name)!")
}

begruessen(name: "Anna")
// Ausgabe: Hallo, Anna!
```
---
### `return`

Gibt einen Wert aus einer Funktion zurück

```swift
func addiere(a: Int, b: Int) -> Int {
    return a + b
}

let summe = addiere(a: 5, b: 3)
print(summe) // Ausgabe: 8
```
---
### `class`

Erstellt eine Klasse

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
### `struct`

Erstellt eine Struktur

```swift
struct Person {
    var name: String
    func begruessen() {
        print("Hallo, mein Name ist \(name).")
    }
}

let person = Person(name: "Hans")
person.begruessen() // Ausgabe: Hallo, mein Name ist Hans.
```
---
### `enum`

Erstellt eine Aufzählung von verwandten Werten

```swift
enum Richtung {
    case norden, süden, osten, westen
}

var richtung = Richtung.norden
switch richtung {
case .norden:
    print("Richtung Norden")
case .süden:
    print("Richtung Süden")
case .osten:
    print("Richtung Osten")
case .westen:
    print("Richtung Westen")
}
// Ausgabe: Richtung Norden
```
---
### `protocol`

Definiert eine Gruppe von Methoden oder Eigenschaften, die andere Typen übernehmen können

```swift
protocol Begruessbar {
    func begruessen()
}

class Person: Begruessbar {
    var name: String
    init(name: String) {
        self.name = name
    }
    func begruessen() {
        print("Hallo, mein Name ist \(name).")
    }
}

let person = Person(name: "Anna")
person.begruessen() // Ausgabe: Hallo, mein Name ist Anna.
```
---
### `extension`

Fügt einer bestehenden Klasse, Struktur oder einem Protokoll neue Fähigkeiten hinzu

```swift
extension String {
    func umgedreht() -> String {
        return String(self.reversed())
    }
}

let original = "Hallo"
let umgekehrt = original.umgedreht()
print(umgekehrt) // Ausgabe: ollaH
```
---
### `guard`

Stellt sicher, dass eine Bedingung wahr ist, sonst verlässt es den aktuellen Block

```swift
func pruefeAlter(alter: Int) {
    guard alter >= 18 else {
        print("Zu jung")
        return
    }
    print("Willkommen")
}

pruefeAlter(alter: 16) // Ausgabe: Zu jung
pruefeAlter(alter: 20) // Ausgabe: Willkommen
```
---
### `defer`

Führt Code aus, wenn der aktuelle Block zu Ende ist

```swift
func einigeFunktion() {
    defer {
        print("Aufräumen")
    }
    print("Funktionskörper")
}

einigeFunktion()
// Ausgabe: Funktionskörper
//         Aufräumen
```
---
### `import`

Fügt ein Modul hinzu

```swift
import Foundation

let datum = Date()
print(datum) // Ausgabe: aktuelles Datum und Uhrzeit
```
---
### `switch`

Wählt einen Codeblock basierend auf einem Wert

```swift
let punkte = 85
switch punkte {
case 90...100:
    print("Ausgezeichnet")
case 80..<90:
    print("Gut")
default:
    print("Verbesserungswürdig")
}
// Ausgabe: Gut
```
---
### `case`

Definiert einen Fall in einer switch-Anweisung

```swift
let wert = 2
switch wert {
case 1:
    print("Eins")
case 2:
    print("Zwei")
default:
    print("Andere")
}
// Ausgabe: Zwei
```
---
### `Parameter`

Eine Eingabe, die eine Funktion benötigt

```swift
func begruessen(name: String) {
    print("Hallo, \(name)!")
}

begruessen(name: "Anna")
// Hier ist "name" der Parameter und "Anna" das Argument
```
---
### `Argument`

Der tatsächliche Wert, der beim Aufruf der Funktion übergeben wird

```swift
begruessen(name: "Bernd")
// Hier ist "Bernd" das Argument
```
---
### `super`

Verweist auf die Superklasse und ruft deren Methode oder Eigenschaft auf

```swift
class Eltern {
    func sprechen() {
        print("Eltern sprechen")
    }
}

class Kind: Eltern {
    override func sprechen() {
        super.sprechen()
        print("Kind spricht")
    }
}

let kind = Kind()
kind.sprechen()
// Ausgabe: Eltern sprechen
//         Kind spricht
```
---
### `override`

Überschreibt eine Methode oder Eigenschaft der Superklasse

```swift
class Eltern {
    func sprechen() {
        print("Eltern sprechen")
    }
}

class Kind: Eltern {
    override func sprechen() {
        print("Kind spricht")
    }
}

let kind = Kind()
kind.sprechen()
// Ausgabe: Kind spricht
```
---
### `final`

Verhindert, dass eine Klasse, Methode oder Eigenschaft überschrieben oder vererbt wird

```swift
final class EndgueltigeKlasse {
    final func sprechen() {
        print("Sprechen")
    }
}

// class Unterklasse: EndgueltigeKlasse {} // Fehler: Inheritance from a final class 'EndgueltigeKlasse'
// class AndereKlasse: EndgueltigeKlasse {
//     override func sprechen() {} // Fehler: Instance method overrides a 'final' instance method
// }
```
---
### `getter`

Definiert eine Methode, die einen Wert zurückgibt

```swift
class Person {
    var name: String
    var begruessung: String {
        get {
            return "Hallo, \(name)"
        }
    }
    init(name: String) {
        self.name = name
    }
}

let person = Person(name: "Anna")
print(person.begruessung) // Ausgabe: Hallo, Anna
```
---
### `setter`

Definiert eine Methode, die einen Wert setzt

```swift
class Person {
    var _alter: Int = 0
    var alter: Int {
        get {
            return _alter
        }
        set(neuesAlter) {
            _alter = neuesAlter
        }
    }
}

let person = Person()
person.alter = 25
print(person.alter) // Ausgabe: 25
```
---
### `didSet`

Führt Code aus, nachdem eine Eigenschaft gesetzt wurde

```swift
class Person {
    var alter: Int = 0 {
        didSet {
            print("Alter geändert zu \(alter)")


        }
    }
}

let person = Person()
person.alter = 25
// Ausgabe: Alter geändert zu 25
```
---
### `is`

Überprüft, ob ein Objekt einen bestimmten Typ hat

```swift
let objekt: Any = "Hallo"
if objekt is String {
    print("Es ist ein String")
}
// Ausgabe: Es ist ein String
```
---
### `as`

Wandelt ein Objekt in einen bestimmten Typ um

```swift
let objekt: Any = "Hallo"
if let string = objekt as? String {
    print(string)
}
// Ausgabe: Hallo
```
