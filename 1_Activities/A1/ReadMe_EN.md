# Activity "A1" : Define the scope of the application

## Goal
It is a question of defining the perimeter that the application will "embrace" and consequently the "surface" that it will cover, ...   
... in other words are "What?" business, what it will do (regardless of how it does it).

### Why do it ?
If we don't clearly define what it must be done, then when we try to develop the application we will be confronted with the problem of "finding a solution" (the How ?) to "a situation" (the What ?) that has never - really - been defined !

### How to do it ?
2 different but complementary ways allow to contribute to the definition of the __perimeter__ of an application.
* The 1st one, based on the description of __concrete use cases__ is very pragmatic and allows from the beginning to start building a test base (= for the "recipe").
* The second one, based on the definition of __business activities__ (connected to each other to constitute a global __business process__) is more theoretical (because instead of basing on counterpart elements, it implements more abstract types of elements). 

## Mantra
The best advice for this activity is probably the following: 
> Define - as far as possible - the activities in terms of __end__ (and NOT in terms of __mean__ )

![BizSpecFctSpec](https://github.com/iPlumb3r/BizApp-Spec-Methodo/blob/master/_Images/BusinessSpecifciation_VS_FunctionalSpecification.png)

The difficulty experienced by customers in "getting back to the business" during the expression of need is well illustrated by Henry Ford's famous phrase: 
> If I had asked my customers what they needed, they would have said "a horse that moves faster" ;-)

## Deliverable(s)
### Use Case :
This is a textual and/or graphic description representing an emblematic situation of the problem to be supported by the computer application. Each particular situation must be described separately in order to "pave" the whole territory "to be covered".

### Business activity sheet / business processes
This is a set of __Business Activity__ sheets that, taken as a whole, make it possible to create a map of "Who carries out what activity for what purpose" (Otherwise called __Business Process__).
 
## Notions Keys
The central notion for this activity is the notion of __BusinessActivity__ (Cf <a href="https://github.com/iPlumb3r/pEAr4pEEr/blob/master/1_Semantic/Conceptionary/%23BusinessActivity.md">#BusinessActivity</a>) which : 
* is carried out by 1 (or more) __BusinessRole(s)__ (Cf <a href="https://github.com/iPlumb3r/pEAr4pEEr/blob/master/1_Semantic/Conceptionary/%23BusinessRole.md">#BusinessRole</a>)
* Consumes 1 (or more) __BusinessObject(s)__ (Cf <a href="https://github.com/iPlumb3r/pEAr4pEEr/blob/master/1_Semantic/Conceptionary/%23BusinessObject.md">#BusinessObject</a>)
* and product 1 (or more) __Business Object(s)__

Other related concepts: <a href="https://github.com/iPlumb3r/pEAr4pEEr/blob/master/1_Semantic/Conceptionary/%23BusinessProcess.md">#BusinessProcess</a>, <a href="https://github.com/iPlumb3r/pEAr4pEEr/blob/master/1_Semantic/Conceptionary/%23BusinessConcept.md">#BusinessConcept</a>, <a href="https://github.com/iPlumb3r/pEAr4pEEr/blob/master/1_Semantic/Conceptionary/%23BusinessSubject.md">#BusinessSubject</a> are defined in the Conceptionary of the pEAr4pEEr initiative: https://github.com/iPlumb3r/pEAr4pEEr/tree/master/1_Semantic/Conceptionary

## Semantic Model
The __Business Activities__ fall within the context of the following semantic model:    
![SemanticModel](https://github.com/iPlumb3r/pEAr4pEEr/blob/master/images/BusinessProcess_2020-05-05.png)
