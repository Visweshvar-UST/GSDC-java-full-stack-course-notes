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
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>

