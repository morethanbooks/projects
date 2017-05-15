# Lord of the Rings Networks

This subrepository contains the files that I have and that I can share to make graphs of the characteres (places and groups) from the books of the *Lord of the Rings*.

I have published some results about this project here: http://www.morethanbooks.eu/graph-network-of-the-lord-of-the-rings/

# Subfolders
## Structure

this files contain three XML-TEI files with some metadata and the structure (books, chapters and paragraphs) of the three books of the *Lord of the Rings* together with the references to each person, place and group (with a sufficient frequency). These files contain no real text because of legal reasons.

## tables

The edges table of each book and one with the sum of all three books. In this project the nodes represent entities (proper names used to reference characters, places or groups) and two of them are connected by an edge if in any paragraph there are references to these two entities. This is how I have defined interaction between character, although like it allways is, life is not so simple.

For example the most frequent interaction between characters is the one between Frodo and Sam. In the three books, there are 533 paragraphs who make references to both of them. And the second one is Frodo and Gandalf with 181 paragraphs.

# Ontologies
This folder contains two tables with basic information about the entities. In pre-ontology.csv the relations between different names and the referenced people (i.e. *Mithrandir* and *Gandalf* are the same person) are defined. Ontology contains the basic metadata about each person together with its identifier (the identifier for Gandalf is "ganda"). This file can be upload as nodes table in graph programs like Gephi.

# Future work
This project was only for fun and I made it while watching *Lord of the Rings*, so I am not offering any kind of support or promises about future steps (altough  it is possible that I will make some changes). It could be improved. What I am publishing here is almost everything that I have about it. 

# Licence
CC-BY

