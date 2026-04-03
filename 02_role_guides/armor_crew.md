# ARMOR CREW GUIDE
## Vehicle Commander, Gunner, and Driver — WCS Conflict Operations

> **Doctrine basis:** WCS Armor Knowledge Packet
> **Applies to:** WCS NA/EU Conflict servers — all ground vehicle crew roles
> **Callsign:** Tempest (Armor element) on 50.0 MHz platoon net

---

## ARMOR CREW ROLES

| Role | Abbreviation | Responsibility |
|---|---|---|
| **Vehicle Commander** | VC | Tactical decision-making, all-around awareness, navigation, radio |
| **Gunner** | — | Weapon system operation, target engagement |
| **Driver** | — | Vehicle movement, terrain navigation, spacing |

The **VC is the aircraft commander equivalent** — every vehicle action comes from the VC's call. The Gunner and Driver execute, the VC commands.

---

## VEHICLES IN WCS SERVICE

| Vehicle | Primary Role | Notes |
|---|---|---|
| **M2A3 Bradley** | Armored infantry fighting vehicle | 25mm autocannon, M240 coaxial, TOW ATGM; carries infantry squad |
| **Stryker ICV** | Infantry carrier | 12.7mm HMG; wheeled, high mobility |
| **LAV-25** | Recon / cavalry | 25mm autocannon; amphibious |
| **M1A2 Abrams** | Main battle tank | 120mm main gun; crew only, no dismounts |

---

## INTERNAL CREW COMMUNICATIONS

### Clock Direction System
All target calls inside the vehicle use the **clock face** for direction. 12 o'clock = straight ahead of the vehicle.

**Format:** `"[Threat type], [clock direction], [high/level/low], [range/description]."`

| Element | Options | Example |
|---|---|---|
| Threat | Enemy tank / IFV / infantry / AT team | "Enemy AT team" |
| Direction | 1–12 o'clock | "3 o'clock" |
| Elevation | High / level / low | "level" |
| Description | Range or landmark | "300 meters, behind the stone wall" |

**Full example:** *"Enemy tank, 10 o'clock, low, 400 meters, treeline."*

### Movement Orders
VC states direction of movement before Driver moves:
- *"Driver, advance."*
- *"Driver, halt."*
- *"Driver, right 45, slow."*
- *"Driver, back up, 20 meters."*

Gunner states when weapon is loaded and ready:
- *"Gunner, up."* — Ready to fire
- *"Gunner, on."* — Weapon on target

---

## CONVOY TACTICS

### Spacing Rules

| Environment | Spacing |
|---|---|
| Open terrain | 50–100 m between vehicles |
| Urban / restricted | 25–50 m |
| Dense forest | 20–50 m |

**Never stop during contact.** If the lead vehicle is engaged, the convoy pushes through the kill zone. Stopping presents a stationary target. Drive through, break out of the ambush, then consolidate. An immobile armored vehicle is a destroyed armored vehicle.

### Convoy Spacing Rationale
Massed vehicles within kill zone distance of a single AT team are all vulnerable to a single engagement. Spacing forces the enemy to choose — they cannot simultaneously engage all vehicles. The vehicles not being engaged become the response element.

---

## VEHICLE FORMATIONS

| Formation | Description | Spacing | Use |
|---|---|---|---|
| **Line** | All vehicles abreast | 75–150 m lateral | Assault, deliberate attack, defensive line |
| **Wedge** | Lead vehicle forward, two wingmen back-left and back-right | 50–100 m | Flexibility, cross-country movement |
| **Column** | Single file | Per environment table | Restricted terrain, roads, urban |
| **Echelon Left** | Column offset to the left | 50–75 m diagonal | Threat from the right, flank engagement |
| **Echelon Right** | Column offset to the right | 50–75 m diagonal | Threat from the left, flank engagement |
| **V Formation** | Two lead vehicles, one trailing center | 75–125 m | Recon, threat expected to front |

**Formation selection is VC's call.** When in doubt, Column for restricted routes, Wedge for open terrain with unknown threat direction.

---

## DISMOUNT PROCEDURES

The VC calls the dismount type. Infantry acknowledge and execute accordingly.

| Type | Description | When Used |
|---|---|---|
| **Full Dismount** | All infantry out, vehicle stays | Area clearing, objective assault |
| **Partial Dismount** | Selected elements out, others remain | Recon/security without full commitment |
| **Rapid Dismount** | Emergency fast exit — all out immediately | Contact, imminent threat to vehicle |
| **Rolling Dismount** | Vehicle moves slowly (~5 mph), infantry step off | Urban movement, soft presence patrol |
| **Deliberate Dismount** | Planned, coordinated exit at a prearranged point | Pre-planned assaults, breach operations |
| **Directional Dismount** | Infantry exits to a specific clock direction | "Dismount 3 o'clock" — flanking insert |

**Rolling dismount / Urban rolling cover:** Infantry dismount while vehicle maintains ~5 mph (8 km/h). Infantry use the vehicle's hull as moving cover — walking 2–3 meters behind/beside it. The vehicle advances in bounds while infantry clear doorways on either side. This is the standard WCS urban tactic for combined arms clearing.

---

## BOUNDING OVERWATCH

Two vehicles or two elements advance in alternating bounds. The stationary element maintains overwatch (weapon on) while the other bounds forward.

### Successive Bounding (Inchworm)
Lead bounds forward to a new covered position. Trail then comes up even with the new lead. Repeat.

```
  [A] ──────► [A+]         Trail follows to new lead position
  [B] (overwatch)   ──► [B] (still overwatch)
```
When to use: Standard movement, one clear direction of threat.

### Alternating Bounding (Leapfrog)
Lead bounds past trail's position to a point *ahead* of trail. Roles swap each bound — the previous lead is now the overwatch element.

```
  [A] ──────────────► [A+] (now forward)
  [B] (overwatch) ──►    [B+] (new forward)
```
When to use: Unknown threat direction, faster tempo needed, complex terrain.

**Standard bound distance:** 50–100 m per bound, adjusted to available covered positions.

---

## COMMS WITH GROUND INFANTRY

The VC maintains comms on the **squad net** or **platoon net (50.0 MHz)** in coordination with the accompanying infantry SL.

**Vehicle to infantry calls:**
- *"Standby for rolling dismount."*
- *"Vehicle suppressing, bound to the treeline."*
- *"Vehicle halting — enemy AT team, 2 o'clock, 200 meters. Do not break cover."*
- *"Infantry clear — vehicle advancing."*

**Infantry to vehicle calls:**
- *"AT team, 2 o'clock, treeline — suppressing."* (gives VC direction to engage)
- *"Clear to advance."*
- *"Vehicle requested, our position — extract."*

---

## THREAT AWARENESS

### AT Priority
Enemy anti-tank teams are the primary threat to armor in WCS. AT teams will attempt to:
1. Flank or approach from dead zones (rear arc, blind spots)
2. Engage from concealed positions at close to medium range
3. Use buildings and terrain to get within effective RPG/SMAW range

**VC responsibility:** Maintain all-around awareness. Use infantry to secure close flanks the vehicle cannot see into.

### Urban Threat
In urban terrain, every window and doorway is a potential AT ambush. Do not commit armor into urban without infantry on foot clearing ahead and flanking. A single RPG from a second-story window ends the vehicle.

### Counter-AT Drill
1. Enemy AT team identifies and fires.
2. If incoming, maneuver (accelerate, change direction) — do not sit still.
3. Gunner and VC call direction: *"AT team, 7 o'clock, second building roof."*
4. Decision: suppress with vehicle weapon and bound away, or pop smoke and egress.
5. Suppress → infantry flanks → eliminates. Or: smoke → egress if situation is unfavorable.

---

## QUICK REFERENCE

```
FORMATION:   Wedge (default open) | Column (roads) | Line (assault)
SPACING:     Open 50-100m | Urban 25-50m | Forest 20-50m

TARGET CALL: "[Threat], [clock], [high/level/low], [range]"
             "Enemy tank, 10 o'clock, level, 400 meters."

DISMOUNT:    VC calls type — Full / Partial / Rapid / Rolling / Deliberate / Directional

BOUNDING:    Successive (inchworm) or Alternating (leapfrog) — 50-100m per bound

URBAN RULE:  Infantry behind/beside armor at ~5 mph — rolling cover
DON'T STOP:  Never halt during contact in kill zone — drive through
```

---

## See Also

- [Movement and Formations SOP](../03_tactical_sop/movement_and_formations.md) — infantry bounding and formation doctrine
- [React to Contact SOP](../03_tactical_sop/react_to_contact.md) — vehicle reaction to ambush and AT contact
- [Communications SOP](../03_tactical_sop/communications_sop.md) — Tempest callsign, 50.0 MHz net
- [NATO Loadouts](../07_loadouts/nato_loadouts.md) — Driver, Gunner, VC crew loadouts
- [Anti-Armor Guide](anti_armor.md) — fighting against armor from the infantry perspective
