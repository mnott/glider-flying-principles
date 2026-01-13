# 3. Aerodynamic Forces (Les forces aérodynamiques)

**Reference:** PDF Pages 19-23

## Introduction

Now that we understand how air flows and behaves, we can explore the forces it creates on objects moving through it. Every aircraft in flight experiences two fundamental aerodynamic forces: **drag** (resistance) and **lift** (sustentation force). Understanding these forces is absolutely critical for pilots because they determine everything - from how much runway you need, to whether you can clear that mountain, to how tight you can turn.

The "why" behind learning this: As a pilot, you're constantly making decisions about airspeed. Should you fly fast or slow? Each choice has consequences for drag and lift. Understanding these relationships transforms you from someone who just follows numbers to someone who truly understands their aircraft's behavior.

Drag always opposes motion - it's the price we pay for flying. Lift is what keeps us airborne - it's the benefit we gain. The art of efficient flight is maximizing lift while minimizing drag.

## 3.1 Air Resistance (Drag) - Traînée

### 3.1.1 What It Depends On

If you stick your hand out of a car window at highway speed, you immediately feel air resistance. The faster you go, the stronger the force. The more you angle your hand, the greater the resistance. These everyday observations reveal the key factors that govern drag.

**Drag depends on:**

1. **Velocity** (and specifically, the square of velocity) - This is huge! Double your speed, and drag quadruples
2. **Shape** (form) - Streamlined vs. blunt makes an enormous difference
3. **Cross-sectional area** (frontal area facing the flow) - Bigger area = more drag
4. **Air density** - Denser air = more drag

**Real-world examples:**

- **Cyclists and competitive skiers** obsess over their position to minimize both form and frontal area
- **Sailors** know that cold, dense air "fills the sails better" - it has higher density and creates more force
- **Speed records** are often set at high altitude where air is less dense (less drag) or with carefully sculpted shapes

### 3.1.2 Quantitative Aspects

To calculate drag precisely, we use a formula that incorporates all these factors:

**Rₓ = Cₓ · (ρ/2) · v² · S**

Where:
- **Rₓ** = drag force in Newtons [N]
- **Cₓ** = drag coefficient (dimensionless number describing the shape)
- **ρ** = air density in kg/m³
- **v** = velocity in m/s
- **S** = reference area in m²

**Understanding Cₓ (Drag Coefficient):**

The drag coefficient Cₓ is a pure number that describes how "aerodynamically clean" a shape is. Lower = better:

| Body Type | Cₓ Value | Notes |
|-----------|----------|-------|
| Flat disk perpendicular to flow | 1.11 | Very poor - maximum resistance |
| Half-sphere (bowl facing flow) | 1.33 | Even worse! |
| Half-sphere (streamlined) | 0.35 | Much better |
| Sphere | 0.15-0.45 | Depends on surface finish |
| Ellipsoid | 0.2-0.4 | Better as it becomes more streamlined |
| Streamlined body | 0.1-0.2 | Excellent |

**Why shape matters so much:** Compare the half-sphere facing into the flow (Cₓ = 1.33) versus streamlined (Cₓ = 0.35). Same object, but orientation alone gives 3.8× difference in drag!

**Important Convention for Aircraft:**

For simple bodies, Cₓ is defined using the **frontal area** (cross-section perpendicular to flow).

For aircraft, Cₓ is defined using the **wing area** (S = total wing plan form area, including the part passing through the fuselage). This is important because it means you can't directly compare aircraft Cₓ values with automobile Cₓ values - they use different reference areas.

**Example Calculations:**

Let's make this concrete with numbers you can verify:

**Example 1:** A disk with area 0.01 m² (diameter ~11 cm) in a 10 m/s flow (36 km/h) with air density 1.23 kg/m³:

Rₓ = 1.11 × 0.5 × 1.23 × 0.01 × 10²
Rₓ = 1.11 × 0.5 × 1.23 × 0.01 × 100
Rₓ = **0.68 N** (about the weight of a small apple)

**Example 2:** Same disk, but streamlined half-sphere (Cₓ = 0.35):

Rₓ = 0.35 × 0.5 × 1.23 × 0.01 × 100
Rₓ = **0.22 N** (only 32% of the flat disk's drag!)

**Example 3:** Streamlined body (Cₓ = 0.15):

Rₓ = 0.15 × 0.5 × 1.23 × 0.01 × 100
Rₓ = **0.09 N** (only 13% of the flat disk's drag!)

**The velocity-squared relationship:**

This is perhaps the most important concept in understanding drag. Let's see what happens when we double the speed from 10 m/s to 20 m/s:

- At 10 m/s: Rₓ ∝ 10² = 100
- At 20 m/s: Rₓ ∝ 20² = 400

**Drag increases by a factor of 4** when speed doubles! This is why:
- Flying fast requires much more power than flying slow
- Speed limits protect structural integrity (forces grow so rapidly with speed)
- Efficient cruise speeds are often much lower than maximum speeds

## 3.2 Lift Force (Portance)

### 3.2.1 Effect of Angle of Attack

Let's return to the hand-out-the-window experiment. Hold your hand horizontal - you feel mainly drag. Now rotate it to a slight angle - suddenly your arm wants to lift! This is the effect of **angle of attack** (α).

**Angle of Attack (α):** The angle between the wing's chord line (imaginary line from leading edge to trailing edge) and the direction of the oncoming airflow.

**Key observations:**

1. At **α = 0°** (flat plate horizontal): Very little lift, mostly just drag
2. As **α increases**: Lift increases dramatically - this is good!
3. Continue increasing: Lift keeps growing... up to a point
4. **Critical angle** (typically α = 14-18°): Maximum lift achieved
5. **Beyond critical angle**: Lift suddenly decreases, drag increases - this is a stall!

**Why this matters for pilots:**

When you pull back on the stick, you increase angle of attack. This is how you command more lift. But there's a limit! Exceed the critical angle and the wing stalls. The stall always occurs at the same critical angle, regardless of airspeed, weight, or bank angle.

**Physics behind it:** At small angles, airflow stays attached to the wing surface (smooth, streamlined flow). At the critical angle, flow starts to separate from the upper surface. Beyond this, flow is completely disrupted - the wing has stalled.

### 3.2.2 Effect of Airfoil Shape

Now let's improve on the flat plate with a proper **airfoil** (wing profile) - a shape specifically designed to generate lift efficiently.

**The Paper Experiment:**

Try this: Hold a piece of paper horizontally in front of your mouth, letting it droop down naturally.

- Blow gently **over** the top surface → The paper lifts up!
- Blow **under** the bottom surface → The paper also lifts up!

**Why both work?**

1. **Blowing over**: Creates the Bernoulli effect - the curved top surface accelerates the air, reducing pressure above (suction lift)

2. **Blowing under**: Creates direct pressure force pushing upward

A proper wing combines both effects!

**Airfoil Design Features:**

A well-designed airfoil has:
- **Curved upper surface** (extrados) - typically more curved than lower surface
- **Relatively flatter lower surface** (intrados)
- **Sharp trailing edge** - ensures smooth flow separation
- **Rounded leading edge** - helps flow attach smoothly

**Why asymmetric profiles work so well:**

Even at zero angle of attack, a cambered (asymmetrically curved) airfoil generates lift because:
1. Upper surface curvature forces flow acceleration → low pressure (suction)
2. Lower surface is relatively flat → higher pressure
3. Result: Net upward force!

### 3.2.3 Profile Lift

Like drag, lift can be expressed with a formula incorporating all relevant factors:

**Rz = Cz · (ρ/2) · v² · S**

Where:
- **Rz** = lift force in Newtons [N]
- **Cz** = lift coefficient (dimensionless)
- **ρ** = air density in kg/m³
- **v** = velocity in m/s
- **S** = wing area in m²

**The Lift Coefficient (Cz):**

Unlike Cₓ which we want small, we want Cz to be as large as possible (more lift is better!).

**Critical relationship:** Cz is NOT constant - it changes with angle of attack:

![Graph: Cz vs. α - increases linearly, then curves over at critical angle]

**Key points on the Cz curve:**

1. **α = α₀** (typically -4° to 0°): Cz = 0 (zero-lift angle - wing generates no net lift)
2. **Linear region** (0° to ~14°): Cz increases linearly with α - predictable, controllable
3. **Cz,max** (at α = α_critical ≈ 14-16°): Maximum lift coefficient achieved
4. **Beyond α_critical**: Cz drops suddenly - STALL condition

**Typical Cz,max values:**
- Simple airfoil: 1.2-1.4
- With flaps deployed: 1.8-2.5
- With slats and flaps: 2.5-3.5

**What determines Cz,max:**
- Airfoil shape (camber, thickness distribution)
- Surface condition (smooth vs. rough)
- Reynolds number (related to speed and chord length)
- High-lift devices (flaps, slats)

**The stall mechanism:**

As angle of attack increases, the adverse pressure gradient on the upper surface becomes steeper. Eventually, the boundary layer can't stay attached and separates. Once separation occurs:
- Lift decreases dramatically (can lose 30-50% immediately)
- Drag increases dramatically
- Wing is "stalled" - not generating enough lift

**Critical angle of attack (α_critical):**

This is THE most important angle in aviation. It's the angle at which the wing achieves maximum lift coefficient before stalling.

**Vital facts about α_critical:**
1. It's a **fixed property** of the airfoil design
2. The stall **always** occurs at the same critical angle, regardless of:
   - Airspeed (you can stall at any speed!)
   - Weight (heavy or light aircraft)
   - Altitude (high or low)
   - Bank angle (though load factor affects stall speed)

**Why pilots must understand this:** Many pilots think "stall = too slow." Wrong! Stall = excessive angle of attack. You can stall at cruise speed if you pull back hard enough (accelerated stall). This happens in steep turns and abrupt pull-ups.

## Wing Loading and Stall Speed

Although we'll cover performance in detail later, it's worth noting here: the minimum speed at which level flight is possible (stall speed) occurs when flying at α_critical with Cz,max:

At stall: **Lift = Weight**

Therefore: **Cz,max · (ρ/2) · V_stall² · S = Weight**

Solving for stall speed:

**V_stall = √[Weight / (Cz,max · (ρ/2) · S)]**

**What this tells us:**
- Higher wing loading (Weight/S) → higher stall speed
- Better airfoil (higher Cz,max) → lower stall speed
- Less dense air (high altitude, hot day) → higher stall speed
- Deploy flaps (increases Cz,max) → lower stall speed

**Connection to previous lessons:**
Remember from Lesson 2 that IAS is what matters for aerodynamic forces. Stall IAS is constant for a given aircraft configuration because it occurs at a specific Cz,max, which is reached at a specific dynamic pressure.

## Questions / Fragen / Questions

### Q1: What factors does aerodynamic drag depend on?

**A:** Drag depends on four main factors: (1) velocity squared - drag increases dramatically with speed, (2) shape - expressed by the drag coefficient Cₓ, (3) cross-sectional/reference area - larger area means more drag, and (4) air density - denser air creates more drag. This is expressed mathematically as Rₓ = Cₓ · (ρ/2) · v² · S.

**DE:** Der Luftwiderstand hängt von vier Hauptfaktoren ab: (1) Geschwindigkeit zum Quadrat - der Widerstand steigt dramatisch mit der Geschwindigkeit, (2) Form - ausgedrückt durch den Widerstandsbeiwert Cₓ, (3) Querschnitts-/Referenzfläche - größere Fläche bedeutet mehr Widerstand, und (4) Luftdichte - dichtere Luft erzeugt mehr Widerstand.

**FR:** La traînée dépend de quatre facteurs principaux : (1) la vitesse au carré - la traînée augmente considérablement avec la vitesse, (2) la forme - exprimée par le coefficient de traînée Cₓ, (3) la section/surface de référence - une plus grande surface signifie plus de traînée, et (4) la densité de l'air - un air plus dense crée plus de traînée.

---

### Q2: Why does drag increase with the square of velocity?

**A:** Drag is proportional to v² because dynamic pressure (½ρv²) increases with the square of velocity. This means if you double your speed, drag quadruples. If you triple your speed, drag increases nine times! This is why high-speed flight requires dramatically more power than low-speed flight.

**DE:** Der Widerstand ist proportional zu v², weil der dynamische Druck (½ρv²) mit dem Quadrat der Geschwindigkeit zunimmt. Das bedeutet, wenn Sie Ihre Geschwindigkeit verdoppeln, vervierfacht sich der Widerstand. Wenn Sie Ihre Geschwindigkeit verdreifachen, erhöht sich der Widerstand um das Neunfache!

**FR:** La traînée est proportionnelle à v² car la pression dynamique (½ρv²) augmente avec le carré de la vitesse. Cela signifie que si vous doublez votre vitesse, la traînée quadruple. Si vous triplez votre vitesse, la traînée augmente neuf fois !

---

### Q3: What is the angle of attack and why is it important?

**A:** The angle of attack (α) is the angle between the wing's chord line and the oncoming airflow direction. It's critically important because it determines how much lift the wing generates. As α increases, lift increases up to a maximum at the critical angle (typically 14-16°). Beyond this critical angle, the wing stalls and lift decreases dramatically. The stall always occurs at the same critical angle of attack, regardless of airspeed.

**DE:** Der Anstellwinkel (α) ist der Winkel zwischen der Flügelprofilsehne und der Richtung der ankommenden Luftströmung. Er ist von entscheidender Bedeutung, weil er bestimmt, wie viel Auftrieb der Flügel erzeugt. Wenn α zunimmt, steigt der Auftrieb bis zu einem Maximum beim kritischen Winkel (typischerweise 14-16°). Jenseits dieses kritischen Winkels setzt das Strömungsabriss ein und der Auftrieb nimmt dramatisch ab.

**FR:** L'angle d'attaque (α) est l'angle entre la corde du profil de l'aile et la direction de l'écoulement d'air incident. Il est extrêmement important car il détermine la portance générée par l'aile. Lorsque α augmente, la portance augmente jusqu'à un maximum à l'angle critique (typiquement 14-16°). Au-delà de cet angle critique, l'aile décroche et la portance diminue considérablement.

---

### Q4: How do airfoil shape and angle of attack combine to create lift?

**A:** A properly shaped airfoil creates lift through two mechanisms: (1) the curved upper surface accelerates airflow (continuity law), creating low pressure above the wing (Bernoulli's principle) - this is "suction lift," and (2) the angle of attack deflects air downward, creating higher pressure below the wing - this is "pressure lift." Together, these create a net upward force. The effect is strongest at moderate angles of attack and diminishes beyond the critical angle when flow separates.

**DE:** Ein richtig geformtes Tragflächenprofil erzeugt Auftrieb durch zwei Mechanismen: (1) die gekrümmte Oberseite beschleunigt die Luftströmung (Kontinuitätsgesetz) und erzeugt niedrigen Druck über dem Flügel (Bernoulli-Prinzip) - dies ist "Saugauftrieb", und (2) der Anstellwinkel lenkt die Luft nach unten ab und erzeugt höheren Druck unter dem Flügel - dies ist "Druckauftrieb".

**FR:** Un profil d'aile correctement conçu crée de la portance par deux mécanismes : (1) la surface supérieure courbée accélère l'écoulement d'air (loi de continuité), créant une basse pression au-dessus de l'aile (principe de Bernoulli) - c'est la "portance par aspiration", et (2) l'angle d'attaque dévie l'air vers le bas, créant une pression plus élevée sous l'aile - c'est la "portance par pression".

---

### Q5: What is the wing area (S) and how is it defined for aircraft?

**A:** The wing area (S) is the total plan form area of the wings as seen from above, including the portion passing through the fuselage. This is the reference area used in the lift and drag formulas for aircraft. It's different from the frontal area used for automobiles or simple bodies. All aerodynamic coefficients (Cz, Cₓ) for aircraft are defined using this wing area.

**DE:** Die Flügelfläche (S) ist die gesamte Grundfläche der Flügel von oben gesehen, einschließlich des Teils, der durch den Rumpf verläuft. Dies ist die Referenzfläche, die in den Auftriebs- und Widerstandsformeln für Flugzeuge verwendet wird. Sie unterscheidet sich von der Stirnfläche, die für Automobile oder einfache Körper verwendet wird.

**FR:** La surface alaire (S) est la surface totale en plan des ailes vue d'en haut, y compris la partie traversant le fuselage. C'est la surface de référence utilisée dans les formules de portance et de traînée pour les aéronefs. Elle diffère de la surface frontale utilisée pour les automobiles ou les corps simples.

---

### Q6: What is the lift coefficient (Cz) and how does it vary?

**A:** The lift coefficient (Cz) is a dimensionless number that indicates how efficiently a wing generates lift at a given angle of attack. Unlike the drag coefficient (which we want small), we want Cz to be large. Cz increases linearly with angle of attack up to a maximum value (Cz,max) at the critical angle (typically 14-16°), then decreases sharply as the wing stalls. Typical Cz,max values range from 1.2 for simple airfoils to 3.5 with high-lift devices deployed.

**DE:** Der Auftriebsbeiwert (Cz) ist eine dimensionslose Zahl, die angibt, wie effizient ein Flügel bei einem bestimmten Anstellwinkel Auftrieb erzeugt. Im Gegensatz zum Widerstandsbeiwert (den wir klein wollen) möchten wir Cz groß haben. Cz steigt linear mit dem Anstellwinkel bis zu einem Maximalwert (Cz,max) beim kritischen Winkel (typischerweise 14-16°), dann nimmt er beim Strömungsabriss stark ab.

**FR:** Le coefficient de portance (Cz) est un nombre sans dimension qui indique l'efficacité avec laquelle une aile génère de la portance à un angle d'attaque donné. Contrairement au coefficient de traînée (que nous voulons petit), nous voulons que Cz soit grand. Cz augmente linéairement avec l'angle d'attaque jusqu'à une valeur maximale (Cz,max) à l'angle critique (typiquement 14-16°), puis diminue brusquement lors du décrochage.

---

### Q7: What is the critical angle of attack and why is it so important?

**A:** The critical angle of attack (α_critical) is the angle at which the wing achieves maximum lift coefficient (Cz,max) before stalling. It's typically between 14-16° for most aircraft. It's critically important because the stall always occurs at this same angle, regardless of airspeed, weight, or altitude. This means you can stall at any speed if you exceed the critical angle - even at cruise speed in a steep turn or abrupt pull-up (accelerated stall). Understanding this prevents the dangerous misconception that "stalls only happen at low speed."

**DE:** Der kritische Anstellwinkel (α_critical) ist der Winkel, bei dem der Flügel den maximalen Auftriebsbeiwert (Cz,max) erreicht, bevor ein Strömungsabriss auftritt. Er liegt typischerweise zwischen 14-16° für die meisten Flugzeuge. Er ist von entscheidender Bedeutung, weil der Strömungsabriss immer bei diesem gleichen Winkel auftritt, unabhängig von Fluggeschwindigkeit, Gewicht oder Höhe.

**FR:** L'angle d'attaque critique (α_critical) est l'angle auquel l'aile atteint le coefficient de portance maximum (Cz,max) avant le décrochage. Il se situe généralement entre 14-16° pour la plupart des aéronefs. Il est extrêmement important car le décrochage se produit toujours à ce même angle, quelle que soit la vitesse, le poids ou l'altitude.

---

### Q8 (Multiple Choice): If airspeed doubles, by what factor does drag increase?

- A) 2 times
- B) 3 times
- C) 4 times
- D) 8 times

**A:** C) 4 times. Drag is proportional to v², so when velocity doubles (v → 2v), drag increases by a factor of (2v)² / v² = 4. This is why flying fast requires so much more power than flying slow.

**DE:** C) 4-fach. Der Widerstand ist proportional zu v², wenn sich die Geschwindigkeit verdoppelt (v → 2v), erhöht sich der Widerstand um den Faktor (2v)² / v² = 4.

**FR:** C) 4 fois. La traînée est proportionnelle à v², donc lorsque la vitesse double (v → 2v), la traînée augmente d'un facteur de (2v)² / v² = 4.

---

### Q9 (Multiple Choice): At what condition does a wing always stall?

- A) At the same airspeed
- B) At the same angle of attack
- C) At the same altitude
- D) At the same power setting

**A:** B) At the same angle of attack. The stall always occurs when the critical angle of attack is exceeded, regardless of airspeed, altitude, weight, or power setting. This is why understanding angle of attack is more important than just monitoring airspeed for stall awareness.

**DE:** B) Beim gleichen Anstellwinkel. Der Strömungsabriss tritt immer auf, wenn der kritische Anstellwinkel überschritten wird, unabhängig von Fluggeschwindigkeit, Höhe, Gewicht oder Leistungseinstellung.

**FR:** B) Au même angle d'attaque. Le décrochage se produit toujours lorsque l'angle d'attaque critique est dépassé, quels que soient la vitesse, l'altitude, le poids ou le réglage de puissance.

## Related Topics

Understanding aerodynamic forces is central to all flight mechanics:

- **[Flow Laws and Speeds](./02-flow-laws-and-speeds.md)** - Foundation: how Bernoulli's principle creates lift
- **[Induced Drag and Wing Geometry](./04-induced-drag-and-wing-geometry.md)** - Additional drag from lift generation
- **[Stalls and Spins](./05-stalls-and-spins.md)** - What happens when critical angle is exceeded
- **[Control Surfaces](./06-control-surfaces.md)** - How control surfaces create forces and moments
- **[Aircraft Stability](./07-aircraft-stability.md)** - How forces balance for stable flight

## External Resources

- [Drag (physics) - Wikipedia](https://en.wikipedia.org/wiki/Drag_(physics))
- [Lift (force) - Wikipedia](https://en.wikipedia.org/wiki/Lift_(force))
- [Angle of attack - Wikipedia](https://en.wikipedia.org/wiki/Angle_of_attack)
- [Airfoil - Wikipedia](https://en.wikipedia.org/wiki/Airfoil)
- [Stall (fluid dynamics) - Wikipedia](https://en.wikipedia.org/wiki/Stall_(fluid_dynamics))
- [NASA - Lift from Flow Turning](https://www.grc.nasa.gov/www/k-12/airplane/right2.html)
- [FAA - Pilot's Handbook: Aerodynamics of Flight](https://www.faa.gov/regulations_policies/handbooks_manuals/aviation/phak)
- [How Wings Work - Cambridge University](https://www.cam.ac.uk/research/news/how-wings-really-work)

## Summary / Zusammenfassung / Résumé

**EN:** Aerodynamic drag (Rₓ) is the resistance force opposing motion through air, depending on velocity squared, shape (Cₓ), reference area (S), and air density (ρ): Rₓ = Cₓ·(ρ/2)·v²·S. The drag coefficient Cₓ varies dramatically with shape, from 1.33 for blunt bodies to 0.1-0.2 for streamlined forms. Lift (Rz) is the upward force generated by wings, following the same formula structure: Rz = Cz·(ρ/2)·v²·S. The lift coefficient Cz depends primarily on angle of attack (α), increasing linearly up to a critical angle (typically 14-16°) where Cz,max is reached, beyond which the wing stalls. The stall always occurs at the same critical angle of attack regardless of airspeed. Proper airfoil shapes generate lift through both reduced pressure on the curved upper surface (Bernoulli effect) and increased pressure from flow deflection below. Understanding the velocity-squared relationship for both drag and lift is fundamental to aircraft performance and safe flight operations.

**DE:** Der aerodynamische Widerstand (Rₓ) ist die Kraft, die der Bewegung durch die Luft entgegenwirkt, abhängig von Geschwindigkeit zum Quadrat, Form (Cₓ), Referenzfläche (S) und Luftdichte (ρ): Rₓ = Cₓ·(ρ/2)·v²·S. Der Widerstandsbeiwert Cₓ variiert dramatisch mit der Form, von 1,33 für stumpfe Körper bis 0,1-0,2 für stromlinienförmige Formen. Auftrieb (Rz) ist die Aufwärtskraft, die von Flügeln erzeugt wird, nach derselben Formelstruktur: Rz = Cz·(ρ/2)·v²·S. Der Auftriebsbeiwert Cz hängt hauptsächlich vom Anstellwinkel (α) ab, steigt linear bis zu einem kritischen Winkel (typischerweise 14-16°), bei dem Cz,max erreicht wird, darüber hinaus setzt der Strömungsabriss ein. Der Strömungsabriss tritt immer beim gleichen kritischen Anstellwinkel auf, unabhängig von der Fluggeschwindigkeit. Richtig geformte Tragflächenprofile erzeugen Auftrieb sowohl durch reduzierten Druck auf der gekrümmten Oberseite (Bernoulli-Effekt) als auch durch erhöhten Druck durch Strömungsablenkung unten.

**FR:** La traînée aérodynamique (Rₓ) est la force de résistance s'opposant au mouvement dans l'air, dépendant de la vitesse au carré, de la forme (Cₓ), de la surface de référence (S) et de la densité de l'air (ρ): Rₓ = Cₓ·(ρ/2)·v²·S. Le coefficient de traînée Cₓ varie considérablement selon la forme, de 1,33 pour les corps émoussés à 0,1-0,2 pour les formes profilées. La portance (Rz) est la force ascendante générée par les ailes, suivant la même structure de formule: Rz = Cz·(ρ/2)·v²·S. Le coefficient de portance Cz dépend principalement de l'angle d'attaque (α), augmentant linéairement jusqu'à un angle critique (typiquement 14-16°) où Cz,max est atteint, au-delà duquel l'aile décroche. Le décrochage se produit toujours au même angle d'attaque critique quelle que soit la vitesse. Les profils d'aile appropriés génèrent de la portance à la fois par pression réduite sur la surface supérieure courbée (effet Bernoulli) et par pression accrue de la déviation du flux en dessous.

---
**Keywords:** drag, traînée, lift, portance, angle of attack, angle d'attaque, drag coefficient, Cₓ, lift coefficient, Cz, airfoil, profil, critical angle, stall, décrochage, aerodynamic forces, velocity squared, air resistance, wing area, Cz,max

---

## Navigation

**⬅ Previous Lesson:** [Flow Laws and Speeds](./02-flow-laws-and-speeds.md)

**[⬆ Back to Course Overview](../README.md)**

**➡ Next Lesson:** [Induced Drag and Wing Geometry](./04-induced-drag-and-wing-geometry.md)
