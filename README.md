# Neo4Stock
graphs4good community.  In repy to Neo4j idea, we decided to share a neo4j Stock managment graph database

Goal:
Easy sharing stock managment between entities (medical or not)
or more simply medical resources sharing, availability announcement, second-hand product proposal.

use case:
"National management of strategic stocks of health products"
"National health threat response plans" 
An incoming scandal about wrong stock managment.


Core is already done, but this particular using need to be inproved.

First needing is real use case to define main caracteristics adapted to medics.


Function:
today, manufactured product is defined by a BOM (Bill of Materials). Any BOM components can be replaced or own made.
An so, Stock become a hierarchical functionnal component grouping. Referencing need to target each BOM component, similar or merging of any parts of defect materials.

First special needing in medical is the ability to share stock and discover available components in other partner entities.

This goal is easy for graph database !

we will add state, cost, comments and others contact informations about each product referenced in.

Why don't use this for bed sharing between hospitals ?

At now, we work about web interfacing.
