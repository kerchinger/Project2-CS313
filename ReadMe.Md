    Questions:
		 -LinkedList (TestIterator) - does it make any difference?
          The linked list is slower is the testEmpty and testAverageValues test of the testIterator.Java code.This is because linked
           lists are not a defined set of values like an array list. So finding whether or not list is empty takes longer because the
           linked list has to go and find values, vs the array list just having the prebuilt length of the list in its function. IN the
           TestIerator performance area array lists seem to be the better choice.

         -LinkedList (TestList) - does it make any difference?
           The linked list's performance shows that it is faster at adding numbers, checking if a number is in the list, and slower at and slower at
            setting up. This just shows that linked list takes a little more to set up because it has a node, and linker nodes. Further, it shows
            that linked lists are advantageous for adding numbers (linked list are not bound by having only a certain number of values), and
            checking/searching for numbers because its pretty fast in iterating through the list, which array list is also pretty fast at as well.

         - In the TestList the performance of a linked list seems to be a litter better.
            The program does not run, this is because list.Remove(77) removes the value at an index of 77, so when the program runs
            it says the index is out of bonds because there is nothing at an index of 77.

        - which of the two lists performs better as the size increases?
            Based off of the Graph, the arrayList is better at adding and removing elements, where the linked list is better at accessing the elements
            as the size increases.