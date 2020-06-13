# SemanticNetwork
This is a study project which aim to implement Semantic networks and three of its major infering techniques : Mark-Propagation, Inheritance and exceptions.

## Features
* [x] Ability to create a semantic network defined by a set of nodes and relations.
* [x] Mark-propagation algorithm provide the ability to infer solutions - if there's any - to the question concerning the existance of a certain relation between 2 nodes or more.
* [x] Saturate the network (infer everything that can be using Inheritance algorithm).
* [x] Deduce all the properties relating to a specific node.
* [x] Display the network's graph view

## IDE
[Netbeans](https://netbeans.org/)

## GUI editor
[SceneBuilder](https://gluonhq.com/products/scene-builder/)

## Used libraries
- [jfoenix-8.0.8](http://jfoenix.com/)
- [commons-lang3-3.10](http://commons.apache.org/proper/commons-lang/download_lang.cgi)
- [JavaFXSmartGraph-0.9.1](https://github.com/brunomnsilva/JavaFXSmartGraph)

## Procedure

### Choice
When launching the application, this interface is the first interface with which a user will interact, you must chose the algorithm you want to use before building the network.

<p align="center">
<img src="screenshots/1.png">
</p>

### Nodes entry
Define at least 2 nodes by giving a name to each node and click on `ADD`, the added nodes are displayed in the table below where you can delete any node.
  
<p align="center">
<img src="screenshots/2.png">
</p>

### Relations entry
Add at least one relation by specifying its parent/child nodes and its name, the table below as with the interface of the nodes displays all the relations added and gives the possibility of deleting those chosen.
  
<p align="center">
<img src="screenshots/3.png">
</p>

### Graph
After setting up the nodes and relations of our network and clicking on `NEXT`, an interface will appear displaying the generated graph.
  
<p align="center">
<img src="screenshots/4.png">
</p>

### Mark-Propagation
Select two nodes (M1: start, M2: goal) - you can add more nodes if you wish by switching the toggle button for each Mi - you must also specify the relation sought then click on `START` to launch the algorithm.

<p align="center">
<img src="screenshots/5.png">
</p>

### Inheritance
In this interface, the inherited relations are displayed in the text zone above, you can deduct all the properties of a certain node by selecting it from the `ChoiceBox` then by clicking on `START`, a panel of dialog will appear showing these properties.
<p align="center">
<img src="screenshots/6.png">
</p>

## Notes
- Exceptions works only with inheritance algorithm
- To add a relation of type simple exception just give it the name `is_not`
