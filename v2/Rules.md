# Corporate Hell v0.2

## Theme
A corporate hell. Incompetent, power hungry devils claw their way up a rigid infernal organisational structure by bending -- but never breaking -- the complicated code of law.

The damned (souls) are the only currency that matters. They are minted into labor (imps), spent to buy talent (agents), and hoarded, embezzled and redistributed by the management (pit lords and the archdevil).

You are commanding a faction of loosely organized devils to reign supreme through perpetual exploitation, extortion, machination and scheming. 

## Objective
The first player to **collect 20 points** wins, at which point the game ends. Ties are resolved in the following order: points, favors, souls in reserves, imps on the map, sectors ruled, scoring order.

Points are scored primarily by contributing to the publicly declared grand projects or through secret individual schemes (TBD).

## Components
- **Boards:** map board with 5 sectors; palace board with pit lord and archdevil palaces, contracting order, operating order, combat order, scoring order, grand projects and limbo; contracts board with agent cards on economy, logistics and warfare tracks. 
- **Player pieces:** 8 imps (2-sided -- fresh and exhausted); 10 control tokens.
- **Faction pieces:** 1 faction card; 2 economy, 2 logistics and 2 warfare agent cards; 1 grand design card.
- **Cards:** 10 economy, 10 logistics and 10 warfare agent cards; 10 grand design cards; 10 scheme cards (TBD).
- **Tokens:** 35 souls; 1 sigil of greed; 1 sigil of wrath; 12 favors.

## Setup
1. Players select their faction and color, then collect their player and faction pieces.
1. Each player puts their faction agents into the appropriate contract decks. The decks are then shuffled. No cards are drawn yet.
1. Each player puts their faction grand project card into the grand project deck. The deck is then shuffled. No cards are drawn yet.
1. Each player collects 5 souls into their reserves.
1. On the map board, place 3 souls on each of the 5 sectors. Then place a sigil of greed on Minauros sector and a sigil of wrath on Gehenna sector. 
1. Starting with the player with the highest prestige (as noted on the faction card), each player in turn chooses to place 1 imp on any sector. Then, starting with the player with the lowest prestige and going counterclockwise, each player places 2 imps on any single sector.
1. Scoring order is set up in prestige order; contracting and combat orders are set up in reverse prestige order.
1. The player with the highest prestige places their control token on the archdevil slot (without placing an agent). Then, they draw 1 grand project card and declare it. 

## Concepts

### Souls

#### Closed Economy
Generally, the economy of souls follows a circular path:
- **From reserves to coffers.** Players spend the souls from their reserves to promote imps, contract agents and lobby pit lords to become the archdevil. This is then collected in the various sector palaces.
- **From coffers to limbo.** The pit lords spend the souls from their coffers to carry out their machinations, the souls are then transferred to limbo.
- **From limbo to sediment.** The souls collected in limbo are regularly distributed into the sediment on each sector.
- **From sediment to reserves.** The souls in sediment are exploited and collected by imps into the player reserves.

#### Distribution
When souls are transitioning from limbo to sediment and from sediment to reserves they follow the distribution rules.

First, a list of participating nodes (e.g. sectors, imps, sigils) are counted and sorted by priority. Then, souls are divided equally among the nodes in cycles:
- A **complete distribution cycle** requires a full set of souls to be divided across all participating nodes.
- An **incomplete distribution cycle** tries to divide all participating souls, where the last cycle starts from the nodes with the most priority and any priority ties are decided by the distributing player. This way, the last cycle may not be completed and some nodes (with less priority) are left without any souls.

### Agents
Each player has a hand of agent cards. These cards are public information for all players, unless noted otherwise. 

Agent cards are bought with souls during contracting phase. In most cases, once used, the agent card is discarded to the bottom of the appropriate contract deck. 

Each agent card is multifunctional and can have a combination of **features**, explained below:
- **Card type.** A card type is defined by its function (economy, logistics, warfare), origin (faction specific or generic) and any combination of keywords. Various game rules may reference the card type.
- **Additional cost.** An agent card may have an additional cost of souls when it is bought from the contract track. By default, the additional cost is 0 and the feature is not shown.
- **Energy.** A number that shows how many times the agent is allowed to act during the operations phase.
- **Power.** A number which represents how strong the agent is during domination and combat.
- **Sector abilities.** Effects that can be executed during operations phase.
- **Combat abilities.** Effects that can be executed before, during or after combat. 
- **Palace ambitions.** Effects that are executed while the agent occupies a pit lord or the archdevil position.

### Sectors

#### Sector Composition
The map board is divided into 5 sectors: Gehenna, Minauros, Erebus, Avernus and Pandemonium. Each sector is adjacent to each other and contains:
- **Palace**, where dominating *pit lords* spend the *coffers* for their *machinations*.
- **Sediment**, where *souls* end up from limbo, then exploited and collected by *imps*; *sigils* are also placed in the sediment.
- **Agent slots** for each player to place their *agent* to act in a sector.

#### Ruling a Sector
The palace is considered ruled by the player whose agent is a pit lord or the archdevil.

Players put their control tokens on the pit lord and archdevil agent cards to indicate ownership and tenure.

A pit lord may become the archdevil through successful lobbying attempts. 

Both the pit lord and the archdevil get additional palace abilities while they rule:
- **Ambitions:** abilities specific to the agent ruling as a pit lord or the archdevil.
- **Machinations:** abilities specific to the palace ruled. Most machinations must be carried out during palace phase, however some provide powers outside of palace phase.

#### Sector Abilities
An agent card added to the agent slot allows the player to influence the sector operations through sector abilities: 
- Sector **actions**: effects that the active player chooses to execute during their turn.
- Sector **passives**: effects that may be executed during any player's turn. 

The sector abilities generally cost energy to execute -- this is noted as a number in parantheses before the sector ability description. Energy is tracked with control tokens and the agent is discarded when the energy reaches 0. 

The most common sector abilities are described as keywords, noted below.

Sector actions:
- **Move X:** take X number of your imps in the active sector and move them to another sector. 
- **Attack:** select a defending player with imps or agent in the active sector to initiate combat (described in more detail later in the combat section).
- **Extract X:** distribute incomplete cycles of X souls from the active sector's sediment to nodes in priority -- pit lord, agents, imps.
- **Promote:** place fresh imps to the active sector (or any sector, if the active sector is Gehenna); pay 1 soul (+1 if the active sector is not Gehenna) to Gehenna's coffers for each imp placed.
- **Heal X:** switch X number of imps in the active sector to their fresh side. 

Sector passives:
- **Defend X:** add X combat strength when defending in this sector.
- **Support:** your imps in this sector may add their combat strength to this or adjacent sector; any player can be supported; supporting imps may become exhausted during the combat.
- **Patrol:** target extract or support abilities in this sector just after activation but before resolution -- these abilities have no effect this turn and the cost is not refunded.

#### Combat
At the start of the combat, the attacking and defending players **in secret** must select to participate 1 agent card from their hand, if able. Otherwise, the acting agent in the sector participates, if present. The cards are revealed at the same time.

Then each side calculates their combat strength (including support):
- Each fresh imp provides 1 combat strength; each exhausted imp provides 0 combat strength. 
- The participating agents add their power to the combat strength.
- Each favor provides 1 combat strength; additional favors may be added during calculation.

The side with more combat strength wins. Ties are resolved in the combat order.

The losing side destroys exhausted imps, then exhausts fresh imps. The losing player may move their exhausted imps from the active sector to an adjacent sector. The losing player then loses 1 energy on their acting agent in the active sector.

If the sector had a **sigil of wrath**, the losing player must give to the winning player a number of souls equal to the difference between the final combat strengths.

Finally, the participating agents are discarded.

Throughout the combat, the participating agents may also activate their **combat abilities**. Whenever the timing of these abilities intersect, the agent with higher power executes their ability first. Any further ties are resolved the same as combat strength.

The most common combat abilities are described as keywords, noted below:
- **Execute X:** after the combat winner is determined, the winning player may choose to destroy X imps of the losing side in the active sector.
- **Protect X**: after the combat winner is determined, the losing player may cancel X execute abilities or ignore exhaustion for X imps.

### Insurgency

A player is considered insurgent if they do not rule any palace as a pit lord or the archdevil.

### Grand Projects

#### Declaring a Grand Project

When a new grand project is declared, it may be placed on any of the first 3 slots. If a grand project is already placed in the chosen slot, it is discarded.

Discarded grand project cards are put to the bottom of the grand project deck.

#### Scoring a Grand Project
Each grand project has a number of available slots where players put their control tokens when scoring. When all of the slots are filled, the grand project is discarded.

## Structure
The game is played in **rounds**. Each round has 4 **phases** that are played one after another: contracting, operations, palace and scoring.

### Contracting Phase
> During this phase players may contract new agents from the pool of available agents in economy, logistics and warfare tracks.

In **contracting order** each participating player either:
- **Spends** the required amount of souls from their reserves into the appropriate coffers and other player reserves, and **takes** an agent card into their hand. The contracting track is then refreshed.
- **Passes** by flipping their control token on the contracting order track to indicate that they are no longer participating.

The **cost** is determined by the bidding level -- more expensive closer to the deck. This cost is then modified depending on the agent card itself:
- By the additional cost marked on the card. 
- If it's a faction agent and the player contracting the agent plays a different faction, they must give 1 soul to the player playing the agent's faction.

The remaining souls are **paid to the appropriate coffers** depending on the contracting track from which the agent card was taken:
- Economy agent cost is paid to Minauros.
- Logistics agent cost is paid to Erebus.
- Warfare agent cost is paid to Avernus.

**Refreshing** a contracting track is done in 2 steps:
1. All cards are shifted away from the deck, to the cheapest possible space.
1. A new card is placed face-up from the deck.

When every player **passes**, the next phase begins. 

In the **first round** the contracting phase is special:
1. The phase is repeated 3 times.
1. Each time a new column of the contracting track is unlocked -- starting with the most expensive one and ending with all tracks unlocked.
1. Agent cards cannot be placed in locked spaces. 

### Operations Phase
> During this phase players use their agents to influence the state of the map board.

The operation phase consists of **2 steps**: planning and acting.

#### 1. Planning Step
Each player simultaneously **places** face-down agent cards from their hand on up to 5 sectors.

When everyone is ready, all face-down agents are **flipped** face-up. Each player places a number of control tokens on each face-up agent card equal to its energy.

Then, **operating order** is updated. It is determined by counting the power of all player's agents and sorting the combined power in a descending order. Any ties are resolved in the combat order. 

Finally, in operating order each player may place any number of **favors** on any number of face-up agents.

#### 2. Acting Step
In **operating order** each participating player either:
- **Executes** a sector ability of one of their face-up agents.
- **Passes** by flipping their control token on the operating order track to indicate that they are no longer participating.

Sector ability execution follows these steps:
1. **Pay** the energy cost: remove the required number of control tokens from the face-up agent card.
1. **Execute** the sector abilities associated with the cost. During execution, the sector with this agent card is considered active.
1. **Check** energy count of all face-up agent cards. If any of the face-up agent cards no longer has any energy, it is discarded.

When every player **passes**, the next phase begins. 

Whenever multiple agent cards are **discarded** at the same time, follow the operation order to determine which player puts their agent cards to the bottom of the contracting track decks first. A player may then choose in what order they discard their cards. 

### Palace Phase
> During this phase players emerge as pit lords and archdevils and carry out their machinations.

The palace phase consists of 3 steps: domination, lobbying and machinations.

#### 1. Domination Step
After the operation phase, the remaining face-up agents try to **dominate** their sectors.

To determine who dominates a sector, each player calculates their **domination count**:
- Each fresh imp adds 1.
- Acting agent adds their power.
- Each favor that was placed on the acting agent adds 2.
- If the sector is ruled by another player, add 1.

The player with the highest domination count has the **opportunity** to dominate the sector if:
- They have an acting agent.
- The total count is higher than the power of the current pit lord.

**Ties** are resolved in the combat order.

If the domination is **successful**, the acting agent becomes the pit lord and the current pit lord agent is discarded.

Finally, the **archdevil** player must pay a number of souls from their reserves into Pandemonium coffers for each control token on the agent card. This player gains the same amount of favors. If the player is unable to pay, the archdevil agent is discarded and the player must return all of their favors.

#### 2. Lobbying Step
Each player who owns at least 1 pit lord **bids** a number of their souls from the reserves in secret, then everyone reveals the bids at the same time. The player with the highest bid must choose to either:
- **Keep** the current archdevil. Add an additional control token on the archdevil agent card.
- **Promote** one of the pit lords to become the archdevil. The previous archdevil agent is discarded.

**Tied bids** are resolved in the scoring order.

All souls used to bid are **paid** into Pandemonium coffers.

#### 3. Machinations Step
Every player who rules a palace as a pit lord or the archdevil may carry out **machinations** associated with the palace. The machinations are carried out simultanesouly, however the archdevil at any point may decide who must carry out their machinations first.

The machinations step **ends** when every player got the opportunity to carry out the machinations of all of their ruled palaces.

| Palace | Coffer Income Source | Machinations |
|---|---|---|
| Archdevil | N/A | <ul><li>During palace phase, spend 1 favor to draw 2 grand project cards. Declare a new grand project and put the other card to the bottom of the deck.</li></ul> |
| Gehenna | Promoting imps | <ul><li>During palace phase, spend 5 souls from coffers to place 1 imp (of any player) in any sector.</li><li>Each time anyone promotes outside of Gehenna, take 1 soul from coffers to reserves.</li></ul> |
| Minauros | Economy contracting track | <ul><li>During palace phase, spend 3 souls from coffers to move the sigil of greed to any sector.</li><li>During palace phase, spend 2 souls from coffers to discard 1 agent from economy contracting track.</li><li>During palace phase, spend 4 souls from coffers to take 1 soul from limbo to reserves (of any player).</li></ul> |
| Erebus | Logistics contracting track | <ul><li>During palace phase, spend 3 souls from coffers to set the contracting order.</li><li>During palace phase, spend 2 souls from coffers to discard 1 agent from logistics contracting track.</li><li>During palace phase, spend 3 souls from coffers to move 1 imp (of any player) to another sector.</li></ul> |
| Avernus | Warfare contracting track | <ul><li>During palace phase, spend 3 souls from coffers to set the combat order.</li><li>During palace phase, spend 2 souls from coffers to move the sigil of wrath.</li><li>During palace phase, spend 3 souls from coffers to discard 1 agent from warfare contracting track.</li><li>Each time an imp is destroyed, take 1 soul from coffers to reserves (if able).</li></ul> |
| Pandemonium | Archdevil's domination and pit lords' lobbying | <ul><li>During palace phase, spend 3 souls from coffers to set the scoring order.</li><li>During palace phase, spend 4 souls from coffers to view the top grand design card, then place it on top or bottom of the deck.</li></ul> |

### Scoring Phase
> During this phase players score the grand projects to earn points and prepare for the next round.

In scoring order, every player tries **scoring** 1 declared grand project if they satisfy the condition or spend the required resources. They then:
1. **Place** their control token on an open slot on the grand project card.
1. **Collect** points equal to the position of the grand project card.
1. **Take** 1 favor.

If at any point any player reaches 20 points, the game ends and that player is the **winner**.

Then **resolve** the end of round steps and start the next round:
1. Discard the rightmost grand project card. **Move** grand project cards one space to the right.
1. Each **insurgent** player chooses to either place 1 imp on any sector or take 2 souls from limbo.
1. **Distribute** complete cycles of souls from limbo to nodes in priority -- sigil of greed, sediment. 

## Glossary
A list of the most important **nouns** used across the rules, with a reference to the relevant *actions*. 
- **Souls:** the main currency circulating the hell in eternity.
- **Imp:** a **soul** with a *promotion*, used for basic labor in the **sectors**.
- **Agent:** an independent contractor, who helps to organize **imps** for work and may occupy important political positions as a **pit lord** or even **archdevil**. 
- **Pit Lord:** an **agent** who has *dominated* a **sector** in order to achieve their *ambitions* and carry out *machinations* in the **sector's palace**.
- **Archdevil:** a **pit lord** rising in power through *lobbying*, who builds their legacy through *declaring* **grand projects**.
- **Palace:** a place from which a **pit lord** or the **archdevil** *rules* and carries out their *machinations*.
- **Limbo:** the collection point of **souls** before they are *distributed* to **sediment**.
- **Coffers:** a bank of **souls** in a **palace**, which are *spent* by a **pit lord** or the **archdevil** to carry out their *machinations*.
- **Reserves:** a bank of **souls** that the player may *spend* for their needs.
- **Sediment:** this is part of a **sector** where **imps** reside and *exploit* **souls** to be taken into the player **reserves**; also where **sigils** are placed.
- **Map:** a collection of all **sectors**.
- **Sector:** a location on the **map** which contains **sediment** and **agents**; during a player's turn when an **agent** acts, the **sector** is considered *active*.
- **Grand Project:** *declared* by the **archdevil**, this is a public objective which, when *scored* by a player, gives them **points**. 
- **Scheme:** TBD
- **Sigil:** the **sigil of greed** draws more **souls** from **limbo** to the **sediment**; the **sigil of wrath** encourages *combat* between players.
- **Points:** required to win the game.

## Content
https://docs.google.com/spreadsheets/d/1EW_OuRDMPRIrT2c4jk-HYR7KzQOYSFV4sxsPVG8tWK4