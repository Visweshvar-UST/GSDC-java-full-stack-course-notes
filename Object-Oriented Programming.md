---


---

<h4 id="java-oops-concepts">Java OOPs Concepts</h4>
<ul>
<li>methodology or paradigm to design program</li>
<li>bottom to up approach</li>
</ul>
<p>inheritance: IS-A generalization relationship</p>
<ul>
<li>single, multi level, hierarchical</li>
<li>compile time and runtime polymorphism</li>
<li>abstraction hiding implementation and provide features</li>
<li>encapsulation using scopes</li>
</ul>
<h4 id="classes-objects-methods">Classes-Objects-Methods</h4>
<h4 id="more-on-classes-objects-methods">More-On-Classes-Objects-Methods</h4>
<p>access modifier - default, public, private, protected</p>
<h4 id="array-of-objects-in-java">Array of Objects in Java</h4>
<p>Class-Name[] Var-Name = new Class-Name[size];</p>
<h4 id="class-constructors">Class Constructors</h4>
<ul>
<li>same name as class name and no return type</li>
<li>if we define any constrictors the java wont provide default constructor</li>
</ul>
<h4 id="java-this-keyword">Java this Keyword</h4>
<ul>
<li>used to avoid instance variable hiding, to call constructor from another constructor<br>
e.g. this(Argument); - and it should be the first statement and cant call more than 1 this call</li>
<li>cant use this keyword in static method</li>
</ul>
<h4 id="final-keyword-in-java">Final Keyword in Java</h4>
<ul>
<li>can use with variable(constant), method (to stop overriding), class(restrict extends)</li>
</ul>
<h4 id="passing-objects-to-methods">Passing Objects to Methods</h4>
<h4 id="java-inheritance">Java Inheritance</h4>
<h4 id="compile-time-polymorphism-vs.-runtime-polymorphism">Compile-time Polymorphism vs. Runtime Polymorphism</h4>
<h4 id="abstract-class-in-java">Abstract Class In Java</h4>
<h4 id="interface-in-java">65. interface-in-java</h4>
<ul>
<li>can achieve multiple inheritance</li>
<li>implement intef1, interf2 is correct</li>
<li>no constructor, only method signature, no access specifiers, no static member</li>
<li>loose coupling</li>
</ul>
<h4 id="polymorphism-in-java">66. Polymorphism In Java</h4>
<h4 id="what-is-encapsulation-in-java">67. What is Encapsulation in Java</h4>
<ul>
<li>restricting the member variables</li>
<li>and we can use getter and setter to assess the secured private members</li>
</ul>
<h4 id="what-are-packages">68. What-Are-Packages</h4>
<ul>
<li>structuring the code base</li>
</ul>
<h4 id="nested-and-inner-class">69. Nested-And-Inner-Class</h4>
<ul>
<li>syntax</li>
<li>outerClass outObj = new outerClass();</li>
<li>outerClass.innterClass inObj = outObj.new InnerClass();</li>
</ul>
<h4 id="java-threads-multithreading">70. Java-Threads-Multithreading</h4>
<ul>
<li>it is light weight sub process</li>
<li>thread lifecycle : new, runnable, waiting, running, terminated</li>
<li>extending thread class, extends runnable</li>
<li>extends the class thread and use obj.start() method to start</li>
<li>extends the class and implements the runnable class</li>
<li>runnable is loose coupling</li>
<li>!!! while 2 threads are using the same object in that it will parallelly works on the object but what we want is it should accept request from multiple threads but it should execute for one thread after other : for that we can use obj.join() or synchronized keyword before method !!! SYNCHRONIZED</li>
</ul>
<h4 id="exception-handling">71. Exception-Handling</h4>
<ul>
<li>errors are unchecked type but the exceptions are both checked and unchecked types are there</li>
<li>throwable (error(jvm, memory framework), exception)</li>
<li>arrayIndexoutofbowndry, nullpointer, numberformat, arithmetic,</li>
</ul>
<h4 id="wrapper-classes">73. Wrapper-Classes</h4>
<ul>
<li>java is 99.9% object oriented because of primitive types</li>
<li>autoboxing unboxing</li>
</ul>
<h4 id="what-is-the-java-collection-framework">74. What is the Java Collection Framework</h4>
<ul>
<li>collection api has interfaces , implementation ,  util functions</li>
</ul>
<h4 id="java-collection-framework-hierarchy">75. Java Collection Framework Hierarchy</h4>
<p><img src="https://flycoolman.com/coding/java/java-collection/featured.png" alt="Java Collection | flycoolman"></p>
<h4 id="what-is-list">76. What is List</h4>
<ul>
<li>.get(), .add(),</li>
</ul>
<h4 id="what-is-arraylist">77. What is ArrayList</h4>
<ul>
<li>add(), addAll(), remove(), removeAll(), set(), contains(), containsAll(), indexOf(), lastIndexOf(), isEmpty(), size(), clear(), subList(), iterator(), toArray()</li>
</ul>
<h4 id="arraylist-constructors">78. ArrayList Constructors</h4>
<h4 id="what-is-the-hierarchy-of-arraylist">80. What is the Hierarchy of ArrayList</h4>
<h4 id="what-is-iterator">81. What is Iterator</h4>
<h4 id="what-is-iterable-interface">82. What is Iterable Interface</h4>
<ul>
<li>hasNext(), next(), remove()</li>
</ul>
<h4 id="what-is-listiterator">83. What is ListIterator</h4>
<ul>
<li>hasPrevious(), previous()</li>
</ul>
<h4 id="how-to-add-object-to-the-arraylist">84. How to add object to the ArrayList</h4>
<ul>
<li>while  (it.hasNext())</li>
<li>{</li>
<li>// Print all elements of List</li>
<li>System.out.println(it.next());</li>
<li>}</li>
</ul>
<h4 id="module-3-add-object-by-index-to-arraylist">86. Module 3 Add Object by Index to ArrayList</h4>
<ul>
<li>obj.add(index_number, value)</li>
<li>obj.add(index_number, collection_object)</li>
</ul>
<h4 id="add-user-defined-object-to-arraylist">87. Add User-Defined Object to ArrayList</h4>
<h4 id="replace-object-in-arraylist">88. Replace Object in ArrayList</h4>
<ul>
<li>obj.set(Index,velue)</li>
</ul>
<h4 id="retain-objects-in-arraylist">89. Retain Objects in ArrayList</h4>
<ul>
<li>arrlist_original and retain_list is we done arrlist_original.retainall(retain_list) then the original list only contains the retain list matching elements in it other are removed</li>
</ul>
<h4 id="remove-objects-from-arraylist">90. Remove Objects from ArrayList</h4>
<ul>
<li>arr_list.remove([index, or value, or ])</li>
<li>removeall(List_of_removal_list)</li>
</ul>
<h4 id="linkedlist-overview">92. LinkedList Overview</h4>
<ul>
<li>obj.add(), obj.addFirst(), obj.addLast(), obj.get(), obj.set(index, val)</li>
<li>obj.remove(), obj.removeFirst(), obj.removeLast()</li>
</ul>
<h4 id="linkedlist-constructors">93. LinkedList Constructors</h4>
<h4 id="add-object-to-linkedlist">94. Add Object to LinkedList</h4>
<h4 id="get-objects-from-linkedlist-using-for-each-loop">95. Get Objects from LinkedList using For-Each Loop</h4>
<h4 id="add-user-defined-object-to-linkedlist">96. Add User-Defined Object to LinkedList</h4>
<h4 id="remove-object-from-linkedlist">97. Remove Object from LinkedList</h4>
<h4 id="remove-multiple-objects-from-linkedlist">99. Remove Multiple Objects from LinkedList</h4>
<ul>
<li>obj.removeAll(obj2)</li>
</ul>
<h4 id="linkedlist-methods-clear-isempty-size">100. LinkedList Methods: clear(), isEmpty(), size()</h4>
<h4 id="java-deque-interface-overview">101. Java Deque Interface Overview</h4>
<ul>
<li>Deque&lt;&gt; dq = new ArrayDeque&lt;&gt;();</li>
<li>dq.add(), dq.addLast(), dq.addFirst();, dq.offerFirst();</li>
<li>dq.pollFirst(), dq.pollLast()</li>
</ul>
<h4 id="deque-push-method">102. Deque: Push Method</h4>
<h4 id="deque-get-elements-using-iterator">103. Deque: Get Elements using Iterator</h4>
<h4 id="deque-remove-and-poll-methods">104. Deque: Remove and Poll Methods</h4>
<h4 id="deque-removefirst-and-pollfirst-methods">106. Deque: RemoveFirst and PollFirst Methods</h4>
<ul>
<li>remove first throws exception if q is empty</li>
<li>poll first return null if q is empty</li>
</ul>
<h4 id="deque-removelast-and-polllast-methods">107. Deque: RemoveLast and PollLast Methods</h4>
<ul>
<li>same as previous</li>
</ul>
<h4 id="deque-element-and-peek-methods">108. Deque: Element and Peek Methods</h4>
<ul>
<li>element throws exception if q is empty</li>
<li>peek return null if q is empty</li>
</ul>
<h4 id="deque-descendingiterator-method">109. Deque: DescendingIterator Method</h4>
<h4 id="deque-getfirst-and-peekfirst-methods">110. Deque: GetFirst and PeekFirst Methods</h4>
<ul>
<li>GetFirst throws exception if q is empty</li>
<li>PeekFirst return null if q is empty</li>
</ul>
<h4 id="deque-pop-method">111. Deque: Pop Method</h4>
<ul>
<li>removes first element in q</li>
</ul>
<h4 id="set-interface-overview---java-collection-framework">113. Set Interface Overview - Java Collection Framework</h4>
<ul>
<li>it wont allow duplicate and it is unorder collection</li>
</ul>
<h4 id="treeset-overview---java-collection-framework">114. TreeSet Overview - Java Collection Framework</h4>
<ul>
<li>it maintains ascending order</li>
<li>wont allow null</li>
</ul>
<h4 id="linkedhashset-overview---java-collection-framework">115. LinkedHashSet Overview - Java Collection Framework</h4>
<ul>
<li>i maintains insertion order</li>
<li>it user double linked list</li>
</ul>
<h4 id="add-object-to-hashset">116. Add Object to HashSet</h4>
<ul>
<li>obj.add() - it return false it it is already there</li>
</ul>
<h4 id="add-multiple-objects-to-linkedhashset">117. Add Multiple Objects to LinkedHashSet</h4>
<ul>
<li>using array list</li>
</ul>
<h4 id="add-object-to-treeset">118. Add Object to TreeSet</h4>
<h4 id="check-size-of-linkedhashset">120. Check Size of LinkedHashSet</h4>
<h4 id="remove-all-objects-from-linkedhashset">121. Remove All Objects from LinkedHashSet</h4>
<h4 id="retain-objects-in-hashset-retainall-method">122. Retain Objects in HashSet (retainAll Method)</h4>
<ul>
<li>it will return true when all the elements are in the hashset and it will remove all the other element except the list we have passed</li>
</ul>
<h4 id="vector-constructors">123. Vector Constructors</h4>
<ul>
<li>default initial capacity of vector is 10</li>
</ul>
<h4 id="add-elements-to-vector">124. Add Elements to Vector</h4>
<h4 id="stack-overview---java-collection-framework">125. Stack Overview - Java Collection Framework</h4>
<h4 id="map-overview---java-collection-framework">126. Map Overview - Java Collection Framework</h4>
<h4 id="map.entry-interface-overview">128. Map.Entry Interface Overview</h4>
<h4 id="hashmap-constructors-overview">129. HashMap Constructors Overview</h4>
<ul>
<li>initial capacity 5</li>
</ul>
<h4 id="add-user-defined-object-to-hashmap">130. Add User-Defined Object to HashMap</h4>
<h4 id="clear-hashmap-clear-method">131. Clear HashMap (Clear Method)</h4>
<h4 id="add-key-value-pair-using-put-method-in-hashmap">132. Add Key-Value Pair using put() Method in HashMap</h4>
<h4 id="add-multiple-key-value-pairs-using-putall-in-hashmap">133. Add Multiple Key-Value Pairs using putAll() in HashMap</h4>
<h4 id="treemap-overview---java-collection-framework">134. TreeMap Overview - Java Collection Framework</h4>
<ul>
<li>it maintains ascending order</li>
<li>not synchronized</li>
</ul>
<h4 id="comparable-vs-comparator-in-java">136. Comparable vs Comparator in Java</h4>
<p>Comparable :  java.lang, compareTo(obj), collection.sort(list)<br>
Comparator :  java.util, compare(obj1,obj2), collections.sor(list, compare())</p>
<h4 id="functional-interface-in-java-8-features">137. Functional Interface in Java 8 Features</h4>
<ul>
<li>it contains only one abstract method</li>
<li>it can contains default and static method</li>
<li>default function interface:</li>
<li>Function&lt;T,R&gt; - apply(T t)</li>
<li>Consumer - accept(T t)</li>
<li>Supplier - get()</li>
<li>Runnable - run() - via thread we can execute it {Thread obj = new Thread(()-&gt;{}); obj.start()}</li>
</ul>
<h4 id="hashing-and-hashcode-overview">138. Hashing and HashCode Overview</h4>
<ul>
<li>process of converting string to hashcode is hashing</li>
</ul>
<h4 id="predicate-interface-in-java-8-with-lambda-examples-">139. Predicate Interface in Java 8 with Lambda Examples ********************</h4>
<ul>
<li>LocalDateTime obj  = LocalDateTime.now()</li>
<li>LocalDateTime.of(date, time)</li>
<li>.parse(…T…)</li>
<li>.MAX , .MIN</li>
</ul>
<h4 id="biconsumer-interface-in-java-8-with-lambda-examples-">140. BiConsumer Interface in Java 8 with Lambda Examples *******************</h4>
<ul>
<li>it accepts 2 elements</li>
<li>BiConsumer(T t1, T t2)</li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
</ul>
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>

