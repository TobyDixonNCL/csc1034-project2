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
  