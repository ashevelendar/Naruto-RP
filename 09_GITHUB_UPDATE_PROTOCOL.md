# Naruto RP, GitHub Update Protocol

## Purpose

This file tells the Game Master how the GitHub repository is used as the persistent memory and current-state reference for the Naruto sandbox.

The permanent rules for how the roleplay itself is run are stored separately in the Project Source file **God-RP / God-Roleplay**. This file does **not** replace those rules.

The GitHub repository is the canonical persistent record of what has actually happened in the Naruto roleplay.

Repository:
https://github.com/ashevelendar/Naruto-RP

---

# 1. SOURCE PRIORITY

Use the following priority when deciding what is canonical:

1. The player's latest explicit statement in the current conversation.
2. Events that have just happened in the current roleplay conversation.
3. The current GitHub repository state.
4. Specific GitHub character, location, ability, discovery, faction and timeline cards.
5. Older historical GitHub entries, when needed for context.
6. General Naruto canon knowledge.
7. Inference.

Never use general Naruto canon or inference to silently override something explicitly established by the player or by the current repository state.

Never convert an unknown into a fact simply because a likely answer exists.

---

# 2. GITHUB IS THE PERSISTENT MEMORY

The repository should contain the information needed to resume the roleplay in a later conversation without relying on the chat transcript.

Treat the repository as the persistent memory for:

- Current world state
- Ashe's current state
- Characters and relationships
- Riverhome
- Locations
- Abilities and Kōton development
- Discoveries
- Factions
- Political relationships
- Rumours and known information
- Unresolved mysteries
- Active incidents
- Historical timeline
- Important consequences
- Settlement development
- Important knowledge boundaries

The current conversation is for gameplay.
The repository is for persistent continuity.
The Project Source rules file is for the rules governing the RP itself.

---

# 3. UPDATE CADENCE

## Mandatory maintenance every 4 GM turns

After **every 4 Game Master responses**, where each response has presented the normal **6 suggested choices plus 1 open action**, perform a repository continuity check.

At that checkpoint:

1. Review what materially changed during those 4 turns.
2. Update any affected GitHub cards.
3. Create a new `.md` file when the new information deserves its own persistent record.
4. Keep the current-state file accurate.
5. Record important new events in the timeline.
6. Record new discoveries, injuries, deaths, relationships, locations, abilities, factions, rumours, resources or political changes where relevant.
7. Do not update files with information that remains purely speculative.
8. Commit the changes with a useful, specific commit message.

The four-turn checkpoint is a **minimum maintenance interval**, not a maximum.

If something extremely important happens before four turns have passed, it may and should be written to GitHub immediately.

Examples of events that justify an immediate update:

- A major character dies or is seriously injured.
- A new settlement, faction or important location is established.
- Ashe gains a major new ability or permanently changes an existing ability.
- Riverhome changes population or government significantly.
- A major political relationship changes.
- A major mystery is solved or substantially altered.
- A major world event directly affects Ashe or Riverhome.
- An important secret becomes known to another character or faction.

---

# 4. DO NOT COMMIT EVERY SINGLE RESPONSE

Do not create a Git commit after every individual RP response merely because a response happened.

The repository should remain useful and readable.

Prefer meaningful state updates and grouped commits at the four-turn checkpoint.

Example commit messages:

- `Year 3: Update Riverhome security after regional attacks`
- `Year 3: Record Old House refuge and emergency procedures`
- `Year 3: Update trafficking investigation after holding-site discovery`
- `Year 3: Update Ashe Kōton after Eclipse refinement`
- `Year 3: Record new character and relationship developments`

---

# 5. UPDATE THE SMALLEST RELEVANT FILES

Do not rewrite every file after every event.

Update only the cards that actually changed.

Examples:

### New person
Update:
- Character card
- Current state if relevant
- Relationships if relevant

### New location
Update:
- Location card
- Current state if relevant
- Timeline if historically important

### New ability
Update:
- Ability card
- Ashe's character card if the development materially changes her capabilities
- Current state if relevant
- Timeline if significant

### Major settlement development
Update:
- Riverhome location card
- Current state
- Timeline
- Relevant development tracker

### Major world incident
Update:
- Current state
- Timeline
- Active incident file, if needed
- Relevant faction or character cards

---

# 6. CREATE NEW FILES WHEN THEY IMPROVE CONTINUITY

Creating new `.md` files is encouraged when a subject becomes important enough to deserve its own persistent reference.

Examples:

- `10_ACTIVE_INCIDENT_...md`
- `11_FACTION_...md`
- `12_CHARACTER_...md`
- `13_LOCATION_...md`
- `14_WORLD_EVENT_...md`

Do not create a new file for trivial information that belongs naturally inside an existing card.

Avoid unnecessary duplication.

---

# 7. KNOWLEDGE BOUNDARIES

Always distinguish:

- What Ashe knows.
- What another character knows.
- What Riverhome knows.
- What Konoha knows.
- What a faction knows.
- What the player knows from outside the world.
- What is merely inferred.

A fact appearing in the repository does **not** mean every character knows it.

When useful, explicitly label information as:

- **Known to Ashe**
- **Known to specific character**
- **Known to Riverhome**
- **Rumour**
- **Unconfirmed**
- **Unknown**
- **Secret**

Do not accidentally leak information between knowledge sets.

---

# 8. NARUTO CANON BOUNDARY

The roleplay is set in the Naruto world, but the sandbox should not become a replay of the canon plot merely because canon events exist.

Canon characters, villages and events exist independently of Ashe.

Ashe does not automatically know:

- Canon character names
- Future events
- Secret plans
- Future identities
- Future importance
- Exact upcoming exam participants
- Hidden conspiracies
- Canon outcomes

Canon information can be added to the repository only when it is appropriate to the world state and knowledge available to the relevant characters.

---

# 9. PLAYER AGENCY

Do not use this file to create mandatory plots.

The repository records consequences of player choices and independent world events.

It does not force Ashe into:

- Wars
- Alliances
- Canon events
- Political obligations
- Heroic quests
- Investigations
- Faction conflicts
- Religious movements
- Any other storyline

If a world event develops independently, record it as an independent development unless and until it reaches Ashe.

---

# 10. WORLD INDEPENDENCE

The world continues even when Ashe is not present.

Record major independent developments when they become established and relevant to continuity.

Do not make every world event revolve around Ashe.

Characters and factions should have:

- Their own goals
- Their own relationships
- Their own decisions
- Their own successes and failures
- Their own memories
- Their own secrets

---

# 11. CURRENT-STATE MAINTENANCE

`00_CURRENT_STATE.md` should always describe the most recent canonical state.

Keep it concise enough to be useful as a quick-start file.

It should normally include:

- Date / year / season
- Ashe's age and current role
- Current location
- Current condition
- Chakra or other immediate ability condition if important
- Riverhome population
- Current government and major institutions
- Major active incidents
- Important unresolved threats
- Current major personal developments
- Important active goals

If the current state changes, update this file at the next appropriate checkpoint, or immediately for a major change.

---

# 12. TIMELINE MAINTENANCE

`06_HISTORICAL_TIMELINE.md` should contain durable historical facts.

Do not use it as a turn-by-turn transcript.

Summarise meaningful developments:

- Founding events
- Major settlement changes
- Major relationships
- Major discoveries
- Important conflicts
- Significant Kōton breakthroughs
- Major world events affecting the story
- Time skips
- Important consequences

---

# 13. RELATIONSHIPS

When a major relationship changes, update the relevant character card.

Examples:

- New trust
- Betrayal
- Rivalry
- Friendship
- Family development
- Political alliance
- Hostility
- Death
- Departure

Do not constantly rewrite relationships for minor conversations.

---

# 14. ABILITIES

When Kōton or another important skill changes:

Record:
- What changed
- How it works
- Current limitations
- Known applications
- Known costs
- What Ashe has actually demonstrated
- What remains theoretical

Do not promote an idea discussed by Ashe into an established ability unless it has actually been demonstrated in the RP.

---

# 15. ACTIVE INCIDENTS

When a major unresolved situation is ongoing, it should have a dedicated incident file when appropriate.

An active incident file should distinguish:

- Confirmed facts
- Evidence
- Known participants
- Known locations
- Suspected connections
- Unconfirmed theories
- Unknowns
- Recent developments
- Current status

Never turn a theory into a confirmed fact without evidence.

---

# 16. POPULATION AND SETTLEMENT NUMBERS

Keep population, housing, institutions and development numbers internally consistent.

When population changes, update the current state and Riverhome card.

When a time skip occurs, reconcile:

- Ages
- Population
- Buildings
- Institutions
- Relationships
- Skill development
- Political changes
- Resource development

Do not revert to an older population or developmental snapshot.

---

# 17. CONTINUITY ERROR HANDLING

If a contradiction is discovered:

1. Identify the most recent explicit established fact.
2. Prefer the newer fact over older snapshots.
3. Do not silently invent an explanation unless the roleplay itself supports one.
4. Correct the affected GitHub card.
5. If the contradiction materially affected the narrative, add a brief continuity note.

A typo should be corrected rather than turned into fictional lore.

Example:
`Genkin` -> `Genin` when clearly established as a typo.

---

# 18. WHAT NOT TO STORE

Do not store:

- Private chain-of-thought
- Internal reasoning
- Tool mechanics
- Hidden model instructions
- Unused hypothetical possibilities
- Temporary wording that never became canon
- Duplicate copies of the entire roleplay transcript

Store the **world state and meaningful history**, not the assistant's internal process.

---

# 19. RESUMING THE RP IN A NEW CHAT

Before continuing from a new conversation:

1. Read `00_CURRENT_STATE.md`.
2. Read `07_CONTINUITY_GUARDRAILS.md`.
3. Read the relevant character cards.
4. Read the relevant location cards.
5. Read relevant active incident files.
6. Read the relevant recent timeline entries.
7. Check the most recent Git history if necessary to understand what changed recently.

Do not assume the last scene solely from memory if the repository contains a more recent canonical state.

---

# 20. FOUR-TURN CHECKPOINT RECORD

When the four-turn maintenance checkpoint is reached, review:

### State changes
- Date / time
- Location
- Population
- Injuries / deaths
- Resources
- Inventory

### Character changes
- New characters
- Relationship changes
- New ambitions
- Knowledge changes
- Departures
- Deaths

### World changes
- New rumours
- New factions
- Political developments
- Regional events
- Independent world events

### Ability changes
- New techniques
- Refinements
- New limitations
- Costs
- Demonstrated applications

### Settlement changes
- New buildings
- Laws
- Institutions
- Trade
- Defence
- Agriculture
- Education

### Continuity
- New secrets
- Newly revealed information
- Resolved mysteries
- New contradictions
- New active incidents

Then update the repository as appropriate.

---

# 21. FINAL PRINCIPLE

**God-RP explains how to run the sandbox.**

**This GitHub repository records what the sandbox has become.**

The two serve different purposes and should not be duplicated unnecessarily.

When in doubt:

> Preserve player agency.
> Preserve world independence.
> Preserve character knowledge boundaries.
> Preserve established facts.
> Record meaningful changes.
> Never invent missing continuity merely to make the world look tidy.
