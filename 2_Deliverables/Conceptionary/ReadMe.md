Conceptionary
==

What is a Conceptionary ?
-
A __Conceptionary__ is a "flat" list of __Concepts__ relevant for a given __Knowledge Domain__ characterized by useful associated informations.

> A __Conceptionary__ is like _"a stone in the middle of the river"_ in the process of building an __Ontology__.   

__Important note__ :   
Each entry of the conceptionary is NOT a #Term ...   
... this is a #Concept   
> A __Conceptionary__ is somewhere a kind of "inverse __Dictionary__"

Cf <a href="https://www.semanticarts.com/the-importance-of-distinguishing-between-terms-and-concepts/">The Importance of Distinguishing between Terms and Concepts</a> 


How to build a Conceptionary ?
-
Building a __Conceptionary__ consist in defining for each __Concept__ a kind of "ID Card" with the following fields :

<table>
    <thead>
        <tr>
            <th>Conceptionary Entry</th>
            <th>Card (Min-Max)</th>
            <th>Comment</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Concept ID</td>
            <td>1-1</td>
            <td>Could be a number, a ramdom alpha-numeric chain or an EnglishCamelCase "word"</td>
        </tr>
          <tr>
            <td>============</td>
            <td>And For Each Language</td>
            <td>============</td>
        </tr>
        <tr>
            <td>Prefered Label</td>
            <td>1-1</td>
            <td></td>
        </tr>
        <tr>
            <td>Alternative Label</td>
            <td>0-N</td>
            <td></td>
        </tr>
        <tr>
            <td>Description</td>
            <td>1-1</td>
            <td>The description must refers to others concepts (via the Concept ID) in order to prepare the work for building the future ontology</td>
        </tr>
        <tr>
            <td>Comment</td>
            <td>0-N</td>
            <td></td>
        </tr>
        <tr>
            <td>Example</td>
            <td>3-7</td>
            <td>Some representative individuals/instances of the concept</td>
        </tr>
    </tbody>
</table>

How this help for building an Ontology ?
-
Less formal than an __Ontology__, the __Conceptionary__ let appears future formal relations - in a textual flavor - inside the description section.

An example
-
An exemple of a __Conceptionary__ could be see here :
* <a href="https://github.com/iPlumb3r/EcosystemMapping/tree/master/1_Semantic/Conceptionary">Root</a> of the Conceptionary   
* <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Agent.md">Info Card</a> for the Concept identified as "@Agent"   
=> You can see here than the "Description" of the __Concept__ referes to others __Concept(s)__ of the __Conceptionary__ ...   
... and you can navigate through those links in order to see the "Description" of the targeted __Concept(s)__ !

__Note__ : GitHub is OK for publich the final version of an already built __Conceptionary__, but not for building it !!!


Which tool to use ?
-

Traditional "Office" applications (such as Word, Excel, Power Point, Mind Manager, ...) are not very suitable for building a __Conceptionary__, just because main requirements are : 
   - Concepts can be linked easily
   - Allow Collaboration
   
 
 Seems that the best tool which answer to both requirements is <a href="https://roamresearch.com/">Roam</a>    
 (You need to create 1 Roam Note for each Concept => Do NOT describe several Concepts in the same Roam Note)

Template/Example : 
* Roam Note 1 : <a href="https://roamresearch.com/#/app/EntangledBootstrap/page/1fZzExIam">Template</a>   
* Roam Note 2 : <a href="https://roamresearch.com/#/app/EntangledBootstrap/page/S5u8LXV2A">Example</a>  

> By creating new Roam Note, with the name of already used Concept, Roam will automatically propose to make a link ...
  
 
 
