# Kancolle Wikia Quest Syntax / Grammar
## Preface
* This is a general quest description grammar, meant to cover 99% of cases.
* The purpose of this is to establish consistency amongst quest descriptions. Many older descriptions contrasted greatly in wording between eachother, and some of them were worded oddly or ambiguously, which only served to cause confusion. This aims to eliminate that going forward.
* There will, for sure, be quests that have requirements that do not fall into this grammar. In those edge cases, follow the grammar as strictly as possible while including the deviant requirements.
* `<>` denotes terms that are not to be taken literally and are defined in the glossary. Examples of each are given where applicable, more will be added as needed.


## Quest Descriptions
### Composition

`Have (ONLY) <Ship> ((<as X ship>), <Ship> (<as X ship>), ... , and <Ship> (<as X ship>)) in your <Fleet Number> fleet.`

### Sortie

`Sortie [a / the <Fleet Number> fleet] with <Ship> ((<as X ship>), <Ship> (<as X ship>), ... , and <Ship> (<as X ship>)) to World(s) X-X(, X-X, ... , and X-X).  [Obtain <Rank> at <Node> (of X-X(, X-X, ... , and X-X)) <Times> / Reach <Node> (of X-X(, X-X, ... , and X-X)) <Times>].  ([Obtain...]) ...`

* Use multiple "Obtain" statements for maps that have many specific requirements.
* X-X is a placeholder for a map ID, they should be filled in as needed and should link to the respective map page.

### Exercise

`(Use a fleet with <Ship> (<as flagship>, <Ship> <as second ship>, ... , and <Ship>) to) (Obtain <Rank>/Participate) in Exercises <times> (<within the same X>).`

### Expedition

`Complete (X) Expedition(s) X(, X, ... , and X) <times> (<within the same X>).`

### Supply/Docking Quests

Handle on a case-by-case basis.

### Arsenal

#### For crafting quests
`Craft (a (piece of) / X (pieces of)) (ship(s)/ equipment).`

#### For scrapping quests
`[Scrap/Dismantle] (a (piece of) / X (pieces of)) (ship(s)/ equipment).`

#### For item conversion/creation quests
```
(Prepare <Equipment>, ... , and <Equipment> in your inventory.) Have <Ship> as secretary (equipped with <Equipment> (<on her Xth slot>)). 
Scrap <Equipment>(, ... , and <Equipment>).

(※ (Equipped) & (prepared) equipment must be unlocked.)
(※ The equipped X will be converted to the reward listed.)
(※ The prepared (resources), (items), and (equipment) will be consumed upon quest completion.)
(Other quest-specific warnings)
```
* Resources should be always be capitalized, as in the scope of the game they are proper nouns (Fuel, Steel NOT fuel, steel)
* "Prepare" statements should list requirements in the order of resources, items, equipment.
	* Furniture Coins are NOT a resource - they are present in the player's inventory, thus they are an item.
* When referring to general groups of items to scrap, link to the item page and use terminology consistent with the title of said page.
	* Example: Anti-air guns vs Machine guns - the group page for the item says Anti-air guns, therefore use Anti-air guns.

### Modernization

Handle on a case-by-case basis.

### Marriage

Refer to applicable sections above.


## Quest Reward Lists
### For quests with no choices
```
<Equipment> xX
(...
<Equipment> xX)
```

### For quests with only choices
```
Choice between
<Equipment> xX
or
<Equipment> xX
((or
...)
then choice between
<Equipment> xX
or
<Equipment> xX
(or
...))
```

### For quests with a mix of given items and choice items
```
<Equipment> xX
((...
<Equipment> xX)
then choice between
<Equipment> xX
or
<Equipment> xX
(or
...))
```
* Non-choice rewards should be listed first, followed by choice rewards.


## Glossary
`X` = Generic placeholder for integer values. X's inside of <>'s are NOT equivalent, see below.

`()` = Denotes terms that are not to be included in every description, but should be included when appropriate.

`[... / ...]` = Use the term either on the left or right side of the '/' for this description.

`<Ship>` = Either a specific or nonspecific ship name.
* specific: Kawakaze Kai Ni; Akagi Kai Ni or Akagi Kai Ni E.
* nonspecific: 2 ships; 2 Light Cruisers; 3 level 70 or above Yuugumo-class Destroyers; 2 additional ships; at least 3 Destroyers/Coastal Defense Ships.
	
`<as X ship>` = Denotes the required position in the fleet for the given ship. X = flag, second, third, fourth, fifth, sixth.
* If X = flag, don't include a space between "flag" and "ship", just write "flagship".
	
`<on her X slot>` = Denotes the required slot that a piece of equipment must be placed in. X = second, third, fourth, fifth. The lack of this term implies that the equipment in question can be in any slot to fulfill quest requirements.
	
`<within the same X>` = Denotes the time period during which specified actions must be completed to fulfill quest requirements. X = day, week, month, etc.
	
`<Fleet Number>` = The number of the required fleet, expressed as first, second, third, fourth. The lack of this term implies that ANY fleet can be used to fulfill quest requirements.
	
`<Rank>` = A given rank.  Valid Ranks are "a S-rank", "an A-rank", "a B-rank", "a C-rank". Implies that the Rank obtained can be at or above the given Rank to fulfill quest requirements.
	
`<Times>` = The number of times an action must be performed to fufill quest requirements. The lack of this term implies that the action must be performed only once; inclusion in these cases may be recommended for the sake of emphasis. Expressed as once, twice, three times, four times, etc.
	
`<Node>` = An expression of the node that is involved in the quest.  Examples: the boss node, node L, the anchor node N.
	
`<Equipment>` = Any piece of equipment, inventory item, or resource. Ranking point rewards are included in this category. Plane proficiency & quantity required are also included here.
* Examples: 5 12.7cm Twin Gun Mount; 1 Ne-type engine; a >> and +max Type 0 Fighter Model 21 (Skilled).
