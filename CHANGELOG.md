# CHANGELOG

* v1.1.0 [2019-11-08]: Added a SmartAI computer opponent.
  Added strategy players.SmartAI
  None of the bugs have been fixed.

* v1.1.0 [2019-10-25]: First major release.
  This version is known to contain some bugs.

* v1.1.1 [2021-01-14]: Bug Fix. Fixed Syntax Error in players.py
  at line 50. Missing parentheses.
  
* v1.1.1 [2021-01-14]: Bug Fix. Fixed game not starting in switch.py. Added
  declaration of object game and added parentheses onto the end of
  function call.
  
* v1.1.1 [2021-01-14]: Bug Fix. Fixed Type Error in switch.py. Changed
  parentheses to square brackets at line 52.
  
* v1.1.1 [2021-01-14]: Bug Fix. Fixed Attribute Error in switch.py. Changed syntax when
  creating players so that name is a parameter when choosing class type from player_classes. 
  
* v1.1.1 [2021-01-14]: Bug Fix. Fixed Name Error in user_interface.py. Changed for loop
  at line 113 to use i instead of card.
  
* v1.1.1 [2021-01-14]: Bug Fix. Fixed Type Error in user_interface.py. Swapped idx and player
  in the enumerate statement so that idx would point to the index and player would point to the player.
  
* v1.1.1 [2021-01-14]: Test Fix. Fixed test case that checks initial values of flags. Self.draw4 changed to
  initially be False instead of true.  
  
* v1.1.1 [2021-01-14]: Test Fix. In cards.py, removed duplicate card number (2) from the list of
  possible values for a cards number. This resulted in stock pile being larger than it should be.
  
* v1.1.1 [2021-01-15]: Test Fix. In switch.py set draw4 to True if the card discarded is a Queen.

* v1.1.1 [2021-01-15]: Test Fix. in switch.py return True for can_discard if card value is in 'QA'.

* v1.1.1 [2021-01-15]: Test Fix. In test_switch.py check can_discard for Queens instead Kings when testing if 
  Queens can always be discarded.
  
* v1.1.1 [2021-1-21]: Syntax Error fix. In switch.py at line 97, changed "self.direction == 1" to 
  "self.direction = 1" when setting the game flags to their initial value.
    
* v1.1.1 [2021-1-21]: Syntax Error fix. In switch.py at line 79, changed print winner of game from 
  "self.players[1]" to "self.players[i]".