Abstraction Layer
================

1. External Layer

Logical Layer Independence

2. Conceptual Layer

Physical Layer Independence

3. Physical Layer - Datastore

Database Objects - Entities that can be used to store and manipulate data. Eg - Tables, Views, Sequences, Indexes, Synonyms

Cost
====
1. Training
2. License, Hardware, Software, Maintenance Cycle, Support from the Vendor End
3. Personnel Cost - Call Center, DBA
4. Data Migration
5. Technological Updates

Entity Relationship Model
=========================

Entity, Entity Type

Attribute
---------
1. Key Attribute
2. Multi Valued Attribute
3. Composite Attribute
4. Derived Attribute

Degree of Relationship - Assossiation between Entity Types
----------------------------------------------------------
1. Unary - One Entity
2. Binary - Two Entity
3. N-ary - More than Two

Cardinality
-----------
1. One To One
2. One To Many
3. Many To Many

Total Participation and Partial Participation
Weak Entity Types

1. Super Class, Sub Class, Union
2. Recursive Relationship, a column becomes a foreign key in that column, referring to the primary key of the same table.

Relations and Attributes
========================

Candidate Key
-------------
A minumum set of attributes that can uniquely identify a tuple is called a candiate key. A candidate key must be unique and not-null.

Super Key
---------
Set of attributes that can uniquely identify a tuple is called a super key. A super key can be constructed by adding 0-n attributes to a candidate key.
Any set of attributes can be a super key, if it uniquely identifies a tuple. In contrast, only minimal super keys are primary/candidate keys. That is, once we remove the columns that are not responsible for it's uniqueness, we get a Candidate/Primary key.

Foriegn Key
-----------
A key which can only take on the values of another attribute is called a Foreign Key.
Referencing Key of a Referencing Table eferences Referenced Key of the referenced table.

Anomalies
=========
1. Insertion Anomaly
2. Updation/Deletion Anomaly

