# MEDEVAC SOP
## Medical Evacuation Procedures for WCS Conflict

> **Doctrine basis:** TC 8-800 (Combat Casualty Care); FM 4-02.2 (Medical Evacuation); TCCC Guidelines
> **Application:** WCS servers — casualty triage, 9-line request, CASEVAC and MEDEVAC procedures

---

## PURPOSE

Every casualty in WCS Conflict will either be recovered and return to the fight, or be abandoned and respawn with a full gear reset. The difference is how fast the element responds and how well casualty procedures are executed.

**This SOP covers:**
- Triage (who gets treated first and why)
- 9-Line MEDEVAC request format
- CASEVAC vs MEDEVAC distinction
- Landing zone procedures
- Buddy aid (what the rifleman does while waiting for the medic)

---

## TRIAGE — WHO GOES FIRST

Triage is the process of sorting casualties by urgency to maximize the number of survivable players. In WCS, this means the Medic and any player rendering buddy aid treats in a specific precedence — not first-come-first-served.

### MEDEVAC Precedence Categories

| Category | Description | Timeframe |
|---|---|---|
| **URGENT** | Life-threatening — will not survive without immediate treatment | Evacuate as soon as possible |
| **URGENT SURGICAL** | Requires surgical intervention that cannot be done in the field | Evacuate immediately to surgical capability |
| **PRIORITY** | Serious but survivable — will deteriorate without treatment | Evacuate within 4 hours |
| **ROUTINE** | Stable — condition will not worsen significantly | Evacuate within 24 hours |
| **CONVENIENCE** | Minor — no effect on outcome if treatment is delayed | Treat when resources allow |

**In WCS field terms:**
- Unconscious, heavy bleeding, unresponsive = **URGENT**
- Responsive but immobile, multiple wounds = **PRIORITY**
- Ambulatory, walking wounded = **ROUTINE**

> **The Medic treats the most critically wounded first — not the first one who calls, not the squad leader, not whoever the loudest player is on the radio. The most critical patient first.**

---

## 9-LINE MEDEVAC REQUEST

The 9-Line is the NATO standard medical evacuation request format. This is the call format used to request helicopter casualty evacuation on any server with air MEDEVAC capability.

**Before the mission:** Confirm the MEDEVAC net frequency and the callsign for the MEDEVAC crew or logistics element. This is not information you want to be looking up at the point of injury.

---

### THE 9 LINES

| Line | Content | Codes / Notes |
|---|---|---|
| **Line 1** | Pickup site location | 6- or 8-digit grid (MGRS). State clearly — this is the most critical line. |
| **Line 2** | Radio frequency and callsign | Net frequency + your callsign. The MEDEVAC crew will contact you directly on this frequency. |
| **Line 3** | Number of patients by precedence | Format: *"1 Urgent, 2 Priority, 0 Routine, 0 Convenience"* |
| **Line 4** | Special equipment required | **A** = None / **B** = Hoist / **C** = Extraction equipment / **D** = Ventilator |
| **Line 5** | Number of patients by type | **L** = Litter (cannot walk) / **A** = Ambulatory (can walk) |
| **Line 6** | Security of pickup zone | **N** = No enemy / **P** = Possible enemy / **E** = Enemy in area *(say "Echo," never the letter E)* / **X** = Armed escort required |
| **Line 7** | Method of marking the LZ | Panels / Pyrotechnic signal / Smoke (state color when aircraft is in sight) / None / Other |
| **Line 8** | Patient nationality and status | **A** = US Military / **B** = US Civilian / **C** = Non-US Military / **D** = Non-US Civilian / **E** = Enemy Prisoner of War |
| **Line 9** | Terrain description | Obstacles, tree lines, wires, surface type, prominent landmarks, recommended approach/departure heading |

---

### EXAMPLE 9-LINE CALL

> *"DUSTOFF, this is FALCON SIX, 9-line MEDEVAC request, over."*
> *(Wait for acknowledgment)*
>
> *"Line 1: Grid 3-7-6-4-5-2, MGRS, over."*
> *"Line 2: Frequency 4-4-point-5, callsign FALCON SIX, over."*
> *"Line 3: 1 Urgent, 1 Priority, over."*
> *"Line 4: Alpha — no special equipment, over."*
> *"Line 5: 1 Litter, 1 Ambulatory, over."*
> *"Line 6: Papa — possible enemy, over."*
> *"Line 7: Smoke, color to follow, over."*
> *"Line 8: Alpha — US Military, over."*
> *"Line 9: Open field, trees on east and west, no wires. Recommend north approach, over."*

---

### KEY NOTES

**Line 6 — Never say the letter "E" on radio.** The brevity code for "enemy in area" is transmitted as **"Echo"** to prevent phonetic confusion. If the pickup zone has enemy nearby:

- Clear LZ: *"Line 6: November"*
- Enemy nearby: *"Line 6: Echo"*
- Need armed escort: *"Line 6: X-Ray"*

**Line 7 — Smoke color procedure:** When the aircraft is inbound and requests smoke identification, pop the smoke *first*, then tell them what color you're using when they ask. **Never tell them the color before they call it.** If you say "popping purple" before they're overhead, the enemy can pop the same color to draw the helicopter to a trap. The pilot calls the color they see; you confirm.

---

## CASEVAC vs MEDEVAC

| | CASEVAC | MEDEVAC |
|---|---|---|
| **What it is** | Casualty evacuation by any available non-medical vehicle | Dedicated medical evacuation vehicle or aircraft |
| **In WCS** | Squad vehicle, truck, ATV — anything drivable | Dedicated medical helicopter if the server has it active |
| **When to use** | No MEDEVAC available; patient stable enough to move; threat requires immediate evacuation | Patient requires higher care; dedicated asset is available; critical patient who can survive the wait |
| **Who calls it** | SL, TL, any player with comms | Medic or SL via 9-line format on the medical net |
| **Advantage** | Fast — any vehicle, right now | Medical capability en route; flight crew can treat while moving |

**In most WCS matches, CASEVAC is the primary means.** Helicopter MEDEVAC requires coordination and frequently is not organized at the server level. Treat CASEVAC as your default and MEDEVAC as the exception when it is available.

---

## CASUALTY COLLECTION POINT (CCP)

When the squad takes multiple casualties during a firefight, treat casualties at a designated CCP rather than treating in place across the objective.

**CCP selection:**
- Out of the direct line of fire — behind a ridgeline, structure, or terrain feature
- Large enough to lay out multiple casualties simultaneously
- Accessible by vehicle for CASEVAC
- Close enough to the fight that the Medic does not have to travel far under fire to reach it

**CCP procedures:**
1. Non-medical players carry or drag casualties to the CCP *(the Medic does not carry patients — the Medic treats patients)*
2. Medic sets up at the CCP and treats in triage precedence
3. Squad Leader reports CCP grid to higher and requests CASEVAC or MEDEVAC
4. One player provides CCP security — the Medic cannot treat and watch their own flanks simultaneously

---

## BUDDY AID — WHAT THE RIFLEMAN DOES

When your buddy goes down and the Medic is not immediately present, you are the first responder.

### MARCH Protocol (adapted for WCS)

| Step | Action |
|---|---|
| **M — Massive hemorrhage** | Apply tourniquet to limb wounds. Apply ACE bandage or packing bandage to torso wounds. |
| **A — Airway** | No direct WCS equivalent — go to next step |
| **R — Respiration** | No direct WCS equivalent — go to next step |
| **C — Circulation** | Apply pressure dressing if additional wounds present |
| **H — Hypothermia / Hazard** | Drag casualty to cover; remove from immediate threat |

**In WCS execution:**
1. Drag casualty behind cover (carry/drag key)
2. Apply bandage to wounds; tourniquet to limb wounds
3. Stabilize and hold until the Medic arrives
4. Report: *"Bravo Six is down, grid X, Priority, needs morphine"*

> **Do NOT attempt casualty care while under direct fire.** Get to cover. Apply care. A second casualty helps no one — and a dead buddy aid provider means the original casualty has no one.

---

## LANDING ZONE (LZ) PREPARATION

If a helicopter MEDEVAC is confirmed inbound, prepare the LZ before it arrives.

### LZ Selection Criteria

- **Minimum 35 × 35 meters** of clear, flat ground — the aircraft needs room to hover or land safely
- **No obstructions** within 50 meters on the approach and departure headings
- **Firm surface** — waterlogged or extremely uneven ground can complicate setting down
- **Away from active fire** — the helicopter is a high-value target; do not land it under direct fire

### LZ Marking Procedure

1. Place VS-17 panels or a smoke grenade at the center or upwind edge of the LZ
2. When the helicopter is inbound and calls for identification: **pop smoke first, then confirm color when the pilot reports it** *(never broadcast the color before the pilot asks — see smoke color procedure above)*
3. When the pilot calls the color they see, confirm or correct
4. If the pilot calls the wrong color: *"Negative, I see [correct color]. Re-smoke, over."*

### LZ Security

Four players minimum — one oriented toward each cardinal direction. The LZ is a priority target when a helicopter is on the ground loading casualties. Security is not optional and does not stand down until the aircraft departs.

---

## COMMUNICATION AT THE POINT OF INJURY

When a player goes down, two transmissions start the evacuation process. Everything else waits.

**Transmission 1 — Witness:**
> *"[Callsign] is down, grid [grid], [urgency]"*

**Transmission 2 — SL or Medic requesting CASEVAC:**
> *"Need a vehicle at [grid], [number] litter, route via [direction]"*

Detailed status updates go after the CASEVAC vehicle is moving. On the initial call: grid, callsign, urgency. That is all.

---

## MEDIC COORDINATION

The Combat Medic runs casualty operations. Every other player defers to the Medic on casualty decisions once contact is broken or the CCP is established.

**Rifleman's job at the CCP:**
- Carry casualties to the Medic — do not wait for the Medic to come to the patient
- Provide security — the Medic cannot treat and watch their flanks
- Give the Medic a brief: *"Two urgent, one routine. Both tourniquet applied."* Then step back and let the Medic work

**SL's job at the CCP:**
- Report to higher, request CASEVAC/MEDEVAC
- Account for all players
- Keep security out — do not collapse everyone into the CCP to watch the Medic work

Refer to the [Combat Medic Guide](../02_role_guides/combat_medic.md) for full medical protocols, ACE treatment mechanics, and damage system details.

---

*Source: TC 8-800 (Combat Casualty Care); FM 4-02.2 (Medical Evacuation); TCCC Guidelines; WCS community doctrine*

---

## See Also

- [Combat Medic Guide](../02_role_guides/combat_medic.md) — full medic role, ACE medical system, morphine protocol, bag drop
- [React to Contact SOP](react_to_contact.md) — casualty handling during active contact, CCP under fire
- [Assault Rifleman Guide](../02_role_guides/assault_rifleman.md) — buddy aid protocol, what to do when your buddy goes down
- [Tactical Fundamentals](../01_foundations/tactical_fundamentals.md) — SALUTE reporting, SA framework, communication doctrine
- [Quick Reference Card](../00_start_here/quick_reference_card.md) — 9-line quick reference, brevity codes
