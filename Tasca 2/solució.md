#  T02: Selecció d’un SAI per una empresa client

**Autor:** Blai Vergés
**Títol:** Informe tècnic per a la selecció d’un SAI per a **TecnoGestió S.L.**

---

## 1️⃣ Inventari d’equips

| Equip                    | Quantitat | Consum estimat (W) | Comentari                                    |
| ------------------------ | --------- | ------------------ | -------------------------------------------- |
| Ordinador de sobretaula  | 4         | 180 W cadascun     | PC d’oficina tipus estàndard                 |
| Monitor LED 22–24″       | 4         | 30 W cadascun      | Monitors LED típics                          |
| Router + switch de xarxa | 1         | 20 W               | Equip de xarxa per accés a Internet          |
| Impressora-fotocopiadora | 1         | 40 W (repòs)       | No es connectarà al SAI (veure justificació) |

**Dispositius connectats al SAI:**

* Ordinadors (4 unitats)
* Monitors (4 unitats)
* Router + switch de xarxa (1 unitat)

---

## 2️⃣ Consulta de les especificacions tècniques i consum estimat

| Equip           | Consum estimat (W) | Factor de potència (cos φ) | Consum VA (W / cos φ) |
| --------------- | ------------------ | -------------------------- | --------------------- |
| Ordinador       | 180 W              | 0,8                        | 225 VA                |
| Monitor         | 30 W               | 0,8                        | 37,5 VA               |
| Router + switch | 20 W               | 0,8                        | 25 VA                 |

---

## 3️⃣ Càlcul de potència total amb marge de seguretat del 20 %

* Potència **Watts amb marge:** `860 W × 1,20 = 1 032 W`
* Potència **VA amb marge:** `1 075 VA × 1,20 = 1 290 VA`

---

## 4️⃣ Determinació de l’autonomia mínima requerida

S’estableix una **autonomia mínima de 10 minuts** per permetre desar els treballs i apagar correctament els equips.

Càlcul d’energia necessària:
→ **SAI mínim: 172 Wh** per mantenir els equips durant 10 minuts a plena càrrega.

---

## 5️⃣ Recerca de models de SAI que compleixin els requisits

### 🟩 Model 1: APC Back-UPS Pro BR1500G

* **Potència:** 1 500 VA / 865 W
* **Autonomia:** 10–12 min a 860 W
* **Tipus:** Line-interactive
* **Preu:** ~250 €
* **Marca:** APC (Schneider Electric)
* **Altres:** Display LCD, protecció de línia, USB
  🔗 [Enllaç al producte](#)

---

### 🟩 Model 2: Eaton Ellipse ECO 1600

* **Potència:** 1 600 VA / 1 000 W
* **Autonomia:** ~10 min a càrrega plena
* **Tipus:** Line-interactive
* **Preu:** ~220 €
* **Marca:** Eaton
* **Altres:** Mode ECO, alta eficiència
  🔗 [Enllaç al producte](#)

---

### 🟩 Model 3: CyberPower CP1500EPFCLCD

* **Potència:** 1 500 VA / 900 W
* **Autonomia:** 10–12 min a càrrega plena
* **Tipus:** Line-interactive (sortida sinusoïdal pura)
* **Preu:** ~180 €
* **Marca:** CyberPower
* **Altres:** Display LCD, protecció avançada
  🔗 [Enllaç al producte](#)

---

## 6️⃣ Comparació resumida

| Model                    | Potència VA / W | Autonomia | Tipus            | Preu (€) | Comentaris                        |
| ------------------------ | --------------- | --------- | ---------------- | -------- | --------------------------------- |
| APC Back-UPS Pro BR1500G | 1 500 / 865     | 10–12 min | Line-interactive | ~250     | Marca líder, pantalla LCD, fiable |
| Eaton Ellipse ECO 1600   | 1 600 / 1 000   | 10 min    | Line-interactive | ~220     | Bona eficiència, ECO mode         |
| CyberPower CP1500EPFCLCD | 1 500 / 900     | 10–12 min | Line-interactive | ~180     | Bona relació qualitat/preu        |

---

## 7️⃣ Justificació de la selecció final

El model **CyberPower CP1500EPFCLCD** és la millor opció ja que:

* Ofereix **potència i autonomia suficients**.
* Té **sortida sinusoïdal pura**, que protegeix millor els equips.
* És **més econòmic** i ofereix una **excel·lent relació qualitat-preu**.
* Incorpora **display LCD** i **protecció avançada**.

 **Conclusió:** el **CyberPower CP1500EPFCLCD** garanteix **estabilitat, seguretat i eficiència**, ideals per a una petita oficina com **TecnoGestió S.L.**
