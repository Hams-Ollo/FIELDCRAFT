# ZEN SOLUTIONS — BLUE FALCON FIST & RECON SOP
## Fire Support and Long Range Reconnaissance — WCS Server Edition

> **Classification:** Community SOP | Zen Solutions | discord.armawcs.com
> **Unit:** Blue Falcon — Forward Observer / Indirect Fire Support Team
> **Area of Operations:** WCS NA Servers — Chernarus, New Everon, Glenwood, Serhiivka, Rostov, Rahhaliyah
> **Game Version:** Arma Reforger 1.6.x | WCS Mod Stack

---

## TABLE OF CONTENTS

1. [Unit Mission and Purpose](#1-unit-mission-and-purpose)
2. [Understanding the Radio Spawn System](#2-understanding-the-radio-spawn-system)
3. [Establishing the Combat Outpost — Two Methods](#3-establishing-the-combat-outpost--two-methods)
4. [Pucker Point COP — Standard Build Order](#4-pucker-point-cop--standard-build-order)
5. [Long Range Reconnaissance Patrol (LRRP)](#5-long-range-reconnaissance-patrol-lrrp)
6. [Sniper / Spotter Pair Doctrine](#6-sniper--spotter-pair-doctrine)
7. [Call for Fire — FIST Procedures](#7-call-for-fire--fist-procedures)
8. [Bradley QRF Screen — COP Defense](#8-bradley-qrf-screen--cop-defense)
9. [Seeding Phase SOP](#9-seeding-phase-sop)
10. [Quick Reference](#10-quick-reference)

---

## 1. Unit Mission and Purpose

Blue Falcon is Zen Solutions' dedicated Fire Support and Long Range Reconnaissance element operating on WCS Realism servers. The unit's mission is threefold:

**Observe.** Establish concealed observation posts that give the team persistent eyes on enemy primary objectives, supply routes, and FOB construction activity — information the broader team cannot otherwise access.

**Report.** Feed accurate grid coordinates, target descriptions, and movement intelligence to Squad Leaders and mortar teams in real time over the platoon radio net. A fire mission called on accurate intelligence is worth more than a squad-level assault.

**Destroy.** Execute precision indirect fire missions from a concealed Combat Outpost, degrading enemy logistics, disrupting FOB construction, and neutralizing high-value targets before the main assault reaches the objective.

This is not a glamour role. Blue Falcon wins matches quietly, from treelines and hilltops, long before most players realize the battle has been decided.

---

## 2. Understanding the Radio Spawn System

This is one of the most underutilized mechanics in Arma Reforger and the foundation of Blue Falcon's entire operational capability.

### How Radio Packs Work

When a server starts, each default squad type — Assault, Recon, Transport, Engineer, Anti-Tank — has a **radio backpack** available as an equipment option. A player takes the radio pack in place of their standard backpack and carries it into the field.

Once placed on the ground and **deployed** (this is a deliberate action — drop the pack, then interact with it to deploy; simply dropping it is not enough), the radio pack functions as a **squad-only spawn point**. Members of that squad can see it on the map and respawn on it.

> **Critical:** Only players in the same squad can see and spawn on a deployed radio pack. It does not appear for the broader team. If you reconnect to a server and your radio pack disappears from the map, you may have been placed in a different squad on reconnect — rejoin the original squad to reacquire it.

### Radio Pack Supply Pool

A deployed radio pack starts with **100 supplies**. Each respawn draws from that pool based on the cost of the loadout the respawning player selects. When the supply pool reaches zero, players can no longer spawn on it.

### The Zero-Cost Loadout Rule

If a player saves a loadout at **zero supply cost** at any arsenal before deploying, they can respawn on the radio pack at no supply cost per spawn. When the entire squad uses a zero-cost saved loadout, the radio pack's supply pool is never drawn down — making it an **indefinite forward spawn point** for as long as it remains deployed and undiscovered.

> **Action required:** Before every deployment, save a functional zero-cost loadout at the base arsenal. This is your contingency respawn kit. It does not need to be your full combat loadout — it just needs to exist so you have a zero-cost option available at the radio pack spawn screen.

### Server Limits on Radio Packs

By default, only **two radio packs can be active simultaneously** per server. WCS servers may modify this limit. Be aware that if two packs are already deployed on your team, placing a third may not function as a spawn point until one of the others is recovered.

### Deployed vs. Carried Radio Pack

There are two states for a radio pack:

| State | Spawn function | Map visibility |
|---|---|---|
| **Carried on back** | Squad members can spawn on the player carrying it (server-setting dependent) | Player position shown to squad |
| **Deployed on ground** | Fixed spawn point at the placed location | Pack location shown to squad only |

For Blue Falcon's forward OP strategy, **deploy on the ground** at a concealed position. This creates a fixed spawn anchor that persists after you move or die.

---

## 3. Establishing the Combat Outpost — Two Methods

### Method A: MCU-Based COP (Preferred — Full Build)

Drive a **Mobile Command Unit (MCU) truck** to the designated COP location. Park and conceal in dense treeline. The MCU performs two functions: it extends NATO radio coverage into the area, and it provides a **team-wide spawn point** visible on the map to all friendly players.

> **Known issue as of v1.6.x:** There is an active bug where MCUs deploy with 0/0 supplies, which can prevent spawning and reduce the MCU to radio extension only. If your MCU is not functioning as a spawn point, manually resupply it using a logistics truck. Check the WCS Discord for the current status of this bug before each session.

The MCU truck **does grant build access** when it has supplies loaded in it — you do not need a separate construction truck. Load the MCU with supplies before driving out and you can build mortar pits, an armory, vehicle depots, and fortifications directly from the MCU. Bringing a separate logistics truck to resupply the MCU mid-build will extend how much you can construct before running dry.

**When to use:** Mid-match once you have reached Sergeant rank and have sufficient supplies staged. This becomes the team's primary forward spawn for the remainder of the match. Because it is visible to all team members on the map, it draws more traffic — and more enemy attention — than a radio pack OP.

### Method B: Construction Truck + Radio Pack (Light COP)

Drive a **construction truck** loaded with supplies to the COP location. A squad member deploys their **radio pack** nearby in concealment. Like the MCU, the construction truck provides full build access for mortar pits, an armory, vehicle depots, and fortifications as long as it has supplies loaded. The radio pack provides the squad spawn point.

**Key differences from Method A:**

- The radio pack spawn is **squad-visible only** — the broader team cannot spawn there, keeping the COP location off the team-wide map
- No MCU means **no radio coverage extension** from this method — factor this into your positioning relative to the existing radio network
- Lower profile and harder for the enemy to locate, but limits who can benefit from the position
- The construction truck is not a spawn point on its own — the radio pack is doing that work here

**When to use:** Early in the match before sufficient rank or supplies are available for the MCU method, or when you deliberately want a clandestine forward position that does not appear on the team map.

---

## 4. Pucker Point COP — Standard Build Order

**Reference position:** Grid 085 040, Chernarus — treeline north of Prigorodki road, between Pusta and the Chernihiv-Elektrozavodsk axis. Provides mortar coverage of all four primary objectives.

> **Rank requirement:** Sergeant rank is required to build Living Quarters (AI tent / defensive AI). Rush Sergeant early via supply runs and objective capping — 3 to 4 full supply runs typically reaches Sergeant on WCS servers. Living Quarters also **halve the supply cost per respawn**, which directly extends the life of your forward supply pool.

Build in this order. Each phase enables the next.

### Phase 1: Establish the Anchor

| Step | Action | Why |
|---|---|---|
| 1 | Park MCU deep in treeline, engine off | Concealment is the COP's primary defense. Engine noise carries. |
| 2 | Deploy radio pack at a secondary concealed position | Backup spawn if MCU is destroyed or bugged |
| 3 | Confirm radio coverage reaches COP location | If not, radio relay station goes up before anything else |

### Phase 2: Logistics Infrastructure

| Step | Action | Why |
|---|---|---|
| 4 | Build Armory — tucked into woods | Full loadout access. Helos and trucks can land supplies directly to it. Place inside camo netting. |
| 5 | Build Heavy Vehicle Depot | If MCU is destroyed, team can redeploy another. Enables Bradley and heavier vehicles. |
| 6 | Build Light Vehicle Depot | Scout and patrol vehicles, light transport for LRRP teams |
| 7 | Build Living Quarters (requires Sergeant) | Spawns defensive AI. Halves respawn supply cost across all spawns at this position. |

### Phase 3: Fire Support

| Step | Action | Why |
|---|---|---|
| 8 | Build 4–5 mortar pits — clustered near Armory | Close to supply source. Multiple pits enable multiple simultaneous fire missions. |
| 9 | Pre-register all TRPs using mortar calculator | Fire missions execute in seconds, not minutes |
| 10 | Stock mortar pits with HE shells (M853A1) | M252 primary platform. Ring 3 standard area; Ring 0–2 for precision point targets |

### Phase 4: Perimeter Defense

| Step | Action | Why |
|---|---|---|
| 11 | Build MG nests covering all road and terrain approaches | 360-degree coverage — no dead angle on any approach |
| 12 | Build bunkers on dominant terrain features around perimeter | Hard cover for defenders during QRF response |
| 13 | Build anti-aircraft emplacement | Helicopter reconnaissance and attack runs are the primary COP threat |
| 14 | Place camo netting over all structures and vehicles | Reduces visual signature from air and distant ground observation. Arsenals inside camo netting are significantly harder to locate and target. |

### Design Philosophy

Everything at Pucker Point is oriented around **cover and concealment**. The COP should look, from the outside, like a patch of woods. From the inside, it should function as a fully equipped fire support base.

Build tight. Keep the footprint small. Spread structures through natural concealment rather than open field layouts. If it looks like a base from the road, it will be found and destroyed. If it disappears into the terrain, it operates all match.

This reflects the same principles used to establish patrol bases in real operations — minimize signature, maximize capability.

---

## 5. Long Range Reconnaissance Patrol (LRRP)

The LRRP is Blue Falcon's primary intelligence-gathering operation. From Pucker Point, recon elements push out on foot or via light vehicle to establish forward observation posts overlooking primary enemy objectives.

### Standard LRRP Composition

Two to four personnel:

| Role | Kit | Function |
|---|---|---|
| Lead Scout / FO | Light chest rig, suppressed carbine, LRF, long-range radio backpack | Navigation, target acquisition, call for fire |
| Sniper | Suppressed DMR (M110 / SVD), high-power variable optic (6–24x) | Precision engagement if compromised; target confirmation |
| Spotter | Standard assault rifle, LRF | Assists sniper, secondary observation, security |
| Radio Op (optional) | Radio pack, zero-cost loadout saved | Deploys radio pack at OP for persistent squad spawn anchor |

> **Radio note:** The long-range radio backpack (AN/PRC-77 for NATO, R-148 equivalent for Russian kit in WCS) operates on a separate frequency band from the short-range squad radio. Range is approximately 40km. Ensure the FO and mortar team are on the same long-range frequency before departure. Short-range radios transmit at 2km range — insufficient for COP-to-OP communication across Chernarus.

### LRRP Movement Doctrine

- Move at night or dawn whenever possible. NVGs and IR lasers mandatory on all LRRP elements.
- Stay off roads entirely. Move through treelines, drainage features, and dead ground.
- Maintain 10–15 meter spacing between personnel.
- **No shooting unless the patrol is about to be wiped.** Gunshots compromise the OP location. The patrol goes dark before it goes loud.
- If a patrol member goes down, do not call for help on squad net unless the position is secure. Move to an alternate position and reassess.
- If fully compromised, call "OP compromised — extracting" on platoon net so mortar crews cease fire in your direction.

### Establishing the Forward OP

Select a position with:
- Observation over the target (enemy base, supply route, FOB construction zone)
- Concealment from the target (treeline, reverse slope, dense brush)
- Multiple egress routes if compromised
- Radio line-of-sight back to Pucker Point or through a relay node

Once the position is confirmed secure:
- Deploy radio pack in the most concealed position available
- Sniper and spotter set up in depth — spotter slightly elevated and offset from sniper, not collocated
- FO confirms LRF ranges to pre-identified reference points and calls TRP confirmations back to mortar crews

### Radio Pack OP — The Persistent Forward Spawn

A deployed radio pack at the forward OP means Blue Falcon members can respawn directly into the observation position after death — bypassing the entire movement from Pucker Point. With zero-cost loadouts saved, this spawn point persists as long as the pack remains deployed and undiscovered.

This is the difference between a one-time patrol and a persistent intelligence asset that survives individual deaths.

---

## 6. Sniper / Spotter Pair Doctrine

The sniper/spotter pair is the precision element of Blue Falcon. Their primary function is intelligence and fire mission support — not body count.

### Roles

**Spotter:**
- Identifies targets first using LRF and optics
- Calls ranges and target description to sniper
- Monitors for movement while sniper is on glass
- Maintains radio contact with Pucker Point mortar crews
- Provides security for the sniper's position

**Sniper:**
- Engages only on the spotter's call or if the patrol is about to be compromised
- Primary function is observation, not engagement
- When engaging: prioritizes enemy FOs, radio operators, logistics truck drivers
- Confirms mortar fire mission impacts and calls adjustments in coordination with spotter

### Engagement Criteria

Only engage when:
1. The patrol is about to be discovered and engagement is the only survivable option
2. A high-value target presents that cannot be addressed by indirect fire (moving MCU, enemy mortar crew)
3. The spotter confirms engagement will not compromise the OP before an active fire mission is complete

Shooting compromises the OP. A compromised OP stops the fire mission. A stopped fire mission lets the enemy rebuild. **The radio is always the more powerful weapon.**

### Fire Mission Spotting from the OP

When mortar rounds are inbound, the spotter observes impact and calls corrections:

- **Add / Drop [Xm]:** Move rounds further from / closer to the OP
- **Left / Right [Xm]:** Shift rounds laterally
- **On target — fire for effect:** Rounds landing accurately, continue
- **End of mission / Target destroyed:** Mission complete, cease fire

The sniper confirms effect independently and cross-checks with the spotter before calling end of mission.

---

## 7. Call for Fire — FIST Procedures

### Standard CFF Format — Blue Falcon to Mortar Crew

```
Step 1: "Mortar, Blue Falcon — Fire Mission, over."
        [Wait for acknowledgment before continuing]

Step 2: "Grid [6 or 8 digit grid]."
        [Or: "TRP [target name]" if pre-registered]

Step 3: "[Enemy description] at [location detail]."
        Example: "Enemy FOB under construction, two trucks,
        squad of infantry digging in."

Step 4: "HE — [N] rounds — Ring [X] — fire for effect."

Step 5: Observe impact. Call adjustment:
        "Add 50, Left 20."  (50m further out, 20m left)
        "On target — fire for effect."  (rounds landing correctly)

Step 6: "Target destroyed. End of mission."
        [Or: "Shift — TRP [next target name]."]
```

### Danger Close Protocol

If friendly elements are within **100 meters** of the target, the FO announces before calling fire:

**"DANGER CLOSE — friendly troops within 100 meters."**

This alerts the mortar crew to use lower ring settings and single rounds to confirm before effect, and alerts nearby friendly infantry to go prone and seek hard cover immediately.

### Mortar Ring Guide — M252 / M853A1 HE

| Ring | Dispersion | Best Use |
|---|---|---|
| 0 | Tightest | Single point target — MCU truck, command position |
| 1 | Tight | Small area target — mortar pit, trench |
| 2 | Medium | FOB construction zone, supply depot |
| 3 | Standard (~32m radius) | Main base area, troop concentration |
| 4 | Wide | Large area suppression, road interdiction |

### Pre-Registered TRPs — Chernarus / Pucker Point

Calculated from Grid 085 040 using M252, M853A1 HE shells via arma-mortar.com (Chernorus Minus map).

| Target | Location | Elevation (mils) | Direction (mils) | Rings | Notes |
|---|---|---|---|---|---|
| Mogilevka — Main | Grid 063 043 | 1025 | 5703 | 2 | Phoenix objective |
| Chernogorsk — Main | Grid 055 030 | 1150 | 4039 | 4 | Alabama objective |
| Elektrozavodsk — Main | Grid 075 030 | 1074 | 2325 | 4 | Dayton objective |
| Staroye — Main | Grid 083 047 | 987 | 853 | 3 | Utah / Sunburst objective |

> **Elevation note:** Chernarus has significant terrain relief. Always verify the elevation delta in the mortar calculator when targets sit on ridgelines versus valley floors — the elevation correction column matters and varies by target height relative to Pucker Point.

> **MCU targeting:** When registered TRPs cover a main base area, also identify the MCU spawn point offset (typically 50–100m from the command tent). Destroying an enemy MCU removes the team's forward spawn anchor and can be a match-deciding single round.

---

## 8. Bradley QRF Screen — COP Defense

Once Pucker Point is fully operational and supplies are sufficient, spawn an **M3A3 Bradley** from the heavy vehicle depot and position it in a **hide site** 200–400 meters from the COP perimeter on the most likely enemy approach route.

### Bradley Hide Site Selection

- Off the main road, in treeline or behind a terrain feature
- Clear observation down the approach corridor
- Able to engage without revealing the COP position
- Multiple covered withdrawal routes back to the COP perimeter

### Bradley Mission — Roving QRF Screen

The Bradley does not sit static. It conducts **roving patrols** along the approaches to Pucker Point, looking for:

- Enemy infantry elements moving to attack the COP
- Enemy vehicles probing toward the mortar position
- Enemy recon elements attempting to locate and call fire on the COP

When contact is made, the Bradley engages and withdraws — it does not hold ground alone. Its job is to break up QRF forces before they can mass against the COP, buying time for mortar crews and base defenders to prepare a response.

### Coordination with Mortar Crews

When the Bradley makes contact and withdraws back toward the COP, mortar crews must be notified immediately to prevent fratricide:

**"Bradley pulling back — check fire [approach direction]."**

---

## 9. Seeding Phase SOP

Seeding is one of the most important — and most misunderstood — aspects of WCS server culture. How players handle seeding defines how the broader WCS community perceives them.

### What Seeding Is

When a WCS server is low population (under 32v32), both factions cooperate informally to build the server to full pop. This means:

- Each faction holds their designated seeding objectives and builds out their supply chains
- Both factions fight only in the agreed contested zone
- Nobody pushes deep into the other team's held territory to cap their objectives
- The server fills organically and both factions enter full pop with functioning infrastructure

### What Is Fair Game During Seeding

Seeding is not a ceasefire. The following are acceptable during the seeding phase:

- Fighting in the designated contested zone
- Intercepting and destroying enemy supply trucks on road routes
- Harassing enemy logistics with small arms and light vehicles
- Mortar harassment within the contested zone
- Recon patrols into no-man's land between seed zones

### What Breaks the Seeding Agreement

- Pushing into and capping the other faction's designated seed objectives
- Attacking the other faction's main base area
- Deliberately destroying infrastructure in the other team's seed zone

### Seeding Message Format

Post to global chat at server start. Keep under 175 characters:

```
SEEDING: [Server] [Map] | NATO: [objectives] | RUS: [objectives] | PvP: [zone] | No deep push til 32v32
```

If the other faction posts one first, acknowledge and confirm your side in chat. Seeding culture is built one session at a time — Zen Solutions leads by example.

### Why This Matters

The goal is to be the community other WCS players are glad to see join the server. Not because we're the most elite unit — but because when Zen Solutions is in the server, games are better organized, seeding is fair, and the fights are more enjoyable for both sides.

Approachable. Tactically credible. Fair. That is the standard.

---

## 10. Quick Reference

### Pre-Deployment Checklist — Blue Falcon LRRP

| # | Item |
|---|---|
| 1 | **Zero-cost loadout saved at base arsenal** |
| 2 | Radio pack equipped (in backpack slot) and confirmed functional |
| 3 | Long-range radio frequency confirmed with mortar crew at Pucker Point |
| 4 | LRF — mandatory |
| 5 | NVGs + IR laser on primary weapon |
| 6 | Suppressed weapon only — no unsilenced fire on patrol |
| 7 | Light chest rig only — no heavy plates |
| 8 | IFAK: 4x tourniquet, 4x bandage, 4x epi, morphine, saline |
| 9 | TRP list confirmed with mortar crews before departure |
| 10 | Egress routes planned and briefed to all patrol members |

### COP Build Priority — Pucker Point

```
1.  MCU concealed in treeline (resupply if spawn shows 0/0)
2.  Radio pack deployed at secondary concealed position
3.  Armory (inside camo netting — supply landing point)
4.  Heavy vehicle depot
5.  Light vehicle depot
6.  Living Quarters / AI Tent (requires Sergeant rank)
7.  Mortar pits x4–5 (clustered near Armory)
8.  MG nests — 360 coverage on all approach routes
9.  Bunkers on dominant terrain
10. Anti-aircraft emplacement
11. Camo netting throughout — all structures and vehicles
```

### CFF Quick Format

```
1. "Mortar, Blue Falcon — Fire Mission, over." [wait]
2. "Grid [XXX XXX]."
3. "[Target description]."
4. "HE — [N] rounds — Ring [X] — fire for effect."
5. Adjust: "Add/Drop [Xm], Left/Right [Xm]."
6. "Target destroyed. End of mission."
```

### LRRP Brevity Codes

| Call | Meaning |
|---|---|
| "Eyes on [TRP name]" | OP has visual on pre-registered target |
| "Splash" | Rounds in the air — impact imminent |
| "Add [X], Left/Right [X]" | Adjustment from observed impact |
| "On target — FFE" | Rounds accurate — fire for effect |
| "Target destroyed — EOM" | Mission complete |
| "Danger Close" | Friendlies within 100m of target |
| "OP compromised — extracting" | Patrol moving — cease all supporting fire |
| "Radio going dark" | Going silent — do not call on net |

---

*Zen Solutions — Blue Falcon FIST*
*WCS NA Servers | discord.armawcs.com | armawcs.wiki.gg*

*"Apparent confusion masks true organization." — Sun Tzu*
