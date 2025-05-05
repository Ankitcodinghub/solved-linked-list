# solved-linked-list
**TO GET THIS SOLUTION VISIT:** [SOLVED:Linked list](https://www.ankitcodinghub.com/product/solvedlinked-list/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;2975&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SOLVED:Linked list&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Singly Linked List. Start by creating a singly linked list to use as your data structure for

this task. In addition to the head field that we practiced with in class, you will also maintain a tail

field. Include the below standard linked list features/methods in your class, which you should call

HiScoresLL. Code up all the method headers exactly as given below.

Basic features of HiScoresLL:

 head and size fields, which we learned about in class and reading

 A tail field that references the last node in the list (akin to the head field)

Keep in mind:

o This field must be used/maintained/updated during operations like removing and adding

nodes in case the last (or only) node is removed or a new node is being added to the end of

the list.

o Keep in mind the end of the list could be the same as the beginning of the list if there is only

one item in it.

o It is initially set to null, when the list is empty, just like the head field.

 A constructor method – creates a new empty linked list

/**

* Constructor that creates an empty list

*/

public HiScoresLL() {

 A display() method – outputs all the high score entries in the list. Remember, GameEntry

objects come with a toString() method (see its definition in the GameEntry class) so you can

directly print a GameEntry object e simply with System.out.println(e).

/**

* Prints out all the game entries in the linked list

*/

public void display(){

COM212 Data Structures Fall 2014

 An addFirst(Node v) method – adds the node v to the front of the list

/**

* Add a node to the head of the list

* @param v

* the Node object to be added

*/

public void addFirst(Node v){

 A removeFirst() method – removes a node from the front of the list

/**

* Removes the first node and returns it,

* this method assumes the list is non-empty

* @return

* the Node that was removed

*/

public Node removeFirst(){

 An addLast(Node v) method – adds the node v to the end of the list. Note: now that we have

a reference to the tail of the list, this method can be implemented in constant time!

/**

* Add a node to the tail of the list

* @param v

* the Node object to be added

*/

public void addLast(Node v){

Doubly Linked List. Create a second program that achieves the same goal as your first

one, but uses a doubly-linked list rather than a singly-linked list. You will need to first create a DNode

class, which you can base on the Node class, that will have an extra field (called prev) for the backward

pointer. DNode is the class you will use to build your doubly linked list. The name of your doubly-linked

list class should be HiScoresDLL and it should be saved in a file called HiScoresDLL.java.

For this program, you needn’t write all the “basic functionality” methods that you did for the singlylinked

list. (This is due to the more general nature of the header and trailer fields in a doubly-linked list,

which we will learn about in class and reading. No special cases to check this time!) So, after creating

the fields and the constructor method, you can go directly to writing the add(GameEntry e) and

remove(int i) methods. Warning: you might be tempted to try copying and pasting from the

methods you wrote above, then modifying the code. However, these methods in a doubly-linked list

class are significantly different, and more streamlined. You should write them from scratch rather than

confuse things by trying to reuse old code. If you find yourself creating code that seems more unwieldy

or complicated than the corresponding code for Part A, then you are going in the wrong direction. Part

B’s code, done well, should be much more compact and elegant, not less. (No special cases needed!)
