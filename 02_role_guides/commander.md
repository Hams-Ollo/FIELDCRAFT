# COMMANDER ROLE GUIDE
## Battlefield Management for WCS Conflict

> **Application:** WCS servers — Commander system mechanics, AI management, logistics direction
> **Source:** Damage Dealer WCS Commander Guide

---

## THE COMMANDER MINDSET

> *"The Commander is a traffic controller, not a boss."*

Your job is to control the flow of the battlefield — not to bark orders at every player. You cannot be everywhere. What you can do is:

- Control the supply chain that determines what the team can build and field
- Build and link the FOB network that defines where the team can spawn
- Spawn AI fire teams and vehicles that multiply team combat power without consuming player slots
- Respond to squad-level support requests faster than any individual player can

A Commander who micromanages loses the team's trust and attention. A Commander who enables combat power wins.

---

## HOW TO BECOME COMMANDER

1. Locate the **Volunteer Sign** at the main base (MOB)
2. Interact to register as a candidate
3. The team votes — majority vote promotes you to Commander
4. You now have access to all three Commander systems

There can only be one Commander at a time. If the current Commander is inactive, another player can volunteer for a new vote.

---

## THE THREE COMMANDER SYSTEMS

### 1. Logistics System

Controls the supply economy. This is your most powerful strategic lever.

**Supply Priority:**
- Assign each base a supply priority: 1, 2, or 3
- Priority 1 bases receive supply first — set this to your most critical frontline FOB
- Set a **maximum supply limit** per base (recommended: 10,000 cap to prevent wasteful stacking that leaves rear depots dry)

**AI Logistics Teams:**
- Assign AI logistics teams from the Commander interface
- Teams auto-task to the nearest supply source and deliver to priority bases
- Multiple teams can run different legs of the supply chain simultaneously
- Manage from the operations table — issue move orders as supply sources change

### 2. Operations Table

Your primary command and control interface.

| Function | How |
|---|---|
| **View any base** | Click "Start Building" on any base marker → view teleports to that location |
| **Build remotely** | Direct construction at any base from the table, no physical presence required |
| **Spawn AI fire teams** | Select type → assign to location |
| **Spawn vehicles** | Vehicles appear at the selected base's vehicle depot |
| **Manage mortar pits** | Position and assign AI mortar crews from the map |

**Base-to-Base Jump:** Operations Table → hover over any base marker → "Start Building" → your view teleports to that base. Use this constantly to monitor all positions without physically traveling.

### 3. Combat Support System

Right-click any map location to open the support request menu:

| Request Type | Effect |
|---|---|
| **Repair** | Dispatch a repair team to a vehicle or position |
| **Reinforce** | Send a fire team to hold a location |
| **Rearm** | Resupply a squad or position |
| **Establish Base** | Initiate FOB construction at a marked location |

**Assigning squads to requests:** Select the specific squad you want to task → issue the support request for their location → the tasking appears in that squad leader's interface.

---

## THE COMMAND TRUCK

The command truck is a **mobile command post** with all three Commander systems on board.

- Contains a full operations table interface
- Can be driven to forward positions for direct battlefield coordination
- **Must remain within radio tower range of a friendly base** — losing radio coverage means losing command access entirely
- Treat the command truck as a protected priority asset — it represents your entire C2 capability in the field

---

## RANK GATES FOR FIRE SUPPORT

Commander rank determines what fire support you can authorize. Know your gate before making fire support promises to squad leaders.

| Rank | Fire Support Capability |
|---|---|
| **Corporal** | Smoke rounds; Illumination (flare) artillery |
| **Sergeant** | HE artillery rounds; ability to **build mortar pits** |
| **Captain** | AI artillery fire teams (mortar teams operating independently) |

> **Planning note:** If you are below Sergeant rank and the team needs HE fire support, you cannot provide it. Build rank early by completing objectives, and plan your fire support capability before it is urgently needed.

---

## MAP MARKERS

| Marker Type | Use |
|---|---|
| **Custom** | Free-form markers for any command purpose |
| **Military** | Preset tactical icons (friendly units, objectives, assets) |
| **Recon** | Intelligence markers — known enemy positions, minefields, obstacles |

Markers can be **moved and deleted** at any time.

**Keep the map clean.** A map cluttered with outdated markers causes wrong decisions. Conventions:
- Mark confirmed enemy positions as Recon markers so the entire team sees the threat picture
- Use Military markers for friendly forces and assigned objectives
- Delete markers when the situation has changed

---

## AI FIRE TEAM MANAGEMENT

**Logistics Teams:**
- Assign to supply circuits from the logistics system
- Position near supply sources and issue destination move orders
- Multiple teams can run different legs of the chain simultaneously

**Mortar Teams (Captain rank required for HE):**
- Assign to a built mortar pit
- Issue an artillery fire command from the map — click the target location
- AI crew fires until ordered to stop or ammo is depleted
- AI mortar teams are reportedly accurate — use them for sustained area suppression while player-crewed mortars handle precision missions

---

## COMMANDER HABITS

- **Check supply levels every 2 minutes.** Frontline FOBs dry out fast during sustained pushes.
- **Build the radio chain before the combat chain.** No comms = your fire support is blind.
- **Communicate support availability.** If you have HE available, tell the squad leaders. If you are out, tell them before they plan their assault around it.
- **Stay at the operations table.** Active management of bases and AI is your primary function. You cannot lead a squad and command at the same time.
- **Protect the command truck.** If it is destroyed in enemy territory, your C2 capability is lost until another is spawned.

---

*Source: Damage Dealer WCS Commander Guide*
*Rank gate mechanics are WCS-specific — verify against current server version if changes have been patched*

---

## See Also

- [Logistics Operator Guide](logistics_operator.md) — ground-level supply running mechanics
- [Call for Fire SOP](../03_tactical_sop/call_for_fire_sop.md) — fire support rank gates, mortar operator procedures
- [Sniper / Recon Guide](sniper_recon.md) — HVT missions, synchronized fire, SALUTE reporting
- [Machine Gunner Guide](machine_gunner.md) — base of fire management, ammo calculus
- [Mission Planning Framework](../04_unit_doctrine/mission_planning_framework.md) — pre-session briefing template
- [Quick Reference Card](../00_start_here/quick_reference_card.md) — objective priority, FOB build order
