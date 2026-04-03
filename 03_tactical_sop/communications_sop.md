# COMMUNICATIONS SOP
## WCS Radio Procedures, Callsigns, and Net Structure

> **Source:** WCS MILSIM Communications Knowledge Packet
> **Application:** All WCS Milsim operations — Arma Reforger
> **Purpose:** Establish standardized communications procedures ensuring effective coordination, clear command and control, and proper use of radio channels during operations.

---

## 1. RADIO FREQUENCY ASSIGNMENTS

All personnel monitor and transmit **only** on their designated channels unless directed otherwise. Radio discipline is maintained at all times.

### 1.1 Platoon & Command Nets

| Frequency | Net | Managed By |
|---|---|---|
| **50.0 MHz** | Platoon Net | Squad Leaders → 1-6 |
| **50.1 MHz** | Platoon Leadership Net | 1-6, 1-7, 1-8, 1-9 |
| **50.2 MHz** | Logistics & Intelligence Net | 1-7 (Hermes) |
| **50.3 MHz** | Squad Coordination Net | Cross-squad deconfliction |

### 1.2 Medical Net

| Frequency | Net | Users |
|---|---|---|
| **49.0 MHz** | Medical Net | Squad Medics, Combat Medics, 1-9 |

> **CLS Radio Rule:** CLS radios remain **OFF** except when calling MASCAS. Only SMs and above monitor 49.0 actively.

### 1.3 Aviation Nets

| Frequency | Net | Users |
|---|---|---|
| **51.0 MHz** | JTAC / Main Aviation Net | JTAC (1-8), all aircraft check-in |
| **51.1 MHz** | AO 1 Operations | Dealer 1 |
| **51.2 MHz** | AO 2 Operations | Dealer 2 |

### 1.4 Mortar, FO, and Recon Net

| Frequency | Net | Users |
|---|---|---|
| **52.0 MHz** | Hammer / Hawkeye / Hitman | Mortars, FO, SNOT/Recon |

### 1.5 Squad-Level Nets (Short Range)

| Callsign | Primary Frequency | Fire Team Range |
|---|---|---|
| **1-1** | 41.0 MHz | Fire teams: 41.1–41.9 |
| **1-2** | 42.0 MHz | Fire teams: 42.1–42.9 |
| **1-3** | 43.0 MHz | Fire teams: 43.1–43.9 |
| **1-4 (Weapons)** | 44.0 MHz | Fire teams: 44.1–44.9 |

### Complete Frequency Reference

```
41.0 – Squad 1       |  50.0 – Platoon Net
42.0 – Squad 2       |  50.1 – Leadership Net
43.0 – Squad 3       |  50.2 – Logistics/Intel
44.0 – Weapons Sq    |  50.3 – Squad Coordination
                     |  
49.0 – Medical       |  51.0 – JTAC/Aviation
                     |  51.1 – AO 1 Ops
52.0 – Mortars/FO/   |  51.2 – AO 2 Ops
       Recon (SNOT)  |
```

---

## 2. CALLSIGN REFERENCE

### Ground Elements

| Callsign | Role | Notes |
|---|---|---|
| **1-1 / 1-2 / 1-3** | Line Squads | First "1" = platoon; second # = squad |
| **1-4** | Weapons Squad | M240B, HAT, WPN team |
| **1-5** | AT/AA Squad | Attaches to 1-4 |
| **1-6** | Platoon Leader | Commands all platoon assets |
| **1-6R** | RTO | Relays for 1-6; transmissions treated as 1-6 direct |
| **1-7** | Platoon Sergeant | Assumes command if 1-6 is down |
| **1-8** | JTAC/CCT (Dealer) | Manages airspace; deconflicts aviation and mortars |
| **1-9** | Platoon Medic | Directs all medical operations |
| **Hammer** | Mortar Section | 100–200m behind 1-4; executes fire missions |
| **Hermes** | Logistics | Transport, resupply, reinsertion |
| **Tempest** | Armor | Bradleys/Abrams; numbered suffix (Tempest 1, 2...) |

> **Dead Leader Procedure:** If 1-6 is down, all SLs shift to **50.0 MHz** and contact 1-7. If 1-6R is also down, 1-7 assumes command.

### Aviation Callsigns

| Callsign | Aircraft | Role |
|---|---|---|
| **Gambler** | UH-60 Blackhawk | Troop transport |
| **Angel** | UH-60 Blackhawk | MEDEVAC (dedicated) |
| **Heavy** | UH-60 Blackhawk | Armed escort |
| **Nimble** | MH-6 Littlebird | Light/precision transport |
| **Hummingbird** | AH-6 Littlebird | Armed CAS |
| **Ghost** | AH-6 Littlebird | Recon (no ordnance) |
| **Bertha** | CH-47 Chinook | Heavy lift / mass transport |
| **Trident / Warden** | AH-64 Apache | Heavy attack |
| **Guardian** | AH-1 Cobra | Attack |

> Multiple aircraft of same type add a number: **Gambler 1**, **Gambler 2**, etc.

---

## 3. RADIO USAGE GUIDELINES

- **Brevity and Clarity** — Keep transmissions short, clear, and professional
- **Call Signs** — Always identify who you are calling AND who you are
- **Acknowledgement** — Always acknowledge transmissions
- **Priority of Traffic** — Critical traffic takes precedence; stand by
- **Cross-Talk Control** — Use **50.3** for squad-to-squad coordination, never 50.0

---

## 4. TRANSMISSION STRUCTURE

Every transmission follows a standard three-part structure.

### 4.1 Call-Up (Opening)

Identify who you are calling, then yourself.

**Format:** `"[Recipient], this is [Sender]"`

**Example:** `"1-6, this is 1-1…"`

### 4.2 Message / Body

Deliver the main content. Use preformatted reports, brevity codes, or specific information.

**Example:** `"1-6, 1-1. Contact bearing 270, 200 meters, fireteam-sized element. 1-1 is maneuvering."`

### 4.3 Closing (End of Transmission)

Indicate whether a response is required.

| Pro-Word | Meaning |
|---|---|
| **Over** | Response expected |
| **Out** | No response required |

> **Rule:** Do not use "Out" to higher command. **Never** use "Over and Out" together — that is a Hollywood myth.

---

## 5. STRUCTURED RADIO REPORTS

### 5.1 Contact Report — SALUTE

When reporting enemy contact, transmit in full SALUTE format:

| Letter | Element | Description |
|---|---|---|
| **S** | Size | Approximate enemy strength |
| **A** | Activity | What the enemy is doing |
| **L** | Location | Grid, landmark, or relative position |
| **U** | Unit/Uniform | Identification marks, vehicles, weapon systems |
| **T** | Time | When contact occurred |
| **E** | Equipment | Weapons, vehicles, notable gear |

**Example:**
```
"1-6, this is 1-2, SALUTE report.
 Size: 2x fireteams.
 Activity: moving north along MSR.
 Location: Grid 042 068.
 Uniform: hostile infantry with light machine guns.
 Time: observed now.
 Equipment: 1x UAZ transport. Over."
```

### 5.2 Situation Report — SITREP

Transmitted at regular intervals or when requested by higher.

| Field | Content |
|---|---|
| **Position** | Current squad location or objective progress |
| **Enemy** | Known enemy locations, activity, or strength |
| **Friendly** | Adjacent friendly units, coordination points |
| **Logistics** | Ammo, equipment, or supply status |
| **Casualties** | WIA/KIA status |
| **Mission** | Current tasking or next steps |

**Example:**
```
"1-6, this is 1-1, SITREP.
 Position: Holding checkpoint Bravo.
 Enemy: No contact in last 15 minutes.
 Friendly: 1-2 moving to our east.
 Logistics: 75% ammo, green on supplies.
 Casualties: 1x WIA treated.
 Mission: Continuing to secure sector. Over."
```

### 5.3 Well-Being Report — ACE

Tracks unit operational status. Each category uses a **color code**:

| Code | Meaning |
|---|---|
| **Green** | Good to fight / No injuries |
| **Amber / Yellow** | Half load / Injured troops |
| **Red** | Combat ineffective / Non-ambulatory |
| **Black** | Empty / KIA |

| Letter | Element | Color Codes Apply To |
|---|---|---|
| **A** | Ammunition | Rounds remaining |
| **C** | Casualties | Personnel status |
| **E** | Equipment | Key special equipment (AT, demo, etc.) |

**Example:**
```
"1-6, this is 1-3, ACE report.
 Ammo: Red.
 Casualties: Yellow.
 Equipment: Green. Over."
```

---

## 6. CHAIN OF COMMUNICATION

```
┌─────────────────────────────────────────┐
│                50.0 MHz                  │
│          PLATOON NET (SQ → 1-6)         │
│  SLs report up; 1-6 issues orders down  │
└─────────────────────────────────────────┘
          │
    ┌─────┴─────┐
    │ 50.1 MHz  │  Leadership (1-6, 1-7, 1-8, 1-9)
    └───────────┘
    │ 50.2 MHz  │  Logistics/Intel (Hermes, 1-7)
    └───────────┘
    │ 50.3 MHz  │  Squad-to-squad coordination
    └───────────┘

49.0 – All medical traffic (SM ↔ CM ↔ 1-9)
51.0 – JTAC and aviation only
52.0 – Mortars, FO, Recon (SNOT/Hitman net)
```

**MASCAS (Mass Casualty Situation):**
- Squads report to SL over squad net → SL transmits to 1-6 over 50.0
- 1-6 calls medical over 50.0; Squad Medic switches to 49.0
- Platoon Medic 1-9 coordinates triage and MEDEVAC over 49.0

---

## 7. GOOD RADIO PRACTICES

| Do | Why |
|---|---|
| **Think before you speak** | Formulate in your head first; key mic only when ready |
| **Pause 1 second after keying** | Prevents cutting off the first word |
| **Use brevity codes** | Saves time; reduces confusion |
| **Name recipient first** | "1-6, this is 1-2" — not "1-2 to 1-6" |
| **Stay calm under stress** | Steady pace is clearer than fast panic |
| **Acknowledge quickly** | "Roger", "Good copy", or readback when needed |
| **Monitor your net** | Keep volume audible; don't miss transmissions |
| **Break × 3 for emergency** | "Break, Break, Break" interrupts for urgent traffic |

---

## 8. RADIO HABITS TO AVOID

| Avoid | Why |
|---|---|
| **Hot mic** | Accidentally transmitting open comms clutters the net |
| **Over-talking** | Wait for others to finish before transmitting |
| **Clogging 50.0** | Command net is not for squad chatter |
| **Doubling** | Listen before transmitting; two simultaneous transmissions = garbled |
| **Slang / mumbling** | Use standardized terms; speak clearly |
| **"Over and Out"** | Contradictory — use one or the other |
| **"Repeat"** | In fire missions, "Repeat" means fire again — say "Say Again" instead |

---

## 9. PRO-WORD GLOSSARY

| Pro-Word | Meaning |
|---|---|
| **All Stations** | Broadcast to all units on the net |
| **Be Advised** | Important information follows |
| **Break** | Pause within a message for others to speak |
| **Break × 3** | Emergency interruption — urgent priority |
| **Broken Arrow** | Unit being overrun — all assets respond immediately |
| **Check Fire** | Stop firing — potential friendly fire |
| **Correction** | Amend error in current/previous transmission |
| **Disregard** | Ignore previous transmission |
| **Good Copy** | Received and understood |
| **I Say Again** | Repeating previous message (importance or clarity) |
| **Interrogative** | Question follows |
| **Lima Charlie** | "Loud and Clear" — good signal |
| **Nothing Heard** | No response received |
| **Oscar Mike** | On the move / en route |
| **Over** | End of transmission; response expected |
| **Roger** | Last transmission received satisfactorily |
| **Say Again** | Repeat last transmission (**never use "Repeat"**) |
| **Silence** | Cease all radio traffic on net — emergency |
| **Silence Lifted** | Radio traffic may resume |
| **Tango Uniform (TU)** | Target destroyed / dead / non-functional |
| **Wait One** | Stand by; sender needs a moment |
| **WILCO** | Will comply — received, understood, will act |

---

## 10. NATO PHONETIC ALPHABET

| Letter | Code | Letter | Code |
|---|---|---|---|
| A | **Alpha** | N | **November** |
| B | **Bravo** | O | **Oscar** |
| C | **Charlie** | P | **Papa** |
| D | **Delta** | Q | **Quebec** |
| E | **Echo** | R | **Romeo** |
| F | **Foxtrot** | S | **Sierra** |
| G | **Golf** | T | **Tango** |
| H | **Hotel** | U | **Uniform** |
| I | **India** | V | **Victor** |
| J | **Juliet** | W | **Whiskey** |
| K | **Kilo** | X | **X-ray** |
| L | **Lima** | Y | **Yankee** |
| M | **Mike** | Z | **Zulu** |

> Example: "B-17" → "**Bravo One Seven**" — eliminates misidentification in poor audio.

---

## 11. KEY ABBREVIATIONS REFERENCE

| Abbreviation | Meaning |
|---|---|
| AA | Assembly Area / Anti-Aircraft |
| AO | Area of Operations |
| BP | Blocking Point (or Battle Position for aircraft) |
| CAS | Close Air Support |
| CCP | Casualty Collection Point |
| CP | Checkpoint |
| DP | Defense Point |
| ETA | Estimated Time of Arrival |
| FOB | Forward Operating Base |
| FRAGO | Fragmentary Order (change to existing order) |
| HVT | High-Value Target |
| LOA | Limit of Advance |
| LZ | Landing Zone |
| MEDEVAC | Medical Evacuation |
| MSR | Main Supply Route |
| NAI | Named Area of Interest |
| OBJ | Objective |
| ORBAT | Order of Battle |
| PID | Positive Identification |
| QRF | Quick Reaction Force |
| ROE | Rules of Engagement |
| RP | Rally Point |
| RTB | Return To Base |
| SITREP | Situation Report |
| VDO | Vehicle Drop Off |
| WARNO | Warning Order |

---

## See Also

- [Quick Reference Card](../00_start_here/quick_reference_card.md) — freq table and callsign quick reference
- [Call for Fire SOP](../03_tactical_sop/call_for_fire_sop.md) — fire mission radio procedures
- [MEDEVAC SOP](../03_tactical_sop/medevac_sop.md) — 9-line format and medical net procedures
- [React to Contact SOP](../03_tactical_sop/react_to_contact.md) — contact report drills
