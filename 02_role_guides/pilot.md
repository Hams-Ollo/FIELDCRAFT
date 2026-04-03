# PILOT / CO-PILOT / WSO GUIDE
## WCS Aviation Operations — Arma Reforger

> **Doctrine basis:** WCS Aviation Knowledge Packet — JTAC/CCT Handbook
> **Applies to:** WCS NA/EU Conflict servers — all aviation roles (Pilot, Co-Pilot, CAS WSO, MEDEVAC Crew Chief)
> **Net:** 51.0 MHz (JTAC/Aviation primary), 51.1 / 51.2 (aux), 49.0 MHz (MEDEVAC)

---

## AVIATION ROLES

| Role | Seat | Responsibility |
|---|---|---|
| **Pilot** | Left seat | Aircraft commander — flies, makes all decisions |
| **Co-Pilot** | Right seat | Navigation, communication assist, secondary systems |
| **WSO** (Weapons Systems Officer) | Rear seat | Targeting, weapons employment for attack/DAP aircraft |
| **Crew Chief** | Cabin | Troop management, door gun (if equipped), MEDEVAC care |

**Uniform and visor color code:**

| Visor | Role |
|---|---|
| **Black visor** | Attack aviation (AH-64, AH-1, AH-6) |
| **Gold visor** | Transport aviation (UH-60, CH-47, MH-6) |
| **Teal visor** | MEDEVAC (UH-60 MEDEVAC) |

Crew Chief wears a face shield. Pilots do not. Modern Green Flight Coveralls + HGU-56/P helmet for all aviation crew.

---

## AIRCRAFT IN WCS SERVICE

### Transport Aircraft

| Aircraft | Capacity | Notes |
|---|---|---|
| **UH-60 Black Hawk** | 8–10 troops | Primary assault/transport; also MEDEVAC variant |
| **CH-47 Chinook** | 20–30+ troops | Heavy lift; use for platoon-level inserts |
| **MH-6 Little Bird** | 4–6 troops | Fast insert/extract; uses external benches |

### Attack Aircraft

| Aircraft | Armament | Notes |
|---|---|---|
| **AH-64 Apache** | M230 30mm cannon, Hydra 70 rockets, AGM-114 Hellfire | Primary CAS platform |
| **AH-1 Cobra** | M197 20mm Gatling cannon | Nimble light attack |
| **AH-6 Little Bird** | Minigun, Hydra 70 rockets, Hellfire | Fast, low-signature attack |
| **MH-60 DAP** | Combined gun + rocket + Hellfire systems | Dual-role assault |

---

## FLIGHT PLANNING CONCEPTS

### Initial Point (IP)
The **IP** is the last waypoint before entering the target area. Aviation halts at the IP and awaits JTAC clearance before proceeding inbound. The IP is briefed in every LZ/HLZ brief and in the Air Mission Brief.

*The IP is the line of departure for aviation. Do not cross it without clearance from JTAC/GFC.*

### Checkpoints (CPs)
Intermediate waypoints from origin to IP. Each CP has:
- A grid
- An altitude gate (fly at or below X meters)
- A speed gate (arrive at or below X km/h)

This allows JTAC and GFC to track aviation movement toward the objective and deconflict airspace with ground elements.

### Air Mission Brief Elements
Before every sortie, the Pilot briefs:
1. **Route:** Origin → CP1 → CP2 → IP → Target/LZ
2. **Altitude:** Corridor altitudes for each leg
3. **Speed:** Gates at each CP
4. **Alternate LZ/HLZ:** If primary is hot
5. **Abort criteria:** What conditions cause the abort

---

## TRANSPORT OPERATIONS

### LZ / HLZ Selection
A clean LZ requires:
- **Space:** Rotor clearance on all sides
- **Surface:** Landing without sinking (avoid water, unstable terrain)
- **Security:** Ground element providing overwatch before and during insert
- **Access:** Troops can sprint on/off without terrain obstruction

*HLZ (Hot LZ) = active threat. LZ = secure. JTAC/SL marks via smoke or IR strobe.*

### Insert Procedures (Standard)
```
1. Approach from the IP at assigned altitude and speed
2. Announce "INBOUND" on 51.0 MHz (or squad net if direct insert)
3. Confirm LZ with ground element: "LZ [name], identify."
4. Ground marks with smoke/strobe; Pilot confirms color/type
5. Flare and reduce speed 100-200m out
6. Touch down; "TROOPS OUT" call
7. Wait for "CLEAR" from Crew Chief or SL
8. Lift off; announce "WHEELS UP" or "DEPARTING [direction]"
```

### Extract Procedures (Standard)
```
1. Ground element requests extract on 51.0 MHz or squad net
2. Pilot responds with ETA
3. Ground pops smoke or IR strobe on LZ
4. Approach from IP; flare; land
5. "TROOPS IN" once all onboard
6. Depart; announce "DEPARTING [direction]"
```

---

## CAS AVIATION — ATTACK PROCEDURES

### MNPOPCA Check-In (with JTAC)
On arrival at station, attack aviation checks in with JTAC on 51.0 MHz:

| Element | Content |
|---|---|
| **M** — Mission | "CAS escort for convoy" |
| **N** — Net | "51.0, 51.1 backup" |
| **P** — Position | "Current grid or area: [X]" |
| **O** — Ordnance | "30mm cannon, 14x Hydra 70, 8x Hellfire" |
| **P** — Platform | "AH-64 Apache, callsign Steel One" |
| **C** — Cockpit | "Single aircraft / flight of two" |
| **A** — Abort criteria | "Abort if friendlies within 100m of target" |

### Types of Control

| Type | What it Means | When Used |
|---|---|---|
| **Type 1** | JTAC has visual of both aircraft AND target; gives explicit clearance each run | High-risk, complex environments |
| **Type 2** | JTAC has visual of target OR aircraft (not both); gives clearance with restrictions | Default for most WCS CAS missions |
| **Type 3** | JTAC authorizes series of attacks without individual clearance; aircraft self-designates | Fast-moving targets, permissive environment |

### 9-Line CAS Request (Received from JTAC)
Aviation receives this from JTAC:

| Line | Element |
|---|---|
| 1 | IP location |
| 2 | Heading from IP to target + distance |
| 3 | Target elevation (MSL) |
| 4 | Target description |
| 5 | Target location (grid) |
| 6 | Datum / mark type |
| 7 | Location of friendlies |
| 8 | Egress direction |
| 9 | Remarks / restrictions |

**Keyhole Method:** Attack aviation approaches perpendicular to friendly lines (not parallel), enters a keyhole pattern inbound, and exits parallel to the far side of the target — minimizing overflight of friendly positions.

### 5-Line CAS (Rapid Engagement)
Used when a full 9-Line is not feasible. Abbreviated direct-to-engagement call:

| Line | Content |
|---|---|
| 1 | Target location |
| 2 | Target description |
| 3 | Ingress direction |
| 4 | Friendliest closest position |
| 5 | Remarks |

### Attack Aviation Pro-Words

| Call | Meaning |
|---|---|
| `INBOUND` | Beginning attack run |
| `ON STATION` | Aircraft arrived, ready for tasking |
| `WINCHESTER` | All ordnance expended |
| `BINGO FUEL` | Minimum fuel — must return to base |
| `JOKER FUEL` | Bingo fuel warning — proceed to IP or return |
| `MAYDAY` | Emergency |

---

## MEDEVAC AVIATION PROCEDURES

**Net:** 49.0 MHz — callsign **ANGEL**

MEDEVAC responds to 9-Line requests from ground medics. Pilot version of the 9-Line:

| Line | Element |
|---|---|
| 1 | IP — halt and await confirmation before approach |
| 2 | Pickup site grid + elevation |
| 3 | Number of patients and type (Urgent/Priority/Routine) |
| 4 | Security at pickup site (Secure / Unsecure / Enemy fire) |
| 5 | Marking (smoke, IR strobe, signal mirror) |
| 6 | Nationality / military / civilian |
| 7 | Area description (terrain, obstructions) |
| 8 | Friendly ETA at LZ |
| 9 | Equipment requested / remarks |

**MEDEVAC pilot approach:**
1. Coordinate with JTAC/GFC to ensure airspace is clear
2. Hold at IP until LZ marked and confirmed secure (or accept risk if Urgent)
3. Approach; ground pops smoke or strobe
4. Confirm marking; land; load patients
5. Crew Chief manages patient loading
6. Depart to Field Hospital grid

---

## FORMATION FLYING

| Formation | Description | When Used |
|---|---|---|
| **Trail** | Aircraft in single file | Default, limited visibility |
| **Echelon Left/Right** | Offset to one side | Mutual support, single approach |
| **V Formation** | Lead front, two wingmen back | Mutual coverage, open terrain |
| **Staggered** | Alternating offsets | Flexibility, space management |
| **Combat Spread** | Maximum lateral separation | High threat, independent maneuvering |

Lead aircraft navigates. Trail aircraft maintains visual on lead and holds assigned interval.

---

## EMERGENCY PROCEDURES

**Engine / airframe failure:**
1. Call "MAYDAY MAYDAY MAYDAY, [callsign], [nature of emergency], [grid]" on 51.0 MHz
2. Attempt controlled landing at nearest suitable site
3. Ground element coordinates security and MEDEVAC for crew

**LZ under fire (Hot LZ):**
1. Call "LZ HOT" — do not land
2. Break off approach; establish safe orbit
3. Coordinate with JTAC for suppression before second approach
4. Approve second approach only after JTAC confirms "LZ Cold"

**Loss of comms:**
- Return to FB/base
- Pre-brief alternate frequency (51.1 backup) before every mission

---

## QUICK REFERENCE

```
TRANSPORT INSERT:
  IP → "INBOUND" → Ground marks LZ → Confirm color → Land
  "TROOPS OUT" → Clear → Liftoff → "WHEELS UP"

MEDEVAC:
  Receive 9-Line on 49.0 → Hold at IP → Confirm LZ mark
  Load patients → Depart to Field Hospital

CAS CHECK-IN (JTAC):
  MNPOPCA format on 51.0 MHz

ATTACK RUN:
  9-Line or 5-Line → Confirm Type of Control
  "INBOUND" → Prosecute → "OFF [direction]" → BDA
```

---

## See Also

- [JTAC/DEALER Guide](../02_role_guides/sniper_recon.md) — fire support integration, JTAC procedures
- [Call for Fire SOP](../03_tactical_sop/call_for_fire_sop.md) — coordinates with 9-Line CFF fire support
- [MEDEVAC SOP](../03_tactical_sop/medevac_sop.md) — 9-Line ground request format, CCP to LZ procedures
- [Communications SOP](../03_tactical_sop/communications_sop.md) — 51.0/49.0 net structure, aviation callsigns
- [NATO Loadouts](../07_loadouts/nato_loadouts.md) — Aviation crew gear, visor color code, extra medical kit
