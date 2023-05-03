Download Link: https://assignmentchef.com/product/solved-cs112-problem-set-2
<br>
<strong>Problem Set 2</strong>

<strong>Linked Lists</strong>

<ol>

 <li>Assume an <strong>IntNode</strong> class defined like this:</li>

</ol>

public class IntNode {          public int data;          public IntNode next;

public IntNode(int data, IntNode next) {              this.data = data; this.next = next;

}

public String toString() {              return data + “”;

}

Implement a method that will add a new integer before a target integer in the list. The method should return a pointer/reference to the front node of the resulting list. If the target is not found, it should return front without doing anything:

public static IntNode addBefore(IntNode front, int target, int newItem) {

/* COMPLETE THIS METHOD */

}

<ol start="2">

 <li>With the same <strong>IntNode</strong> class definition as above, implement a method that will add a new integer before the last item in a</li>

</ol>

linked list. (In other words, the added integer will become the second-to-last item in the resulting linked list.) The method should return a pointer/reference to the front node of the resulting linked list. If the input linked list is empty, the method should return null, without doing anything.

public static IntNode addBeforeLast(IntNode front, int item) {

/* COMPLETE THIS METHOD */

}

<ol start="3">

 <li>Given the following definition of a StringNode class:</li>

</ol>

public class StringNode {          public String data;          public StringNode next;

public StringNode(String data, StringNode next) {              this.data = data; this.next = next;

}

public String toString() {              return data;

}       }

Implement a method that will search a given linked list for a target string, and return the number of occurrences of the target:

public static int numberOfOccurrences(StringNode front, String target) {

/* COMPLETE THIS METHOD */

}




<ol start="4">

 <li><strong>*</strong> Assuming the IntNode class definition of problem 1, implement a method to delete EVERY OTHER item from an integer linked list. For example:</li>

</ol>

before: 3-&gt;9-&gt;12-&gt;15-&gt;21     after: 3-&gt;12-&gt;21




before: 3-&gt;9-&gt;12-&gt;15     after: 3-&gt;12




before: 3-&gt;9     after: 3

before: 3     after: 3

If the list is empty, the method should do nothing.

public static void deleteEveryOther(IntNode front) {

/* COMPLETE THIS METHOD */

}

<ol start="5">

 <li><strong>*</strong> With the same StringNode definition as in the previous problem, implement a method that will delete all occurrences of a given target string from a linked list, and return a pointer to the first node of the resulting linked list:</li>

</ol>




public static StringNode deleteAllOccurrences(StringNode front, String target) {

/* COMPLETE THIS METHOD */

}

<ol start="6">

 <li><strong>*</strong> Implement a (NON-RECURSIVE) method to find the common elements in two <strong>sorted</strong> linked lists, and return the common elements in <strong>sorted</strong> order in a NEW linked list. The original linked lists <strong>should not</strong> be modified. So, for instance,</li>

</ol>

l1 = 3-&gt;9-&gt;12-&gt;15-&gt;21    l2 = 2-&gt;3-&gt;6-&gt;12-&gt;19

should produce a new linked list:

3-&gt;12

You may assume that the original lists do not have any duplicate items.

Assuming an <strong>IntNode</strong> class defined like this:




public class IntNode {          public int data;          public IntNode next;

public IntNode(int data, IntNode next) {              this.data = data; this.next = next;

}

public String toString() {              return data + “”;

}

Complete the following method:

// creates a new linked list consisting of the items common to the input lists       // returns the front of this new linked list, null if there are no common items       public IntNode commonElements(IntNode frontL1, IntNode frontL2) {

…

}


