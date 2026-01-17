# 2. Flow Laws and Speeds (Lois des écoulements et vitesses)

**Reference:** PDF Pages 13-17

## Introduction

Understanding how air flows around objects is crucial for comprehending how wings generate lift and why aircraft behave the way they do. This chapter introduces two fundamental laws of fluid dynamics that govern all aerodynamic phenomena: the **continuity equation** and **Bernoulli's principle**.

These principles, developed in the 18th century, remain the cornerstone of aerodynamics today. They explain why wings work, how airspeed indicators function, and why venturi effects occur. More importantly for pilots, they help explain many observed flight phenomena - from why flying faster requires more power, to how altitude affects indicated airspeed.

The "why" behind these laws: Air, though it seems insubstantial, is a fluid with mass and energy. When it flows, its energy can change form (between pressure energy and kinetic energy), but the total energy remains constant. These laws describe those energy transformations.

## 2.1 Laws of Air Flow

### 2.1.1 Continuity Law (Conservation of Mass)

As long as we remain well below the speed of sound, air flows can always be considered **incompressible** (subsonic aerodynamics). This is a fundamental assumption that simplifies our calculations tremendously.

**The Principle:**
In an incompressible fluid flow, the **volume flow rate** (the product of cross-sectional area S and velocity V, expressed in m³/s) is the same at all cross-sections of the flow:

**S · V = constant**

**What this means in practice:**

Imagine water flowing through a hose. If you partially block the end (reducing the cross-sectional area), the water speeds up and shoots out faster. The same amount of water must pass through per second, so smaller area = higher velocity.

**Example calculation:**

Consider a flow with 1 m³/s passing through various cross-sections:
- Section 1: Area = 1 m² → Velocity = 1 m/s (because 1 m² × 1 m/s = 1 m³/s)
- Section 2: Area = 0.5 m² → Velocity = 2 m/s (because 0.5 m² × 2 m/s = 1 m³/s)
- Section 4: Area = 2 m² → Velocity = 0.5 m/s (because 2 m² × 0.5 m/s = 1 m³/s)

**Key insight:** Velocity is **inversely proportional** to cross-sectional area. Small area = high velocity; large area = low velocity.

**Application to wings:**

When air flows over a wing's curved upper surface, the flow tubes must "squeeze" through a smaller effective area (due to the wing's curvature). According to the continuity law, the air must speed up. This acceleration over the top of the wing is part of what creates lift.

![Continuity Law Diagram - Air speeding up as cross-section decreases]

### 2.1.2 Bernoulli's Law (Conservation of Energy)

If we place pressure-measuring instruments (manometers) at different sections of a flow, they show values that vary inversely with velocity.

**Bernoulli's Principle (simplified):**

**High velocity = Low static pressure**
**Low velocity = High static pressure**

This is perhaps the most important principle in all of aerodynamics. It seems counterintuitive at first - shouldn't fast-moving air create more pressure? But remember, we're talking about **static pressure** (the pressure measured perpendicular to the flow), not dynamic pressure.

**The Physics Behind It:**

Bernoulli's law is actually a statement of energy conservation. The total energy in a flowing fluid remains constant, but it can exist in different forms:
- **Pressure energy** (static pressure p)
- **Kinetic energy** (related to velocity v)
- **Potential energy** (related to height - less important for our purposes)

When velocity increases, kinetic energy increases, so pressure energy must decrease to keep total energy constant.

**Formal Expression:**

The total pressure H (also called stagnation pressure) is constant:

**H = p + q = constant**

Where:
- **p** = static pressure (the pressure in the fluid)
- **q** = dynamic pressure = ½ρv² (related to velocity)
- **ρ** = air density
- **v** = velocity

**Why this matters:** As velocity increases, dynamic pressure q increases, so static pressure p must decrease to maintain constant total pressure.

### 2.1.3 Application to Wing Profiles

These two laws working together explain a significant portion of how wings generate lift:

1. **Continuity Law**: Air flowing over the curved upper surface of a wing must accelerate (flow tubes squeeze together)

2. **Bernoulli's Law**: This acceleration causes a **decrease in static pressure** on the upper surface

3. **Result**: Lower pressure above the wing, higher pressure below = **upward force** (lift)

This is often called "suction lift" because the wing is literally being sucked upward by the low pressure region above it. In fact, about 70-80% of a wing's lift comes from this low pressure on top, with only 20-30% from higher pressure pushing up from below.

**Important Note:** While Bernoulli's principle explains part of lift generation, it's not the complete picture. Circulation theory and Newton's third law (deflecting air downward) also contribute. But Bernoulli gives us an excellent starting point for understanding wing behavior.

## 2.2 Airspeed Measurement

### 2.2.1 Measuring Airspeed

**Relative Velocity Concept:**

When we talk about airspeed, we're always discussing **relative velocity** between the air flow and the aircraft. There's no difference between:
- Wind blowing at 50 km/h on a stationary aircraft, or
- An aircraft moving at 50 km/h through still air

Both create the same aerodynamic forces.

**The Pitot-Static System:**

To measure airspeed, we measure **dynamic pressure** by finding the difference between total pressure and static pressure:

**q = H - p**

**Components:**

1. **Pitot Tube** (or nose probe on gliders): Faces directly into the airflow, measures **total pressure H**. At this point, air velocity is brought to zero (stagnation point), so all kinetic energy is converted to pressure.

2. **Static Port**: Opening on the side of the fuselage (or around the Pitot tube in a Prandtl tube), measures **static pressure p** - the ambient air pressure undisturbed by the aircraft's motion.

3. **Airspeed Indicator (ASI)**: An aneroid instrument that displays the pressure difference (H - p = q) as a speed reading.

**How it works:**

The ASI is essentially a pressure gauge calibrated to show speed. It measures dynamic pressure q = ½ρ₀v², then solves for v using a **standard density** ρ₀ (the density at sea level in standard atmosphere = 1.225 kg/m³).

**The catch:** The instrument assumes standard sea level density. If actual density is different (at altitude or in non-standard temperature), the indicated speed will differ from true airspeed.

### 2.2.2 Indicated Airspeed (IAS), True Airspeed (TAS), and Ground Speed (GS)

#### Indicated Airspeed (IAS)

**IAS** is what your airspeed indicator shows. It's subject to several errors:

1. **Instrument errors**: Manufacturing imperfections
2. **Position errors**: Disturbed airflow at the static port location (especially in sideslips)
3. **Density error**: The big one - the instrument is calibrated for standard sea level density

**Critical Point:** All the speeds in your aircraft's Flight Manual (AFM) - stall speed, maneuvering speed, never-exceed speed, best glide speed - are given in **IAS**. This is because IAS directly relates to the aerodynamic forces on the aircraft.

#### True Airspeed (TAS)

**TAS** is your actual speed through the air mass. It's what you'd read if you could magically measure your speed relative to the surrounding air.

**The relationship:**

**TAS = IAS × √(ρ₀/ρ)**

Where:
- ρ = actual air density
- ρ₀ = standard sea level density

**What this means:**

As you climb and air density decreases, TAS becomes increasingly higher than IAS. At high altitudes, the difference can be dramatic.

**Example:**
- IAS = 100 km/h at sea level → TAS ≈ 100 km/h
- IAS = 100 km/h at 10,000 ft → TAS ≈ 115 km/h
- IAS = 100 km/h at 20,000 ft → TAS ≈ 135 km/h

**Why this matters:**
- **Navigation**: Your actual progress through an air mass depends on TAS
- **Fuel consumption**: Engine power relates more to TAS than IAS
- **Wind effects**: Wind speeds must be compared to TAS, not IAS

#### Ground Speed (GS)

**GS** is your actual speed over the ground. It's what GPS shows.

**The relationship:**

**GS = TAS ± wind component**

**Examples:**
- TAS = 100 km/h, 20 km/h headwind → GS = 80 km/h
- TAS = 100 km/h, 20 km/h tailwind → GS = 120 km/h
- TAS = 100 km/h, 20 km/h crosswind from the side → GS = ~102 km/h (using vector addition)

**Why this matters:**
- **Navigation**: Your actual progress over the ground determines arrival time
- **Fuel planning**: Distance to cover is measured over ground
- **Legal requirements**: Some speed limits are ground speed limits

### 2.2.3 Summary of Speed Relationships

**IAS** (what you see)
→ corrected for density → **TAS** (your speed through the air)
→ corrected for wind → **GS** (your speed over the ground)

**Rule of thumb for density correction:**
TAS increases by approximately 2% per 1,000 ft of altitude above sea level.

At 10,000 ft: TAS ≈ IAS × 1.20 (20% higher)

## Questions / Fragen / Questions

### Q1: What does the continuity law state for incompressible flow?

**A:** The continuity law states that in an incompressible flow, the volume flow rate (S × V) remains constant throughout the flow. This means that when the cross-sectional area decreases, velocity must increase proportionally, and vice versa.

**DE:** Das Kontinuitätsgesetz besagt, dass in einer inkompressiblen Strömung die Volumenströmungsrate (S × V) konstant bleibt. Das bedeutet, dass bei Verringerung der Querschnittsfläche die Geschwindigkeit proportional zunehmen muss und umgekehrt.

**FR:** La loi de continuité stipule que dans un écoulement incompressible, le débit volumique (S × V) reste constant. Cela signifie que lorsque la section transversale diminue, la vitesse doit augmenter proportionnellement, et vice versa.

---

### Q2: What is Bernoulli's principle?

**A:** Bernoulli's principle states that in a flowing fluid, an increase in velocity corresponds to a decrease in static pressure, and vice versa. The total pressure (static + dynamic) remains constant. This is fundamentally a statement of energy conservation.

**DE:** Das Bernoulli-Prinzip besagt, dass in einer strömenden Flüssigkeit eine Erhöhung der Geschwindigkeit einer Verringerung des statischen Drucks entspricht und umgekehrt. Der Gesamtdruck (statisch + dynamisch) bleibt konstant. Dies ist grundsätzlich eine Aussage über Energieerhaltung.

**FR:** Le principe de Bernoulli stipule que dans un fluide en écoulement, une augmentation de la vitesse correspond à une diminution de la pression statique, et vice versa. La pression totale (statique + dynamique) reste constante. C'est fondamentalement une déclaration de conservation de l'énergie.

---

### Q3: How do the continuity and Bernoulli laws explain lift generation on a wing?

**A:** The continuity law causes air to accelerate over the curved upper surface of a wing (as the effective cross-section decreases). Bernoulli's law then tells us this acceleration creates a region of low pressure. The pressure difference between the lower and upper surfaces creates an upward force - lift.

**DE:** Das Kontinuitätsgesetz bewirkt, dass sich die Luft über der gekrümmten Oberseite eines Flügels beschleunigt (da sich der effektive Querschnitt verringert). Das Bernoulli-Gesetz sagt uns dann, dass diese Beschleunigung einen Niederdruckbereich erzeugt. Der Druckunterschied zwischen Unter- und Oberseite erzeugt eine Aufwärtskraft - Auftrieb.

**FR:** La loi de continuité fait accélérer l'air sur la surface supérieure courbée d'une aile (la section effective diminue). La loi de Bernoulli nous dit alors que cette accélération crée une région de basse pression. La différence de pression entre les surfaces inférieure et supérieure crée une force ascendante - la portance.

---

### Q4: What is the difference between total pressure, static pressure, and dynamic pressure?

**A:** Total pressure (H) is the sum of static pressure (p) and dynamic pressure (q). Static pressure is the ambient pressure in the fluid. Dynamic pressure (q = ½ρv²) represents the kinetic energy of the moving fluid. A Pitot tube measures total pressure, while a static port measures static pressure. The difference gives dynamic pressure, which is used to determine airspeed.

**DE:** Der Gesamtdruck (H) ist die Summe aus statischem Druck (p) und dynamischem Druck (q). Der statische Druck ist der Umgebungsdruck in der Flüssigkeit. Der dynamische Druck (q = ½ρv²) repräsentiert die kinetische Energie der bewegten Flüssigkeit. Ein Pitot-Rohr misst den Gesamtdruck, während eine statische Öffnung den statischen Druck misst. Die Differenz ergibt den dynamischen Druck, der zur Bestimmung der Fluggeschwindigkeit verwendet wird.

**FR:** La pression totale (H) est la somme de la pression statique (p) et de la pression dynamique (q). La pression statique est la pression ambiante dans le fluide. La pression dynamique (q = ½ρv²) représente l'énergie cinétique du fluide en mouvement. Un tube de Pitot mesure la pression totale, tandis qu'une prise statique mesure la pression statique. La différence donne la pression dynamique, qui est utilisée pour déterminer la vitesse de l'air.

---

### Q5: What is Indicated Airspeed (IAS) and why does it differ from True Airspeed (TAS)?

**A:** IAS is the speed shown on the airspeed indicator, calculated assuming standard sea level air density. TAS is the actual speed through the air mass. They differ because air density changes with altitude and temperature. At higher altitudes, air is less dense, so TAS is higher than IAS. The relationship is: TAS = IAS × √(ρ₀/ρ).

**DE:** IAS ist die vom Fahrtmesser angezeigte Geschwindigkeit, berechnet unter der Annahme der Standard-Luftdichte auf Meereshöhe. TAS ist die tatsächliche Geschwindigkeit durch die Luftmasse. Sie unterscheiden sich, weil sich die Luftdichte mit Höhe und Temperatur ändert. In größeren Höhen ist die Luft weniger dicht, daher ist TAS höher als IAS. Die Beziehung ist: TAS = IAS × √(ρ₀/ρ).

**FR:** L'IAS est la vitesse indiquée sur l'indicateur de vitesse, calculée en supposant la densité de l'air standard au niveau de la mer. La TAS est la vitesse réelle à travers la masse d'air. Elles diffèrent car la densité de l'air change avec l'altitude et la température. À des altitudes plus élevées, l'air est moins dense, donc la TAS est supérieure à l'IAS. La relation est : TAS = IAS × √(ρ₀/ρ).

---

### Q6: Why are aircraft performance speeds given in IAS rather than TAS?

**A:** Aircraft performance speeds (stall speed, maneuvering speed, never-exceed speed, etc.) are given in IAS because IAS directly relates to the aerodynamic forces acting on the aircraft. The dynamic pressure (which determines lift and drag) depends on the indicated airspeed, not the true airspeed. This makes IAS the most relevant speed for flight operations and structural limits.

**DE:** Flugzeugleistungsgeschwindigkeiten (Überziehgeschwindigkeit, Manövriergeschwindigkeit, Höchstgeschwindigkeit usw.) werden in IAS angegeben, weil IAS direkt mit den aerodynamischen Kräften auf das Flugzeug zusammenhängt. Der dynamische Druck (der Auftrieb und Widerstand bestimmt) hängt von der angezeigten Fluggeschwindigkeit ab, nicht von der wahren Fluggeschwindigkeit. Dies macht IAS zur relevantesten Geschwindigkeit für Flugbetrieb und strukturelle Grenzen.

**FR:** Les vitesses de performance des aéronefs (vitesse de décrochage, vitesse de manœuvre, vitesse à ne jamais dépasser, etc.) sont données en IAS car l'IAS est directement liée aux forces aérodynamiques agissant sur l'aéronef. La pression dynamique (qui détermine la portance et la traînée) dépend de la vitesse indiquée, non de la vitesse vraie. Cela fait de l'IAS la vitesse la plus pertinente pour les opérations de vol et les limites structurelles.

---

### Q7: What is Ground Speed and how does it differ from TAS?

**A:** Ground Speed (GS) is the actual speed of the aircraft over the ground, as shown by GPS. It differs from TAS because it includes the effect of wind. GS = TAS + wind component (positive for tailwind, negative for headwind). GS is what determines your actual progress in navigation and fuel planning.

**DE:** Die Geschwindigkeit über Grund (GS) ist die tatsächliche Geschwindigkeit des Flugzeugs über dem Boden, wie vom GPS angezeigt. Sie unterscheidet sich von TAS, weil sie die Wirkung des Windes einschließt. GS = TAS + Windkomponente (positiv für Rückenwind, negativ für Gegenwind). GS bestimmt Ihren tatsächlichen Fortschritt bei Navigation und Treibstoffplanung.

**FR:** La vitesse sol (GS) est la vitesse réelle de l'aéronef par rapport au sol, affichée par le GPS. Elle diffère de la TAS car elle inclut l'effet du vent. GS = TAS + composante du vent (positive pour vent arrière, négative pour vent de face). La GS détermine votre progression réelle en navigation et planification du carburant.

---

### Q8 (Multiple Choice): If airspeed is constant and the cross-sectional area of airflow decreases, what happens to air velocity?

- A) Velocity decreases
- B) Velocity remains constant
- C) Velocity increases
- D) Velocity becomes zero

**A:** C) Velocity increases. According to the continuity law (S × V = constant), when cross-sectional area S decreases, velocity V must increase to maintain constant volume flow rate.

**DE:** C) Die Geschwindigkeit nimmt zu. Gemäß dem Kontinuitätsgesetz (S × V = konstant) muss die Geschwindigkeit V zunehmen, wenn die Querschnittsfläche S abnimmt, um einen konstanten Volumenfluss aufrechtzuerhalten.

**FR:** C) La vitesse augmente. Selon la loi de continuité (S × V = constante), lorsque la section transversale S diminue, la vitesse V doit augmenter pour maintenir un débit volumique constant.

## Related Topics

Flow laws and airspeed measurement connect to multiple aerodynamics concepts:

- **[Earth and Atmosphere](./01-earth-and-atmosphere.md)** - Foundation: air density and atmospheric properties
- **[Aerodynamic Forces](./03-aerodynamic-forces.md)** - How Bernoulli's principle creates lift
- **[Induced Drag and Wing Geometry](./04-induced-drag-and-wing-geometry.md)** - Flow behavior around wingtips
- **[Stalls and Spins](./07-stalls-and-spins.md)** - IAS relationship to stall speed
- **[Control Surfaces](./08-control-surfaces.md)** - How control deflection affects flow

## External Resources

- [Bernoulli's Principle - Wikipedia](https://en.wikipedia.org/wiki/Bernoulli%27s_principle)
- [Continuity Equation - Wikipedia](https://en.wikipedia.org/wiki/Continuity_equation)
- [Airspeed - Wikipedia](https://en.wikipedia.org/wiki/Airspeed)
- [Pitot-Static System - SKYbrary](https://skybrary.aero/articles/pitot-static-system)
- [FAA - Pilot's Handbook: Flight Instruments](https://www.faa.gov/regulations_policies/handbooks_manuals/aviation/phak)
- [NASA - Bernoulli and Newton](https://www.grc.nasa.gov/www/k-12/airplane/bernnew.html)
- [How Airspeed Indicators Work - Bold Method](https://www.boldmethod.com/learn-to-fly/aircraft-systems/how-airspeed-indicators-work/)

## Summary / Zusammenfassung / Résumé

**EN:** In incompressible flow (subsonic speeds), the continuity law states that volume flow rate (S×V) remains constant, meaning velocity is inversely proportional to cross-sectional area. Bernoulli's principle states that high velocity corresponds to low static pressure and vice versa, with total pressure remaining constant (H = p + q). These laws explain how wings generate lift through accelerated flow and reduced pressure over the upper surface. Airspeed is measured using the Pitot-static system, which determines dynamic pressure. IAS (Indicated Airspeed) is shown on the instrument and is calibrated for standard sea level density. TAS (True Airspeed) is actual speed through the air mass and equals IAS corrected for density. GS (Ground Speed) is TAS corrected for wind and represents actual progress over the ground.

**DE:** Bei inkompressibler Strömung (Unterschallgeschwindigkeiten) besagt das Kontinuitätsgesetz, dass die Volumenströmungsrate (S×V) konstant bleibt, was bedeutet, dass die Geschwindigkeit umgekehrt proportional zur Querschnittsfläche ist. Das Bernoulli-Prinzip besagt, dass hohe Geschwindigkeit niedriger statischer Druck entspricht und umgekehrt, wobei der Gesamtdruck konstant bleibt (H = p + q). Diese Gesetze erklären, wie Flügel durch beschleunigte Strömung und reduzierten Druck über der Oberseite Auftrieb erzeugen. Die Fluggeschwindigkeit wird mit dem Pitot-Statik-System gemessen, das den dynamischen Druck bestimmt. IAS (angezeigte Fluggeschwindigkeit) wird auf dem Instrument angezeigt und ist für Standard-Meereshöhendichte kalibriert. TAS (wahre Fluggeschwindigkeit) ist die tatsächliche Geschwindigkeit durch die Luftmasse und entspricht IAS korrigiert für Dichte. GS (Geschwindigkeit über Grund) ist TAS korrigiert für Wind und repräsentiert den tatsächlichen Fortschritt über dem Boden.

**FR:** Dans un écoulement incompressible (vitesses subsoniques), la loi de continuité stipule que le débit volumique (S×V) reste constant, ce qui signifie que la vitesse est inversement proportionnelle à la section transversale. Le principe de Bernoulli stipule qu'une vitesse élevée correspond à une pression statique faible et vice versa, la pression totale restant constante (H = p + q). Ces lois expliquent comment les ailes génèrent de la portance par un écoulement accéléré et une pression réduite sur la surface supérieure. La vitesse de l'air est mesurée à l'aide du système Pitot-statique, qui détermine la pression dynamique. L'IAS (vitesse indiquée) est affichée sur l'instrument et est calibrée pour la densité standard au niveau de la mer. La TAS (vitesse vraie) est la vitesse réelle à travers la masse d'air et équivaut à l'IAS corrigée pour la densité. La GS (vitesse sol) est la TAS corrigée pour le vent et représente la progression réelle par rapport au sol.

---
**Keywords:** continuity law, Bernoulli principle, airflow, incompressible flow, static pressure, dynamic pressure, total pressure, Pitot tube, static port, indicated airspeed, IAS, true airspeed, TAS, ground speed, GS, airspeed indicator, ASI, lift generation, pressure distribution

---

## Navigation

**⬅ Previous Lesson:** [Earth and Atmosphere](./01-earth-and-atmosphere.md)

**[⬆ Back to Course Overview](../README.md)**

**➡ Next Lesson:** [Aerodynamic Forces](./03-aerodynamic-forces.md)
