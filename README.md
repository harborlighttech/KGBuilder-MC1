# KGBuilder-MC1
Speed Presentation

## Table of Contents

1. [Problem & Use Cases](#1-problem--use-cases)
2. [Proposed Schema Elements](#2-proposed-schema-elements)
   - [Conceptual Model](#conceptual-model)
   - [Ontology](#ontology)
3. [Identifier Strategy](#3-identifier-strategy)

## 1-Problem & Use Cases

### Problem 
Existing bookmarking tools like Pinterest and browser favorites save web links but fail to organize them around the ideas they support—whether insights, decisions, or hypotheses. Over time, I remember my conclusions but cannot easily trace which sources informed multiple ideas, identify authors, or recall dissenting perspectives, making it difficult to reconstruct my evidence-based thinking or recognize cross-referenced content.

I want to create a knowledge graph that helps me accomplish two main objectives:

1) organize & annotate information in a way that builds up to how I view it supporting an idea, hypothesis or decision;
2) be able to start by formulating an idea, hypothesis or decision and build the supporting data as I progress.

#### Scenario/Industry

I've built a couple of application ontologies in the past, and I wanted to take a stab at something higher-level. I am looking to develop some pattern that can be applied across multiple industries. For this exercise, the scenarios I've chosen are 

1. Decision-making - in software development, there is a strategy called Architectural Decision Records (ADRs) that are typically used in Git repositories that summarize decisions made by a team  that are hard to decipher by reading an issue - especially lengthy issues. As a new person to the repository, it's hard to understand who the voices of authority and influence are, what pieces of content can be ignored, etc. An ADR is a summary of all this content (example: https://github.com/ESIPFed/science-on-schema.org/tree/main/decisions)

### Use Cases

1. Who are the top 5 people that contributed to my belief in that the "4% rule" is an effective retirement withdrawal strategy?
2. What are all the decisions asserted by myself having any dissenters that supported the decision to invest in "data-centric architecture" that are stored in Github?

## 2-Proposed Schema Elements

### Conceptual Model
![Conceptual Model](KGC-MC1-conceptual-model.png)
![Graphical Notation](KGC-MC1-graphical-notation.png)

### Ontology

[Ontology (ttl)](ontology.ttl) - here is a Turtle file built using Protege. 

![Protege](protege.png)


## 3-Identifier Strategy
