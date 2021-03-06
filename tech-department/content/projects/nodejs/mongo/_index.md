---
title: Node & mongoDB assignment
ready: true
weight: 2
pre: "<b>2 (alt): </b>"
---

You are required to create a back-end service that will help capture basic information about prospective students who come to inquire here at Umuzi.

## database setup

1. Create a database and name it UmuziProspects
2. Create a collection inside the database and name it Visiter.
3. The collection must contain the following fields :

- id: This should be automatically generated by MongoDB
- visitor name
- visitor's age
- date of visit
- time of visit
- name of the person who assisted the visitor
- comments

## functionality

Create a single index script with the following functions:

- `addNewVisitor`. This should save the Visitor into the database
- list all visitors. This should return an array of all the visitor names and ids
- delete a visitor
- update a visitor
- view one visitor: given a visitor's id, return all information about that visitor
- delete all visitors

## NOTE

You will be expected to properly test your code. You can use whatever testing framework you want. If you use something that isn't taught at Umuzi please justify your choice (if you found something cool we might incorporate it into the syllabus)

## Resources

{{% contentlink "topics/js-and-node-specific/mongodb" %}}
