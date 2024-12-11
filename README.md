**Alles Wichtige über Primzahlen und Rechnen mit Qn, ggT und kgV**

---

### **1. Was sind Primzahlen?**
Primzahlen sind natürliche Zahlen, die nur zwei Teiler haben: **1** und **sich selbst**. Beispiele: \( 2, 3, 5, 7, 11, 13, 17, 19, \dots \)

- **Wichtig:** Die Zahl \( 1 \) ist keine Primzahl.
- **Besonderheit:** Die Zahl \( 2 \) ist die einzige gerade Primzahl.

---

### **2. Wie findet man heraus, ob eine Zahl \( n \) eine Primzahl ist?**
1. **Prüfe Teilbarkeit:** Eine Zahl ist keine Primzahl, wenn sie durch eine kleinere Zahl (außer 1) ohne Rest teilbar ist.
2. **Grenze mit Quadratwurzel:** Es reicht, \( n \) nur bis zur **Quadratwurzel von \( n \)** zu testen. Alle größeren Zahlen sind keine neuen Faktoren.

#### **Beispiel:** Ist \( n = 37 \) eine Primzahl?
1. Quadratwurzel von \( 37 \): Ungefähr \( 6 \).
2. Prüfe Teilbarkeit durch Primzahlen kleiner als \( 6 \): \( 2, 3, 5 \).
   - \( 37 \div 2 \): Rest \( 1 \)
   - \( 37 \div 3 \): Rest \( 1 \)
   - \( 37 \div 5 \): Rest \( 2 \)
3. Ergebnis: \( 37 \) ist eine Primzahl.

---

### **3. Der Euklidische Algorithmus (ggT)**
Der **Größte Gemeinsame Teiler (ggT)** zweier Zahlen ist die größte Zahl, die beide Zahlen teilt.

#### **Schritte:**
1. Teile die größere Zahl durch die kleinere und merke dir den Rest.
2. Ersetze die größere Zahl durch die kleinere und die kleinere durch den Rest.
3. Wiederhole, bis der Rest \( 0 \) ist. Die letzte nicht-null Zahl ist der ggT.

#### **Beispiel:** ggT von \( 48 \) und \( 18 \)
1. \( 48 \div 18 = 2 \) Rest \( 12 \)
2. \( 18 \div 12 = 1 \) Rest \( 6 \)
3. \( 12 \div 6 = 2 \) Rest \( 0 \)
4. Ergebnis: ggT = \( 6 \).

---

### **4. Kleinstes Gemeinsames Vielfaches (kgV)**
Das **Kleinste Gemeinsame Vielfache (kgV)** ist die kleinste Zahl, die von zwei Zahlen ohne Rest geteilt wird.

#### **Zusammenhang mit ggT:**
\[ kgV(a, b) = \frac{a \cdot b}{ggT(a, b)} \]

#### **Beispiel:** kgV von \( 12 \) und \( 18 \)
1. Berechne ggT: \( ggT(12, 18) = 6 \).
2. Setze in die Formel ein: \[ kgV = \frac{12 \cdot 18}{6} = 36 \]
3. Ergebnis: \( kgV = 36 \).

---

### **5. Primfaktorzerlegung**
Die Primfaktorzerlegung zerlegt eine Zahl in das Produkt von Primzahlen. Sie ist nützlich für das Finden von ggT und kgV.

#### **Beispiel:** Zerlege \( 60 \) und \( 45 \) in Primfaktoren:
- \( 60 = 2^2 \cdot 3 \cdot 5 \)
- \( 45 = 3^2 \cdot 5 \)

#### **ggT mit Primfaktoren:**
Nimm die **kleinsten Potenzen** der gemeinsamen Faktoren:
- Gemeinsame Faktoren: \( 3 \) und \( 5 \).
- \( ggT = 3 \cdot 5 = 15 \).

#### **kgV mit Primfaktoren:**
Nimm die **größten Potenzen** der Faktoren:
- \( kgV = 2^2 \cdot 3^2 \cdot 5 = 180 \).

---

### **6. Zusammenfassung auf einen Blick**
- **Primzahlen:** Nur durch \( 1 \) und sich selbst teilbar.
- **Primzahltest:** Prüfe Teilbarkeit bis zur Quadratwurzel.
- **ggT:** Nutze den Euklidischen Algorithmus.
- **kgV:** Nutze die Formel \( kgV = \frac{a \cdot b}{ggT(a, b)} \).
- **Primfaktoren:** Zerlege Zahlen, um ggT und kgV schnell zu berechnen.

Fertig! Mit diesen Regeln bist du bestens vorbereitet! 🙂


