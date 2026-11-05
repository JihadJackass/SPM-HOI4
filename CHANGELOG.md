# Single Player Magic 2.3.2 (HOI4 1.19)

- The State Transfer button no longer covers the army / navy / air experience counters: it sits right after the
  top bar counters, and its window opens below the alert icons

# Single Player Magic 2.3.1 (HOI4 1.19)

- No more dark blue: SPM: Politics is now orange and SPM: Equipment salmon; the other category colours were
  spread out so neighbouring categories do not share a colour (War is magenta, Factions mustard, Country Rules white, World Tension cyan)

# Single Player Magic 2.3.0 (HOI4 1.19)

- SPM decisions work again. The main Single Player Magic category is always in your decisions tab with a green
  Show the SPM Decisions / red Hide the SPM Decisions; everything else is hidden by default (the panel's
  SPM Decisions tick does the same)
- The full decision set is back for players who cannot use the panel: Resources, Politics, Combat and Production,
  Country Modifiers, Equipment, States, War, Subjects, Factions, Country Rules, World Tension, Country Specific
- Multiplayer: every player now has their own panel page, selections and State Transfer switch, so several players can
  use it at the same time. The host decisions moved into the main SPM category: Become the SPM Host, Step Down,
  and Let Every Player Use the SPM Panel / SPM Panel for the Host Only. While nobody is host, everyone can use it
- Delete This Type for ships works (it now goes by hull: light and heavy cruisers share one, as do battlecruisers and battleships)
- Look Like It should no longer write errors to the log
- The old Toolpack multiplayer category and its empty action log are gone

# Single Player Magic 2.2.0 (HOI4 1.19)

- State Transfer is back on the top bar (Ctrl+Shift+T). While it is on, clicking a state opens a small window:
  mark states, a whole country or its colonies, click a state of the receiving country, then Send or Send and Core
- Panel values for the owner (popularity, stability, war support, political power, experience...) read the owner a different way, since they all showed 0
- Everything left out of 2.1 is back: delete divisions (one type, or all with two clicks), delete ships of a type,
  unlock division templates, kamikaze and female aces rules, look like another country, and the Building Tool's
  shift-click (+5 / -5), right-click (remove all), automatic technology for radar, refineries, silos, rockets and
  reactors, and building in every marked state at once
- New tick in the panel header shows or hides all SPM decision categories; the main SPM category is otherwise always shown
- Long subject types and other values no longer wrap; nothing sits on the panel border any more
- Resources are one per line; shorter titles; the panel is slightly taller (560 x 440)

# Single Player Magic 2.1.0 (HOI4 1.19)

## Panel: five pages, Toolpack and State Transfer Tool built in
State | Economy | Country | Diplomacy | Military. Everything from the Toolpack and the State Transfer
Tool is in here now, so neither needs to be loaded separately.

- State: give to you or its core owner, take control, capital, core / uncore for the owner, claim / unclaim,
  demilitarise, resource rights, compliance and resistance. Mark states one by one, a whole country or
  only its colonies (with a live count), then send them all to another country or core them for it
- Economy: population, state size up / down, the six resources, every building with its level, quick builds
- Country: put any ideology in power, party popularity, elections, purge rivals, stability, war support,
  political power, research slots, major power, start or win a civil war, country rules, borrowed look
- Diplomacy: every subject level (dominion to Reichskommissariat), autonomy, annex, free subjects,
  undo bad peace deals, white peace, war / peace with you, guarantees, non-aggression, access, opinion, factions
- Military: divisions in this state, ships for the owner, experience, command power, manpower, equipment

## Decisions
- Every category and decision is colour-coded; ideologies use their own colours
- Each category is folded behind a green Show Options / red Hide Options decision
- Enable (green) / Disable (red) for every toggle; names are in Title Case
- New Country Modifiers category: Expanded Volunteers, Research Boost, Political Boost, National Unity,
  Mass Conscription, Logistics Mastery, Expanded High Command, Rapid Planning, Fast Reinforcement,
  Intelligence Network, Quiet Lend-Lease
- Optional: Make SPM Spirits Visible / Hidden swaps every SPM bonus between a national spirit and a silent bonus
- Factions: 20 historical alliances in three groups (great powers, regional pacts, ideological blocs), each with
  a proper name; lists of factions to join and countries to invite can be shown or hidden
- Peace Fixes moved to the bottom and hidden unless you turn them on in the main SPM category

# Single Player Magic 2.0.0 (HOI4 1.19)

## Everything in one panel
The old toolpack (14 separate tool windows) is gone. Press the arrow at the bottom right (or Ctrl+T),
then click any state. One window, four pages, live values next to every control:

- State (the state you clicked): give it to you or its core owner, core it, make it the capital,
  mark several states and send them to another country, population, the six resources, and every
  building type with its current level and +1 / -1
- Country (its owner): put any ideology in power with one click, popularity of each party, elections,
  purge rivals, stability, war support, political power, research slots; make it your puppet,
  integrated puppet, dominion or colony, set it free, annex it; country rules as tick boxes; borrowed
  name and flag of another ideology
- Military: spawn divisions in this state (8 types, any number, trained or veteran), spawn ships for
  its owner (7 types, 5 design eras), army / navy / air experience, command power, manpower and equipment
- World: undo the latest peace conference (and step further back), undo the owner's last lost peace,
  return its cores, hand back conquered land, take your cores back, free its subjects, snapshot of the
  whole map, world tension, white peace, win a civil war, war / peace / guarantee / non-aggression /
  military access / opinion with you, factions

Every peace conference is recorded automatically before it opens, so it can be undone later.
The undo and snapshot actions are also in the "SPM: Peace Fixes" decision category.

## Decisions (ported from the Kaiserreich version)
Resources, Army (separate land / naval / air bonuses), Politics (boost or switch any ideology, purge rival parties, elections, Italy balance of power), States, Equipment (1.19 equipment names), Production, War (white peace, win civil war), World Tension, Subjects, Factions (found, join, invite, leave), Country Rules (allow / reset each rule), Paranoia.

## Fixes
- Decision category icon was 114x108; now 53x40 like the base game icons
- Every national spirit has a name and description
- Building Tool building counts never showed (broken scripted localisation)
- Politics Tool elections buttons used an invalid ruling party; factions now use the 1.19 faction templates
- Old decisions that did nothing (empty "ban parties", always-hidden industry bonus), wrong paranoia maths, missing equipment types, a 1000% submarine bonus, and swapped "enabled/disabled" tooltips
- Multiplayer action log text did not load
- Missing tooltips and research-speed sign in the Politics Tool
- All new text is also copied into the other languages so nothing shows raw keys
