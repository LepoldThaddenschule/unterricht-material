---
layout: default
title: kreisbewegung
---

Unterrichtsverlauf: Gleichförmige Kreisbewegung

# Material
- Ball oder Gummistopfen an einer Schnur
- Brett mit Kette und Glas
- Animation Kreisbewegung


---

# Unterrichtsverlauf
## 1. Beschreibung einer Kreisbewegung
### Einstieg 
Ball/Gummistopfen nicht loslassen
### Analyse
Wie können wir diese Bewegung beschreiben?

### Sicherung:
Bewegt sich ein Objekt mit **konstantem Geschwindikeitsbetrag** (|v|=const) auf einer Kreisbahn, so spricht man von einer gleichförmigen **Kreisbewegung**.
Wichtige physikalische Größen:
- Radius \(r\) in [m]
- Umlaufdauer/Periodendauer \(T\) in [s]: Zeit die für eine vollständige Umdrehung benötigt wird
- Frequenz \(f\) in [Hz]: Anzahl der Umdrehungen pro Sekunde ($f = \frac{n}{t_n}=\frac{1}{T}$)
- Bahngeschwindigkeit \(v\) in [m/s]: Geschwindigkeitsbetrag entlang der Kreisbahn ($v=\frac{s}{t}=\frac{2\pi r}{T}$)
- Winkelgeschwindigkeit $\omega$ in [1/s]: Die Winkelgeschwindigkeit beschreibt, wieviel Winkel pro Zeit zurückgelegt wird. ($\omega = \frac{\alpha}{t}=\frac{360°}{T}=\frac{2\pi}{T}$)

### Zusammenhänge:
$$
\omega = \frac{2\pi}{T}=2\pi f \text{ (mit} f=\frac{1}{T})\\
v=\frac{2\pi r}{T}=\frac{2\pi}{T}r=\omega r
$$
### Animation Kreisbewegung1.html
### Arbeitblatt Kreisbewegung1

## 2. Ursache einer Kreisbewegung
### Ball/Gummistopfen loslassen - Wie fliegt er weiter?
Um welche art von Bewegung handelt es sich?
-> Beschleunigte Bewegung. (Richtung ändert sich)
Hier muss eine Kraft wirken!
In welche Richtung zeigt die Kraft?

### Sicherung:
Eine Kreisbewegung ist eine beschleunigte Bewegung. Auch wenn sich der Betrag der Geschwindigkeit nicht ändert. Es ändert sich die Richtung der Geschwindigkeit. Es muss demnach eine Kraft in Richtung der Änderung wirken. Diese Kraft heißt Zentripedalkraft ($F_Z$) und zeigt zum Mittelpunkt der KRreisbewegung.

### Experiment: Von was hängt diese Kraft ab

Bobycar, Kurve oder Drehen mit Masse an Schnur.

Folgenden Abhöngigkeiten:
- v
- m
- r

### Sicherung:
Die Zentripedalkraft ist definiert als
$$
F_z=\frac{mv^2}{r}.
$$

### Zusammenhang:
mit $v=\omega\cdot r$ gilt:
$$
F_Z=\frac{mv^2}{r}=\frac{m(\omega\cdot r)^2 }{r}=m\omega^2r
$$

[Link zur Animation](https://lepoldthaddenschule.github.io/unterricht-material/physik/klasse-10/Zentripedalkraft_Animation.html)

### Vergleiche Konstanntes $v$ vs $\omega$

1. $v$ konstannt: $F_Z\propto\frac{1}{r}$
Beispiel: Fahrrad um kleine und große Kurve
2. $\omega$ konst.: $F_Z\propto r$
Beispiel: Kettenkarusell

### AB_Zentripedalkraft.pdf (auf GitHub)
[Zum AB](https://lepoldthaddenschule.github.io/unterricht-material/physik/klasse-10/AB_Zentripedalkraft.pdf)

<details>
<summary>Lösung anzeigen</summary>


### Teil A

$$
F_\mathrm{Z}=\frac{m v^2}{r}
$$

Für $r_1=10\,\mathrm{m}$:

$$
F_{\mathrm{Z},1}
=
\frac{75\,\mathrm{kg}\cdot \left(5{,}0\,\frac{\mathrm{m}}{\mathrm{s}}\right)^2}{10\,\mathrm{m}}
=
187{,}5\,\mathrm{N}
$$

Für $r_2=5{,}0\,\mathrm{m}$:

$$
F_{\mathrm{Z},2}
=
\frac{75\,\mathrm{kg}\cdot \left(5{,}0\,\frac{\mathrm{m}}{\mathrm{s}}\right)^2}{5{,}0\,\mathrm{m}}
=
375\,\mathrm{N}
$$

**Vergleich:** Halbiert man bei gleichem $v$ den Radius, verdoppelt sich $F_\mathrm{Z}$.

**Skizze:**  
$\vec r$ zeigt vom Mittelpunkt zum Fahrzeug.  
$\vec v$ zeigt tangential zur Bahn.  
$\vec F_\mathrm{Z}$ zeigt zum Mittelpunkt.

---

### Teil B

$$
v=\omega r
$$

$$
v_1
=
0{,}60\,\frac{1}{\mathrm{s}}\cdot 2{,}0\,\mathrm{m}
=
1{,}2\,\frac{\mathrm{m}}{\mathrm{s}}
$$

$$
v_2
=
0{,}60\,\frac{1}{\mathrm{s}}\cdot 4{,}0\,\mathrm{m}
=
2{,}4\,\frac{\mathrm{m}}{\mathrm{s}}
$$

$$
F_\mathrm{Z}=m\omega^2 r
$$

$$
F_{\mathrm{Z},1}
=
75\,\mathrm{kg}\cdot \left(0{,}60\,\frac{1}{\mathrm{s}}\right)^2 \cdot 2{,}0\,\mathrm{m}
=
54\,\mathrm{N}
$$

$$
F_{\mathrm{Z},2}
=
75\,\mathrm{kg}\cdot \left(0{,}60\,\frac{1}{\mathrm{s}}\right)^2 \cdot 4{,}0\,\mathrm{m}
=
108\,\mathrm{N}
$$

**Vergleich:** Verdoppelt man bei gleichem $\omega$ den Radius, verdoppelt sich $F_\mathrm{Z}$.

---

### Teil C

$$
F_{\mathrm{H,max}}=\mu m g
$$

$$
F_{\mathrm{H,max}}
=
0{,}60\cdot 75\,\mathrm{kg}\cdot 9{,}81\,\frac{\mathrm{m}}{\mathrm{s}^2}
\approx
441\,\mathrm{N}
$$

Maximale Geschwindigkeit:

$$
\frac{m v^2}{r}=\mu m g
$$

$$
v^2=\mu g r
$$

$$
v=\sqrt{\mu g r}
$$

$$
v
=
\sqrt{
0{,}60\cdot 9{,}81\,\frac{\mathrm{m}}{\mathrm{s}^2}\cdot 8{,}0\,\mathrm{m}
}
\approx
6{,}9\,\frac{\mathrm{m}}{\mathrm{s}}
$$

Das entspricht ungefähr:

$$
6{,}9\cdot 3{,}6
\approx
25\,\frac{\mathrm{km}}{\mathrm{h}}
$$

Die Masse $m$ kürzt sich heraus.

---

### Teil D

A: **richtig**  
Bei kleinerem $r$ wird $F_\mathrm{Z}$ bei gleichem $v$ größer.

B: **richtig**  
Bei gleichem $\omega$ gilt:

$$
F_\mathrm{Z}=m\omega^2r
$$

Außen ist $r$ größer, also ist auch $F_\mathrm{Z}$ größer.

C: **falsch**  
Die Masse kürzt sich bei der maximalen Kurvengeschwindigkeit heraus.

D: **falsch**  
Wegen

$$
F_\mathrm{Z}\sim v^2
$$

führt doppelte Geschwindigkeit zu vierfacher Zentripetalkraft.

---

### Zusatzaufgabe

$$
v=\omega r
$$

$$
\omega=\frac{v}{r}
$$

$$
\omega
=
\frac{4{,}0\,\frac{\mathrm{m}}{\mathrm{s}}}{6{,}0\,\mathrm{m}}
\approx
0{,}67\,\frac{1}{\mathrm{s}}
$$

$$
F_\mathrm{Z}=\frac{m v^2}{r}
$$

$$
F_\mathrm{Z}
=
\frac{75\,\mathrm{kg}\cdot \left(4{,}0\,\frac{\mathrm{m}}{\mathrm{s}}\right)^2}{6{,}0\,\mathrm{m}}
=
200\,\mathrm{N}
$$
<details>