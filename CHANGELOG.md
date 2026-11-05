# Single Player Magic 1.2.0 (HOI4 1.19)

## One panel for everything
Press the arrow at the bottom right (or Ctrl+T), then click any state. One window shows that state and
its owner, with tabs down the side. Every button acts on the state you clicked or on its owner, so a
job like "give this state to Germany and make Germany my puppet" no longer needs three windows.

- Fix: undo the peace its owner lost, undo the latest peace conference (click again to go further back),
  return its cores, hand back conquered land, save / load a snapshot of the whole map, take your cores back
- Territory: give the state to you or to its core owner, core it, make it the capital, mark states and
  send all marked states to another country in one click
- Subjects: make the owner your puppet, integrated puppet, dominion or colony; set it free; free or annex its subjects; annex it
- Politics: ruling party (70% popularity), elections, purge rival parties, stability, war support
- War: white peace, win its civil war, peace with you, declare war, factions
- Resources: political power, manpower, command power, equipment, and instant factories, infrastructure and air bases in the state
- Advanced: the detailed tools from the old menu (divisions, ships, buildings, research slots and so on)

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
