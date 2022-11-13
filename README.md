COP3330C Module 6 Programming Assignment

Implement the Abstract Animal Factory in Demonstration 1 of Ch. 4 in
Java Design Patterns, 3rd Ed. (Sarcar, ISBN 978-1-4842-7970-0).

Add an Elephant interface with a "showMe" method where the elephant
describes their activities in their preferred habitat and an 
"inviteDog" method where the elephant describes where they might
observe a (wild or pet) dog depending on their own classification
as a wild elephant or a pet elephant.

After creating each set of animals (wild dog, wild tiger, wild elephant), 
(pet dog, pet tiger, pet elephant), add the objects to a Collections
Stack and LinkedList, respectively. Once each animal has described itself,
use a while loop to remove each element from the Stack (use the pop method)
and display it, then do the same with the LinkedList.

**Sample output:**  
  
You opt for a wild animal factory.  
  
A wild dog with white color is created.  
A wild tiger with golden and cinnamon color is created.  
A wild Elephant with grey color is created.  
The wild dog says: I prefer to roam freely in jungles.  
The wild tiger says: I prefer hunting in jungles.  
The wild tiger says: I saw a wild dog in the jungle.  
The wild elephant says: I prefer bathing in the river.  
The wild elephant says: I saw a wild dog in the jungle.  
Here is the list of wild animals:  
wild elephant  
wild tiger  
wild dog  
  
************  
  
You opt for a pet animal factory.  
  
A pet dog with black color is created.  
A pet tiger with yellow color is created.  
A pet Elephant with grey color is created.  
The pet dog says: I prefer to stay at home.  
The pet tiger says: I play in an animal sanctuary.  
The pet tiger says: I saw a pet dog in my town.  
The pet elephant says: I prefer walking in a sanctuary.  
The pet elephant says: I saw a pet dog in a car.  
Here is the list of pet animals:  
pet dog  
pet tiger  
pet elephant  
