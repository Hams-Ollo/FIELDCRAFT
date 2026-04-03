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
**Synchronized sniper + indirect fire:** When a sniper/recon element has eyes on a High Value Target (HVT) such as an officer or commander, the fire mission should be pre-briefed *before* the shot is taken. Transmit the full fire mission as *“at my command”* — the mortar is loaded and oriented, waiting. The sniper engages the HVT, then **immediately calls “Fire”** over the net. The window between the HVT going down and the enemy reacting to cover is measured in seconds. Pre-briefing the crew compresses the delay to near-zero — enemy starts responding to their commander going down and the mortars hit before they can rally or communicate.
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

**Rangefinder mortar adjustment mode:** Hold `V`, tap `C` to enter mortar adjustment mode on the Laser Rangefinder. Mark the current round's impact as the first point, then drag to where you want the next round to land. The rangefinder outputs Left/Up correction numbers directly in the mortar crew's reference frame. Pass those numbers directly to the operator — no math required on the observer's end.

**Multi-angle observer correction — the 45° problem:** When the observer is positioned at a significant angle to the mortar-to-target axis, the observer's “left” and “right” do not correspond to the mortar crew's “left” and “right.” If you call “right 50” from a 90° offset position, the crew adjusts in a direction that may be toward you or away from the target rather than correcting the miss. Solutions: (1) Use rangefinder mortar adjustment mode — it handles angle translation automatically. (2) Give corrections in mils rather than cardinal direction — mils are absolute, not relative to observer position. (3) Mark the impact and intended target on the map and let the crew calculate their own correction.

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
---

## MORTAR OPERATOR PROCEDURES

> *This section covers the gun crew's side of the fire mission. The FO Handbook (above) covers the observer's side. Both elements operate the same mission — from opposite ends of the radio.*

*Source: Ironbeard Mortar Operator Guide; King Alex TacTalk*

---

### PLACEMENT REQUIREMENTS

- **Rank gate:** Sergeant rank required to build a mortar pit
- **Build from:** Command tent or construction truck — you do not need to be inside a base perimeter
- **Site selection:** Place on the flattest available ground. Sloped ground affects the gun's ability to traverse and level correctly.
- **Positioning:** Forward positions are legal — a mortar pit 300m from the front is more responsive than one at the main base. Weigh the tradeoff: range advantage vs survivability.

---

### ROUND TYPES

| Round | Use |
|---|---|
| **HE** | Primary offensive round. Fragmentation effect against personnel and light vehicles. |
| **Smoke** | Concealment. Blind enemy crew-served positions. Mark objectives. |
| **Illumination (Flare)** | Night operations. **Critical:** The detonation fuse time must be **less than the round's flight time** or the flare will not activate — it will impact the ground as a dud. The auto-setting handles this correctly in most cases, but verify for extreme ranges. |

---

### SELF-LOCATION VIA RESECTION

Your mortar's accuracy depends entirely on knowing where *you* are. An accurate grid for the mortar position is not optional. If you do not know your position, your first round will be wrong regardless of how precisely you calculate everything else.

**Resection procedure (triangulation from known landmarks):**

1. Identify 3 or more known landmarks visible from your position (radio towers, prominent buildings, hilltops marked on the map).
2. Shoot a compass bearing to each landmark. Write them down.
3. Open the **Protractor** (default key: `B`) on your map.
4. Center the protractor on the **map marker** for the first landmark.
5. Open the **Pencil** (default key: `N`).
6. On the protractor, locate your bearing reading in mills. **Use the outer ring — the outer ring is mills, the inner ring is degrees.**
7. Draw a line from the bearing reading through the center of the protractor and extend it across the map.
8. Repeat for all landmarks.
9. The point where the lines intersect is your position. Mark it.

> **Accuracy note:** The intersection of two lines gives an approximate position. Three lines reduce error significantly — you should get a small triangle rather than a point. Your position is inside that triangle. The more landmarks used, the tighter the intersection.

---

### FIRING SOLUTION

With your position confirmed, calculating the firing solution is a four-step process.

**Step 1 — Draw the gun-to-target line:**
On the map, draw a line from your mortar position to the target grid.

**Step 2 — Read the azimuth:**
Center the protractor on your position. Read the azimuth to the target in **mills** (outer ring). This is your **deflection setting** — it appears at the bottom of the screen when you are on the gun.

**Step 3 — Measure the range:**
Use the ruler aligned to the gun-to-target line. Read the distance in **meters**.

**Step 4 — Find elevation in the ballistic table:**
Open the **Ballistic Manual** from the arsenal (quickslot to `0`). Find the M821H shell table.

- Locate the row matching your range
- Read the elevation value in **mills**
- **Charge rings** are the flammable attachments on the round — more rings = more propellant = more range. After the first round is manually inspected and charged, the game auto-sets rings for subsequent rounds.
- The current elevation setting is displayed on the left side of the screen when on the gun

---

### ELEVATION INTERPOLATION BETWEEN TABLE ENTRIES

When your exact range falls between two rows in the ballistic table (e.g., your target is 950m and the table has rows for 900m and 1000m):

1. Find the mills values for both rows (e.g., 900m = 1247 mills, 1000m = 1198 mills)
2. Subtract to find the total mills change across that 100m span: 1247 − 1198 = 49 mills per 100m
3. Divide by 100 to get mills-per-meter: 49 ÷ 100 = 0.49 mills/m
4. Multiply by your offset from the closer known row: 50m from the 900m row = 0.49 × 50 = ~25 mills
5. **Longer range = lower elevation mills** (flatter angle). Subtract to go farther, add to go shorter:
   - Your range is 950m (farther than 900m) → 1247 − 25 = **1222 mills**

> Use this same calculation to correct for a long or short registration round — the FO gives you the range error in meters; apply the math above to find the elevation correction.

---

### REGISTRATION ROUND AND FIRE FOR EFFECT

**Step 1 — Set up and fire the registration round:**
- Load a single HE round
- Set azimuth (deflection) to your calculated value
- Set elevation to your calculated value
- Fire one round
- Transmit: *“Shot out”* to the FO

**Step 2 — FO observes:**
- FO calls *“Splash”* 5 seconds before impact so the crew is timing the observation
- FO reports the result

**Step 3 — Adjust or FFE:**
- If the round is on target: *“Fire for effect.”* Pump rounds.
- If adjustment needed: apply the corrections from the FO (see below)

---

### RECEIVING AND APPLYING CORRECTIONS

The FO has two tools for measuring miss distance:

**Lateral correction (azimuth adjust):**
- FO marks the impact point on the map with a dot
- FO centers the protractor on the impact and measures the lateral deviation to the target **in mills**
- FO transmits: *“Left 30 mills”* or *“Right 45 mills”*
- Operator adjusts the azimuth dial by that mills amount in the stated direction

**Range correction (elevation adjust):**
- FO measures the range error with the ruler: *“Add 150 meters”* or *“Drop 80 meters”*
- Operator runs the elevation interpolation math above to convert meters to mills
- Operator adjusts the elevation setting accordingly

---

### AI MORTAR TEAMS

**Rank requirement:** Captain rank required to use AI mortar teams with HE rounds.

**Procedure:**
1. Build a mortar pit (Sergeant rank)
2. Spawn an AI mortar team (Commander operations table)
3. Issue the AI team a *“Get in”* command at the mortar position
4. From the map, issue an **artillery fire command** on the target location
5. AI crew will fire until ordered to stop or ammo is depleted

> AI mortar teams are reportedly accurate once properly positioned and given a valid target. Use them for sustained area suppression missions. Player crews provide better precision for time-sensitive HVT or danger-close missions.

---

## WCS MILSIM — SPECIFIC PROCEDURES

*These procedures apply specifically to WCS Milsim operations where the M252 mortar and WCS doctrine are in use. They supplement the FM 6-30 doctrine above.*

### WCS Callsigns (52.0 MHz)

| Callsign | Role |
|---|---|
| **Hawkeye Actual** | Forward Observer (FO) — calls the mission |
| **Hammer One** | Mortar/FCO — executes the mission |
| **Hitman Actual** | SNOT/Recon spotter requesting fire support |

All CFF traffic flows on **52.0 MHz** (Hammer/Hawkeye/Hitman net).

### WCS CFF Transmission Format

The WCS format adds a step: the observer requests, then awaits FCO acknowledgment before transmitting data.

```
FO:   "Hammer One, Hawkeye Actual, standby for fire mission."
FCO:  "Hawkeye Actual, Hammer One, send it."
FO:   [Warning Order] "Fire mission, adjust fire, HE."
FO:   [Target Location] "Grid [10-digit]" — OR polar method (see below)
FO:   [Method] "HE, [N] rounds, at my command."
FCO:  [Calculates, loads] "Ready."
FO:   "Fire."
FCO:  "SHOT!" (round leaves the tube)
FO:   [5-10 sec before impact] "SPLASH!" (warn friendlies)
FO:   [observes] "IMPACT!" [then corrections or FFE]
```

### Polar Observation Method (Preferred for WCS)

When the FO cannot determine the target's absolute grid, they provide a **polar plot** — their own location plus bearing and distance to the target. The FCO inputs this to the ballistic calculator.

**FO transmits:**
1. **FO 10-digit grid** + elevation (meters): *"FO grid: 04523-12340, elevation 8 meters."*
2. **Bearing** to target (degrees true): *"Bearing 057 degrees."*
3. **Distance** to target (meters): *"Distance 207 meters."*
4. **Height difference** (target vs FO, ±): *"Height difference: plus 14 meters."*

**FCO enters into ballistic calculator → outputs:**
- Elevation setting (mils)
- Azimuth setting (mils)
- Time of Flight (seconds)

### External Ballistic Calculator (Recommended)

> **GitHub:** [arcticfr33d0m/ArmaReforgerMortarCalculator](https://github.com/arcticfr33d0m/ArmaReforgerMortarCalculator)

The external calculator handles all the math for polar plotting. Input:
- Mortar grid (10-digit)
- FO grid (10-digit)
- Bearing from FO to target
- Distance FO to target
- Elevation difference
- Ammunition type

Output: Elevation (mils), Azimuth (mils), Time of Flight.

### Vector 21 Controls for Polar Input

The Vector 21 rangefinder is the FO's primary measurement tool:

| Action | Input |
|---|---|
| Measure range only | Hold `R` |
| Measure range + vertical difference | Hold `R`, then tap `R` again |
| Measure azimuth (bearing) | Hold `V` |
| Measure range + azimuth simultaneously | Hold `R` + `V` |
| Fall of Shot mode (measure corrections) | Tap `V`, hold `V`, tap `C` |

**Getting a 10-digit grid from the map:**
- Use DAGR/Orion GPS: read Eastings first, then Northings
- 10-digit grid = 5 easting digits + 5 northing digits

### Fire Sequence Calls

| Call | Who | When |
|---|---|---|
| `"SHOT!"` | FCO/Mortar | Round leaves tube |
| `"SPLASH [time]!"` | FO | 5-10 seconds before impact — warn friendlies |
| `"IMPACT!"` | FO | Round impacts — observe effects |
| Corrections | FO | If adjustment needed: "Add 80, Right 30" |
| `"Fire for effect."` | FO | On target — continue |
| BDA | FO | After FFE: battle damage assessment |
| `"End of mission."` | FO | When target neutralized |

**ACE Report (mortar crew to FCO after FFE):**
*"HE: [X] rounds remaining, Smoke: [X], ILLUM: [X]."*

### Advanced WCS Techniques

**Creeping Strike** — Walk rounds forward in 50m increments to clear protected infantry positions step by step.

**Shoot and Scoot** — Fire 2-3 rounds, displace mortar position before enemy can locate and return fire. Especially critical when enemy mortars are active.

**Smoke Screen** — Fire 4+ WP/smoke rounds across a front to conceal squad movement. Coordinate with SL before firing — smoke direction (wind) matters.

**Hasty Defensive Barrage** — Pre-register a TRP at the most likely enemy avenue of approach before the mission. If enemy breaks through, FO has an immediate FFE solution ready with zero calculation time.

---

## See Also

- [Sniper / Recon Guide](../02_role_guides/sniper_recon.md) — observer role, rangefinder mortar mode, synchronized sniper + indirect fire
- [Commander Guide](../02_role_guides/commander.md) — fire support rank gates, AI mortar team management
- [Tactical Fundamentals](../01_foundations/tactical_fundamentals.md) — OCOKA for OP selection, SA framework
- [Blue Falcon FIST SOP](../04_unit_doctrine/blue_falcon_fist_sop.md) — unit-level fire support and LRRP doctrine
- [Quick Reference Card](../00_start_here/quick_reference_card.md) — CFF format quick reference
- [Pucker Point CFF App](../06_tools/pucker_point_cff_app.html) — live CFF mission calculator with firing solution math
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
