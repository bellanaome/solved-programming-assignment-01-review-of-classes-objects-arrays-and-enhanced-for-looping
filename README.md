Download Link: https://assignmentchef.com/product/solved-programming-assignment-01-review-of-classes-objects-arrays-and-enhanced-for-looping
<br>
Given:

UML Class Diagram of Policy (on Blackboard)

Test harness shell: Test_Policy. java (on Blackboard)

These instructions

Sample output (on Blackboard)

Grading Rubric (on Blackboard)

Tasks:

<ol>

 <li>Write the Java code to describe class Policy in accordance with the provided UML Class</li>

</ol>

Diagram and the published Basic Coding Standards document

<ol start="2">

 <li>Complete the code for Test _ Policy. java such that it successfully serves to test the class</li>

</ol>

Policy and meets the specific requirements listed below.

Requirements:

Policy. java

<ol>

 <li>Code the Java class Policy according the LJMN Class Diagram provided and the instructions</li>

</ol>

included here.

<ol start="2">

 <li>The class Policy will require two constructors:</li>

 <li>The default or null constructor will accept no parameters and will produce a Policy object having no established instance variable values.</li>

 <li>The full constructor will accept five (5) values: three (3) String values, an int, and a double.</li>

 <li>The full constructor will call the appropriate “set” methods to assign the received values to the appropriate instance variables. NOTE: Direct assignment of instance variable values effectively invalidates the full constructor. In such a case, the student will lose all points assigned for the full constructor.</li>

 <li>Write “set” methods for all instance variables.</li>

 <li>Flag all “set” methods as “final” methods.</li>

 <li>Each “set” method will accept the appropriate data type value and assign it to the appropriate instance variable.</li>

 <li>“Set” methods do not return values.</li>

 <li>“Set” methods must not contain any code other than that required to set a value for the given instance variable.</li>

 <li>Naming of “set” methods must be according to published standards.</li>

</ol>




<ol start="4">

 <li>“Get” methods will be written for all instance variables.</li>

 <li>“Get” methods are flagged as “final” methods.</li>

 <li>“Get” methods accept no parameters.</li>

 <li>Each “get” method must return a type appropriate to the instance variable with which it is associated.</li>

 <li>“Get” methods will not contain any code other than that required to set a value for the given instance variable.</li>

 <li>Naming of “get” methods must be according to published standards.</li>

</ol>




<ol start="5">

 <li>Method txtP01Type will return a String translation of the coded type instance value:</li>

 <li>If type 1: return “AIJTO”</li>

 <li>If type = 2: return “HOMEOWNERS”</li>

 <li>Method toString:</li>

 <li>Returns a reference to a formatted String obiect containing a description of the</li>

</ol>

Policy object as shown in the Class Diagram

<ol>

 <li>Must use “get” and other methods as appropriate to retrieve instance variable values.</li>

</ol>

NOTE: Direct reference to instance variables in the toString method will invalidate

the method, resulting in zero points for that code.

<ol>

 <li>Use the format method to format the returned String obiect correctly/appropriately.</li>

 <li>Do not include any unnecessary or unneeded code.</li>

 <li>Use Basic Coding Standards. This specifically applies to the commenting of code.</li>

</ol>




Test _ Policy. java

The assignment folder includes the basic code for testing your Policy class. Add code to complete the

following functions:

<ol>

 <li>Each kinstantiated Policy object will be stored in an array. To accomplish this, you must declare a</li>

</ol>

one-dimensional array structure to hold Policy objects.

<ol>

 <li>Name the array grpP01icy.</li>

 <li>Declare the array to hold six (6) Policy objects.</li>

 <li>In the printToStrings method, complete the enhanced for loop statement.</li>

 <li>Use the name oneContract as the local reference to the current Policy object.</li>

 <li>Do not change the System. out . printf statement in any way.</li>

 <li>Do not add any unneeded code.</li>

 <li>Do add comments as appropriate.</li>

 <li>Follow Basic Coding Standards.</li>

</ol>




Testing Your Code




Be sure to test your code thoroughly. While a structure for the test harness has been provided and your

test harness will be validated, I will do additional testing as well. Your code must meet requirements in

those additional test cases.


