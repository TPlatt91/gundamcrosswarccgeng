Errors:
* DO NOT try to change type of multicolor cards, can result in crash, despite options being disabled.

Problems:



Missing Features:
* Autosort (2.0)


Alternate Styles:
* Units exist with *mid* and *max* line styles with no ryme or reason - most noticeable difference: the group of small lines on the left you see on crew cards.
* 3 different Collection/Promo/Rare Style:
	* No-Top-Corner Unit (PR-T001 / PR-U001 to PR-U039) - Identical to normal Unit, but no "top corner"

	* Goldframe Unit (BT06-097-CR / PR-U040) - Note: Colored ATK/DEF text; Golden circles around ATK/DEF; gold lines, bottom and title bar.
	* Goldframe Crew (BT01-148-CR / PR-C007 to PR-C012) - Note: Shares Goldframe Unit's gold lines, bottom and title bar. No Bottom Color field. Quote as *calligraphy*.

	* Transparent-Frame Unit (BT06-077) - Note: White ATK/DEF strength text


==========================================================
Version 0.9.3
Flavortext has variant of card-color (much lighter / card colored dropshadow) & Unit ATK/DEF have Unit Colors
* > implemented

Warship Circles lack text
* > implemented

Version 0.9.2

2nd Yellow dropshadows and bad alignment of dropshadows, tertiary Rule misaligned.
* > Re-written dropshadows from 0.

Version 0.9.1

Collectors Number way too large, too wide Font
* > Other font, new position, shrunk.

Artist / Illus: Text is not readable due to font selection
* > New Font with backdrop blur (Covid19, in the GundamCrossWars.fonts folder)

Text Boxes overlap some rings, even with line breaks and spaces inserted
* > Bottom edge realigned, font allowed to downsize to 12

Trait Box does not scale with text
* > Trait now shrinks width of text to conform to box 

==========================================================

Resolved (0.9): 
* Card Layouts v2
* Set Name needs to start *more left* (Warship-style on non circled, at the ATK circle for Units/Pilot/Crew)
* Illustrator at right edge, above Size/type marker, Top to bottom, Aligned at Bottom corner, Black text, white aurora
* Event: only single textbox center formated
* Crew: single textbox center formated on single color crew
* Crew: rule line on multicolor Crew
* Pilots & Armament with Tertiary Rule 
* Promo Warship PR-W001 uses normal Warship Style
* Added missing Red Token & Green Bridge Abilities
* 0 cost icon with 0
* Swapping card type after swapping to multicolor throws an error.
