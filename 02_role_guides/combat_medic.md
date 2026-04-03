# COMBAT MEDIC GUIDE
## Keeping Your Squad in the Fight — WCS Conflict Servers

> **Doctrine basis:** US Army TC3 / TCCC (Tactical Combat Casualty Care) — adapted for WCS vanilla medical system
> **Applies to:** WCS NA/EU Conflict servers — vanilla Arma Reforger medical + Realism Overhaul Medical mod
> **Version note:** This guide covers the current WCS medical system. Advanced mods like ACE Medical and KAT introduce additional mechanics (CPR, cardiac arrest, IV lines, vitals monitoring) not covered here. If your server runs those, treat this as your foundational layer.

---

## THE MEDIC'S MISSION

The medic is not a shooter who also carries bandages. The medic is a **combat multiplier** — a specialist whose entire value is keeping the squad's weapons in the fight. Every player you save is one more gun on the line. Every player you lose is a respawn timer, a lost position, a hole in the formation.

Your weapon is your medical bag. Your primary tactic is getting to casualties fast, treating efficiently, and getting them back on their feet before the squad loses momentum.

Real TC3 doctrine taught to every combat medic in the US Army divides the battlefield into three phases of care: **Care Under Fire**, **Tactical Field Care**, and **Tactical Evacuation Care**. WCS gameplay maps almost exactly onto the first two. Understanding the phase you are in dictates what you do and how fast you need to do it.

---

## PHASE 1 — CARE UNDER FIRE

*The fight is still active. Rounds are incoming. The casualty just went down.*

In real TC3, Care Under Fire has one priority: **return fire and achieve fire superiority first.** A dead medic treats nobody. A medic who runs to a casualty while the squad is still taking effective fire will likely become a second casualty — compounding the problem instead of solving it.

**Your actions in this phase:**

**1. Return fire.** Even as a medic, you contribute to suppression. If you are not in a covered position, get to one. Your squad needs to win the firefight before any treatment is possible.

**2. Call it out.** Announce the casualty on squad net so the squad leader knows: *"Litter, northwest corner of the building."* The squad knows there is a man down and where.

**3. Direct your squad.** If you have communication with the squad leader, call for suppressive fire on the enemy position to create a window for movement. *"Covering fire, I'm moving to the casualty."*

**4. Use smoke.** Once you are ready to move, pop a white smoke grenade between you and the enemy before breaking cover. White smoke blocks line of sight and gives you concealment for the movement to the casualty and the treatment. This is one of the most underused mechanics on WCS servers. Two white smokes buys you a treatment window that direct suppression alone cannot guarantee.

**5. Move to the casualty under cover.** Sprint, stay low, use terrain. Get to the casualty and get down.

> **Do not attempt treatment while rounds are still impacting near your position.** The only treatment appropriate under direct fire is a tourniquet — fast, one-handed, buys time. Everything else waits for the next phase.

---

## PHASE 2 — TACTICAL FIELD CARE

*Fire superiority has been achieved. The squad is covering. You have a treatment window.*

This is where the majority of your work happens. You have time measured in seconds to minutes — not indefinitely. Stay aware of the tactical situation. If contact resumes, you may need to break off and return to Phase 1.

**On WCS servers:** You cannot drag a casualty to a better position. You work on them where they fell. If they are in a dangerously exposed position, use smoke to create concealment around them before beginning treatment. You can roll the patient onto their back or side using the interaction menu — do this if they are face-down and you cannot access their wounds.

---

## THE TREATMENT SEQUENCE

This is the core of WCS medical. Execute this in order every time. Deviations waste time and supplies.

### Step 1 — CHECK INJURIES

Before touching anything, use the **Check Injuries** interaction on the casualty. This gives you the injury report: which limbs are bleeding, severity (light, moderate, heavy), and whether the head or torso is injured.

**Quick injury check:** Hold `F` to inspect a patient's injuries without opening the full interaction menu — useful for rapid status assessment mid-treatment.

> **Enemy casualty:** If you encounter a wounded enemy and the tactical situation is active, **middle mouse button** to execute. Do not expend treatment time or supplies on enemy combatants while your own squad needs care.

Assess the situation in three seconds:
- Where is the bleeding?
- How heavy is it?
- Is it limbs only, or head/torso involved?

This dictates your entire treatment plan.

**Bleeding indicators:**
- **Yellow color** — Light bleeding. Lower urgency but will accumulate.
- **Red color** — Heavy bleeding. Immediate attention required.

---

### Step 2 — TOURNIQUET BLEEDING LIMBS

For any bleeding **limb** (arms, legs), apply a tourniquet first.

**Why tourniquet before bandage:**
Tourniquets are significantly faster to apply than bandages — especially on WCS servers running Realism Overhaul Medical, where bandage application time is 10 seconds self-applied and 15 seconds on a buddy. A tourniquet goes on in a fraction of that time and immediately slows bleeding by more than 50%, buying you critical seconds to address other wounds.

**Key rules:**
- Tourniquets only work on **limbs**. They cannot be applied to the head, chest, or torso.
- They slow bleeding but do not stop it completely. They are a bridge, not a fix.
- They reduce mobility and weapon accuracy while on — remove them once bandaging is complete.
- Tourniquets are **reusable**. You get them back after removal.

Apply tourniquets to all bleeding limbs before moving to bandaging.

---

### Step 3 — BANDAGE HEAD AND TORSO WOUNDS

While tourniquet-controlled limb bleeding is slowing, immediately address any **head or chest wounds** with bandages. These cannot be tourniqueted — bandaging is your only option and it must happen fast because bleeding to these areas is life-threatening and cannot be temporarily controlled.

**Bandage priority order:**
1. Head wounds — highest priority, cannot tourniquet
2. Chest/torso wounds — cannot tourniquet
3. Limb wounds if no tourniquet available

**Key rules:**
- Bandages are **single use** — consumed on application.
- Quick-applying a bandage will automatically target the most severe wound first.
- For specific wound targeting: use the injury menu to select the exact wound location.
- Bandages do not restore blood or health — they only stop bleeding.

---

### Step 4 — BANDAGE TOURNIQUETED LIMBS AND REMOVE TOURNIQUETS

Once head and torso wounds are addressed, go back to the limbs. Bandage each tourniqueted wound, then remove the tourniquet from that limb.

**Why remove tourniquets:**
They degrade the patient's combat effectiveness — reduced sprint speed, reduced weapon stability. A patient who can fight is worth more than a patient who is technically stable but cannot run or aim.

Remove tourniquets as soon as bandaging is complete on that limb, not at the end of treatment.

---

### Step 5 — SALINE FOR BLOOD LOSS

Once all bleeding is stopped, assess blood volume. The visual indicator is screen desaturation — the image loses color as blood volume drops.

Administer a saline bag if:
- The patient has significant color loss on screen
- The patient is unconscious and bleeding has been controlled (low blood volume may be preventing recovery of consciousness)
- The patient has multiple wounds suggesting high cumulative blood loss

**Key rules:**
- Saline restores blood volume, not health — it does not close wounds or speed regeneration
- Do not waste saline on minor injuries with minimal blood loss — it costs supplies and should be prioritized for significant casualties
- One 500ml saline bag is usually sufficient for most field casualties. Severe blood loss may require a second.

---

### Step 6 — MORPHINE TO ACCELERATE HEALING

Once bleeding is controlled and saline is administered, give morphine. Morphine accelerates health regeneration — the wounds begin closing faster and the patient's combat effectiveness recovers. Morphine works through progressive severity stages:

`Serious → Heavy → Moderate → Light → Full recovery`

Administer morphine before epinephrine because it starts the healing process that epi then builds on when waking the patient.

**On WCS with Realism Overhaul Medical:** The morphine cooldown is 120 seconds between doses (versus 25 seconds in vanilla). This is not a spam item. One dose, assess, wait for effect before considering a second.

**When to use:**
- Bleeding is fully controlled
- Patient is stable but injuries are degrading their performance — reduced accuracy, impaired movement, screen effects
- Administer before epinephrine on unconscious patients so healing is already underway when they regain consciousness

**Key rule:** One dose at a time. The 120-second cooldown on WCS means a second dose cannot help for two full minutes anyway. Do not double-dose.

---

### Step 7 — EPINEPHRINE TO WAKE UNCONSCIOUS PATIENTS

After morphine has been administered and bleeding is fully controlled, give epinephrine to any patient who remains unconscious.

**What it does on WCS:** Epinephrine temporarily raises the patient's blood level above the unconscious threshold, allowing them to regain consciousness and return to the fight. It is a short-term bridge — the morphine administered in Step 6 is doing the underlying healing work. The epi gets them on their feet so they can move to cover and continue recovering.

**When to use:**
- Patient is unconscious and bleeding is fully controlled
- Morphine has already been administered
- You need them back in the fight

**When NOT to use:**
- Patient is still actively bleeding — control the bleed first or epi is wasted
- Patient is already conscious

---

## THE COMPLETE TREATMENT SEQUENCE AT A GLANCE

```
1. CHECK INJURIES          — assess all wounds before touching anything
2. TOURNIQUET limbs        — fast, buys time on all bleeding limbs
3. BANDAGE head/chest      — cannot tourniquet, do these first
4. BANDAGE limbs           — bandage tourniqueted limbs, then remove tourniquets
5. SALINE                  — restore blood volume if significant loss
6. EPINEPHRINE             — wake unconscious patient once bleeding is controlled
7. MORPHINE                — accelerate recovery, address pain effects
```

---

## TRIAGE — MULTIPLE CASUALTIES

When multiple players are down simultaneously, you cannot treat everyone at once. Triage is the process of prioritizing who gets treated first.

**Drop your medical bag immediately.** At the start of any MASCAS event, place your medical bag on the ground where your squad can access it. Players can pull supplies directly from the bag — this converts your personal carry into a shared team resource and prevents a situation where your squad goes untreated because all the supplies are locked in one player's inventory.

**Real TC3 triage categories:**
- **Immediate** — will die without treatment in minutes. Severe bleeding, unconscious.
- **Delayed** — can wait. Wounds controlled, conscious, stable.
- **Expectant** — injuries incompatible with survival given available resources.

**WCS application:**

Treat in this order:

**First — anyone with uncontrolled heavy bleeding.** This is the clock. Everything else can wait. A tourniquet on every bleeding limb takes ten seconds and can stabilize multiple casualties rapidly before you treat any of them fully. Run through all casualties applying tourniquets before you begin full treatment on anyone.

**Second — unconscious patients with bleeding controlled.** They need epi and saline to come back.

**Third — conscious, stable patients with light bleeding.** They can wait and may be able to self-treat.

**The triage principle:** Do the most good for the most people in the least time. A fast tourniquet on three casualties is more valuable than a full treatment sequence on one while the other two bleed out.

---

## TRIAGE UNDER FIRE — THE HARD TRUTH

Real TC3 includes a concept that is difficult to accept but essential to understand: during active fire, the medic's job is to fight, not to treat. Treatment happens when the tactical situation permits.

On WCS servers, this means:
- **Do not break cover to treat a casualty during an active firefight.** You will become a second casualty.
- **Do not bunch up around a downed player** — it presents a cluster target and removes guns from the fight.
- **Call for smoke, call for suppression, then move.** Create the conditions for treatment before exposing yourself.

The hardest moment in any firefight is watching a squadmate down and knowing you cannot immediately help them. That restraint is not abandonment — it is the tactical discipline that keeps you alive to treat them.

---

## SELF-TREATMENT

All medical items can be self-applied. The mechanics are the same — equip the item, apply to the injured area.

**Self-treatment priority:**
1. Tourniquet any bleeding limb immediately — you can do this while still in the fight
2. Find cover before attempting bandaging — it takes 10 seconds and you cannot fire during it
3. Saline and morphine can be self-administered in cover or behind a vehicle

**The self-treatment rule:** A medic who goes down because they were treating themselves in the open helps nobody. Get to cover first.

---

## MEDIC LOADOUT — WCS RECOMMENDED

Your loadout serves two purposes: keeping yourself alive long enough to treat others, and carrying enough supplies to handle multiple casualties.

### Weapon
Lightweight carbine. No heavy optics. Your job is not to win gunfights — it is to survive them long enough to reach casualties. Avoid anything that adds unnecessary weight.

### Medical Pack (mandatory)
Carry the largest available medical backpack. Suggested minimum contents:

| Item | Quantity | Role |
|---|---|---|
| Tourniquet | 6–8x | Fast limb bleed control. Reusable but carry extras. |
| Bandage | 8–10x | One per wound. Multiple casualties burn through fast. |
| Saline Bag (500ml) | 4x | Blood volume restoration. |
| Epinephrine Auto-injector | 4–5x | Casualty revival. |
| Morphine Auto-injector | 4–5x | Recovery acceleration. |

### Personal IFAK (always carry regardless of role)
Every player carries a baseline IFAK and medics use the patient's supplies first before drawing from their own pack. Your personal IFAK (confirmed in-game loadout across all WCS roles):

- 5x Bandage
- 3x Tourniquet
- 3x Ammonium Carbonate (Epi substitute — dispensed by medic only in ACE)
- Morphine, Saline, and Epinephrine auto-injectors are **medic-dispensed items** — infantry do not spawn with them

### Smoke Grenades
Carry more smoke than any other role. White smoke is your most important tactical tool as a medic. Minimum 4x white smoke. You will use them.

### Armor
Standard plate carrier is fine. Do not sacrifice armor for weight savings as a medic — you need to survive the movement to the casualty. But avoid the heaviest possible configurations that will limit your sprint speed when closing distance to a downed player.

---

## THE MEDICAL KIT — WHAT IT ACTUALLY DOES ON WCS

The Medical Kit is widely misunderstood. It is a logistics item, not a field healer.

**What it does:**
- Distributes bandages and morphine to nearby players — useful for restocking teammates
- Provides unlimited bandages and tourniquets when placed on the ground
- Enables partial healing of limb injuries, but only when near a **Field Hospital structure or ambulance**

**What it does not do:**
- It cannot fully heal injuries in open field without a medical facility nearby
- Morphine distributed from a Medical Kit requires it to be placed on the ground first

**Practical use:** The Medical Kit is most valuable at or near an established FOB with a Field Hospital built. Out in the field, your individual supplies in your backpack are your primary treatment tools.

---

## SITUATIONAL AWARENESS — THE MEDIC'S CONSTANT TASK

Beyond treatment, the medic maintains a running awareness of the squad's medical status:

- Who is carrying full IFAKs and who is running low?
- Who took hits in the last engagement that they did not report?
- Where is the nearest Field Hospital for full recovery?
- Is there a safe route back to the ambulance if a casualty needs full care?

The medic is the squad's health officer. After every engagement, do a quick check: *"Anyone need a top-off? Check your tourniquets."* Players often do not report minor injuries until they become serious.

---

## PRIORITIZING PATIENTS BY ROLE

When multiple players need treatment and time is limited, consider role priority:

| Priority | Role | Reason |
|---|---|---|
| 1 | Squad Leader | Command and control loss compounds every other loss |
| 2 | Medics | A second medic down removes all treatment capability for the squad |
| 3 | Machine Gunner / Automatic Rifleman | Losing the base of fire degrades every other element's ability to move |
| 4 | Radio Operator / FO | Losing comms cuts off fire support and coordination |
| 5 | Assault elements | Multiple players in this role — one down is painful but manageable |

This is not a rigid rule — a player with catastrophic bleeding gets treated before a squad leader with a scratch. But when injuries are comparable in severity, role priority guides your decision.

---

## TACTICAL COMMUNICATION — WHAT THE MEDIC CALLS

The medic communicates constantly:

| Call | Meaning |
|---|---|
| "Litter, [location]" | Casualty requiring immediate medical attention |
| "Need smoke, [direction]" | Request suppression or smoke to enable movement to casualty |
| "Moving to casualty" | I am exposing myself to treat — cover me |
| "Casualty stable" | Patient is treated and conscious — back in the fight |
| "Need evac, [location]" | Casualty requires transport to Field Hospital for full recovery |
| "Low on supplies" | Medic pack is running low — need resupply or return to FOB |
| "Check your IFAKs" | Post-engagement reminder for all players to assess their kit |

---

## DOCTRINE SUMMARY — TC3 TO WCS

Real TC3/TCCC follows the MARCH algorithm: Massive hemorrhage, Airway, Respiration, Circulation, Hypothermia. In WCS, the game simulates the most critical elements:

| TC3 Element | WCS Equivalent |
|---|---|
| Massive Hemorrhage Control | Tourniquet limbs, bandage head/chest — stop the bleed first |
| Airway | Not simulated in WCS vanilla medical |
| Respiration | Not simulated in WCS vanilla medical |
| Circulation | Saline to restore blood volume |
| Hypothermia / Head injury | Not simulated in WCS vanilla medical |

The game captures the most lethal battlefield injury mechanism — hemorrhage — with enough fidelity that real TC3 training translates directly. The priority sequence is the same. The tools are simplified but the logic is identical.

*If you have TC3 training, trust that training. The game rewards the same discipline.*

---

## QUICK REFERENCE — TREATMENT SEQUENCE

```
CARE UNDER FIRE:
  Return fire. Achieve fire superiority.
  Pop smoke for concealment.
  Move to casualty.

TACTICAL FIELD CARE:
  1. Check Injuries
  2. Tourniquet — all bleeding limbs (fast)
  3. Bandage — head and chest first (cannot tourniquet)
  4. Bandage — limbs, then remove tourniquets
  5. Saline — if significant blood loss or desaturated screen
  6. Morphine — accelerate healing before waking the patient
  7. Epinephrine — wake unconscious patient after morphine administered

MULTIPLE CASUALTIES:
  Tourniquet everyone first. Then treat in order: heaviest bleed,
  unconscious stable, conscious stable.

TRIAGE RULE:
  Most good for the most people in the least time.
```

---

*Doctrine basis: US Army TC3 / TCCC (Tactical Combat Casualty Care)*
*Game system: Arma Reforger vanilla medical + Realism Overhaul Medical (WCS mod stack)*
*"A dead medic treats nobody. Fire superiority first." — TC3 Care Under Fire principle*

---

## WCS MILSIM — ADVANCED MEDICAL PROTOCOLS

*From the WCS Medical Handbook. These procedures apply on WCS servers with the full medical mod stack.*

### Medical Net — 49.0 MHz

All medical coordination goes on **49.0 MHz**. Medics monitor this net alongside their squad net.

- **ANGEL** — MEDEVAC helicopter callsign (UH-60 MEDEVAC). Use when requesting rotary wing casualty extraction.
- **Angel Flight** convention: request via 9-Line on 49.0 MHz

### Blood Loss Classification

Use this table to gauge severity and prioritize treatment:

| Class | Blood Loss | Signs | WCS Equivalent |
|---|---|---|---|
| **I** | < 750 mL | Normal vitals, mild pallor | Screen tint barely noticeable |
| **II** | 750–1,500 mL | Anxious, increased HR | Desaturation visible on screen edges |
| **III** | 1,500–2,000 mL | Confused, hypotension | Strong screen desaturation, unsteady |
| **IV** | > 2,000 mL | Unconscious / near death | Patient down — requires immediate saline + epi |

Class III–IV require **immediate saline administration** before epinephrine.

### MIST Report — Casualty Handoff Format

When handing off a casualty to another medic, the field hospital, or calling for MEDEVAC, report in MIST format:

| Element | Meaning | Example |
|---|---|---|
| **M** | Mechanism of injury | "Small arms, gunshot wound right leg" |
| **I** | Injuries observed | "Two GSW lower limb, one chest wound" |
| **S** | Signs / Symptoms | "Heavy blood loss, unconscious" |
| **T** | Treatment given | "Two TQs applied, one bandage, one saline" |

*"Litter [name]: Mechanism — small arms chest wound. Injuries — one thoracic GSW. Signs — unconscious, severe blood loss. Treatment — bandaged, one saline administered."*

### 9-Line MEDEVAC Request (Medical Version)

Call on **49.0 MHz** to Angel (MEDEVAC pilot):

| Line | Element | Example |
|---|---|---|
| 1 | Location of pickup site | "Grid 04527-12345" |
| 2 | Radio frequency and callsign | "49.0, Bravo Four Six" |
| 3 | Number of patients by precedence | "1 Urgent, 2 Priority" |
| 4 | Special equipment required | "None" |
| 5 | Number of patients by type | "2 Litter, 1 Ambulatory" |
| 6 | Security at pickup site | "Secure" / "Enemy fire" |
| 7 | Method of marking LZ | "Smoke" / "IR strobe" |
| 8 | Nationality and status | "Military, US" |
| 9 | NBC contamination | "None" |

### MASCAS Triage Categories

Used for mass casualty events (3+ patients):

| Color | Category | Action |
|---|---|---|
| **Red** | Immediate | Life-threatening — treat now |
| **Yellow** | Delayed | Serious but stable — can wait |
| **Green** | Minimal | Walking wounded — self-treat |
| **Black** | Expectant | Unsurvivable given available resources |

**Fast sweep procedure for MASCAS:** Run through all casualties applying tourniquets (Red first). Then circle back for full treatment in Red → Yellow → Green order.

### CCP and Field Hospital Setup

**Casualty Collection Point (CCP):** A rally point near the objective where casualties are moved once bleeding is controlled. Ideally:
- Covered from direct fire (building, reverse slope)
- Marked with **white smoke** for identification
- Guarded by one rifleman minimum while medic works

**Field Hospital:** A permanent structure built at the FOB. Required for full injury recovery when Morphine alone is insufficient. Medics should know the grid of the nearest Field Hospital before every mission.

Tier of care:
1. **Self-aid / buddy aid** — field (tourniquet + bandage)
2. **CCP** — medic stabilizes (full treatment sequence)
3. **Field Hospital** — full recovery, resupply
4. **MEDEVAC** — helicopter extraction to field hospital for casualties unable to walk

---

## See Also

- [MEDEVAC SOP](../03_tactical_sop/medevac_sop.md) — 9-line request format, CCP procedures, LZ marking, CASEVAC vs MEDEVAC
- [React to Contact SOP](../03_tactical_sop/react_to_contact.md) — casualty handling during active contact, CCP under fire
- [Quick Reference Card](../00_start_here/quick_reference_card.md) — MEDEVAC sequence, pre-spawn IFAK checklist
- [Tactical Fundamentals](../01_foundations/tactical_fundamentals.md) — react to contact, smoke for concealment, fire superiority first
- [Movement & Formations SOP](../03_tactical_sop/movement_and_formations.md) — squad positioning and casualty collection
- [WCS Complete Onboarding Guide](../01_foundations/wcs_complete_onboarding_guide.md) — full medical system context and medic loadout
