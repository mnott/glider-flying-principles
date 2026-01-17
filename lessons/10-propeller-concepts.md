# 8. Propeller Concepts (Notions sur l'Hélice)

**Reference:** PDF Pages 71-74 (Part 2)

## Introduction

With the increasing popularity of self-launching gliders and touring motor gliders (TMG), understanding propeller operation has become relevant for glider pilots. The propeller is the mechanical interface between engine power and forward thrust—it's a rotating wing that accelerates air backward, producing forward thrust through Newton's third law (action-reaction).

This chapter covers the fundamental aerodynamics of propellers, how blade geometry varies along the radius, the concepts of geometric and effective pitch, performance characteristics at different speeds, and special considerations like variable-pitch and constant-speed propellers. Understanding these concepts helps pilots operate powered gliders efficiently and recognize why certain procedures (like feathering) are critical for optimal glide performance.

**Why this matters:** For TMG pilots, proper propeller management directly affects climb performance, cruise efficiency, and glide performance with engine off. Improper propeller configuration (especially forgetting to feather after engine shutdown) can dramatically reduce glide ratio and potentially lead to off-field landings. Understanding propeller aerodynamics makes you a more competent powered glider pilot.

## Fundamental Principles

### How All Propulsion Systems Work

All propulsion systems operate on Newton's third law of motion (action-reaction principle):
- **Action:** System ejects mass backward
- **Reaction:** System experiences forward thrust force

**Different propulsion types:**

**Propeller systems (aircraft, helicopters):**
- Blow air backward
- Work in atmosphere
- Efficient at subsonic speeds

**Jet engines (turbojets, turbofans):**
- Eject high-velocity combustion products backward
- Work in atmosphere
- Efficient at high subsonic and supersonic speeds

**Rockets:**
- Eject combustion products of onboard fuel and oxidizer
- Work in atmosphere AND vacuum
- Can operate in space

**Key insight:** Propellers create thrust by accelerating a large mass of air to moderate velocity. Jets accelerate smaller mass to higher velocity. For subsonic flight, the propeller approach is more efficient.

### The Propeller as Rotating Wings

A propeller consists of **blades (pales)**—rotating airfoil sections. Each blade section is a miniature wing that generates lift, which becomes **thrust** when rotated at high speed.

**Velocity components at any point on the blade:**

At any radius from the propeller hub, the blade section experiences two velocity components:

1. **Rotational velocity (Vr - vitesse de rotation or vitesse de brassage):**
   - Due to rotation around the shaft
   - Increases proportionally with distance from hub: Vr = ω × r (where ω = angular velocity, r = radius)
   - At wingtip: highest velocity
   - At hub: zero velocity

2. **Forward velocity (V - vitesse de vol):**
   - Due to aircraft forward motion
   - Same for all blade sections (entire aircraft moving forward at same speed)

**Resultant relative velocity:** Vector sum of V and Vr

The blade section sees the relative wind at an angle determined by the composition of these two velocities.

## Blade Geometry and Twist

### Why Blades Are Twisted

Since rotational velocity Vr increases with radius, but forward velocity V is constant, the relative wind angle changes dramatically along the blade. To maintain optimal angle of attack along the entire blade, **blades are twisted (vrillage de pale).**

**Blade twist characteristics:**
- **Blade angle (β - angle de calage):** Angle between blade chord line and plane of rotation
- **Decreases from root to tip** (negative twist)
- Root sections: High blade angle (steep pitch)
- Tip sections: Low blade angle (fine pitch)

This ensures each blade section operates at approximately optimal angle of attack for maximum efficiency.

### Aerodynamic Forces on Blade Sections

At each blade section, the relative wind creates aerodynamic forces:

**Angles:**
- **α (alpha):** Angle of attack - angle between chord line and relative velocity
- **β (beta):** Blade angle - angle between chord line and plane of rotation
- **φ (phi):** Helix angle (advance angle) - angle between relative velocity and plane of rotation
- **Relationship:** φ = β - α

**Forces:**
- **T (Traction):** Thrust component - perpendicular to relative velocity, contributes to forward thrust
- **R (Résistance):** Resistance component - parallel to relative velocity, opposes rotation

**Note:** These are NOT the same as lift and drag!
- Lift is perpendicular to relative velocity
- Drag is parallel to relative velocity
- T and R are resolved from the aerodynamic resultant in directions useful for analyzing propeller performance

**Thrust generation:**
- Each blade section's T component contributes to total propeller thrust
- Sum of all T forces along all blades = total thrust

**Torque requirement:**
- Each blade section's R component creates resistance to rotation
- Sum of all R resistance moments = torque that engine must overcome

## Pitch Concepts

### Geometric Pitch (Pas Géométrique)

**Definition:** The theoretical distance the propeller would advance in one revolution if it were screwing through a solid medium (like a screw in wood).

**Determined by:** Blade angle β

**Analogy:** Just like a wood screw's threads determine how far it advances per turn, the propeller blade angle determines geometric pitch.

**Characteristic pitch:** Often specified as the pitch at 2/3 radius (representative pitch for the blade)

### Effective Pitch (Pas Effectif)

**Definition:** The actual distance the propeller advances through the air in one revolution.

**Determined by:** Angle of attack α (which depends on forward velocity and rotational velocity)

**Reality:** Effective pitch is always less than geometric pitch because:
- Air is fluid, not solid
- Blade must have positive angle of attack to generate thrust
- Blade "slips" backward relative to ideal geometric advance

### Slip (Recul)

**Definition:** Slip = Geometric pitch - Effective pitch

**Represents:** The "lost" forward motion due to blade operating at angle of attack in fluid medium

**Typical values:** 10-30% depending on propeller design and operating condition

**Physical meaning:** If geometric pitch is 2 meters and effective pitch is 1.7 meters, the propeller "slips" backward 0.3 meters per revolution—this is the necessary condition for generating thrust in a fluid medium.

## Propeller Performance

### Matching Propeller to Flight Condition

Like wings, propellers have optimal angle of attack for best efficiency. The challenge is that angle of attack changes with:
- Forward velocity (V)
- Rotational speed (RPM, which determines Vr)

**Climb (low speed, high RPM):**
- Low forward velocity V
- High rotational velocity Vr
- To achieve good angle of attack: need **low blade angle β** ("fine pitch" or "small pitch")
- Characteristics: High thrust, high power absorption, lower efficiency at speed

**Cruise (high speed, moderate RPM):**
- High forward velocity V
- Moderate rotational velocity Vr
- To achieve good angle of attack: need **high blade angle β** ("coarse pitch" or "large pitch")
- Characteristics: Efficient at speed, lower thrust, efficient power use

**The problem with fixed-pitch propellers:** Optimized for one flight condition, inefficient at others.

### Fixed-Pitch Propeller Limitations

A fixed-pitch propeller delivers full power only in a narrow speed range.

**"Climb propeller" (fine pitch):**
- Excellent for takeoff and climb
- Poor cruise efficiency (high RPM, high drag, low speed)
- Engine may over-rev at high speed

**"Cruise propeller" (coarse pitch):**
- Excellent for high-speed cruise
- Poor takeoff/climb performance (insufficient thrust, engine can't reach full power)
- May not allow engine to develop full rated power

**Performance graph insight:**
The power vs. speed curve for a fixed-pitch propeller shows peak power delivered only in a limited speed range. Outside this range, performance drops significantly.

### Variable-Pitch Propellers

**Solution:** Allow blade angle to be changed in flight

**Advantages:**
- Optimize angle of attack for different flight phases
- Achieve maximum engine power across wide speed range
- Better efficiency in all flight regimes

**Types:**

**1. Manual Variable-Pitch**
- Pilot selects pitch setting
- Different settings for takeoff, climb, cruise
- Common on many self-launching gliders

**2. Constant-Speed Propeller**
- Automatically adjusts blade angle to maintain constant RPM
- Pilot sets desired RPM; governor adjusts pitch as needed
- Most sophisticated system
- Keeps engine and propeller at optimal efficiency throughout flight

**How constant-speed works:**
- Fly slower → blade angle automatically decreases (fine pitch) → maintains RPM
- Fly faster → blade angle automatically increases (coarse pitch) → maintains RPM
- Engine operates at optimal RPM for power and efficiency regardless of airspeed

## Propeller Efficiency

### Efficiency Definition

**Propeller efficiency (η - rendement)** = Power delivered to aircraft / Power supplied by engine

**Typical values:** 80-90% for well-designed propellers

**What happens to the "lost" power?**
- Kinetic energy left in accelerated air (wake)
- Blade drag
- Tip losses (vortices at blade tips)
- Compressibility losses at high tip speeds

### Factors Affecting Efficiency

**1. Diameter vs. RPM**

**Larger diameter, slower RPM:**
- Higher efficiency
- Each blade section operates in cleaner flow
- Lower tip speeds reduce losses
- **But:** Weight, ground clearance, and structural limitations

**Smaller diameter, higher RPM:**
- Lower efficiency
- Higher tip speeds create more losses
- Can generate same thrust but less efficiently
- **Advantages:** Lighter, more compact, better ground clearance

**2. Number of Blades**

**Two blades:**
- Highest efficiency
- Simplest, lightest
- Requires larger diameter for given thrust

**Three blades:**
- Good compromise
- Slightly lower efficiency than two-blade
- Allows smaller diameter for same thrust
- Smoother operation (better balance, less vibration)

**Four or more blades:**
- Lower efficiency (blade interference effects)
- Allows very small diameter
- Very smooth operation
- Common on high-power installations where diameter is limited

**3. Tip Speed**

**Problem:** High tip speeds can approach or exceed sonic velocity
- Creates shock waves
- Dramatically increases drag
- Generates noise
- Destroys efficiency

**Design consideration:** Blade tip design (taper, twist, airfoil selection) critical for minimizing tip losses

## Special Considerations for Gliders

### Windmilling in Glide

**With engine off and propeller not feathered:**

The propeller is driven by the airflow (windmilling):
- Blade angle of attack becomes **negative**
- Propeller acts as **very effective airbrake**
- Glide performance severely degraded

**Effect:** Glide ratio can be reduced by 30-50% or more with windmilling propeller

### Feathering

**Feathering** means rotating blades to minimum drag position:
- Blade chord lines approximately parallel to airflow
- Minimum frontal area
- Minimum angle of attack (near zero)
- Blades stationary (not rotating)

**Critical procedure for TMG pilots:** After engine shutdown, immediately feather the propeller!

**Feathering dramatically improves glide performance:**
- Restores most of clean glider performance
- Typical loss: 2-5% of clean glide ratio (vs. 30-50% windmilling)

**On self-launchers with retractable engines:** Retract engine/propeller assembly into fuselage for cleanest glide configuration.

### Asymmetric Thrust Effects

**Single-engine aircraft with propeller ahead of CG:**

The propeller slipstream (helical airflow) wraps asymmetrically around the fuselage:
- Creates angle of attack on vertical fin
- Generates side force on fin
- Creates yawing moment

**For clockwise-rotating propeller (viewed from cockpit):**
- Slipstream hits left side of fin
- Creates yawing moment to the left
- Pilot must hold slight right rudder to maintain straight flight

**Note:** This is NOT gyroscopic effect (common misconception)—it's purely aerodynamic slipstream effect.

**Pylon-mounted engines:** Much less pronounced effect due to propeller being further from fuselage and vertical fin.

## Questions / Fragen / Questions

### Q1: How does a propeller generate thrust using Newton's third law?

**A:** A propeller operates on Newton's third law (action-reaction). The rotating blades are airfoils that accelerate air backward (action). By ejecting mass (air) backward, the propeller experiences an equal and opposite forward force (reaction)—this is thrust. The propeller is essentially a rotating wing; each blade section generates "lift" that, when rotated at high speed, becomes forward thrust that propels the aircraft.

**DE:** Ein Propeller arbeitet nach Newtons drittem Gesetz (Aktion-Reaktion). Die rotierenden Blätter sind Tragflächen, die Luft nach hinten beschleunigen (Aktion). Durch das Ausstoßen von Masse (Luft) nach hinten erfährt der Propeller eine gleiche und entgegengesetzte Vorwärtskraft (Reaktion) – das ist Schub. Der Propeller ist im Wesentlichen ein rotierender Flügel; jeder Blattabschnitt erzeugt "Auftrieb", der bei Rotation mit hoher Geschwindigkeit zum Vorwärtsschub wird, der das Flugzeug antreibt.

**FR:** Une hélice fonctionne selon la troisième loi de Newton (action-réaction). Les pales rotatives sont des profils aérodynamiques qui accélèrent l'air vers l'arrière (action). En éjectant de la masse (air) vers l'arrière, l'hélice subit une force vers l'avant égale et opposée (réaction) – c'est la traction. L'hélice est essentiellement une aile rotative ; chaque section de pale génère une "portance" qui, lorsqu'elle est tournée à haute vitesse, devient une traction vers l'avant qui propulse l'avion.

### Q2: Why are propeller blades twisted (have varying blade angle along their length)?

**A:** Propeller blades are twisted because rotational velocity (Vr) increases proportionally with radius from the hub, while forward velocity (V) is constant. Near the hub, Vr is low, so blade angle must be high to achieve proper angle of attack. At the tip, Vr is very high, so blade angle must be low to achieve the same angle of attack. This twist (vrillage) ensures each blade section operates at approximately optimal angle of attack for maximum efficiency along the entire blade length.

**DE:** Propellerblätter sind verdreht, weil die Rotationsgeschwindigkeit (Vr) proportional mit dem Radius von der Nabe zunimmt, während die Vorwärtsgeschwindigkeit (V) konstant ist. Nahe der Nabe ist Vr niedrig, daher muss der Blattwinkel hoch sein, um den richtigen Anstellwinkel zu erreichen. An der Spitze ist Vr sehr hoch, daher muss der Blattwinkel niedrig sein, um denselben Anstellwinkel zu erreichen. Diese Verdrehung (Vrillage) stellt sicher, dass jeder Blattabschnitt bei ungefähr optimalem Anstellwinkel für maximale Effizienz entlang der gesamten Blattlänge arbeitet.

**FR:** Les pales d'hélice sont tordues car la vitesse de rotation (Vr) augmente proportionnellement avec le rayon depuis le moyeu, tandis que la vitesse d'avancement (V) est constante. Près du moyeu, Vr est faible, donc l'angle de calage doit être élevé pour obtenir un angle d'attaque approprié. À l'extrémité, Vr est très élevée, donc l'angle de calage doit être faible pour obtenir le même angle d'attaque. Cette torsion (vrillage) garantit que chaque section de pale fonctionne à un angle d'attaque approximativement optimal pour une efficacité maximale sur toute la longueur de la pale.

### Q3: What is the difference between geometric pitch and effective pitch?

**A:** **Geometric pitch** is the theoretical distance a propeller would advance in one revolution if it were screwing through a solid (like a wood screw), determined by the blade angle β. **Effective pitch** is the actual distance the propeller advances through the air in one revolution, determined by the angle of attack α. Effective pitch is always less than geometric pitch because the blade must operate at a positive angle of attack in the fluid medium (air) to generate thrust—this difference is called **slip (recul)**, typically 10-30%.

**DE:** **Geometrische Steigung** ist die theoretische Strecke, die ein Propeller in einer Umdrehung zurücklegen würde, wenn er sich durch einen Festkörper schrauben würde (wie eine Holzschraube), bestimmt durch den Blattwinkel β. **Effektive Steigung** ist die tatsächliche Strecke, die der Propeller in einer Umdrehung durch die Luft zurücklegt, bestimmt durch den Anstellwinkel α. Die effektive Steigung ist immer kleiner als die geometrische Steigung, weil das Blatt bei einem positiven Anstellwinkel im flüssigen Medium (Luft) arbeiten muss, um Schub zu erzeugen – dieser Unterschied wird **Schlupf (Recul)** genannt, typischerweise 10-30%.

**FR:** **Le pas géométrique** est la distance théorique qu'une hélice parcourrait en un tour si elle se vissait dans un solide (comme une vis dans du bois), déterminé par l'angle de calage β. **Le pas effectif** est la distance réelle que l'hélice parcourt dans l'air en un tour, déterminé par l'angle d'attaque α. Le pas effectif est toujours inférieur au pas géométrique car la pale doit fonctionner à un angle d'attaque positif dans le milieu fluide (air) pour générer de la traction – cette différence s'appelle le **recul**, typiquement 10-30%.

### Q4: Why is a variable-pitch propeller more efficient than a fixed-pitch propeller?

**A:** A fixed-pitch propeller is optimized for only one flight condition (either climb or cruise), and operates inefficiently at other speeds. A variable-pitch propeller allows the pilot to adjust blade angle for different flight phases: fine pitch (low blade angle) for takeoff/climb with low speed and high RPM, and coarse pitch (high blade angle) for efficient high-speed cruise. This allows the propeller to maintain optimal angle of attack across the entire speed range, delivering maximum engine power and best efficiency in all flight regimes.

**DE:** Ein Propeller mit fester Steigung ist nur für eine Flugbedingung optimiert (entweder Steigflug oder Reiseflug) und arbeitet bei anderen Geschwindigkeiten ineffizient. Ein Verstellpropeller ermöglicht dem Piloten, den Blattwinkel für verschiedene Flugphasen anzupassen: feine Steigung (niedriger Blattwinkel) für Start/Steigflug mit niedriger Geschwindigkeit und hoher Drehzahl, und grobe Steigung (hoher Blattwinkel) für effizienten Hochgeschwindigkeits-Reiseflug. Dies ermöglicht dem Propeller, über den gesamten Geschwindigkeitsbereich einen optimalen Anstellwinkel beizubehalten und maximale Motorleistung und beste Effizienz in allen Flugregimen zu liefern.

**FR:** Une hélice à calage fixe est optimisée pour une seule condition de vol (montée ou croisière), et fonctionne de manière inefficace à d'autres vitesses. Une hélice à calage variable permet au pilote d'ajuster l'angle de calage pour différentes phases de vol : calage fin (faible angle de calage) pour le décollage/la montée avec une vitesse faible et un régime élevé, et calage grossier (angle de calage élevé) pour une croisière efficace à haute vitesse. Cela permet à l'hélice de maintenir un angle d'attaque optimal sur toute la gamme de vitesses, délivrant une puissance moteur maximale et une meilleure efficacité dans tous les régimes de vol.

### Q5: Multiple Choice - What happens to a propeller in glide when the engine is off and the propeller is NOT feathered?

A) It stops rotating and creates minimal drag
B) It windmills and acts as an effective airbrake, severely degrading glide performance
C) It automatically feathers due to aerodynamic forces
D) It improves glide performance by generating some residual thrust

**A:** **B is correct.** When the engine is off and the propeller is not feathered, the airflow through the propeller causes it to windmill (rotate). The blade angle of attack becomes negative, and the propeller acts as a very effective airbrake, creating enormous drag. This can reduce glide ratio by 30-50% or more. This is why feathering (rotating blades to minimum drag position with chord lines parallel to airflow) is a critical procedure for TMG pilots after engine shutdown—it restores most of the clean glider performance.

**DE:** **B ist richtig.** Wenn der Motor aus ist und der Propeller nicht in Segelflugstellung gebracht wurde, verursacht die Luftströmung durch den Propeller ein Windmühlen (Rotation). Der Blattanstellwinkel wird negativ, und der Propeller wirkt als sehr effektive Bremsklappe und erzeugt enormen Widerstand. Dies kann die Gleitzahl um 30-50% oder mehr reduzieren. Deshalb ist das In-Segelflugstellung-Bringen (Drehen der Blätter in die Position mit minimalem Widerstand, wobei die Profilsehnen parallel zur Strömung verlaufen) ein kritisches Verfahren für TMG-Piloten nach dem Motorstopp – es stellt den größten Teil der sauberen Segelflugzeugleistung wieder her.

**FR:** **B est correct.** Lorsque le moteur est éteint et que l'hélice n'est pas mise en drapeau, l'écoulement d'air à travers l'hélice la fait tourner en moulinet. L'angle d'attaque de la pale devient négatif, et l'hélice agit comme un aérofrein très efficace, créant une traînée énorme. Cela peut réduire le rapport de plané de 30 à 50% ou plus. C'est pourquoi la mise en drapeau (rotation des pales vers une position de traînée minimale avec les cordes de profil parallèles à l'écoulement) est une procédure critique pour les pilotes de TMG après l'arrêt du moteur – elle restaure la plupart des performances de planeur propre.

### Q6: What creates the yawing moment in single-engine aircraft with tractor propellers?

**A:** The asymmetric helical slipstream from the propeller wraps around the fuselage and strikes the vertical fin (rudder) at an angle of attack, creating a side force. This side force, acting at a distance behind the center of gravity, creates a yawing moment. For a clockwise-rotating propeller (viewed from cockpit), the slipstream creates a yawing moment to the left, requiring slight right rudder to maintain straight flight. This is a purely aerodynamic effect—not a gyroscopic effect as commonly misunderstood. Pylon-mounted engines show much less effect.

**DE:** Der asymmetrische spiralförmige Schraubenstrahl des Propellers umwickelt den Rumpf und trifft die vertikale Flosse (Seitenruder) in einem Anstellwinkel, wodurch eine Seitenkraft entsteht. Diese Seitenkraft, die in einem Abstand hinter dem Schwerpunkt wirkt, erzeugt ein Giermoment. Bei einem im Uhrzeigersinn rotierenden Propeller (vom Cockpit aus gesehen) erzeugt der Schraubenstrahl ein Giermoment nach links, was leichtes rechtes Seitenruder erfordert, um geraden Flug beizubehalten. Dies ist ein rein aerodynamischer Effekt – kein gyroskopischer Effekt, wie häufig missverstanden. Bei Pylonmotoren ist dieser Effekt viel geringer.

**FR:** Le souffle hélicoïdal asymétrique de l'hélice s'enroule autour du fuselage et frappe la dérive (gouverne de direction) à un angle d'attaque, créant une force latérale. Cette force latérale, agissant à une distance derrière le centre de gravité, crée un moment de lacet. Pour une hélice tournant dans le sens horaire (vue du cockpit), le souffle crée un moment de lacet vers la gauche, nécessitant un léger palonnier droit pour maintenir un vol rectiligne. C'est un effet purement aérodynamique – pas un effet gyroscopique comme souvent mal compris. Les moteurs en pylône montrent un effet beaucoup moins prononcé.

### Q7: Multiple Choice - Why is a larger-diameter, slower-turning propeller generally more efficient than a smaller, faster-turning propeller?

A) It has lower manufacturing costs
B) It creates less noise only, with no efficiency advantage
C) Each blade section operates in cleaner flow with lower tip speeds, reducing losses
D) It requires less engine power to turn

**A:** **C is correct.** A larger-diameter propeller turning at lower RPM is more efficient because each blade section operates in cleaner airflow (less interference), and the blade tips move at lower velocities, reducing tip losses from vortices and compressibility effects. High tip speeds (approaching sonic velocity) create shock waves, dramatically increasing drag and reducing efficiency. However, large-diameter propellers have disadvantages: greater weight, ground clearance limitations, and structural requirements. The design is always a compromise between efficiency and practical constraints.

**DE:** **C ist richtig.** Ein Propeller mit größerem Durchmesser, der sich bei niedrigerer Drehzahl dreht, ist effizienter, weil jeder Blattabschnitt in saubererem Luftstrom arbeitet (weniger Interferenz), und die Blattspitzen sich mit niedrigeren Geschwindigkeiten bewegen, wodurch Spitzenverluste durch Wirbel und Kompressibilitätseffekte reduziert werden. Hohe Spitzengeschwindigkeiten (die sich der Schallgeschwindigkeit nähern) erzeugen Schockwellen, die den Widerstand dramatisch erhöhen und die Effizienz reduzieren. Propeller mit großem Durchmesser haben jedoch Nachteile: größeres Gewicht, Bodenfreiheitsbeschränkungen und strukturelle Anforderungen. Das Design ist immer ein Kompromiss zwischen Effizienz und praktischen Einschränkungen.

**FR:** **C est correct.** Une hélice de plus grand diamètre tournant à un régime plus bas est plus efficace car chaque section de pale fonctionne dans un écoulement d'air plus propre (moins d'interférence), et les extrémités de pale se déplacent à des vitesses plus faibles, réduisant les pertes aux extrémités dues aux tourbillons et aux effets de compressibilité. Les vitesses élevées aux extrémités (approchant la vitesse sonique) créent des ondes de choc, augmentant dramatiquement la traînée et réduisant l'efficacité. Cependant, les hélices de grand diamètre ont des inconvénients : poids plus important, limitations de garde au sol et exigences structurelles. La conception est toujours un compromis entre efficacité et contraintes pratiques.

## Related Topics

Propeller concepts apply aerodynamic principles to powered gliders:

- **[Flow Laws and Speeds](./02-flow-laws-and-speeds.md)** - Propeller blades are airfoils subject to flow laws
- **[Aerodynamic Forces](./03-aerodynamic-forces.md)** - Blade sections generate lift (thrust)
- **[Induced Drag and Wing Geometry](./04-induced-drag-and-wing-geometry.md)** - Blade twist similar to wing twist
- **[Control Surfaces](./08-control-surfaces.md)** - Variable-pitch propellers change blade angle like flaps

## External Resources

- [FAA Pilot's Handbook of Aeronautical Knowledge - Chapter 7: Powerplants](https://www.faa.gov/regulations_policies/handbooks_manuals/aviation/phak) - Section on propeller theory
- [Wikipedia: Propeller (Aeronautics)](https://en.wikipedia.org/wiki/Propeller_(aeronautics)) - Comprehensive propeller overview
- [Wikipedia: Variable-Pitch Propeller](https://en.wikipedia.org/wiki/Variable-pitch_propeller) - Types and mechanisms
- [Wikipedia: Constant-Speed Propeller](https://en.wikipedia.org/wiki/Constant-speed_propeller) - Automatic pitch control systems
- [NASA: Propeller Propulsion](https://www.grc.nasa.gov/www/k-12/airplane/propeller.html) - Educational resources on propeller aerodynamics
- [Hartzell Propeller Resources](https://hartzellprop.com/resources/) - Technical information from major propeller manufacturer
- [EASA CS-22 Powered Sailplanes](https://www.easa.europa.eu/document-library/certification-specifications/cs-22-sailplanes-and-powered-sailplanes) - Certification standards including propeller requirements

## Summary / Zusammenfassung / Résumé

**EN:** Propellers generate thrust through Newton's third law by accelerating air backward. Each blade is a rotating airfoil with velocity components from rotation (Vr, increases with radius) and forward motion (V, constant). Blades are twisted because optimal angle of attack requires decreasing blade angle from root to tip as rotational velocity increases. Geometric pitch (determined by blade angle) is theoretical advance per revolution; effective pitch (determined by angle of attack) is actual advance; the difference is slip. Fixed-pitch propellers are efficient only at one speed—either climb or cruise. Variable-pitch propellers adjust blade angle for different flight phases: fine pitch for climb, coarse pitch for cruise. Constant-speed propellers automatically maintain optimal RPM across all speeds. Propeller efficiency (80-90%) depends on diameter, RPM, blade count, and tip speed. Larger, slower propellers are more efficient but heavier. In glide, windmilling propellers create severe drag (30-50% performance loss)—feathering is critical for TMG pilots to restore glide performance. Slipstream effects create yawing moments in single-engine aircraft requiring rudder compensation.

**DE:** Propeller erzeugen Schub nach Newtons drittem Gesetz, indem sie Luft nach hinten beschleunigen. Jedes Blatt ist ein rotierendes Tragflächenprofil mit Geschwindigkeitskomponenten aus Rotation (Vr, nimmt mit Radius zu) und Vorwärtsbewegung (V, konstant). Blätter sind verdreht, weil optimaler Anstellwinkel abnehmenden Blattwinkel von Wurzel zu Spitze erfordert, während Rotationsgeschwindigkeit zunimmt. Geometrische Steigung (bestimmt durch Blattwinkel) ist theoretischer Vortrieb pro Umdrehung; effektive Steigung (bestimmt durch Anstellwinkel) ist tatsächlicher Vortrieb; die Differenz ist Schlupf. Propeller mit fester Steigung sind nur bei einer Geschwindigkeit effizient – entweder Steigflug oder Reiseflug. Verstellpropeller passen Blattwinkel für verschiedene Flugphasen an: feine Steigung für Steigflug, grobe Steigung für Reiseflug. Konstantdrehzahlpropeller halten automatisch optimale Drehzahl über alle Geschwindigkeiten. Propellereffizienz (80-90%) hängt von Durchmesser, Drehzahl, Blattzahl und Spitzengeschwindigkeit ab. Größere, langsamere Propeller sind effizienter, aber schwerer. Im Gleitflug erzeugen windmühlende Propeller schweren Widerstand (30-50% Leistungsverlust) – Segelflugstellung ist kritisch für TMG-Piloten zur Wiederherstellung der Gleitleistung. Schraubenstrahleffekte erzeugen Giermomente in einmotorigen Flugzeugen, die Seitenruderkompensation erfordern.

**FR:** Les hélices génèrent une traction selon la troisième loi de Newton en accélérant l'air vers l'arrière. Chaque pale est un profil aérodynamique rotatif avec des composantes de vitesse de rotation (Vr, augmente avec le rayon) et de mouvement vers l'avant (V, constant). Les pales sont tordues car l'angle d'attaque optimal nécessite un angle de calage décroissant de l'emplanture à l'extrémité à mesure que la vitesse de rotation augmente. Le pas géométrique (déterminé par l'angle de calage) est l'avance théorique par révolution ; le pas effectif (déterminé par l'angle d'attaque) est l'avance réelle ; la différence est le recul. Les hélices à calage fixe sont efficaces à une seule vitesse – soit montée soit croisière. Les hélices à calage variable ajustent l'angle de calage pour différentes phases de vol : calage fin pour la montée, calage grossier pour la croisière. Les hélices à vitesse constante maintiennent automatiquement un régime optimal à toutes les vitesses. L'efficacité de l'hélice (80-90%) dépend du diamètre, du régime, du nombre de pales et de la vitesse en bout de pale. Les hélices plus grandes et plus lentes sont plus efficaces mais plus lourdes. En planeur, les hélices en moulinet créent une traînée sévère (30-50% de perte de performance) – la mise en drapeau est critique pour les pilotes de TMG pour restaurer les performances de plané. Les effets de souffle créent des moments de lacet dans les avions monomoteurs nécessitant une compensation au palonnier.

---
**Keywords:** propeller, hélice, thrust, traction, blade, pale, pitch, pas, geometric pitch, pas géométrique, effective pitch, pas effectif, slip, recul, variable-pitch, calage variable, constant-speed, vitesse constante, feathering, mise en drapeau, windmill, moulinet, propeller efficiency, rendement d'hélice, blade angle, angle de calage, angle of attack, TMG, motor glider, self-launcher

---

## Navigation

**⬅ Previous Lesson:** [Aircraft Stability](./09-aircraft-stability.md)

**[⬆ Back to Course Overview](../README.md)**
