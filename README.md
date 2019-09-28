# StormCube
Storm_Cube, the cube where everyone drafts storm
this project is aims to have 3 initial features
a framework that creates selects cards from a list to form 
archetypal cores in a draft

As of 9/28/19 the current design is for each pack is 15 cards, with 6 types of cards that can be included
Power Cards are cards that find themselves in every deck and super easy to splash (lotus, moxen)

Lands (L) are for fixing, but some archetype lands make their way into this slot (afford me the knowledge of fixing pls, Dark Depths)

uncommon archetype cards (UC) are cards that require a hard commmit to a specific archetype (Glimpse of Nature, KCI)

common archetype cards (CC) are cards taht suggest a particular archetype, but are flexible to see their way into others (Llanowar Elves, Grizzlebrand)

enablers(E) are less powerful versions of power cards. They're super splashable and generally allow for chaining of spells in a single turn (Dark Ritual, Ponder)

Interaction cards (I) are there to make the cube not a race among ships passing into the night. (Ethersworn Cannonist, Thoughtseize)

Storm cards (S) are cards with storm. this is extremely narrow, but they are almost all archetype based anyway, so their inclusion isn't hard to justify. Also includes stuff that functionally has storm in some way (Tendrils of agony, Aetherflux Resiviour)

Signaling cards (G) are cards taht require super heavy build around to make work and their inclusion will be optional and on a future build of this project(Sram)
    

15. Land
14. Power card
13. Uncommon archetype card
12. Uncommon archetype card 
11. Storm card
10. interaction card or enabler
9. interaction card or enalber 
8. enabler or common archetype
7. enabler or common archetype
6. enabler or common archetype
5. enabler or common archetype
4. enabler
3. enalber
2. enalber
1. enalber

Each archetype in the cube is defined, there is some planned overlap planned. 
The high level framework 

UI elements : drafter and archetype selector
Users will select an archetype that they thinkk would be fun to draft, however this only selects the archetype for drafting
it does not mean they will draft this archetype. Drafting is done after the selectors form the pact

Pack Sloter 
recieves the cores from each pack and then shoves them into one of the slots among the 3 packs per player.
dual slots are chosen based on a seed. this might change in future releases 

Archetype selector 
selects uncommons and common archetype cards that have a high degree of overlap based on selected archetypes
changes based on color balence, and type balence are future releasses

storm selector 
selects storm cards that fit the archeytpes and excludes ones that are not (no astral steel if there are 0 creature archetypes)

enabler selector 
selects enablers by archeytpe overlap. 

interaction selector
selects interaction by enabler or archetype restrctions 

power card selector 
selects power cards based off seed. These are super flexible and could probably go into any deck

land selector
selects lands in proportion to the spells being cast. 
