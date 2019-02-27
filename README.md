# CISC275-Fall2018-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?

The five objects created are:
  1. ArrayList of type Dog named doges
  2. Dog with the name "Fido" and 4 legs
  3. Dog with the name "Fido" and 3 legs
  4. Dog with the name "Alfie" and 4 legs
  5. Comparator of type Animal that implements the compare method

.
3. Can you spot the comparator constructor call? Where is the class definition for the comparator?

The comparator constructor call is within the Collections.sort call. The constructor call is
new Comparator<Animal>(). The class definition is the code that follows from the @Override until
the curly brace before the parenthese that closes the Collection.sort call. The class is
defined all within the Collection.sort method call.
