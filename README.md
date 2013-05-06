camxes.js
=========

Lojban Parser written in JavaScript. Based on camxes.

ChangeLog:
* 4/29/2013: Initial commit. camxes.js.peg -> A PEG for PEG.js. Currently it's too slow (both to compile a parser and to parse a sentence)
* 5/2/2013 : Updated the PEG for clearer parse trees. Use the "Use results cache" option for PEG.js for faster search. 
* 5/3/2013 : Finished up until COI
* 5/4/2013 : Finished writing the whole basic parser - checked up until JOI
* [FIXED 5/4/2013] [TO DO] zei (strange behavior of gismu)
* [FIXED 5/4/2013] [TO DO] remove dangling nodes (e.g., tail_terms) 
* 5/6/2013 : Fixed some bugs related to SI, removed empty nodes (intro_null, text_part_2, etc.)

