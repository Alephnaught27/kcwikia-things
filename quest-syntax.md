# Kancolle Wikia Quest Syntax / Grammar
## Preface
* This is a general quest description grammar, meant to cover 99% of cases.
* The purpose of this is to establish consistancy amongst quest descriptions. Many older descriptions contrasted greatly in wording between eachother, and some of them were worded oddly or ambiguously, which only served to cause confusion. This aims to eliminate that going forward.
* There will, for sure, be quests that have requirements that do not fall into this grammar. In those edge cases, follow the grammar as strictly as possible while including the variant requirements.
* `<>` denotes terms that are not to be taken literally and are defined in the glossary. Examples of each are given where applicable, more will be added as needed.

## Composition

`Have (ONLY) <Ship> (<as flagship>, <Ship> <as second ship>, ... , and <Ship>) in your <fleet number> fleet.`

## Sortie

`Sortie [a/the <fleet number> fleet] with <Ship> (<as flagship>, <Ship> <as second ship>, ... , and <Ship>) to World(s) X-X(, X-X, ... , and X-X).  (Obtain <Rank> at <Node> (at X-X) <times>) (or) (Reach <Node> <times>, whichever is applicable).  (Obtain...) ...`

* Use multiple "Obtain" statements for maps that have lots of specific requirements.  A quest that involves 1-6 does NOT necessarily require mutliple "Obtain" statements, as reflected in the grammar.
* X-X is a placeholder for a world ID, they should be filled in as needed and should link to the respective world page.

## Exercise

`(Use a fleet with <Ship> (<as flagship>, <Ship> <as second ship>, ... , and <Ship>) to) (Obtain <Rank>/Participate) in Exercises <times> (<within the same X>).`

## Expedition

`Complete (X) Expedition(s) X <times> (<within the same X>).`

## Supply/Docking Quests

[  ]

## Arsenal

### For crafting quests
`Craft (a (piece) / X (pieces)) (of) (ship(s)/ equipment).`

### For scrapping quests
`[Scrap/Dismantle] (a (piece) / X (pieces)) (of) (ship(s)/ equipment).`

### For item conversion/creation quests
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

## Modernization

[  ]

## Marriage

Refer to applicable sections above.

## Rewards

### For quests with no choices
```
<Equipment> xX
(...
<Equipment> xX)
```

### For quests with only choices
```
choice between
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
* Non-choice rewards first, followed by choice rewards.

## Glossary
`X` = Generic placeholder for integer values. X's inside of <>'s are NOT equivalent, see below.

`()` = Denote terms that are not included in every description, but should be included when appropriate.

`[.../...]` = Use the term either on the left or right side of the '/' for this description.

`<Ship>` = Either a specific or nonspecific ship name
* specific: Kawakaze Kai Ni; Maya Kai or Maya Kai Ni
* nonspecific: 2 ships; 2 CL; 3 level >=70 Yuugumo-class DD; 2 additional ships; at least 3 DD or DE.
	
`<as flagship>` = Denotes that the given Ship must be the flagship of the given fleet.
	
`<as X ship>` = Denotes the required position in the fleet for the given ship. X = second, third, fourth, fifth, sixth.
	
`<on her X slot>` = Denotes the required slot that a piece of equipment must be placed in.  X = second, third, fourth, fifth. The lack of this term implies that the equipment in question can be in any slot to fufill quest requirements.
	
`<within the same X>` = Denotes the time period during which specified actions must be completed to fulfill quest requirements.
	
`<fleet number>` = The number of the required fleet, expressed as first, second, third, fourth. The lack of this term implies that ANY fleet can be used to fufill quest requirements.
	
`<Rank>` = A given rank.  Valid Ranks are "a S-rank", "an A-rank", "a B-rank", "a C-rank". Implies that the Rank obtained can be at or above the given Rank to fufill quest requirements.
	
`<Times>` = The number of times an action must be performed to fufill quest requirements. The lack of this term implies that the action must be performed only once; inclusion in these cases may be recommended for the sake of emphasis. Expressed as once, twice, three times, four times, etc.
	
`<Node>` = An expression of the node that is involved in the quest.  Examples: boss node, node L, anchor node N.
	
`<Equipment>` = Any piece of equipment, inventory item, or resource. Ranking point rewards are included in this category. Plane chevron specfications & quantity required are also included here.
* Examples: 5 12.7cm Twin Gun Mount; 1 Ne-type engine, a >>'d and +max Type 0 Model 21 (Skilled).
