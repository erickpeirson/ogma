Notes on relation model
=======================

Without annotations
-------------------

Given two entities with text positions, are they related?

* categorical[sent,para,page,arti] - proximity

If they are related...

* categorical - part of speech
* scalar - distance from entities
* scalar - transition probability for NER category of first entity?

With annotations
----------------

add...

* scalar - transition probability (to) for Conceptpower category of first entity?
* scalar - transition probability (from) for Conceptpower category of second entity?
* 