---
layout: essay
type: essay
title: Application Design on the Mind!
# All dates must be YYYY-MM-DD format!
date: 2018-05-02
labels:
  - Computer Science
  - Software Engineering
  - Design Patterns
  - React
  - Meteor
  - Software Web App Development
  - Group Collaboration
  - Grub n' Go
---
## Know the Feeling of Having Everything in a Project Figured Out Before You get Started? Neither do I.

I've been on many collaborative teams and strategizing or developing an overall design for a project is probably one of the most difficult aspects of the project. Not only does the skeleton of the project need to be created, but you must also consider possible problems that you might stumble across along the way and how to resolve them. Luckily, there are a number of established software engineering <a href="https://sourcemaking.com/design_patterns">design patterns</a> you may choose from to aid you and your team in developing project guidelines that best fits your project’s needs.

## The Three Software Engineering Design Pattern

There are three main software engineering design patterns you can choose from:
1.	Creational
2.	Structural
3.	Behavioral

### Creational Design Patterns
<img class="ui right floated rounded image" src="/images/creationalDP.png" style="max-width: 200px;" style="max-height: 200px;"/>The <a href="https://sourcemaking.com/design_patterns/creational_patterns">creation design pattern</a> focuses on class instantiation or the creation of objects of the class type. This design method aims to reduce any unwanted design complexity by properly controlling the objects created.<br />

### Structural Design Patterns  
The <a href="https://sourcemaking.com/design_patterns/structural_patterns">structural design pattern</a> aims to simplify the design process by understanding the relationships between entities. This design strategy can be further broken down into the following design patterns: decorator and proxy.<br />

#### Decorator Design Pattern
<img class="ui left floated rounded image" src="/images/decoratorDP.jpg" style="max-width: 200px;" style="max-height: 200px;"/>You can think of the <a href="https://sourcemaking.com/design_patterns/decorator">decorator design pattern</a> as functioning similar to that of applying decorations to a Christmas tree. For example, there are many decorations you can add to a tree: lights, ornaments, the star on top of the tree, snow, garland, etc. Each decoration had additional functionality—for example, controlling the on/off switch of the lights. <br /><br /><br /><br /><br />

#### Proxy Design Pattern
<img class="ui right floated rounded image" src="/images/ProxyDP.png" style="max-width: 200px;" style="max-height: 200px;"/> The <a href="https://sourcemaking.com/design_patterns/proxy">proxy design pattern</a> creates a place holder for objects that require a lot of resources. For example, let’s say you want to purchase an item but you have all of your cash in your bank account. You can write out a check to take the place of money you have in your bank for the time being so that you may purchase the item.<br />

### Behavioral Design Patterns
Lastly there are <a href="https://sourcemaking.com/design_patterns/behavioral_patterns">behavioral design patterns</a> which identifies and utilizes communication patterns between objects. There are two types of behavioral design patterns you can consider: interpreter or state.<br />

#### Interpreter Design Patterns
<img class="ui left floated rounded image" src="/images/BehavioralDP.png " style="max-width: 200px;" style="max-height: 200px;"/>The <a href="https://sourcemaking.com/design_patterns/interpreter">interpreter design pattern</a> maybe described as a strategy that takes input, interprets it, then outputs the translation as useful results. For example, you can think of a musician as the interpreter who can read sheet music and translate those notes into actual pitches and sounds represented by sheet music.<br /><br /><br /><br />

#### State Design Patterns
<img class="ui right floated rounded image" src="/images/StateDP.png " style="max-width: 200px;" style="max-height: 200px;"/> The <a href="https://sourcemaking.com/design_patterns/state">state design pattern</a> may be used to control the state of a function and the internal state changes allow certain actions to take place. For example, vending machines can have different states depending on whether money was deposited, inventory, whether change must be returned, etc. <br /><br />

## Grub ‘N’ Go Design Pattern Implementation
For my software engineering I course during the spring of 2018 my team members: [Brian Hoole](https://brianhoole.github.io), [Chaster Mateo](https://haychaster.github.io), [Yubi Peterson](https://notyubi.github.io) and myself, [Victoria Soto](https://victoria-soto.github.io) were tasked with developing an application that assists users at UH Manoa in locating various food options available to them on campus. We collectively agreed upon the name <a href="https://grubngo.github.io/">Grub ‘n’ Go</a>.<br />

I’ll be honest—neither one of my team members nor I considered specific design when organizing the structure of our application. However, after looking back at the code, we did (unintentionally) incorporate some of the design patterns I discussed above. This could be due to the fact that we’ve been sort of hardwired to design in a certain way from the classes we’ve taken.

The design patterns we’ve incorporated include the: decorator
