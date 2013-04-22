Misc stuff, I've acquired over the years
========================================

This repository contains miscellania, I've done or acquired over the years.

Inflection of Latvian nouns
---------------------------

[loc.php](loc.php) contains code (old as the world, of course), which can inflect Latvian nouns, given their
nominative case in singular, and gender. It has its exceptions and shortcomings, but go ahead - fork it and throw a 
pull request at me.

Pupiņvaloda
-----------

Script [pup.php](pup.php) converts Latvian text to so called "pupiņvaloda". It has simple rules, but helps children
to train diction and thinking, since they have to know how to split a word into syllables and memorize last one on
the go, to prepend it with "p".

Transliteration
---------------

[conv.php](conv.php) provides dump transliteration and detransliteration of Latvian text. It does try to keep
capitalization intact while converting. Also, it has a list of some common exceptions (_sheema_ should become 
_shēma_, not _šēma_, etc).
