---
layout: post
title:  "Journal #One [DAT601]"
author: d-stephenson
categories: [ DAT601, Journal, Database Design & Administration ]
image: assets/images/conceptualDiagram.png
featured: true
hidden: true
---

JOURNAL #ONE [DAT601]

Learning Summary<br>

<u>WHAT</u>

Class sessions have involved group work surrounding the development of a Conception Model Entity Relationship Diagram (ERD) for an online tile game that our group have called 'Game of Tiles'.

In class sessions we have looking at the structure of the ERD specifically the notations and symbols involved in conceptual visualization of a relational database.

A Conceptual ERD is used to present a high level view of the business system or organisation. It is used to define the business objects involved, listed as Entities and shoe the relationships between the Entities. 

<i>N.B. Research carried out into Conceptual Diagrams show there is disagreement as to whether Attributes and Cardinality should be included at this level. Sources show attributes and Cardinality being introduced at the Logical level.</i>

<i>Guide to the ERD:</i>

Entity = Rectangle or Square<br>
Attributes = Oval<br>
Relationship = Diamond<br> 

<b>Entity:</b>

An entity is a definable or major element, commonly a noun, that is represented in the database. This could be an object or a person, a concept or event. The entity is the first consideration when looking at database design.

<b>Attribute:</b>

An attribute is something that characterizes the entity. For example in the case of 'Game of Tiles' we have a entity of 'Skill', the attributes related to the entity are skills that can be used by the Characters in the game.

<b>Relationship:</b>

Relationships signify a link between two entities. For example in the case of 'Game of Tiles' Character has a relationship with Player. The Player plays the Character and the Character is played by the Player. 

<b>Cardinality:</b>

Cardinality looks at the number of occurrence's or the potential occurrence's between entities that have a relationship. For example in the case of 'Game of Tiles' a Character can play 1 Game, but a Game can have many (m) Characters.

There are three cardinal relationships discussed in class that are used in the ERD: 

<i>1 to 1:</i> Can split an entity such as Player and Character to make the data easier to understand.

<i>1 to Many (m):</i> A sole instance of one entity relates to many of another entity.

<i>Many (m) to Many (n):</i> Many instances of one entity relates to many of another entity.

<u>WHY</u>

Creating ERDs is extremely useful when trying to understand how a business system or organisation functions. 

ERDs allow all users or potential users of the system to visualize who the entities are interacting with the data system, what the relationships are between the entities and what attributes are associated with the entities. The development team can use the diagram to determine what the technical requirements are of the software and what data is required.

Fundamentally ERDs help stakeholders of the system, in conjunctions with other diagramming techniques, to create a visual image of how the data in the system is connected in a very general way so that multiple user groups can review and provide input based on their perspective.

<u>HOW</u>









