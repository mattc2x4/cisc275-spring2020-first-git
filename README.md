# cisc275-fall2019-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?
    an ArrayList called dogs
    3 dog objects, fido, fido, and alfie
    and a comparator, typed animal. 


3. Can you spot the Comparator constructor call? Where is the class definition for the Comparator?
    Collections.sort(dogs, new Comparator<Animal>() {
                            ^
    the class definition for comparator:
        Java Util:
        java.util.Comparator<Animal>
        A comparison function, which imposes a total ordering on some collection of objects. Comparators can be passed to a sort method (such as Collections.sort or Arrays.sort) to allow precise control over the sort order. Comparators can also be used to control the order of certain data structures (such as sorted sets or sorted maps), or to provide an ordering for collections of objects that don't have a natural ordering.