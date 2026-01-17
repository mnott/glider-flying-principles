# 4. Induced Drag, Aspect Ratio, and Wing Geometry (La traînée induite et effets de géométrie)

**Reference:** PDF Pages 25-35 (Chapter 4 and Chapter 5)

## Introduction

Everything we've discussed so far assumes an ideal wing of infinite span - a theoretical simplification that doesn't exist in reality. Real wings have tips, and at those tips, something remarkable and problematic happens: the high pressure air below the wing tries to

 escape around the wingtip to the low pressure region above. This creates swirling vortices that trail behind the aircraft like invisible tornadoes.

These **wingtip vortices** are not just an interesting phenomenon - they have serious consequences. They create additional drag (induced drag), reduce lift efficiency, and can be dangerously strong behind large aircraft. Understanding this is crucial because it affects every aspect of glider design and performance.

The "why" behind this chapter: Glider designers obsess over wing aspect ratio and wingtip design because induced drag dominates at low speeds - exactly where gliders spend most of their time. The difference between a mediocre and excellent glider often comes down to how well it manages wingtip vortices. As a pilot, you need to understand these effects to optimize your flying and avoid wake turbulence.

## 4.1 Wingtip Vortices - Causes and Consequences

### 4.1.1 The Physical Mechanism

Imagine you're a particle of high-pressure air under the wing. You're constantly being pushed upward by the wing's pressure, but you can't escape through the wing itself. However, at the wingtip, there's suddenly an edge - an escape route to the low-pressure region above!

**What happens:**

1. **Pressure equalization**: High pressure air from below spills around the wingtip trying to reach the low pressure above
2. **Spanwise flow**: This creates a flow component along the span (from root to tip on the bottom, tip to root on top)
3. **Vortex formation**: These spanwise flows, combined with the main airflow, create a rotating vortex at each wingtip
4. **Trailing vortices**: These vortices trail behind the aircraft in a cone shape, persisting for minutes or even miles

**Why vortices form:**

Think of water draining from a bathtub - it naturally forms a vortex due to rotation. Similarly, the pressure difference at the wingtip, combined with the forward motion, naturally forms a rotating flow pattern.

**Visualization:**

Sometimes on humid days, you can actually see these vortices! The low pressure in the vortex core causes moisture to condense, making the invisible visible. You'll see spiral trails emanating from the wingtips, especially during takeoff and landing when lift (and thus pressure difference) is high.

### 4.1.2 Consequences of Wingtip Vortices

The effects are multiple and significant:

**1. Induced Drag**

The vortices represent wasted energy - energy that goes into swirling air instead of forward motion. This shows up as additional drag called **induced drag** or **drag due to lift**.

**Key characteristics:**
- Increases as lift increases (more lift = stronger vortices)
- Increases as speed decreases (at low speed, you need high angle of attack for same lift)
- Dominant at low speeds (unlike profile drag which dominates at high speed)
- Can be 40-50% of total drag during climb or slow flight
- Negligible at high cruise speeds

**Why it's called "induced" drag:** It's induced (caused) by the act of generating lift itself. You can't eliminate it entirely - if you're generating lift, you're generating induced drag. You can only minimize it through clever design.

**2. Lift Degradation**

The vortices don't just create drag - they also reduce lift effectiveness, especially near the wingtips. The spanwise flow disrupts the ideal pressure distribution over the wing.

**Effect:** The lift coefficient Cz effectively decreases, especially in the outer third of the wing span. It's as if the wingtip portions of the wing are working less efficiently than the center section.

**3. Downwash and Effective Angle of Attack**

The vortices create a downward-moving air mass behind the wing (downwash). This changes the effective angle of attack seen by the tail and affects pitch stability.

**For pilots:** This is why the elevator trim setting changes with speed - the downwash angle varies with lift (and thus angle of attack and speed).

### 4.1.3 Wake Turbulence - A Safety Issue

Behind large aircraft, these vortices can be extremely powerful - strong enough to roll a smaller aircraft inverted or cause structural damage.

**Characteristics of wake vortex:**
- Strongest behind heavy, slow, "clean" aircraft (gear and flaps up)
- Descend at 400-500 feet per minute initially
- Drift with wind, but also under their own dynamics
- Persist for 2-3 minutes or more
- Can extend 5-10 nautical miles behind large aircraft

**Safety implications:**
- Stay above the flight path of large aircraft
- When landing behind large aircraft, aim to touch down beyond their touchdown point
- In cruise, stay laterally displaced from large aircraft flight paths
- Be especially careful when crossing behind departing large aircraft

**Real accident** history includes several general aviation aircraft that encountered wake turbulence from airliners and crashed. This is not theoretical - it's a real hazard.

## 4.2 Influence of Wing Geometry

### 4.2.1 Wing Aspect Ratio (λ)

The single most important geometric parameter affecting induced drag is the **aspect ratio** (λ, lambda):

**λ = wingspan² / wing area = b² / S**

Or equivalently:

**λ = wingspan / average chord = b / c_average**

**What it means:**

Aspect ratio is essentially the "slenderness" of the wing:
- High aspect ratio = long, skinny wing (like a glider)
- Low aspect ratio = short, stubby wing (like a fighter jet)

**Example calculations:**

**Glider (high performance):**
- Wingspan: 18 m
- Wing area: 10 m²
- λ = 18² / 10 = 324 / 10 = **32.4** (very high!)

**Light aircraft:**
- Wingspan: 10 m
- Wing area: 15 m²
- λ = 100 / 15 = **6.7** (moderate)

**Fighter jet:**
- Wingspan: 12 m
- Wing area: 40 m²
- λ = 144 / 40 = **3.6** (low)

**Why aspect ratio matters so much:**

High aspect ratio dramatically reduces induced drag because:

1. **Smaller wingtip proportion**: On a high aspect ratio wing, the wingtips represent a smaller fraction of total span
2. **Weaker vortices**: For the same total lift, the pressure difference at any point is lower, so vortex strength is reduced
3. **Better lift distribution**: High aspect ratio wings achieve more elliptical lift distribution (the ideal)

**The trade-off:**

High aspect ratio wings are aerodynamically superior but have disadvantages:
- **Structural weight**: Long, slender wings are harder to build strong enough
- **Storage/hangar**: Very long wings are difficult to accommodate
- **Maneuverability**: Lower roll rate (more inertia to overcome)
- **Gust sensitivity**: Long wings experience more bending from turbulence

**Why gliders have high aspect ratio:**

Gliders fly slowly and need maximum efficiency at low speeds - exactly where induced drag dominates. A glider with λ = 30 might have 1/3 the induced drag of a light aircraft with λ = 7 at the same lift coefficient.

**Why fighters have low aspect ratio:**

Fighters need:
- High roll rate for maneuverability
- Strength for high-g maneuvers
- Compactness for carrier operations
- High-speed capability (where profile drag dominates, not induced drag)

### 4.2.2 Effect of Wing Planform Shape

Even with the same aspect ratio, wing planform (the shape when viewed from above) significantly affects induced drag.

**Ranking from best to worst:**

1. **Elliptical** - Theoretical optimum, uniform downwash, minimum induced drag
2. **Tapered** - Good compromise, almost as efficient as elliptical
3. **Rectangular** - Simple to build but less efficient

**Elliptical wings:**

The **Supermarine Spitfire** famously used elliptical wings. This shape produces the most uniform lift distribution and minimizes induced drag for a given span and area.

**Why not everyone uses elliptical:**
- Difficult and expensive to manufacture
- Structural complexity
- The benefit over a well-designed tapered wing is only 5-10%

**Tapered wings:**

Most modern aircraft use tapered wings (chord decreases from root to tip). With proper taper ratio, they approach elliptical efficiency at much lower manufacturing cost.

**Typical taper ratios:**
- Tip chord / Root chord = 0.4 to 0.6
- Too much taper (very pointy tips) can cause tip stall problems

**Rectangular wings:**

Simple to build (constant chord) but least efficient. Common on:
- Older designs (simpler manufacturing)
- Homebuilt aircraft (ease of construction)
- Trainers (docile stall characteristics - root stalls first)

### 4.2.3 The Lift Distribution Problem

All these geometric effects ultimately affect **lift distribution** - how lift varies along the wingspan.

**Ideal distribution:** Elliptical - lift is highest at the center and smoothly decreases to zero at the tips, following an elliptical curve.

**Why elliptical is ideal:** It produces uniform downwash along the span, minimizing energy wasted in vortices.

**Real aircraft:** Nearly all use non-elliptical planforms, so lift distribution is not quite ideal, meaning slightly higher induced drag.

**Effect of aspect ratio on Cz,max:**

Looking at PDF Figure 2 (Chapter 5), we see that:
- High aspect ratio wings achieve higher Cz,max before stall
- Low aspect ratio wings have lower Cz,max
- The difference can be 15-20% in maximum lift coefficient

**Why:** High aspect ratio wings have less adverse influence from tip vortices on the overall lift distribution, allowing higher average Cz before stall.

## 4.3 Devices to Reduce Induced Drag

### 4.3.1 Wingtip Design Features

Since we can't eliminate tip vortices entirely, we can at least manage them cleverly:

**1. Wingtip Fairings (Saumons)**

Smooth, rounded caps at the wingtips that:
- Reduce the sharp pressure discontinuity
- Smooth the flow around the tip
- Slightly reduce vortex strength
- Benefit: 2-5% drag reduction

**Example:** The **ASK-21** school glider has distinctive upswept tip fairings.

**2. Winglets (Pennes)**

Vertical or near-vertical extensions at the wingtips, like small vertical fins.

**How they work:**
- Block some of the spanwise flow trying to escape around the tip
- Recapture some vortex energy by generating a small inward force
- Act like a small additional bit of wingspan
- Very effective: 5-10% drag reduction or more

**Trade-offs:**
- Added weight and complexity
- Some additional profile drag from the winglet itself
- Structural loads on wing root
- But: net benefit is positive for most gliders

**Modern gliders:** Many high-performance gliders now use winglets as standard equipment. The **DG-808** and similar modern designs feature prominent winglets.

**Commercial aviation:** Modern airliners (Boeing 737 MAX, Airbus A350, etc.) all use winglets - the fuel savings are enormous over millions of flight hours.

**3. Tip Tanks (on powered aircraft)**

External fuel tanks mounted at wingtips serve double duty:
- Carry fuel (obvious)
- Disrupt tip vortex formation (side benefit)

**4. Split Tips**

Some designs split the wingtip into multiple smaller surfaces, spreading out the vortex formation over multiple points rather than one concentrated vortex.

### 4.3.2 Wing Twist (Washout)

Another problem created by tip vortices: premature tip stall.

**The problem:** Tip vortices can cause flow separation at the wingtips before the critical angle is reached for the whole wing. If tips stall first:
- Ailerons (located near tips) become ineffective
- Roll control is lost right when you most need it (low speed, high angle of attack)
- Can lead to wing drop and spin entry

**The solution: Aerodynamic or geometric washout**

**Geometric washout (vrillage géométrique):**

The wing is built with a twist - the angle of incidence (angle between wing chord and aircraft reference line) **decreases** from root to tip.

**Typical washout:** 2-4° (wing tip has 2-4° less angle of incidence than wing root)

**Effect:**
- At any given aircraft attitude, the wing root has a higher angle of attack than the tip
- As you approach stall, the root reaches critical angle first
- Root stalls first, tips keep flying (and ailerons keep working!)
- Stall is gentle and controllable

**Aerodynamic washout:**

Achieve the same effect by changing the airfoil section from root to tip:
- Root: Higher camber airfoil (stalls at higher α)
- Tip: Lower camber or symmetric airfoil (stalls at lower α)
- Or mix of profile shape changes

**Why both exist:**
- Geometric washout: Simple, visible, traditional
- Aerodynamic washout: Can be more efficient, but requires family of airfoils

**Visual check:** Look along the wing of a glider from behind - you'll often see the tip angled down slightly relative to the root. That's geometric washout.

### 4.3.3 The Ground Effect

Here's a fascinating phenomenon that every pilot experiences but many don't fully understand.

**The phenomenon:**

When flying very close to the ground (within one wingspan of the surface), the aircraft suddenly flies more efficiently:
- Induced drag decreases significantly
- Lift slightly increases
- You can fly at lower speed than normal
- The aircraft "floats" and seems reluctant to land

**What causes it:**

The ground interferes with the development of wingtip vortices:

1. **Vortex disruption**: The ground surface physically blocks and distorts the vortex formation pattern
2. **Downwash reduction**: The downwash angle behind the wing is reduced by ground proximity
3. **Pressure recovery**: The cushion of air between wing and ground provides additional pressure

**Think of it as:** Flying in ground effect is somewhat like flying in a "tunnel" - the ground acts like a mirror, effectively giving you additional wingspan.

**Quantitative effect:**

At height = wingspan / 4:
- Induced drag: Reduced by ~25-40%
- Lift: Increased by ~10-20%
- These are huge effects!

**When you experience it:**

**During takeoff:**
- Aircraft accelerates more easily just after liftoff
- Climb performance seems better than expected
- But: leaving ground effect requires extra speed/energy

**During landing:**
- Aircraft "floats" in the flare
- Touchdown speed seems slower than approach speed
- Novice pilots often flare too high, then float way down the runway

**Critical for pilots:**

1. **Don't confuse ground effect with normal flight:** An aircraft that flies fine in ground effect might not be able to climb out of it if overloaded or if density altitude is high

2. **Land with proper approach speed:** Don't slow down excessively thinking you're in ground effect prematurely - it only works very close to the ground

3. **Expect float:** Plan for it, especially on smooth approaches at light weight

**Dangerous situations:**

- **High density altitude takeoffs:** Aircraft lifts off in ground effect, pilot thinks it's flying well, tries to climb, can't - crashes beyond departure end of runway

- **Overweight takeoffs:** Same issue - flies in ground effect but can't climb out

- **Formation flying low:** Very dangerous - ground effect varies with height, making formation difficult

**Practical test:** You know you're in ground effect when:
- Sink rate suddenly decreases approaching runway
- Aircraft resists your attempts to descend the last few feet
- After touchdown, aircraft wants to fly again if you pull back even slightly

## Summary of Wing Design Trade-offs

| Feature | Advantage | Disadvantage |
|---------|-----------|--------------|
| **High Aspect Ratio** | Low induced drag, good glide | Heavy, fragile, poor roll rate, storage issues |
| **Low Aspect Ratio** | Maneuverable, strong, compact | High induced drag, poor glide |
| **Elliptical Planform** | Minimum induced drag | Expensive, complex structure |
| **Rectangular Planform** | Simple, cheap, docile stall | High induced drag, inefficient |
| **Winglets** | Reduce induced drag 5-10% | Added weight, complexity, some profile drag |
| **Wing Washout** | Safe stall characteristics | Slightly less efficient at cruise |

**The designer's challenge:** Balance all these factors for the mission:
- Gliders: Maximize aspect ratio, accept handling compromises
- Trainers: Docile stalls, tough structure, accept lower performance
- Aerobatic: Low aspect ratio, superb roll rate, fuel efficiency not critical
- Cross-country: Compromise aspect ratio, good efficiency, reasonable handling

## Questions / Fragen / Questions

### Q1: What causes wingtip vortices?

**A:** Wingtip vortices are caused by the pressure difference between the lower surface (high pressure) and upper surface (low pressure) of the wing. At the wingtip, high-pressure air from below spills around the tip to the low-pressure region above, creating a rotating vortex. These vortices trail behind the aircraft in a cone pattern and represent wasted energy that appears as induced drag.

**DE:** Randwirbel entstehen durch den Druckunterschied zwischen der Unterseite (hoher Druck) und der Oberseite (niedriger Druck) des Flügels. An der Flügelspitze strömt Hochdruckluft von unten um die Spitze herum zum Niederdruckbereich oben und erzeugt einen rotierenden Wirbel. Diese Wirbel ziehen hinter dem Flugzeug in einem Kegelmuster und repräsentieren verschwendete Energie, die als induzierter Widerstand erscheint.

**FR:** Les tourbillons marginaux sont causés par la différence de pression entre la surface inférieure (haute pression) et la surface supérieure (basse pression) de l'aile. À l'extrémité de l'aile, l'air haute pression d'en dessous s'écoule autour de la pointe vers la région de basse pression au-dessus, créant un tourbillon rotatif. Ces tourbillons traînent derrière l'aéronef en forme de cône et représentent l'énergie gaspillée qui apparaît comme traînée induite.

---

### Q2: What is induced drag and when is it most significant?

**A:** Induced drag is additional drag created by the formation of wingtip vortices - it's drag "induced" by the act of generating lift. It's most significant at low speeds and high angles of attack (during takeoff, landing, and slow flight) where it can represent 40-50% of total drag. It decreases as speed increases and becomes negligible at high cruise speeds. Unlike profile drag which increases with speed squared, induced drag decreases with speed squared.

**DE:** Induzierter Widerstand ist zusätzlicher Widerstand, der durch die Bildung von Randwirbeln entsteht - er wird durch den Akt der Auftriebserzeugung "induziert". Er ist am bedeutendsten bei niedrigen Geschwindigkeiten und hohen Anstellwinkeln (während Start, Landung und Langsamflug), wo er 40-50% des Gesamtwiderstands ausmachen kann. Er nimmt mit zunehmender Geschwindigkeit ab und wird bei hohen Reisegeschwindigkeiten vernachlässigbar.

**FR:** La traînée induite est une traînée supplémentaire créée par la formation de tourbillons marginaux - c'est une traînée "induite" par l'acte de générer de la portance. Elle est la plus significative aux basses vitesses et aux grands angles d'attaque (pendant le décollage, l'atterrissage et le vol lent) où elle peut représenter 40-50% de la traînée totale. Elle diminue lorsque la vitesse augmente et devient négligeable aux vitesses de croisière élevées.

---

### Q3: What is wing aspect ratio and why is it important?

**A:** Aspect ratio (λ) is the ratio of wingspan squared to wing area (λ = b²/S), essentially measuring wing "slenderness." High aspect ratio (long, narrow wings) dramatically reduces induced drag because wingtips represent a smaller proportion of total span and vortices are weaker. Gliders use very high aspect ratios (25-35) for efficiency at low speeds where induced drag dominates. Fighters use low aspect ratios (3-5) for maneuverability and structural strength. Aspect ratio is the single most important geometric parameter affecting induced drag.

**DE:** Das Streckungsverhältnis (λ) ist das Verhältnis der Spannweite zum Quadrat zur Flügelfläche (λ = b²/S), im Wesentlichen ein Maß für die "Schlankheit" des Flügels. Hohes Streckungsverhältnis (lange, schmale Flügel) reduziert den induzierten Widerstand dramatisch, weil die Flügelspitzen einen kleineren Anteil der Gesamtspannweite darstellen und die Wirbel schwächer sind. Segelflugzeuge verwenden sehr hohe Streckungsverhältnisse (25-35) für Effizienz bei niedrigen Geschwindigkeiten, wo induzierter Widerstand dominiert.

**FR:** L'allongement (λ) est le rapport de l'envergure au carré sur la surface alaire (λ = b²/S), mesurant essentiellement l'"élancement" de l'aile. Un allongement élevé (ailes longues et étroites) réduit considérablement la traînée induite car les extrémités d'aile représentent une proportion plus faible de l'envergure totale et les tourbillons sont plus faibles. Les planeurs utilisent des allongements très élevés (25-35) pour l'efficacité aux basses vitesses où la traînée induite domine.

---

### Q4: How does wing planform shape affect induced drag?

**A:** Wing planform (shape viewed from above) significantly affects induced drag efficiency. Ranked from best to worst: (1) Elliptical - theoretical optimum with uniform lift distribution and minimum induced drag (e.g., Spitfire), (2) Tapered - good compromise approaching elliptical efficiency, used by most modern aircraft, (3) Rectangular - simplest but least efficient, though it has docile stall characteristics. The difference between elliptical and well-designed tapered is only 5-10%, which is why most aircraft use tapered planforms for easier manufacturing.

**DE:** Die Flügelgrundform (Form von oben betrachtet) beeinflusst die induzierte Widerstandseffizienz erheblich. Von best nach schlechtesten rangiert: (1) Elliptisch - theoretisches Optimum mit gleichmäßiger Auftriebsverteilung und minimalem induziertem Widerstand (z.B. Spitfire), (2) Trapezförmig - guter Kompromiss mit fast elliptischer Effizienz, von den meisten modernen Flugzeugen verwendet, (3) Rechteckig - am einfachsten, aber am wenigsten effizient, hat aber gutmütige Überziehungseigenschaften.

**FR:** La forme en plan de l'aile (forme vue d'en haut) affecte considérablement l'efficacité de la traînée induite. Classement du meilleur au pire : (1) Elliptique - optimum théorique avec distribution uniforme de portance et traînée induite minimale (ex. Spitfire), (2) Trapézoïdale - bon compromis approchant l'efficacité elliptique, utilisée par la plupart des aéronefs modernes, (3) Rectangulaire - la plus simple mais la moins efficace, bien qu'elle ait des caractéristiques de décrochage dociles.

---

### Q5: What are winglets and how do they work?

**A:** Winglets are vertical or near-vertical extensions at the wingtips, like small vertical fins. They work by: (1) blocking some of the spanwise flow trying to escape around the wingtip, (2) recapturing some vortex energy by generating a small inward force, and (3) effectively acting like additional wingspan. They can reduce induced drag by 5-10% or more, which is why modern gliders and airliners commonly use them. The trade-off is added weight, complexity, and some additional profile drag from the winglet itself, but the net benefit is positive.

**DE:** Winglets sind vertikale oder nahezu vertikale Erweiterungen an den Flügelspitzen, wie kleine vertikale Flossen. Sie funktionieren durch: (1) Blockieren eines Teils der Spannweitenströmung, die versucht, um die Flügelspitze zu entweichen, (2) Zurückgewinnen eines Teils der Wirbelenergie durch Erzeugen einer kleinen nach innen gerichteten Kraft, und (3) effektiv wirken wie zusätzliche Spannweite. Sie können den induzierten Widerstand um 5-10% oder mehr reduzieren, weshalb moderne Segelflugzeuge und Verkehrsflugzeuge sie häufig verwenden.

**FR:** Les winglets sont des extensions verticales ou presque verticales aux extrémités d'aile, comme de petites dérives verticales. Ils fonctionnent en : (1) bloquant une partie du flux d'envergure essayant de s'échapper autour de l'extrémité d'aile, (2) récupérant une partie de l'énergie du tourbillon en générant une petite force vers l'intérieur, et (3) agissant effectivement comme une envergure supplémentaire. Ils peuvent réduire la traînée induite de 5-10% ou plus, c'est pourquoi les planeurs modernes et les avions de ligne les utilisent couramment.

---

### Q6: What is wing washout and why is it important?

**A:** Wing washout (vrillage) is a twist built into the wing where the angle of incidence decreases from root to tip (typically 2-4°). This ensures that at any aircraft attitude, the wing root has a higher angle of attack than the tip. As you approach stall, the root reaches critical angle first and stalls first, while tips keep flying. This is crucial for safety because it keeps the ailerons (located near tips) effective during slow flight and stall, allowing maintained roll control. Without washout, tips could stall first, causing sudden wing drop and potential spin entry.

**DE:** Flügelverwindung (vrillage) ist eine in den Flügel eingebaute Verdrehung, bei der der Anstellwinkel von der Wurzel zur Spitze abnimmt (typischerweise 2-4°). Dies stellt sicher, dass bei jeder Fluglage die Flügelwurzel einen höheren Anstellwinkel hat als die Spitze. Wenn Sie sich dem Überziehen nähern, erreicht die Wurzel zuerst den kritischen Winkel und zieht zuerst über, während die Spitzen weiterfliegen. Dies ist entscheidend für die Sicherheit, weil es die Querruder (nahe den Spitzen) während des Langsamflugs und Überziehens effektiv hält.

**FR:** Le vrillage de l'aile est une torsion intégrée dans l'aile où l'angle de calage diminue de l'emplanture à l'extrémité (typiquement 2-4°). Cela garantit qu'à toute attitude de l'aéronef, la racine de l'aile a un angle d'attaque plus élevé que l'extrémité. Lorsque vous approchez du décrochage, la racine atteint d'abord l'angle critique et décroche en premier, tandis que les extrémités continuent de voler. Ceci est crucial pour la sécurité car cela maintient les ailerons (situés près des extrémités) efficaces pendant le vol lent et le décrochage.

---

### Q7: What is ground effect and how does it affect flight?

**A:** Ground effect is a phenomenon occurring when flying within approximately one wingspan of the surface, where induced drag decreases significantly (25-40%) and lift slightly increases. This happens because the ground interferes with wingtip vortex formation and reduces downwash. Aircraft in ground effect experiences: (1) better acceleration during takeoff roll, (2) ability to fly at slower speeds, (3) "floating" during landing flare, and (4) improved efficiency. Dangers include false sense of performance (aircraft may lift off but not be able to climb out of ground effect if overloaded or at high density altitude).

**DE:** Bodeneffekt ist ein Phänomen, das auftritt, wenn man innerhalb etwa einer Spannweite von der Oberfläche fliegt, wobei der induzierte Widerstand erheblich abnimmt (25-40%) und der Auftrieb leicht zunimmt. Dies geschieht, weil der Boden die Bildung von Randwirbeln stört und den Abwind reduziert. Gefahren umfassen falsches Gefühl der Leistung (Flugzeug kann abheben, aber möglicherweise nicht aus dem Bodeneffekt herausklettern können, wenn überladen oder bei hoher Dichtehöhe).

**FR:** L'effet de sol est un phénomène se produisant lors du vol à environ une envergure de la surface, où la traînée induite diminue considérablement (25-40%) et la portance augmente légèrement. Cela se produit parce que le sol interfère avec la formation de tourbillons marginaux et réduit le flux descendant. Les dangers incluent une fausse impression de performance (l'aéronef peut décoller mais ne pas pouvoir grimper hors de l'effet de sol s'il est surchargé ou à une altitude-densité élevée).

---

### Q8 (Multiple Choice): A glider has a wingspan of 15m and wing area of 9m². What is its aspect ratio?

- A) 1.67
- B) 15
- C) 25
- D) 225

**A:** C) 25. Aspect ratio λ = b²/S = 15²/9 = 225/9 = 25. This is a typical high aspect ratio for a mid-performance glider, optimized for low induced drag.

**DE:** C) 25. Streckungsverhältnis λ = b²/S = 15²/9 = 225/9 = 25. Dies ist ein typisches hohes Streckungsverhältnis für ein mittleres Leistungssegelflugzeug, optimiert für niedrigen induzierten Widerstand.

**FR:** C) 25. Allongement λ = b²/S = 15²/9 = 225/9 = 25. C'est un allongement élevé typique pour un planeur de performance moyenne, optimisé pour une faible traînée induite.

---

### Q9 (Multiple Choice): When is ground effect most noticeable?

- A) Flying at 10,000 feet
- B) In a steep turn
- C) Just before touchdown during landing
- D) During cruise at high speed

**A:** C) Just before touchdown during landing. Ground effect is only significant when flying within approximately one wingspan height of the surface. It's most noticeable during the landing flare when the aircraft suddenly requires less power to maintain flight and tends to "float" along the runway.

**DE:** C) Kurz vor dem Aufsetzen während der Landung. Bodeneffekt ist nur signifikant, wenn man innerhalb ungefähr einer Spannweitenhöhe von der Oberfläche fliegt. Er ist am deutlichsten während des Landeausschwebens, wenn das Flugzeug plötzlich weniger Leistung benötigt, um den Flug aufrechtzuerhalten, und entlang der Landebahn "schwebt".

**FR:** C) Juste avant le toucher lors de l'atterrissage. L'effet de sol n'est significatif que lorsqu'on vole à environ une hauteur d'envergure de la surface. Il est plus perceptible pendant l'arrondi d'atterrissage lorsque l'aéronef nécessite soudainement moins de puissance pour maintenir le vol et tend à "flotter" le long de la piste.

## Related Topics

Wing geometry and induced drag connect to performance and design:

- **[Aerodynamic Forces](./03-aerodynamic-forces.md)** - Foundation: lift generation creates induced drag
- **[Stalls and Spins](./07-stalls-and-spins.md)** - Wingtip vortices and tip stall behavior
- **[Control Surfaces](./08-control-surfaces.md)** - Adverse yaw from aileron-induced drag
- **[Aircraft Stability](./09-aircraft-stability.md)** - Wing sweep and dihedral for stability

## External Resources

- [Wingtip vortices - Wikipedia](https://en.wikipedia.org/wiki/Wingtip_vortices)
- [Lift-induced drag - Wikipedia](https://en.wikipedia.org/wiki/Lift-induced_drag)
- [Aspect ratio (aeronautics) - Wikipedia](https://en.wikipedia.org/wiki/Aspect_ratio_(aeronautics))
- [Winglet - Wikipedia](https://en.wikipedia.org/wiki/Winglet)
- [Ground effect (aerodynamics) - Wikipedia](https://en.wikipedia.org/wiki/Ground_effect_(aerodynamics))
- [Wake turbulence - SKYbrary](https://skybrary.aero/articles/wake-turbulence)
- [FAA - Wake Turbulence](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/chap7_section_3.html)
- [NASA - Induced Drag](https://www.grc.nasa.gov/www/k-12/airplane/induced.html)

## Summary / Zusammenfassung / Résumé

**EN:** Wingtip vortices form when high-pressure air from below the wing spills around the wingtip to the low-pressure region above, creating rotating vortices that trail behind the aircraft. These vortices cause induced drag - additional drag created by the act of generating lift, most significant at low speeds (40-50% of total drag) and decreasing with speed squared. Wing aspect ratio (λ = b²/S) is the most important geometric parameter: high aspect ratio (gliders: 25-35) minimizes induced drag by reducing vortex strength, while low aspect ratio (fighters: 3-5) favors maneuverability and strength. Wing planform affects efficiency: elliptical is optimal, tapered is a good compromise, rectangular is least efficient. Devices to reduce induced drag include winglets (5-10% reduction), wingtip fairings, and optimal planform design. Wing washout (geometric twist of 2-4° from root to tip) ensures root stalls before tips, maintaining aileron effectiveness for safe handling. Ground effect occurs within one wingspan of the surface, reducing induced drag by 25-40% and creating the "floating" sensation during landing, but can be dangerous if aircraft cannot climb out when overloaded.

**DE:** Randwirbel bilden sich, wenn Hochdruckluft von unter dem Flügel um die Flügelspitze zur Niederdruckregion oben strömt und rotierende Wirbel erzeugt, die hinter dem Flugzeug folgen. Diese Wirbel verursachen induzierten Widerstand - zusätzlichen Widerstand durch den Akt der Auftriebserzeugung, am bedeutendsten bei niedrigen Geschwindigkeiten (40-50% des Gesamtwiderstands) und abnehmend mit dem Quadrat der Geschwindigkeit. Das Streckungsverhältnis (λ = b²/S) ist der wichtigste geometrische Parameter: hohes Streckungsverhältnis (Segelflugzeuge: 25-35) minimiert induzierten Widerstand durch Reduktion der Wirbelstärke, während niedriges Streckungsverhältnis (Jäger: 3-5) Manövrierfähigkeit und Festigkeit begünstigt. Die Flügelgrundform beeinflusst die Effizienz: elliptisch ist optimal, trapezförmig ist ein guter Kompromiss, rechteckig ist am wenigsten effizient. Geräte zur Reduktion des induzierten Widerstands umfassen Winglets (5-10% Reduktion), Flügelspitzenverkleidungen und optimales Grundformdesign. Flügelverwindung (geometrische Verdrehung von 2-4° von Wurzel zu Spitze) stellt sicher, dass die Wurzel vor den Spitzen überzieht und die Querruderwirksamkeit für sicheres Handling aufrechterhält. Bodeneffekt tritt innerhalb einer Spannweite von der Oberfläche auf, reduziert induzierten Widerstand um 25-40% und erzeugt das "Schwebe"-Gefühl während der Landung, kann aber gefährlich sein, wenn das Flugzeug beim Überladen nicht herausklettern kann.

**FR:** Les tourbillons marginaux se forment lorsque l'air haute pression de dessous l'aile s'écoule autour de l'extrémité vers la région de basse pression au-dessus, créant des tourbillons rotatifs qui traînent derrière l'aéronef. Ces tourbillons causent la traînée induite - traînée supplémentaire créée par l'acte de générer de la portance, la plus significative aux basses vitesses (40-50% de la traînée totale) et diminuant avec le carré de la vitesse. L'allongement (λ = b²/S) est le paramètre géométrique le plus important : allongement élevé (planeurs : 25-35) minimise la traînée induite en réduisant la force du tourbillon, tandis qu'un faible allongement (chasseurs : 3-5) favorise la manœuvrabilité et la résistance. La forme en plan affecte l'efficacité : elliptique est optimal, trapézoïdal est un bon compromis, rectangulaire est le moins efficace. Les dispositifs pour réduire la traînée induite incluent les winglets (réduction de 5-10%), les carénages d'extrémité d'aile et la conception optimale de la forme en plan. Le vrillage de l'aile (torsion géométrique de 2-4° de la racine à l'extrémité) garantit que la racine décroche avant les extrémités, maintenant l'efficacité des ailerons pour une manipulation sûre. L'effet de sol se produit à moins d'une envergure de la surface, réduisant la traînée induite de 25-40% et créant la sensation de "flottement" pendant l'atterrissage, mais peut être dangereux si l'aéronef ne peut pas grimper lorsqu'il est surchargé.

---
**Keywords:** wingtip vortices, tourbillons marginaux, induced drag, traînée induite, aspect ratio, allongement, λ, winglets, pennes, washout, vrillage, ground effect, effet de sol, wake turbulence, wing planform, elliptical wing, tapered wing, vortex formation, downwash, lift distribution

---

## Navigation

**⬅ Previous Lesson:** [Aerodynamic Forces](./03-aerodynamic-forces.md)

**[⬆ Back to Course Overview](../README.md)**

**➡ Next Lesson:** [Straight Flight](./05-straight-flight.md)
