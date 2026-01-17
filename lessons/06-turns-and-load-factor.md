# 6. Turns and Load Factor - Mechanics of Curved Flight (Le vol non rectiligne)

**Reference:** PDF Pages 45-50 (Chapter 7)

## Introduction

In our previous lessons, we've analyzed straight flight where forces are perfectly balanced and motion is unchanging - the realm of Newton's first law. But the moment we bank the wings to turn, we enter a fundamentally different physics domain: curved flight, where continuous acceleration is required to change the direction of our velocity vector.

Turning flight involves concepts that can seem counterintuitive at first. There is no "centrifugal force" throwing you outward (despite what your body feels!). Instead, your flight path curves inward because the horizontal component of lift provides the centripetal force needed to continuously deflect your trajectory toward the turn center. This same banked-wing configuration also increases the total load on the wing structure and the apparent weight you feel in your seat.

The "why" behind this chapter: Understanding load factor (n) is critical for safety. In a 60° bank turn, your stall speed increases by 41% - from perhaps 75 km/h to 106 km/h! Low-altitude steep turns have killed many pilots who didn't understand that their wing would stall at a much higher airspeed than in level flight. Additionally, structural load limits must be respected to avoid overstressing the airframe. For glider pilots, understanding turn performance is essential - turning in thermals at optimal bank angles, recognizing how finesse degrades in turns, and knowing the relationship between turn radius and sink rate.

This chapter covers the mechanics of circular motion, the definition and physical meaning of load factor, and how turning flight changes your glider's performance polar.

## 7.1 Le vol en virage (Turning Flight)

### 7.1.1 Circular Motion and Centripetal Force

Before we can understand turning flight, we need to grasp a fundamental physics concept that often gets misunderstood: circular motion requires a force directed toward the center of the circle.

**A common misconception:**

When you're in a car going around a curve, you feel pushed outward against the door. Many people think this is a "centrifugal force" pushing you out. **This is wrong!** There is no outward force. What you're feeling is your body's inertia - your tendency to continue in a straight line while the car curves underneath you. The door pushes you inward, forcing you to turn with the car.

**The physics of circular motion:**

According to Newton's first law, an object naturally moves in a straight line at constant speed when no forces act on it. To make an object move in a circle (changing direction continuously), you need a force directed toward the center of the circle. This is called **centripetal force** (from Latin "centrum" = center, "petere" = to seek).

**Centripetal force is not a new type of force** - it's simply the name we give to whatever force is causing circular motion. Different situations provide centripetal force in different ways:

**Example 1: Stone on a string**

Swing a stone on a string in a horizontal circle above your head:
- The stone wants to fly off in a straight line (Newton's first law)
- The string tension pulls it continuously toward your hand (center)
- This inward tension is the centripetal force
- If the string breaks, the stone flies off tangentially (not radially outward!)

**What you feel:** Your hand feels an outward pull. This is the reaction force from the string (Newton's third law: action-reaction). The stone pulls out, you pull in. But the force making the stone go in a circle is directed inward, not outward.

**Example 2: Moon orbiting Earth**

- Moon naturally wants to move in straight line through space
- Earth's gravity pulls it continuously toward Earth's center
- Gravity provides the centripetal force
- Result: Moon follows curved path (orbit) around Earth

**Example 3: Aircraft in a turn**

- Aircraft naturally wants to continue straight (Newton's first law)
- Pilot banks the wings, creating horizontal component of lift
- This horizontal component points toward turn center
- This is the centripetal force that makes the aircraft turn

**The mathematical relationship:**

For an object of mass m moving at speed v in a circle of radius r, the required centripetal force is:

**Fc = m × v² / r**

Where:
- Fc = centripetal force (in Newtons)
- m = mass (in kg)
- v = tangential velocity (speed along the circular path, in m/s)
- r = radius of circular path (in meters)

**What this equation tells us:**

1. **Faster speed requires more force:** Double the speed → need 4× the force (v² relationship)
2. **Tighter turn requires more force:** Half the radius → need 2× the force
3. **Heavier object requires more force:** Double the mass → need 2× the force

**In aviation terms:**

To turn an aircraft, we need a centripetal force = m × v² / r. This force must come from the horizontal component of lift, which we create by banking the wings.

### 7.1.2 Forces in a Level Turn

Now let's analyze the forces acting on an aircraft in a **steady, level turn** - constant altitude, constant airspeed, constant bank angle.

**Three forces act on the aircraft in a turn (for unpowered glider):**

1. **Weight (P)** - Acts vertically downward (toward Earth's center)
2. **Lift (Rz)** - Acts perpendicular to the wings (tilted inward due to bank)
3. **Drag (Rx)** - Acts opposite to flight direction (along flight path, backward)

*(For powered aircraft, thrust (T) is added along the flight path forward)*

**The key insight: banking tilts the lift vector**

When you bank the wings to angle φ (phi, the bank angle), the lift Rz is no longer vertical - it tilts toward the turn center. We can decompose this tilted lift into two components:

**Vertical component of lift:**
Rz,vertical = Rz × cos(φ)

This component must equal weight for level flight (no climb/descent):
**Rz × cos(φ) = P**

**Horizontal component of lift:**
Rz,horizontal = Rz × sin(φ)

This component provides the centripetal force needed for circular motion:
**Rz × sin(φ) = Fc = m × v² / r**

**What this means:**

- **Bank angle determines the balance** between supporting weight (vertical) and providing turning force (horizontal)
- **Shallow bank:** Most of lift goes to supporting weight, little left for turning → large turn radius
- **Steep bank:** Significant lift goes to turning, less for supporting weight → must increase total lift (more back pressure) to maintain altitude

**Along the flight path (fore-aft forces):**

For gliding turn: The component of weight along the flight path equals drag (as in straight glide)
For powered turn: Thrust equals drag (as in level straight flight)

**Diagram interpretation (PDF Figure 5):**

The diagram shows the aircraft viewed from behind, banked to the left:

```
        Rz (Lift - perpendicular to wings, tilted)
        ↑ ↖
        |  \__ Horizontal component (toward turn center)
        |      = Fc (centripetal force)
        |
        • Aircraft (banked left at angle φ)
        ↓
        | Vertical component of lift = P
        P (Weight)
```

The weight P always points down. Lift Rz points perpendicular to the wings (tilted due to bank). The vertical component of Rz must equal P, while the horizontal component provides Fc.

**Why you need back pressure in a turn:**

From Rz × cos(φ) = P, we can solve for required lift:

**Rz = P / cos(φ)**

Since cos(φ) < 1 for any bank angle φ > 0°, we need **Rz > P** in a turn. You must pull back on the stick (increase angle of attack) to generate more lift than in level flight.

**Example calculations:**

**15° bank:**
- cos(15°) = 0.966
- Rz = P / 0.966 = 1.04 × P
- Need 4% more lift than level flight

**30° bank:**
- cos(30°) = 0.866
- Rz = P / 0.866 = 1.15 × P
- Need 15% more lift than level flight

**45° bank:**
- cos(45°) = 0.707
- Rz = P / 0.707 = 1.41 × P
- Need 41% more lift than level flight

**60° bank:**
- cos(60°) = 0.500
- Rz = P / 0.500 = 2.00 × P
- Need 100% more lift (double!) than level flight

This ratio Rz / P has a special name: **load factor**, which we'll explore in depth next.

## 7.2 Le facteur de charge (Load Factor)

### 7.2.1 Definition

**Load factor (n)** is the ratio of total aerodynamic force on the aircraft to its weight:

**n = Rz / P**

Where:
- n = load factor (dimensionless, often expressed as "g's")
- Rz = total lift force (in Newtons)
- P = aircraft weight (in Newtons)

**Special cases:**

**Straight and level flight:**
- Rz = P
- n = 1
- This is the reference condition

**Turning or pulling up:**
- Rz > P
- n > 1
- Example: 60° bank → n = 2 (experiencing "2 g's")

**Push-over or dive recovery:**
- Rz < P (or even negative!)
- n < 1 (or negative)
- Example: parabolic flight → n ≈ 0 (weightlessness)

### 7.2.2 Load Factor vs. Bank Angle

From our earlier analysis: Rz = P / cos(φ)

Therefore: **n = 1 / cos(φ)**

This simple equation reveals everything about how load factor increases with bank angle:

**Load factor table (critical to memorize!):**

| Bank Angle φ | cos(φ) | Load Factor n | Increase |
|--------------|--------|---------------|----------|
| 0° (level) | 1.000 | 1.00 | -- |
| 15° | 0.966 | 1.04 | +4% |
| 30° | 0.866 | 1.15 | +15% |
| 45° | 0.707 | 1.41 | +41% |
| 60° | 0.500 | 2.00 | +100% |
| 70° | 0.342 | 2.92 | +192% |
| 75° | 0.259 | 3.86 | +286% |
| 80° | 0.174 | 5.76 | +476% |

**Critical observations:**

1. **Load factor increases slowly at first:** Up to 30° bank, load factor is only 1.15 - quite manageable
2. **Rapid increase at steep banks:** Beyond 45°, load factor increases dramatically
3. **60° is a key threshold:** n = 2 means double the load - both on structure and stall speed
4. **80° bank means almost 6 g's!** This exceeds structural limits for most gliders

### 7.2.3 Load Factor in Pull-ups (Ressource)

The same physics applies to any maneuver where lift exceeds weight:

**Pull-up (ressource):**

When you pull back on the stick in level flight, you increase angle of attack, generating more lift. If Rz > P, the aircraft curves upward (flight path becomes curved, even though you're not banked).

The load factor is: **n = Rz / P** (same formula!)

**Example: Zoom climb from high-speed cruise**

- Flying level at 150 km/h (well above best glide)
- Pull back smoothly
- Increase α, generating Rz = 2 × P
- Load factor n = 2 (you feel 2 g's in your seat)
- Aircraft curves upward, trading speed for altitude

**Recovery from dive:**

Similar situation:
- Diving at high speed
- Pull back to level out
- Must generate high Rz to curve flight path from descending to level
- Load factor can reach 3-4 g's if pulled too aggressively!
- This is why dive recoveries must be smooth and gradual

**Combination: Turning pull-up**

The most demanding maneuver combines both effects:
- Banked turn: already need Rz = P / cos(φ)
- Pull up simultaneously: need even more lift
- Load factor can be: **n = (P / cos φ) × (additional pull factor)**
- Easy to exceed structural limits!

### 7.2.4 Physical Meaning - What Load Factor Feels Like

**What does n = 2 mean for you in the cockpit?**

Load factor is the **apparent weight increase** you experience. When n = 2:

1. **Your body feels twice as heavy**
   - Your arms feel heavy, hard to move
   - Your head feels like it weighs twice as much
   - Blood pools in lower body (can lead to grey-out/blackout)

2. **Your seat pushes up with twice your normal weight**
   - If you normally weigh 80 kg, at n = 2, seat pushes with 160 kg force
   - This is what you feel as "g-force"

3. **All loose objects are twice as heavy**
   - Your flight bag, water bottle, charts - all feel doubled in weight
   - Drop something at n = 2, it "falls" twice as fast relative to cockpit

**Why this happens:**

Your body isn't actually becoming more massive. But the aircraft (and seat) is accelerating upward (in turns or pull-ups), and to accelerate with it, you need an upward force of n × your weight. This force comes from the seat pushing you, which you perceive as increased weight.

**The physiological limits:**

- **n = 1:** Normal weight, no issues
- **n = 1.5-2:** Noticeably heavier, increased effort to move
- **n = 3-4:** Very heavy feeling, blood pools in legs, grey-out begins
- **n = 5-6:** Blackout for most people without g-suit, serious risk
- **n = 9+:** Only fighter pilots with g-suits can sustain this briefly

For glider pilots, we rarely exceed n = 2-2.5 in normal flight, perhaps n = 3-3.5 in aggressive thermaling or aerobatics.

**Structural implications:**

Every part of the aircraft experiences this increased load:
- Wing spars must support n × aircraft weight
- Wing attachment fittings see n × loads
- Control linkages experience n × forces
- Pilot's body in harness: n × body weight

This is why aircraft have **load factor limits** in their flight manuals:

**Typical glider limits:**
- **Utility category:** +5.3 g, -2.65 g
- **Aerobatic category:** +7 g, -5 g
- **Never exceed these limits!** Structural failure can result

**Maneuvering speed (Va):**

This is the maximum speed at which you can apply full control deflection without exceeding structural limits. Above Va, full control input might generate loads exceeding limit load factor.

## 7.3 Polaires en virage et spirale (Turn Polars and Spiral Performance)

### 7.3.1 Turn Polars - Performance Degradation

In straight flight, we use the **speed polar** to understand glider performance. In turning flight, performance degrades - we sink faster at every airspeed.

**Why performance worsens in turns:**

1. **Higher load factor requires higher lift coefficient:**
   - Rz = n × P (must support apparent weight)
   - Cz must increase to generate this lift at same speed
   - Higher Cz means higher induced drag (Di ∝ Cz²)

2. **Or higher speed at same Cz:**
   - To maintain same Cz while generating more lift
   - Must fly faster: v_turn = v_straight × √n
   - Higher speed means higher drag overall

**The turn polar diagram (PDF Figure 6):**

Instead of a single polar curve, we have a **family of curves**, one for each load factor (bank angle):

```
Vz (sink rate, m/s)
  0 ├─────────────────────→ v (km/h)
    |    80   100   120   140
 -0.5│      •___  n=1 (straight)
    |     /    \___
 -1.0│    /        \___•
    |   /   •___  n=1.15 (30° bank)
 -1.5│  /   /    \___
    | / • /   n=1.41 (45° bank)
 -2.0│  //
    | /
 -2.5│•    n=2.00 (60° bank)
```

**Key observations:**

1. **Each curve is lower** (worse sink rate) than the previous one
2. **Higher load factor → higher sink rate** at every speed
3. **The minimum sink point shifts right** (higher speed needed)
4. **Best glide speed also increases**

**Quantitative relationship:**

For a given Cz (angle of attack), the sink rate increases proportionally to load factor:

**vz_turn = vz_straight × n^(3/2)**

Where:
- vz_turn = sink rate in turn (m/s)
- vz_straight = sink rate in straight flight at same Cz (m/s)
- n = load factor

**Example calculation:**

**Straight flight at 90 km/h:**
- Sink rate: 0.60 m/s
- This is near best glide

**30° bank (n = 1.15):**
- vz_turn = 0.60 × (1.15)^1.5 = 0.60 × 1.23 = 0.74 m/s
- Sink increased by 23%!

**45° bank (n = 1.41):**
- vz_turn = 0.60 × (1.41)^1.5 = 0.60 × 1.68 = 1.01 m/s
- Sink increased by 68%!

**60° bank (n = 2.00):**
- vz_turn = 0.60 × (2.00)^1.5 = 0.60 × 2.83 = 1.70 m/s
- Sink nearly tripled!

**Practical implications for thermaling:**

When circling in a thermal, you must balance:
- **Steep bank** → tight turn radius → stay centered in thermal core
- **But steep bank** → high sink rate → eats away your climb rate

**Optimal bank angle depends on thermal diameter:**
- **Narrow thermal (50m diameter):** Need 45-50° bank, accept high sink
- **Wide thermal (200m diameter):** Use 30-35° bank, minimize sink
- **Rule of thumb:** Weakest thermals want shallowest banks

### 7.3.2 Spiral Polar - Turn Radius vs. Sink Rate

Another useful diagram for thermaling is the **spiral polar**, showing the relationship between turn radius and sink rate for different bank angles.

**What it shows:**

- **Horizontal axis:** Turn radius r (in meters)
- **Vertical axis:** Sink rate vz (m/s)

**The curve shape:**

For each constant airspeed, there's a curve showing how changing bank angle (thus turn radius) affects sink rate:

```
Vz (sink rate)
  |
  |\
  | \
  |  \___   (flying at constant speed,
  |      \_  varying bank angle)
  |        \____
  |             \______
  └─────────────────────→ r (turn radius)
```

**The physics:**

**Turn radius in steady turn:**
From the force balance, turn radius can be calculated as:

**r = v² / (g × tan φ) = v² / (g × √(n² - 1))**

Where:
- r = turn radius (m)
- v = airspeed (m/s)
- g = gravitational acceleration (9.81 m/s²)
- φ = bank angle
- n = load factor

**What this tells us:**

1. **Tighter turn (smaller r) requires steeper bank** (higher φ)
2. **Steeper bank means higher sink** (as we saw in turn polars)
3. **For each speed, there's a minimum achievable radius** (at maximum bank before stall)

**Example:**

**Flying at 90 km/h = 25 m/s:**

**30° bank (n = 1.15):**
- r = 25² / (9.81 × tan 30°) = 625 / 5.66 = 110 m
- Sink rate: ~0.75 m/s

**45° bank (n = 1.41):**
- r = 25² / (9.81 × tan 45°) = 625 / 9.81 = 64 m
- Sink rate: ~1.0 m/s

**60° bank (n = 2.00):**
- r = 25² / (9.81 × tan 60°) = 625 / 17.0 = 37 m
- Sink rate: ~1.7 m/s

**Practical use:**

When you encounter a thermal:
1. Estimate thermal diameter (from strength, smoothness, conditions)
2. Choose bank angle to match turn radius to thermal size
3. Adjust speed for optimal climb rate (thermal climb minus sink rate)

**Modern variometers calculate this automatically**, suggesting optimal speed and bank for maximum net climb rate.

### 7.3.3 Critical Safety Issue: Stall Speed in Turns

This is perhaps the most important safety lesson from load factor analysis:

**Stall speed increases with load factor!**

**The physics:**

Stall occurs at Cz,max (maximum lift coefficient). At stall:
Rz = Cz,max × (ρ/2) × v² × S

In a turn: Rz = n × P

Therefore: n × P = Cz,max × (ρ/2) × v² × S

Solving for stall speed in turn:
**v_stall,turn = v_stall,straight × √n**

**What this means:**

Your stall speed increases by the square root of load factor!

**Stall speed table (assume straight-flight stall = 75 km/h):**

| Bank Angle φ | Load Factor n | Stall Speed | Increase |
|--------------|---------------|-------------|----------|
| 0° (straight) | 1.00 | 75 km/h | -- |
| 30° | 1.15 | 80 km/h | +7% |
| 45° | 1.41 | 89 km/h | +19% |
| 60° | 2.00 | 106 km/h | +41% |
| 70° | 2.92 | 128 km/h | +71% |
| 75° | 3.86 | 147 km/h | +96% |

**The deadly scenario: Low-altitude steep turn**

This has killed countless pilots:

1. **Base to final turn, low altitude (200m AGL)**
2. **Overshoot the turn, need to tighten**
3. **Steepen bank to 60°**
4. **Airspeed bleeds off in turn (due to high drag)**
5. **Pilot doesn't realize stall speed now 106 km/h instead of 75 km/h**
6. **Airspeed drops to 85 km/h - feels safe, well above "normal" stall**
7. **Wing stalls, aircraft spins**
8. **Insufficient altitude to recover - fatal crash**

**This accident has happened thousands of times!**

**How to prevent this:**

1. **Never exceed 30° bank below 300m AGL** (stall speed only +7%)
2. **Maintain speed margin:** Fly at least 1.3 × Vs in turns
3. **If you overshoot final approach:** Go around! Never try to "save it" with steep turn
4. **Practice steep turns at altitude:** Feel how much speed bleeds off
5. **Load factor awareness:** Know that 60° bank doubles your stall speed buffer requirement

**Competition and thermaling:**

Even in thermals, steep banks near terrain are dangerous:
- **Thermaling in valley:** Keep bank moderate, accept wider turn
- **Ridge soaring in turns:** Speed margin critical, ridge is unforgiving
- **Low save attempt:** Shallow bank until you have height margin

**Accelerated stall:**

In steep turns or pull-ups, you can stall at ANY airspeed if you exceed Cz,max. This is called an **accelerated stall**:
- Wing reaches critical angle of attack
- Load factor makes it worse (need higher Cz for given lift)
- Stall occurs even at high speed
- Often happens in one wing first → snap roll or spin entry

**Recovery:**

If stall occurs in turn:
1. **Release back pressure immediately** (reduce α, reduce n)
2. **Level wings** (eliminate bank)
3. **Recover from stall** (normal stall recovery)
4. **Don't pull up too quickly** (avoid secondary stall)

**The fundamental principle:**

Higher load factor = higher stall speed. Always maintain adequate speed margin in turns, especially at low altitude where ground proximity compounds the risk.

## Summary / Zusammenfassung / Résumé

**EN:** Turning flight requires continuous centripetal force directed toward the turn center, provided by the horizontal component of lift when wings are banked. There is no outward "centrifugal force" - that sensation is merely inertia. In a steady level turn, the vertical component of lift equals weight (Rz cos φ = P) while the horizontal component provides centripetal force (Rz sin φ = mv²/r). Load factor (n) is the ratio of total lift to weight (n = Rz/P = 1/cos φ), representing the apparent weight increase experienced by pilot and structure. Load factor increases slowly at shallow banks but rises dramatically beyond 45°: at 60° bank, n = 2 (double weight). Turn polars show that performance degrades in turns - sink rate increases by approximately n^1.5 for a given angle of attack. Critically, stall speed increases by √n in turns: a glider that stalls at 75 km/h straight-and-level will stall at 106 km/h in a 60° banked turn, making low-altitude steep turns extremely dangerous.

**DE:** Kurvenflug erfordert kontinuierliche Zentripetalkraft in Richtung Kurvenmitte, bereitgestellt durch die horizontale Komponente des Auftriebs bei Querneigung. Es gibt keine nach außen gerichtete "Zentrifugalkraft" - diese Empfindung ist lediglich Trägheit. In einer stationären horizontalen Kurve entspricht die vertikale Komponente des Auftriebs dem Gewicht (Rz cos φ = P), während die horizontale Komponente die Zentripetalkraft liefert (Rz sin φ = mv²/r). Der Lastvielfach (n) ist das Verhältnis des Gesamtauftriebs zum Gewicht (n = Rz/P = 1/cos φ) und stellt die vom Piloten und der Struktur erfahrene scheinbare Gewichtszunahme dar. Der Lastvielfach steigt bei flachen Querlagen langsam an, steigt aber über 45° dramatisch an: Bei 60° Querneigung ist n = 2 (doppeltes Gewicht). Kurvenpolaren zeigen, dass sich die Leistung in Kurven verschlechtert - die Sinkrate steigt für einen gegebenen Anstellwinkel um etwa n^1,5. Kritisch ist, dass die Überziehgeschwindigkeit in Kurven um √n steigt: Ein Segelflugzeug, das im Geradeausflug bei 75 km/h überzieht, überzieht in einer 60°-Kurve bei 106 km/h, was steile Kurven in niedriger Höhe extrem gefährlich macht.

**FR:** Le vol en virage nécessite une force centripète continue dirigée vers le centre du virage, fournie par la composante horizontale de la portance lorsque les ailes sont inclinées. Il n'y a pas de "force centrifuge" vers l'extérieur - cette sensation n'est que l'inertie. Dans un virage en palier stabilisé, la composante verticale de la portance égale le poids (Rz cos φ = P) tandis que la composante horizontale fournit la force centripète (Rz sin φ = mv²/r). Le facteur de charge (n) est le rapport de la portance totale au poids (n = Rz/P = 1/cos φ), représentant l'augmentation du poids apparent ressentie par le pilote et la structure. Le facteur de charge augmente lentement pour les faibles inclinaisons mais monte considérablement au-delà de 45° : à 60° d'inclinaison, n = 2 (poids doublé). Les polaires de virage montrent que les performances se dégradent en virage - le taux de chute augmente d'environ n^1,5 pour un angle d'attaque donné. De manière critique, la vitesse de décrochage augmente de √n en virage : un planeur qui décroche à 75 km/h en vol rectiligne décrochera à 106 km/h dans un virage à 60°, rendant les virages serrés à basse altitude extrêmement dangereux.

---
**Keywords:** turning flight, vol en virage, Kurvenflug, centripetal force, force centripète, Zentripetalkraft, load factor, facteur de charge, Lastvielfach, bank angle, angle d'inclinaison, Querneigung, circular motion, mouvement circulaire, Kreisbewegung, turn polar, polaire de virage, Kurvenpolare, stall speed in turns, vitesse de décrochage en virage, Überziehgeschwindigkeit in Kurven, accelerated stall, décrochage accéléré, beschleunigter Strömungsabriss

---

## Questions / Fragen / Questions

### Q1: What is centripetal force and what provides it in turning flight?

**A:** Centripetal force is the force directed toward the center of a circular path that is required to make an object move in a circle rather than a straight line. In turning flight, centripetal force is provided by the horizontal component of lift when the wings are banked (Fc = Rz × sin φ). There is no real "centrifugal force" pushing outward - that sensation is your body's inertia resisting the change in direction. The banking of wings tilts the lift vector, creating both a vertical component (to support weight) and a horizontal component (to provide the inward force for circular motion).

**DE:** Zentripetalkraft ist die zum Mittelpunkt eines Kreisweges gerichtete Kraft, die erforderlich ist, damit sich ein Objekt in einem Kreis statt in einer geraden Linie bewegt. Im Kurvenflug wird die Zentripetalkraft durch die horizontale Komponente des Auftriebs bereitgestellt, wenn die Flügel geneigt sind (Fc = Rz × sin φ). Es gibt keine echte "Zentrifugalkraft", die nach außen drückt - dieses Gefühl ist die Trägheit Ihres Körpers, die der Richtungsänderung widersteht. Das Neigen der Flügel kippt den Auftriebsvektor und erzeugt sowohl eine vertikale Komponente (um das Gewicht zu tragen) als auch eine horizontale Komponente (um die nach innen gerichtete Kraft für die Kreisbewegung bereitzustellen).

**FR:** La force centripète est la force dirigée vers le centre d'un chemin circulaire qui est nécessaire pour faire bouger un objet en cercle plutôt qu'en ligne droite. En vol en virage, la force centripète est fournie par la composante horizontale de la portance lorsque les ailes sont inclinées (Fc = Rz × sin φ). Il n'y a pas de véritable "force centrifuge" poussant vers l'extérieur - cette sensation est l'inertie de votre corps résistant au changement de direction. L'inclinaison des ailes fait basculer le vecteur de portance, créant à la fois une composante verticale (pour supporter le poids) et une composante horizontale (pour fournir la force vers l'intérieur pour le mouvement circulaire).

---

### Q2: What is load factor and how is it calculated?

**A:** Load factor (n) is the ratio of total lift force to aircraft weight: n = Rz / P. It represents the apparent weight increase experienced during maneuvers. In straight and level flight, n = 1. In a banked turn, n = 1 / cos(φ) where φ is bank angle. Load factor represents both the structural loading on the aircraft and the physiological "g-force" felt by the pilot - at n = 2, everything feels twice as heavy. Load factor is dimensionless but often expressed in "g's" (multiples of gravitational acceleration).

**DE:** Der Lastvielfach (n) ist das Verhältnis der Gesamtauftriebskraft zum Flugzeuggewicht: n = Rz / P. Er stellt die scheinbare Gewichtszunahme dar, die während Manövern erfahren wird. Im geraden Horizontalflug ist n = 1. In einer Kurve ist n = 1 / cos(φ), wobei φ der Querneigungswinkel ist. Der Lastvielfach repräsentiert sowohl die strukturelle Belastung des Flugzeugs als auch die physiologische "g-Kraft", die der Pilot spürt - bei n = 2 fühlt sich alles doppelt so schwer an. Der Lastvielfach ist dimensionslos, wird aber oft in "g" ausgedrückt (Vielfache der Gravitationsbeschleunigung).

**FR:** Le facteur de charge (n) est le rapport de la force de portance totale au poids de l'avion : n = Rz / P. Il représente l'augmentation du poids apparent ressentie pendant les manœuvres. En vol rectiligne en palier, n = 1. Dans un virage incliné, n = 1 / cos(φ) où φ est l'angle d'inclinaison. Le facteur de charge représente à la fois la charge structurelle sur l'avion et la "force g" physiologique ressentie par le pilote - à n = 2, tout semble deux fois plus lourd. Le facteur de charge est sans dimension mais souvent exprimé en "g" (multiples de l'accélération gravitationnelle).

---

### Q3: What is the load factor at common bank angles?

**A:** Load factor n = 1/cos(φ) varies with bank angle: 0° (level): n = 1.00; 15°: n = 1.04; 30°: n = 1.15; 45°: n = 1.41; 60°: n = 2.00; 75°: n = 3.86. Note that load factor increases slowly at shallow banks but rises dramatically beyond 45°. At 60° bank, you experience 2 g's (double your normal weight), and structural loads are doubled. At 75°, you're experiencing nearly 4 g's, which approaches or exceeds the structural limits of many gliders.

**DE:** Lastvielfach n = 1/cos(φ) variiert mit dem Querneigungswinkel: 0° (horizontal): n = 1,00; 15°: n = 1,04; 30°: n = 1,15; 45°: n = 1,41; 60°: n = 2,00; 75°: n = 3,86. Beachten Sie, dass der Lastvielfach bei flachen Querneigungen langsam ansteigt, aber über 45° dramatisch steigt. Bei 60° Querneigung erleben Sie 2 g (doppeltes normales Gewicht), und die strukturellen Lasten verdoppeln sich. Bei 75° erleben Sie fast 4 g, was die strukturellen Grenzen vieler Segelflugzeuge erreicht oder überschreitet.

**FR:** Le facteur de charge n = 1/cos(φ) varie avec l'angle d'inclinaison : 0° (palier) : n = 1,00 ; 15° : n = 1,04 ; 30° : n = 1,15 ; 45° : n = 1,41 ; 60° : n = 2,00 ; 75° : n = 3,86. Notez que le facteur de charge augmente lentement pour les faibles inclinaisons mais monte considérablement au-delà de 45°. À 60° d'inclinaison, vous ressentez 2 g (le double de votre poids normal), et les charges structurelles sont doublées. À 75°, vous ressentez près de 4 g, ce qui approche ou dépasse les limites structurelles de nombreux planeurs.

---

### Q4: How does sink rate change in turns compared to straight flight?

**A:** Sink rate increases in turns due to higher induced drag from increased lift requirements. For a given angle of attack (Cz), sink rate increases approximately by n^1.5 where n is load factor. Example: if straight flight has 0.60 m/s sink, a 30° bank (n=1.15) gives ~0.74 m/s (+23%), 45° bank (n=1.41) gives ~1.0 m/s (+68%), and 60° bank (n=2.0) gives ~1.7 m/s (nearly triple!). This is why steep thermaling circles reduce net climb rate - the higher sink partially cancels the thermal's lift.

**DE:** Die Sinkrate steigt in Kurven aufgrund des höheren induzierten Widerstands durch erhöhte Auftriebsanforderungen. Für einen gegebenen Anstellwinkel (Cz) steigt die Sinkrate ungefähr um n^1,5, wobei n der Lastvielfach ist. Beispiel: Wenn der Geradeausflug 0,60 m/s Sinken hat, ergibt eine 30°-Querneigung (n=1,15) ~0,74 m/s (+23%), 45°-Querneigung (n=1,41) ~1,0 m/s (+68%) und 60°-Querneigung (n=2,0) ~1,7 m/s (fast das Dreifache!). Deshalb reduzieren steile Thermikkreise die Nettosteigrate - das höhere Sinken hebt teilweise den Auftrieb der Thermik auf.

**FR:** Le taux de chute augmente en virage en raison d'une traînée induite plus élevée due aux exigences accrues de portance. Pour un angle d'attaque donné (Cz), le taux de chute augmente d'environ n^1,5 où n est le facteur de charge. Exemple : si le vol rectiligne a 0,60 m/s de chute, une inclinaison de 30° (n=1,15) donne ~0,74 m/s (+23%), une inclinaison de 45° (n=1,41) donne ~1,0 m/s (+68%), et une inclinaison de 60° (n=2,0) donne ~1,7 m/s (presque le triple !). C'est pourquoi les cercles thermiques serrés réduisent le taux de montée net - la chute plus élevée annule partiellement la portance du thermique.

---

### Q5: Why does stall speed increase in turns?

**A:** Stall occurs when wing reaches maximum lift coefficient (Cz,max), regardless of flight condition. In a turn, wing must generate higher total lift (Rz = n × P) to support the increased apparent weight. At a given speed, this requires higher Cz. Therefore, the wing reaches Cz,max at a higher airspeed than in straight flight. The relationship is: v_stall,turn = v_stall,straight × √n. For example, a glider stalling at 75 km/h straight will stall at 106 km/h in a 60° bank (n=2) - a dangerous 41% increase that pilots often fail to account for.

**DE:** Ein Strömungsabriss tritt auf, wenn der Flügel den maximalen Auftriebsbeiwert (Cz,max) erreicht, unabhängig vom Flugzustand. In einer Kurve muss der Flügel höheren Gesamtauftrieb erzeugen (Rz = n × P), um das erhöhte scheinbare Gewicht zu tragen. Bei einer gegebenen Geschwindigkeit erfordert dies höheres Cz. Daher erreicht der Flügel Cz,max bei einer höheren Fluggeschwindigkeit als im Geradeausflug. Die Beziehung ist: v_Überziehen,Kurve = v_Überziehen,gerade × √n. Beispielsweise wird ein Segelflugzeug, das im Geradeausflug bei 75 km/h überzieht, in einer 60°-Kurve (n=2) bei 106 km/h überziehen - eine gefährliche Erhöhung um 41%, die Piloten oft nicht berücksichtigen.

**FR:** Le décrochage se produit lorsque l'aile atteint le coefficient de portance maximum (Cz,max), quelle que soit la condition de vol. Dans un virage, l'aile doit générer une portance totale plus élevée (Rz = n × P) pour supporter le poids apparent accru. À une vitesse donnée, cela nécessite un Cz plus élevé. Par conséquent, l'aile atteint Cz,max à une vitesse plus élevée qu'en vol rectiligne. La relation est : v_décrochage,virage = v_décrochage,rectiligne × √n. Par exemple, un planeur décrochant à 75 km/h en rectiligne décrochera à 106 km/h dans un virage à 60° (n=2) - une augmentation dangereuse de 41% que les pilotes ne prennent souvent pas en compte.

---

### Q6 (Multiple Choice): In a 45° banked turn, by what factor does stall speed increase?

- A) 1.15× (15% increase)
- B) 1.19× (19% increase)
- C) 1.41× (41% increase)
- D) 2.00× (100% increase)

**A:** B) 1.19× (19% increase). At 45° bank, load factor n = 1.41. Stall speed increases by √n = √1.41 = 1.19. So if straight-flight stall is 75 km/h, stall in 45° bank is 75 × 1.19 = 89 km/h - a 19% increase. Note that this is NOT the same as the load factor itself (which is 41% increase) - stall speed increases by square root of load factor.

**DE:** B) 1,19× (19% Erhöhung). Bei 45° Querneigung ist der Lastvielfach n = 1,41. Die Überziehgeschwindigkeit steigt um √n = √1,41 = 1,19. Wenn also die Überziehgeschwindigkeit im Geradeausflug 75 km/h beträgt, ist die Überziehgeschwindigkeit in 45°-Kurve 75 × 1,19 = 89 km/h - eine Erhöhung um 19%. Beachten Sie, dass dies NICHT dasselbe ist wie der Lastvielfach selbst (der eine Erhöhung um 41% ist) - die Überziehgeschwindigkeit steigt um die Quadratwurzel des Lastvielfachs.

**FR:** B) 1,19× (augmentation de 19%). À 45° d'inclinaison, le facteur de charge n = 1,41. La vitesse de décrochage augmente de √n = √1,41 = 1,19. Donc si le décrochage en vol rectiligne est de 75 km/h, le décrochage dans un virage à 45° est de 75 × 1,19 = 89 km/h - une augmentation de 19%. Notez que ce n'est PAS la même chose que le facteur de charge lui-même (qui est une augmentation de 41%) - la vitesse de décrochage augmente par la racine carrée du facteur de charge.

---

### Q7: Why are low-altitude steep turns so dangerous?

**A:** Low-altitude steep turns combine multiple hazards: (1) Steep bank (>45°) significantly increases stall speed (up to 41% at 60° bank), (2) High drag in turns causes airspeed to bleed off unless power/altitude is added, (3) Pilot may not realize stall speed has increased and believes airspeed is safe, (4) If stall occurs, spin entry is likely in a turn, (5) Insufficient altitude to complete spin recovery before ground impact. The classic fatal scenario is overshooting base-to-final turn and tightening the turn instead of going around - this has killed countless pilots. Rule: never exceed 30° bank below 300m AGL.

**DE:** Steile Kurven in niedriger Höhe kombinieren mehrere Gefahren: (1) Steile Querneigung (>45°) erhöht die Überziehgeschwindigkeit erheblich (bis zu 41% bei 60° Querneigung), (2) Hoher Widerstand in Kurven führt zum Geschwindigkeitsabbau, wenn keine Leistung/Höhe hinzugefügt wird, (3) Pilot bemerkt möglicherweise nicht, dass die Überziehgeschwindigkeit gestiegen ist und glaubt, die Fluggeschwindigkeit sei sicher, (4) Wenn ein Überziehen auftritt, ist ein Trudelneintritt in einer Kurve wahrscheinlich, (5) Unzureichende Höhe, um die Trudelausleitung vor dem Bodenaufprall abzuschließen. Das klassische tödliche Szenario ist das Überschießen der Kurve von Queranflug auf Endanflug und das Verschärfen der Kurve anstatt durchzustarten - dies hat unzählige Piloten getötet. Regel: Niemals mehr als 30° Querneigung unter 300m AGL.

**FR:** Les virages serrés à basse altitude combinent plusieurs dangers : (1) L'inclinaison prononcée (>45°) augmente considérablement la vitesse de décrochage (jusqu'à 41% à 60° d'inclinaison), (2) La traînée élevée dans les virages fait diminuer la vitesse sauf si de la puissance/altitude est ajoutée, (3) Le pilote peut ne pas réaliser que la vitesse de décrochage a augmenté et croit que la vitesse est sûre, (4) Si le décrochage se produit, l'entrée en vrille est probable dans un virage, (5) Altitude insuffisante pour compléter la sortie de vrille avant l'impact au sol. Le scénario fatal classique est de dépasser le virage vent arrière-finale et de serrer le virage au lieu de remettre les gaz - cela a tué d'innombrables pilotes. Règle : ne jamais dépasser 30° d'inclinaison en dessous de 300m sol.

---

### Q8 (Multiple Choice): What is the primary reason gliders sink faster in turns?

- A) Reduced wing efficiency due to asymmetric flow
- B) Increased profile drag from higher control deflections
- C) Increased induced drag from higher lift coefficient needed
- D) Reduced airspeed causing separation at wing tips

**A:** C) Increased induced drag from higher lift coefficient needed. In a turn, the wing must generate more total lift (n × weight) to support the increased apparent weight. This requires either higher Cz at the same speed, or higher speed at the same Cz. Higher Cz produces dramatically more induced drag (Di ∝ Cz²), which is the dominant factor increasing sink rate in turns. This is why turn polars show progressively worse performance as bank angle increases.

**DE:** C) Erhöhter induzierter Widerstand durch benötigten höheren Auftriebsbeiwert. In einer Kurve muss der Flügel mehr Gesamtauftrieb (n × Gewicht) erzeugen, um das erhöhte scheinbare Gewicht zu tragen. Dies erfordert entweder höheres Cz bei gleicher Geschwindigkeit oder höhere Geschwindigkeit bei gleichem Cz. Höheres Cz erzeugt dramatisch mehr induzierten Widerstand (Di ∝ Cz²), was der dominierende Faktor für die Erhöhung der Sinkrate in Kurven ist. Deshalb zeigen Kurvenpolaren progressiv schlechtere Leistung, wenn der Querneigungswinkel zunimmt.

**FR:** C) Traînée induite accrue due au coefficient de portance plus élevé nécessaire. Dans un virage, l'aile doit générer une portance totale plus élevée (n × poids) pour supporter le poids apparent accru. Cela nécessite soit un Cz plus élevé à la même vitesse, soit une vitesse plus élevée au même Cz. Un Cz plus élevé produit considérablement plus de traînée induite (Di ∝ Cz²), qui est le facteur dominant augmentant le taux de chute dans les virages. C'est pourquoi les polaires de virage montrent des performances progressivement pires à mesure que l'angle d'inclinaison augmente.

---

## Related Topics

Turns and load factor connect to broader flight mechanics:

- **[Straight Flight](./05-straight-flight.md)** - Foundation: force balance in non-turning flight
- **[Aerodynamic Forces](./03-aerodynamic-forces.md)** - Lift and drag fundamentals
- **[Stalls and Spins](./07-stalls-and-spins.md)** - Critical: stall behavior in turns
- **[Control Surfaces](./08-control-surfaces.md)** - How ailerons and rudder coordinate turns
- **[Aircraft Stability](./09-aircraft-stability.md)** - Spiral stability and Dutch roll

## External Resources

### English
- [Load Factor and Bank Angle - FAA](https://www.faa.gov/regulations_policies/handbooks_manuals/aviation/phak/media/09_phak_ch7.pdf)
- [Turning Flight Physics - NASA](https://www.grc.nasa.gov/www/k-12/airplane/turns.html)
- [Accelerated Stalls - AOPA](https://www.aopa.org/training-and-safety/students/presolo/special/accelerated-stalls)
- [Load Factor in Turns - Boldmethod](https://www.boldmethod.com/learn-to-fly/aerodynamics/load-factor/)
- [Turn Performance - Wikipedia](https://en.wikipedia.org/wiki/Standard_rate_turn)

### Deutsch
- [Lastvielfaches - Wikipedia](https://de.wikipedia.org/wiki/Lastvielfaches)
- [Kurvenflug Physik - Segelflug Wiki](https://www.segelflug-wiki.de/index.php/Kurvenflug)
- [Strömungsabriss in Kurven - DAeC](https://www.daec.de/sportarten/segelflug/ausbildung/)

### Français
- [Facteur de charge - Wikipedia](https://fr.wikipedia.org/wiki/Facteur_de_charge_(a%C3%A9ronautique))
- [Vol en virage - Planeur.net](https://www.planeur.net/technique-de-vol/vol-en-virage/)
- [Décrochage en virage - FFVV](https://www.ffvv.org/fr/formation/securite)

---

## Navigation

**⬅ Previous Lesson:** [Straight Flight](./05-straight-flight.md)

**[⬆ Back to Course Overview](../README.md)**

**➡ Next Lesson:** [Stalls and Spins](./07-stalls-and-spins.md)
