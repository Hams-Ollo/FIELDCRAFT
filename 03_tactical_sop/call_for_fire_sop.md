# CALL FOR FIRE SOP
## Indirect Fire Procedures for WCS Conflict

> **Doctrine basis:** FM 6-30 / ATP 3-09.30 — Observed Fire Procedures
> **Application:** All WCS servers, M252 mortar platform, player-controlled fire support

---

## WHAT THE FORWARD OBSERVER ACTUALLY DOES

> *"The forward observer is the eyes of the field artillery and mortars. Their primary duty is to locate targets and call for and adjust indirect fire support."*
> — FM 6-30

In WCS Conflict, the Forward Observer (FO) role is filled by recon elements, squad leaders with good position and optics, or dedicated FIST personnel like Blue Falcon. The FO does not need to engage the enemy directly. Their weapon is the radio, the LRF, and the map.

An accurate fire mission from a concealed OP destroys more combat power than a squad-level assault. A fire mission called on a supply truck eliminates that truck's supplies and denies the enemy the ability to build and spawn at the front. A fire mission on an enemy FOB under construction collapses their logistics chain before it is established.

The observer who never fires a shot and calls three accurate fire missions has done more for the team than the player with twenty kills.

---

## THE SIX ELEMENTS OF A CALL FOR FIRE

*Derived directly from FM 6-30 Chapter 4. Adapted for WCS mechanics.*

FM 6-30 defines the call for fire as six elements, transmitted in sequence. Every element has a purpose. Nothing is omitted.

### Element 1 — Observer Identification and Warning Order

**Purpose:** Clear the radio net. Alert the mortar crew. Tell them what type of mission is coming.

**Format:** *"[Mortar callsign], this is [Observer callsign] — Fire Mission, over."*

**In WCS:** *"Mortar, Blue Falcon — Fire Mission, over."*

Wait for acknowledgment before continuing. The mortar crew needs a moment to get on the gun, orient, and prepare to receive data.

> **Doctrine note:** FM 6-30 specifies this as the "Warning Order" element. It tells the firing unit the type of mission (adjust fire, fire for effect, suppression, immediate suppression) and clears the net. In WCS we default to fire for effect unless the target requires adjustment first.

---

### Element 2 — Target Location

**Purpose:** Tell the mortar crew where to shoot.

**Format — Grid (preferred):** *"Grid [6 or 8 digit coordinate]."*
Example: *"Grid 063 043."*

**Format — Shift from known point:** *"From TRP [name], shift [direction] [distance]."*
Example: *"From Mogilevka Main, shift Right 200."*

**Format — Landmark:** *"[Landmark], [direction] [distance]."*
Example: *"Radio tower at Novy Sobor, 150 meters East."*

**Accuracy requirement:** FM 6-30 states the observer must locate targets to an accuracy of 100 meters for effective fire. In WCS, use the 6-digit grid from the map for area targets. Use 8-digit for point targets like a parked MCU.

> **Doctrine note:** The preferred method in FM 6-30 is grid (most accurate). Shift from a known point is the backup when the observer cannot determine an exact grid quickly. Landmark is the last resort. In WCS, TRPs serve as the "known point" for rapid shifts during an active mission.

---

### Element 3 — Target Description

**Purpose:** Tell the mortar crew what they are shooting at, so they can confirm it is worth the ammunition and choose the right effect.

**Format:** *"[Size/type of target] at [brief location detail]."*

Examples:
- *"Enemy FOB under construction, one truck, squad of infantry."*
- *"Logistics truck, stopped on the road."*
- *"Enemy mortar pit, two personnel."*
- *"MCU truck, concealed in treeline."*

Keep it short. The crew does not need a paragraph — they need to know what it is and whether to shoot.

---

### Element 4 — Method of Engagement

**Purpose:** Tell the mortar crew how to attack the target — what ammunition, how many rounds, what fuze or ring setting.

**Format:** *"[Shell type] — [number of rounds] — [Ring setting] — [fire for effect or adjust]."*

Standard call: *"HE — [N] rounds — Ring [X] — fire for effect."*

**Ring selection guide:**

| Ring | Dispersion (~radius) | Target type |
|---|---|---|
| 0 | Tightest | Single vehicle, MCU, precise point target |
| 1 | Tight | Mortar pit, crew-served weapon position |
| 2 | Medium | Small FOB, supply depot, vehicle cluster |
| 3 | Standard (~32m) | Main base area, troop concentration |
| 4 | Wide | Road interdiction, large area suppression |

> **Doctrine note:** FM 6-30 calls this "Method of Engagement" and includes shell-fuze combination, number of rounds, and delivery method. We replace the fuze call with ring setting (the WCS mortar mechanic) but the structure is identical. "Adjust fire" is called when you want one round to observe before committing to effect — use this when the target location is uncertain.

---

### Element 5 — Method of Fire and Control

**Purpose:** Specify timing and any coordination requirements.

**Standard:** Fire for effect on command. In most WCS missions, this element is satisfied by the "fire for effect" call in Element 4.

**If coordination is needed:** *"At my command"* — mortar loads and awaits your fire order before shooting. Use this when you need to synchronize the strike with a ground assault.

**Danger Close:** If friendly forces are within 100 meters of the target, announce this immediately: *"DANGER CLOSE — friendly troops within 100 meters."* This is not part of the six-element sequence — it overrides everything else and must be said first.

> **Doctrine note:** FM 6-30 defines Danger Close as the zone within which friendly troops require special precautionary measures. The firing unit uses this to apply lower ring settings and fire single confirmation rounds before effect. In WCS, it tells the mortar crew to reduce rings and the nearby infantry to go prone.

---

### Element 6 — Observer Actions After Fire

This is not a transmitted element — it is what the observer does after the rounds are in the air.

**Call "SPLASH"** 5 seconds before impact so the spotter knows to watch: *"Splash, out."*

**Observe the impact.**

**Call the result:**
- Accurate: *"On target — fire for effect."* (if adjusting) or *"Good rounds — repeat."*
- Adjustment needed: *"Add [Xm], Left [Xm]."* or *"Drop [Xm], Right [Xm]."*
- Mission complete: *"Target destroyed. End of mission."*
- Shift to next target: *"Shift — TRP [name]."*

---

## COMPLETE CALL FOR FIRE — EXAMPLE

```
FO:     "Mortar, Blue Falcon — Fire Mission, over."

MORTAR: "Blue Falcon, Mortar — send it, over."

FO:     "Grid 063 043."

MORTAR: "Grid 063 043, out."

FO:     "Enemy logistics truck and squad of infantry, 
         digging in south side of building."

FO:     "HE — three rounds — Ring 2 — fire for effect."

MORTAR: "HE, three rounds, Ring 2, fire for effect — 
         rounds out."

FO:     [5 seconds later] "Splash, out."

FO:     [observes] "Add 50, Right 20."

MORTAR: "Add 50, Right 20 — rounds out."

FO:     "On target — fire for effect."

MORTAR: "Rounds out."

FO:     "Target destroyed. End of mission."
```

---

## ADJUSTMENT OF FIRE

*FM 6-30 Chapter 5 — adapted*

When the first round lands off-target, the observer adjusts. Adjustments are made along two axes:

**Range (Add / Drop):** Add = further from observer. Drop = closer to observer.
**Deflection (Left / Right):** Left and Right from the observer's perspective looking at the target.

**Bold corrections:** FM 6-30 instructs observers to use bold corrections — do not creep. If the round landed 200m short, call Add 200 — not Add 50. Small adjustments on a big miss waste ammunition and time.

**Bracketing (when time permits):** Fire a round short, then a round long, then split the bracket. This achieves accuracy in fewer rounds than creeping. In WCS time pressure usually means going straight to fire for effect rather than bracketing, but bracketing is correct procedure when the target is high-value and time permits.

---

## OBSERVER POST (OP) SELECTION

*FM 6-30 Chapter 2 — adapted*

FM 6-30 states: *"The selection of the observation post is critical to the ability of the observer to effectively call for fire and to survive."*

A good OP has:
- **Observation over the target** — line of sight to the area you are calling fire on
- **Concealment from the target** — the enemy cannot see you or your position
- **Multiple egress routes** — you can leave in at least two directions if compromised
- **Radio communication** — line of sight or relay to reach the mortar crew

Apply OCOKA to every OP selection. The perfect OP that cannot communicate is worthless. The OP with great comms but no concealment gets destroyed before the first mission.

---

## TARGET REFERENCE POINTS (TRPs)

*FM 6-30 Section 4-2 — adapted*

A Target Reference Point is a pre-registered location that allows rapid fire missions without recalculating data from scratch. Before a session, the FO and mortar crew identify key locations on the map, calculate the firing solution, and assign each location a name.

During the mission, instead of transmitting a grid, the FO says *"TRP Mogilevka Main"* and the crew immediately dials in the pre-calculated solution. This reduces the time from observation to first round landing from minutes to seconds.

**TRP registration procedure:**
1. Identify a high-value location on the map (enemy main base, supply depot, FOB construction zone)
2. Use the mortar calculator (arma-mortar.com) to calculate elevation, direction, and ring
3. Record: Target name, grid, elevation in mils, direction in mils, ring setting
4. Brief all mortar crew members before the session starts

**Chernarus / Pucker Point pre-registered TRPs:**

| TRP Name | Grid | Elevation (mils) | Direction (mils) | Rings |
|---|---|---|---|---|
| Mogilevka Main | 063 043 | 1025 | 5703 | 2 |
| Chernogorsk Main | 055 030 | 1150 | 4039 | 4 |
| Elektrozavodsk Main | 075 030 | 1074 | 2325 | 4 |
| Staroye Main | 083 047 | 987 | 853 | 3 |

---

## SALUTE REPORT — INTELLIGENCE FORMAT

When observing enemy activity that does not immediately warrant a fire mission, the FO reports using the SALUTE format:

| Letter | Meaning | Example |
|---|---|---|
| **S** — Size | How many? | "Squad of eight infantry" |
| **A** — Activity | What are they doing? | "Constructing FOB" |
| **L** — Location | Where? | "Grid 067 041, south side of road" |
| **U** — Unit | Who are they? | "Russia — standard kit" |
| **T** — Time | When observed? | "Just now / two minutes ago" |
| **E** — Equipment | What do they have? | "One logistics truck, two shovels" |

*"Recon-1, contact report: Grid 067 041. Squad of eight infantry constructing FOB. One logistics truck on site. Observed two minutes ago."*

---

## QUICK REFERENCE

```
CFF FORMAT:
1. "[Mortar], [Observer] — Fire Mission, over." [wait]
2. "Grid [XXX XXX]." — or TRP name
3. "[Target description]."
4. "HE — [N] rounds — Ring [X] — fire for effect."
   → DANGER CLOSE if friendlies within 100m
5. "Splash." [5 sec before impact]
   Adjust: "Add/Drop [Xm], Left/Right [Xm]."
6. "Target destroyed. End of mission."
   or: "Shift — TRP [name]."

ADJUSTMENTS: Bold corrections. Add = further. Drop = closer.
DANGER CLOSE: 100m threshold. Call immediately, before anything else.
```

---

*Doctrine basis: FM 6-30 Observed Fire Procedures | ATP 3-09.30 Techniques for Observed Fire*
*Tool: arma-mortar.com — Chernorus Minus, M252, M853A1 HE*
