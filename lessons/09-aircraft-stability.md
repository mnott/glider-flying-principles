# 7. Aircraft Stability (Stabilité)

**Reference:** PDF Pages 65-70 (Part 2)

## Introduction

Stability is what makes an aircraft return to equilibrium after a disturbance—whether from turbulence, a control input, or other forces. It's the aerodynamic equivalent of a ball in a valley: push it, and it rolls back to the bottom. Without stability, flight would require constant, exhausting pilot corrections. Too much stability, however, makes an aircraft sluggish and unresponsive.

Understanding stability isn't just academic theory—it directly affects how your glider handles, how fatiguing it is to fly, and whether it recovers safely from upsets. This chapter explores the principles that make aircraft naturally return to trimmed flight, the design features that provide stability around each axis, and the inherent trade-off between stability and maneuverability.

**Why this matters:** Stability characteristics determine whether a glider is forgiving for student pilots or responsive for experienced competition pilots. Understanding how your aircraft is stabilized helps you recognize normal behavior versus dangerous departures from controlled flight. It also explains why certain center-of-gravity limits exist and why they're critically important for safety.

## Principles and Definitions

### What is Stability?

To understand stability, we analyze how a system behaves after a perturbation (disturbance).

**Three types of equilibrium:**

**1. Stable Equilibrium (Équilibre stable)**
- After disturbance, the system returns to original state
- Example: Ball in a valley—push it, it rolls back to center
- **In aviation:** Aircraft returns to trimmed flight after turbulence

**2. Unstable Equilibrium (Équilibre instable)**
- After disturbance, the system moves further from original state
- Example: Ball balanced on top of a hill—slightest push makes it roll away
- **In aviation:** Disturbance causes divergence from original flight condition

**3. Neutral/Indifferent Equilibrium (Équilibre indifférent)**
- After disturbance, system settles in new equilibrium
- Example: Ball on flat surface—push it, it stays in new position
- **In aviation:** Aircraft remains in disturbed attitude without returning or diverging

### Aircraft Stability Concepts

An aircraft in stabilized flight is in:
- **Translational equilibrium:** Sum of forces = zero (no acceleration)
- **Rotational equilibrium:** Sum of moments = zero (no rotation)

A perturbation can come from:
- Brief control input
- Turbulence/gust
- Sudden change in air mass properties

These create momentary rotation around one of the three axes (pitch, roll, yaw).

**A stable aircraft returns to the original flight attitude automatically.**

### Types of Stability

**1. Static Stability vs. Dynamic Stability**

**Static stability:** Does the aircraft initially move back toward equilibrium after disturbance?
- Examines immediate tendency (first moment after disturbance)
- Positive static stability = initial restoring tendency
- Neutral static stability = no initial tendency
- Negative static stability = initial diverging tendency

**Dynamic stability:** How does the aircraft return to equilibrium over time?
- Examines the motion pattern during return
- Can be oscillatory (damped oscillations)
- Can be direct (smooth return without overshoot)
- Requires positive static stability as foundation

**This course focuses on static stability** as it's more fundamental and easier to understand.

**2. Controls-Fixed vs. Controls-Free Stability**

**Controls-fixed:** Control surfaces held in fixed position (locked)
**Controls-free:** Control surfaces free to move with aerodynamic forces

**We'll discuss only controls-fixed stability** (assuming control surfaces remain fixed during disturbance).

### Stability vs. Maneuverability

**Maneuverability** is the ease with which an aircraft can be made to change attitude:
- Low control forces = high maneuverability
- Quick response to inputs = high maneuverability

**The inherent trade-off:**
- High stability → Low maneuverability (aircraft resists attitude changes)
- High maneuverability → Low stability (aircraft doesn't strongly resist changes)

**Design philosophy:**
- **Training gliders:** More stability (forgiving, returns to safe flight easily)
- **Competition gliders:** Less stability (responsive, efficient control inputs)
- **Aerobatic aircraft:** Low stability (highly maneuverable)

Theory shows that stability and maneuverability are fundamentally opposed characteristics. Aircraft design is always a compromise based on intended mission.

## Longitudinal Stability (Pitch Stability / Stabilité de Tangage)

Longitudinal stability is stability around the pitch (lateral) axis—the aircraft's tendency to return to trimmed angle of attack after a pitch disturbance.

### Key Centers and Their Relationship

**Center of Gravity (CDG / Centre de Gravité)**
- Point where weight force acts
- Location determined by mass distribution
- Can be adjusted by adding ballast (nose weight, tail weight)
- **CG limits** specified by manufacturer are critical for safety

**Center of Pressure (CDP / Centre de Poussée)**
- Point where resultant aerodynamic force acts
- Determined by wing profile, aircraft shape, and angle of attack
- **Migrates slightly forward as angle of attack increases**
- Cannot be changed without altering aircraft shape

### Design for Longitudinal Stability

**Two fundamental requirements:**

**1. CG ahead of CP (within limits)**

The center of gravity must be forward of the center of pressure—but not too far forward. This creates the foundation for stable pitch behavior.

**2. Negative incidence angle on horizontal stabilizer**

The horizontal stabilizer (tail plane) is set at a slight negative angle of incidence relative to the wing. This means:
- When the wing is at positive angle of attack (creating lift)
- The tail is at less positive or negative angle of attack
- **The tail produces downward force** (negative lift)

### How Longitudinal Stability Works

**In equilibrium flight:**

- **Wing lift (RzA):** Acts at center of pressure, creating **nose-down pitching moment (MP)** about the CG
- **Tail down-force (RzE):** Acts at tail, creating **nose-up pitching moment (MC)** about the CG
- **In equilibrium:** MP = MC (moments balance)

**After nose-up disturbance (pitch up):**

Two stabilizing effects occur:

**Effect 1 - Wing:**
- Angle of attack increases
- Wing lift (RzA) increases
- **Nose-down moment (MP) increases**

**Effect 2 - Tail:**
- Angle of attack of tail increases (becomes less negative or more positive)
- Tail down-force (RzE) decreases (or may reverse to upward force)
- **Nose-up moment (MC) decreases**

**Result:** Two nose-down effects combine → Aircraft pitches nose-down back toward equilibrium.

**After nose-down disturbance (pitch down):**

The reader should reason through this:
- Wing angle of attack decreases → RzA decreases → MP decreases
- Tail angle of attack decreases → RzE increases → MC increases
- Result: Nose-up restoring moment

**Phugoid Motion**

The return to equilibrium may involve oscillations (phugoid trajectory):
- Aircraft pitches up, slows, pitches down
- Pitches down, speeds up, pitches back up
- Oscillations gradually dampen out
- Period typically 30-60 seconds in gliders

**Well-designed aircraft:** Phugoid oscillations dampen quickly without pilot input.

### CG Position and Stability

**CG too far forward:**
- Very stable (large stabilizing moments)
- Heavy control forces (hard to change pitch attitude)
- Poor maneuverability
- May be unable to flare for landing (insufficient elevator authority)

**CG too far aft:**
- Reduced stability
- Light control forces
- Excellent maneuverability
- **DANGEROUS:** Beyond aft limit, aircraft becomes unstable
- Unstable aircraft can diverge into uncontrollable pitch-up or pitch-down

**CG limits exist for critical safety reasons.** Always check CG is within limits before flight.

## Lateral Stability (Roll Stability / Stabilité de Roulis)

Lateral stability is the aircraft's tendency to return to wings-level flight after a roll disturbance.

### Design Features for Roll Stability

**1. Dihedral Angle (Angle de Dièdre - δ)**

The upward angle of the wings from root to tip when viewed from front.

**How dihedral provides stability:**

When aircraft rolls (say, right wing drops):
1. **Lift vector tilts with aircraft**
2. Tilted lift has lateral component
3. **Lateral component causes sideslip** (aircraft slides sideways toward lowered wing)
4. Sideslip creates **relative wind from the side**
5. Lowered wing sees increased angle of attack (wind hits it more from below)
6. Raised wing sees decreased angle of attack (wind hits it more from above)
7. **Lowered wing gets more lift; raised wing gets less lift**
8. Differential lift creates rolling moment that levels the wings

**Additional effect:** The raised wing is partially masked by the fuselage, further reducing its lift.

**Design variations:**
- Constant dihedral along entire span
- Progressive dihedral (changing from root to tip)
- Example: DG-1000 has progressively increasing dihedral

**2. High Wing Configuration**

Vertical surfaces (fuselage, vertical stabilizer) below the wing contribute to roll stability through keel effect.

**3. Winglets (Pennes)**

Vertical surfaces at wingtips can contribute to roll stability while also reducing induced drag.

## Directional Stability (Yaw Stability / Stabilité de Lacet)

Directional stability is the aircraft's tendency to align with the relative wind—like a weathervane.

### Design Features for Yaw Stability

**1. Vertical Stabilizer (Fin / Dérive)**

The primary source of directional stability through weathervane effect.

**How it works:**

When aircraft yaws (nose swings left):
1. **Vertical stabilizer gets angle of attack** to the side
2. Fin develops side force (F)
3. Side force × lever arm creates yawing moment
4. **Yawing moment rotates nose back into wind**

The larger the fin area and longer the fuselage (lever arm), the stronger the directional stability.

**2. Wing Sweep (Flèche)**

The angle the wing makes with the lateral axis when viewed from above.

**Types:**
- **Positive sweep:** Leading edge angled backward (swept back)
- **Negative sweep:** Leading edge angled forward (swept forward)
- **Variable sweep:** Different sweep angles along span

**How sweep provides yaw stability:**

When aircraft yaws (nose swings right):
1. Right wing (now advanced) sees higher angle of attack than left wing
2. Right wing also presents more frontal area to airflow
3. Right wing generates more **drag** than left wing
4. **Differential drag creates yawing moment** that rotates nose back left

Modern high-performance gliders often have:
- Straight or slightly swept wings at root
- Swept tips
- Example: ASW-27B combines constant dihedral with swept wing tips

### Complex Interactions

Roll and yaw motions are intimately coupled:
- Roll disturbance induces yaw (through induced drag differences)
- Yaw disturbance induces roll (through dihedral effect)
- Adverse yaw from ailerons couples roll and yaw
- Spiral stability involves both roll and yaw stability

**The reality:** Stability analysis is highly complex. Our treatment here provides only basic understanding of fundamental principles.

## Stability Summary Across Axes

| Stability Type | Primary Design Features | Stabilizing Mechanism |
|----------------|------------------------|----------------------|
| **Longitudinal (Pitch)** | CG ahead of CP, Negative tail incidence | Tail down-force creates restoring moment when disturbed |
| **Lateral (Roll)** | Dihedral angle, Winglets | Sideslip causes differential angle of attack → differential lift → leveling moment |
| **Directional (Yaw)** | Vertical fin, Wing sweep | Weathervane effect (fin) and differential drag (sweep) align aircraft with relative wind |

**Key principle:** Stable aircraft has design features that create restoring moments opposing any disturbance from equilibrium flight.

## Questions / Fragen / Questions

### Q1: What are the three types of equilibrium and how do they relate to aircraft stability?

**A:** The three types are:
1. **Stable equilibrium** - system returns to original state after disturbance (desired in aircraft)
2. **Unstable equilibrium** - system diverges further after disturbance (dangerous in aircraft)
3. **Neutral/indifferent equilibrium** - system remains in new state after disturbance

In aircraft terms, a stable aircraft returns to trimmed flight after disturbances like turbulence or brief control inputs. An unstable aircraft would diverge into increasingly extreme attitudes. Neutral stability would mean the aircraft remains in whatever attitude the disturbance left it in.

**DE:** Die drei Typen sind:
1. **Stabiles Gleichgewicht** - System kehrt nach Störung zum ursprünglichen Zustand zurück (erwünscht bei Flugzeugen)
2. **Instabiles Gleichgewicht** - System weicht nach Störung weiter ab (gefährlich bei Flugzeugen)
3. **Neutrales/indifferentes Gleichgewicht** - System verbleibt nach Störung im neuen Zustand

In Flugzeugbegriffen kehrt ein stabiles Flugzeug nach Störungen wie Turbulenz oder kurzen Steuereingaben zum getrimmten Flug zurück. Ein instabiles Flugzeug würde in zunehmend extreme Lagen abweichen. Neutrale Stabilität würde bedeuten, dass das Flugzeug in der Lage verbleibt, in die es die Störung versetzt hat.

**FR:** Les trois types sont :
1. **Équilibre stable** - le système retourne à l'état original après perturbation (souhaité pour les avions)
2. **Équilibre instable** - le système diverge davantage après perturbation (dangereux pour les avions)
3. **Équilibre neutre/indifférent** - le système reste dans le nouvel état après perturbation

En termes aéronautiques, un avion stable retourne au vol stabilisé après des perturbations comme la turbulence ou de brèves commandes. Un avion instable divergerait vers des attitudes de plus en plus extrêmes. Une stabilité neutre signifierait que l'avion reste dans l'attitude où la perturbation l'a laissé.

### Q2: What is the fundamental trade-off between stability and maneuverability?

**A:** Stability and maneuverability are inherently opposed. A highly stable aircraft strongly resists changes in attitude, requiring larger control forces and responding slowly—it has low maneuverability. A highly maneuverable aircraft responds quickly with light control forces but naturally has low stability. Aircraft design is always a compromise: training gliders prioritize stability (forgiving, safe), while competition gliders and aerobatic aircraft prioritize maneuverability (responsive, efficient control).

**DE:** Stabilität und Manövrierfähigkeit stehen grundsätzlich im Gegensatz. Ein hochstabiles Flugzeug widersteht stark Lageänderungen, erfordert größere Steuerkräfte und reagiert langsam – es hat geringe Manövrierfähigkeit. Ein hochmanövrierfähiges Flugzeug reagiert schnell mit leichten Steuerkräften, hat aber naturgemäß geringe Stabilität. Flugzeugdesign ist immer ein Kompromiss: Schulungssegelflugzeuge priorisieren Stabilität (verzeihend, sicher), während Wettbewerbssegelflugzeuge und Kunstflugzeuge Manövrierfähigkeit priorisieren (reaktionsschnell, effiziente Steuerung).

**FR:** La stabilité et la maniabilité sont fondamentalement opposées. Un avion très stable résiste fortement aux changements d'attitude, nécessitant des forces de commande plus importantes et répondant lentement – il a une faible maniabilité. Un avion très maniable répond rapidement avec des forces de commande légères, mais a naturellement une faible stabilité. La conception d'avion est toujours un compromis : les planeurs d'entraînement privilégient la stabilité (tolérant, sûr), tandis que les planeurs de compétition et les avions acrobatiques privilégient la maniabilité (réactif, contrôle efficace).

### Q3: Why must the center of gravity be ahead of the center of pressure for longitudinal stability?

**A:** With CG ahead of CP, the wing's lift force creates a nose-down pitching moment about the CG, while the horizontal stabilizer's down-force creates a balancing nose-up moment. When disturbed nose-up, wing lift increases (increasing nose-down moment) while tail down-force decreases (decreasing nose-up moment)—both effects pitch the nose down toward equilibrium. This creates the fundamental restoring tendency needed for pitch stability. If CG were behind CP, these effects would reverse, creating divergent (unstable) behavior.

**DE:** Mit dem Schwerpunkt vor dem Druckpunkt erzeugt die Auftriebskraft des Flügels ein nickabwärts gerichtetes Moment um den Schwerpunkt, während die Abwärtskraft des Höhenleitwerks ein ausgleichendes nickaufwärts gerichtetes Moment erzeugt. Bei einer Störung nach oben erhöht sich der Flügelauftrieb (erhöht nickabwärts gerichtetes Moment), während die Hecklastkraft abnimmt (verringert nickaufwärts gerichtetes Moment) – beide Effekte neigen die Nase nach unten zum Gleichgewicht. Dies schafft die grundlegende Rückstelltendenz, die für Nickstabilität erforderlich ist. Läge der Schwerpunkt hinter dem Druckpunkt, würden sich diese Effekte umkehren und divergentes (instabiles) Verhalten erzeugen.

**FR:** Avec le CDG en avant du CDP, la force de portance de l'aile crée un moment piqueur autour du CDG, tandis que la force vers le bas du stabilisateur horizontal crée un moment cabreur équilibrant. Lors d'une perturbation cabrant, la portance de l'aile augmente (augmentant le moment piqueur) tandis que la force vers le bas de la queue diminue (diminuant le moment cabreur) – les deux effets font piquer le nez vers l'équilibre. Cela crée la tendance de restauration fondamentale nécessaire pour la stabilité de tangage. Si le CDG était derrière le CDP, ces effets s'inverseraient, créant un comportement divergent (instable).

### Q4: How does wing dihedral provide roll stability?

**A:** When a wing drops (roll disturbance), the tilted lift force creates a lateral component that causes the aircraft to sideslip toward the lowered wing. This sideslip creates relative wind from the side. Due to dihedral, the lowered wing now sees this sidewind from below (increased angle of attack) while the raised wing sees it from above (decreased angle of attack). The lowered wing generates more lift, the raised wing less lift, creating a rolling moment that levels the wings. Additionally, the raised wing is partially masked by the fuselage, further reducing its lift.

**DE:** Wenn ein Flügel absinkt (Rollstörung), erzeugt die geneigte Auftriebskraft eine Seitenkomponente, die das Flugzeug zum abgesenkten Flügel seitlich abrutschen lässt. Dieses Seitenabrutschen erzeugt relativen Wind von der Seite. Aufgrund der V-Form sieht der abgesenkte Flügel diesen Seitenwind nun von unten (erhöhter Anstellwinkel), während der angehobene Flügel ihn von oben sieht (verringerter Anstellwinkel). Der abgesenkte Flügel erzeugt mehr Auftrieb, der angehobene Flügel weniger Auftrieb, wodurch ein Rollmoment entsteht, das die Flügel nivelliert. Zusätzlich wird der angehobene Flügel teilweise vom Rumpf verdeckt, was seinen Auftrieb weiter reduziert.

**FR:** Lorsqu'une aile descend (perturbation de roulis), la force de portance inclinée crée une composante latérale qui fait glisser l'avion latéralement vers l'aile abaissée. Ce glissement latéral crée un vent relatif sur le côté. En raison du dièdre, l'aile abaissée voit maintenant ce vent latéral d'en bas (angle d'attaque augmenté) tandis que l'aile relevée le voit d'en haut (angle d'attaque diminué). L'aile abaissée génère plus de portance, l'aile relevée moins de portance, créant un moment de roulis qui nivelle les ailes. De plus, l'aile relevée est partiellement masquée par le fuselage, réduisant encore sa portance.

### Q5: Multiple Choice - What happens if an aircraft's center of gravity is too far aft (behind the aft CG limit)?

A) The aircraft becomes very stable and safe
B) Control forces become heavier
C) The aircraft becomes unstable and potentially uncontrollable
D) Maneuverability decreases significantly

**A:** **C is correct.** When CG is too far aft, the aircraft loses longitudinal stability and can become unstable. The stabilizing moments from the wing-tail combination become too weak or reverse. The aircraft may enter divergent pitch oscillations (increasingly severe pitch-ups or pitch-downs) that the pilot cannot control. This is extremely dangerous and can lead to loss of control. CG limits exist for critical safety reasons—they must never be exceeded.

**DE:** **C ist richtig.** Wenn der Schwerpunkt zu weit hinten liegt, verliert das Flugzeug die Längsstabilität und kann instabil werden. Die stabilisierenden Momente aus der Flügel-Heck-Kombination werden zu schwach oder kehren sich um. Das Flugzeug kann divergente Nickschwingungen (zunehmend schwere Aufwärts- oder Abwärtsbewegungen) eingehen, die der Pilot nicht kontrollieren kann. Dies ist äußerst gefährlich und kann zum Kontrollverlust führen. Schwerpunktgrenzen existieren aus kritischen Sicherheitsgründen – sie dürfen niemals überschritten werden.

**FR:** **C est correct.** Lorsque le CDG est trop en arrière, l'avion perd sa stabilité longitudinale et peut devenir instable. Les moments stabilisateurs de la combinaison aile-empennage deviennent trop faibles ou s'inversent. L'avion peut entrer dans des oscillations de tangage divergentes (cabré ou piqué de plus en plus sévères) que le pilote ne peut pas contrôler. C'est extrêmement dangereux et peut conduire à une perte de contrôle. Les limites de CDG existent pour des raisons de sécurité critiques – elles ne doivent jamais être dépassées.

### Q6: What is the weathervane effect and how does it provide directional stability?

**A:** The weathervane (or weather vane) effect is how the vertical stabilizer provides directional stability, similar to how a weathervane aligns with wind. When the aircraft yaws (nose swings sideways), the vertical fin develops an angle of attack to the relative wind, creating a side force. This force, acting at a distance (lever arm) behind the center of gravity, creates a yawing moment that rotates the nose back into alignment with the airflow. The larger the fin area and longer the tail moment arm, the stronger this stabilizing effect.

**DE:** Der Wetterfahneneffekt ist, wie das Seitenleitwerk für Richtungsstabilität sorgt, ähnlich wie eine Wetterfahne sich mit dem Wind ausrichtet. Wenn das Flugzeug giert (Nase schwingt seitlich), entwickelt die vertikale Flosse einen Anstellwinkel zum relativen Wind und erzeugt eine Seitenkraft. Diese Kraft, die in einem Abstand (Hebelarm) hinter dem Schwerpunkt wirkt, erzeugt ein Giermoment, das die Nase zurück in Ausrichtung mit der Luftströmung dreht. Je größer die Flossenfläche und je länger der Heckmomentarm, desto stärker dieser stabilisierende Effekt.

**FR:** L'effet de girouette est la façon dont la dérive fournit une stabilité directionnelle, similaire à la façon dont une girouette s'aligne avec le vent. Lorsque l'avion effectue un lacet (le nez oscille latéralement), la dérive verticale développe un angle d'attaque par rapport au vent relatif, créant une force latérale. Cette force, agissant à une distance (bras de levier) derrière le centre de gravité, crée un moment de lacet qui fait tourner le nez pour se réaligner avec l'écoulement d'air. Plus la surface de la dérive est grande et plus le bras de levier de la queue est long, plus cet effet stabilisant est fort.

### Q7: Multiple Choice - In a phugoid oscillation after a pitch disturbance, what happens?

A) The aircraft spirals downward uncontrollably
B) The aircraft oscillates in pitch, alternately gaining and losing speed and altitude
C) The aircraft immediately returns to trimmed flight without oscillation
D) Only the wings oscillate while the fuselage remains stable

**A:** **B is correct.** A phugoid (or phugoid motion) is a long-period oscillation in pitch attitude, airspeed, and altitude that occurs after a pitch disturbance in a longitudinally stable aircraft. The aircraft pitches up (slowing and climbing), then pitches down (accelerating and descending), then pitches up again in cycles that typically last 30-60 seconds. In well-designed stable aircraft, these oscillations gradually dampen and the aircraft returns to trimmed flight. The phugoid demonstrates dynamic stability—the manner in which the aircraft returns to equilibrium over time.

**DE:** **B ist richtig.** Eine Phygoide (oder Phygoidbewegung) ist eine langperiodische Schwingung in Nicklage, Fluggeschwindigkeit und Höhe, die nach einer Nickstörung in einem längsstabilen Flugzeug auftritt. Das Flugzeug neigt sich nach oben (verlangsamt und steigt), dann nach unten (beschleunigt und sinkt), dann wieder nach oben in Zyklen, die typischerweise 30-60 Sekunden dauern. Bei gut konzipierten stabilen Flugzeugen dämpfen diese Schwingungen allmählich ab und das Flugzeug kehrt zum getrimmten Flug zurück. Die Phygoide demonstriert dynamische Stabilität – die Art und Weise, wie das Flugzeug im Laufe der Zeit zum Gleichgewicht zurückkehrt.

**FR:** **B est correct.** Une phugoïde (ou mouvement phugoïde) est une oscillation à longue période en attitude de tangage, vitesse et altitude qui se produit après une perturbation de tangage dans un avion longitudinalement stable. L'avion cabre (ralentit et monte), puis pique (accélère et descend), puis cabre à nouveau en cycles qui durent généralement 30 à 60 secondes. Dans les avions stables bien conçus, ces oscillations s'amortissent progressivement et l'avion retourne au vol stabilisé. La phugoïde démontre la stabilité dynamique – la manière dont l'avion retourne à l'équilibre au fil du temps.

## Related Topics

Stability ties together aerodynamic forces and design geometry:

- **[Aerodynamic Forces](./03-aerodynamic-forces.md)** - Forces that must balance for stability
- **[Induced Drag and Wing Geometry](./04-induced-drag-and-wing-geometry.md)** - Dihedral and sweep provide stability
- **[Stalls and Spins](./07-stalls-and-spins.md)** - CG position affects stall/spin characteristics
- **[Control Surfaces](./08-control-surfaces.md)** - Tail surfaces provide stabilizing forces

## External Resources

- [FAA Pilot's Handbook of Aeronautical Knowledge - Chapter 5: Aerodynamics](https://www.faa.gov/regulations_policies/handbooks_manuals/aviation/phak) - Section on stability and control
- [Wikipedia: Aircraft Flight Dynamics](https://en.wikipedia.org/wiki/Flight_dynamics_(fixed-wing_aircraft)) - Comprehensive coverage of stability concepts
- [Wikipedia: Longitudinal Static Stability](https://en.wikipedia.org/wiki/Longitudinal_static_stability) - Detailed pitch stability analysis
- [NASA: Aircraft Stability](https://www.grc.nasa.gov/www/k-12/airplane/stabilty.html) - Educational resources on stability principles
- [EASA CS-22 Sailplanes Certification](https://www.easa.europa.eu/document-library/certification-specifications/cs-22-sailplanes-and-powered-sailplanes) - Regulatory requirements for stability
- [Wikipedia: Phugoid](https://en.wikipedia.org/wiki/Phugoid) - Detailed explanation of phugoid oscillations
- [Wikipedia: Center of Gravity](https://en.wikipedia.org/wiki/Center_of_gravity_of_an_aircraft) - CG calculation and importance

## Summary / Zusammenfassung / Résumé

**EN:** Aircraft stability is the tendency to return to equilibrium after disturbances. Stable equilibrium returns to original state; unstable equilibrium diverges; neutral equilibrium remains in disturbed state. We focus on static stability (initial tendency) with controls fixed. Stability and maneuverability are inversely related—stable aircraft are less maneuverable. Longitudinal stability requires CG ahead of CP and negative tail incidence; wing lift creates nose-down moment while tail down-force creates nose-up moment that balance in trim. Pitch disturbances create differential changes in these moments that restore equilibrium. Lateral stability comes from dihedral angle and winglets; roll disturbance causes sideslip that creates differential lift to level wings. Directional stability comes from vertical fin (weathervane effect) and wing sweep (differential drag). Return to equilibrium may involve damped oscillations (phugoid). CG position critically affects stability—too far aft causes instability and potential loss of control. Understanding stability helps pilots recognize normal aircraft behavior and maintain safe flight.

**DE:** Flugzeugstabilität ist die Tendenz, nach Störungen zum Gleichgewicht zurückzukehren. Stabiles Gleichgewicht kehrt zum ursprünglichen Zustand zurück; instabiles Gleichgewicht weicht ab; neutrales Gleichgewicht verbleibt im gestörten Zustand. Wir konzentrieren uns auf statische Stabilität (anfängliche Tendenz) mit festen Steuerungen. Stabilität und Manövrierfähigkeit sind umgekehrt proportional – stabile Flugzeuge sind weniger manövrierfähig. Längsstabilität erfordert Schwerpunkt vor Druckpunkt und negative Hecklage; Flügelauftrieb erzeugt nickabwärts gerichtetes Moment, während Hecklastkraft nickaufwärts gerichtetes Moment erzeugt, die im Trimm ausbalancieren. Nickstörungen erzeugen differentielle Änderungen in diesen Momenten, die das Gleichgewicht wiederherstellen. Seitenstabilität kommt von V-Form und Winglets; Rollstörung verursacht Seitenabrutschen, das differentiellen Auftrieb zum Nivellieren der Flügel erzeugt. Richtungsstabilität kommt von vertikaler Flosse (Wetterfahneneffekt) und Flügelpfeilung (differentieller Widerstand). Rückkehr zum Gleichgewicht kann gedämpfte Schwingungen (Phygoide) beinhalten. Schwerpunktposition beeinflusst kritisch die Stabilität – zu weit hinten verursacht Instabilität und potenziellen Kontrollverlust. Stabilitätsverständnis hilft Piloten, normales Flugzeugverhalten zu erkennen und sicheren Flug zu erhalten.

**FR:** La stabilité des avions est la tendance à retourner à l'équilibre après des perturbations. L'équilibre stable retourne à l'état original ; l'équilibre instable diverge ; l'équilibre neutre reste dans l'état perturbé. Nous nous concentrons sur la stabilité statique (tendance initiale) avec commandes fixes. La stabilité et la maniabilité sont inversement liées – les avions stables sont moins maniables. La stabilité longitudinale nécessite le CDG en avant du CDP et une incidence de queue négative ; la portance de l'aile crée un moment piqueur tandis que la force vers le bas de la queue crée un moment cabreur qui s'équilibrent en trim. Les perturbations de tangage créent des changements différentiels dans ces moments qui restaurent l'équilibre. La stabilité latérale provient de l'angle de dièdre et des winglets ; la perturbation de roulis provoque un glissement latéral qui crée une portance différentielle pour niveler les ailes. La stabilité directionnelle provient de la dérive verticale (effet de girouette) et de la flèche de l'aile (traînée différentielle). Le retour à l'équilibre peut impliquer des oscillations amorties (phugoïde). La position du CDG affecte de manière critique la stabilité – trop en arrière provoque une instabilité et une perte potentielle de contrôle. Comprendre la stabilité aide les pilotes à reconnaître le comportement normal de l'avion et à maintenir un vol sûr.

---
**Keywords:** stability, stabilité, equilibrium, équilibre, longitudinal stability, stabilité de tangage, lateral stability, stabilité de roulis, directional stability, stabilité de lacet, center of gravity, centre de gravité, center of pressure, centre de poussée, dihedral, dièdre, weathervane effect, effet de girouette, wing sweep, flèche, phugoid, phugoïde, static stability, dynamic stability, maneuverability, maniabilité, CG limits

---

## Navigation

**⬅ Previous Lesson:** [Control Surfaces](./08-control-surfaces.md)

**[⬆ Back to Course Overview](../README.md)**

**➡ Next Lesson:** [Propeller Concepts](./10-propeller-concepts.md)
