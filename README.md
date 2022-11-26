# JSconcepts-variable-Datatype

                            [Concepts In JS]  :A)Asynchronous Communication
Also known as AJAX (Asynchronous Javascript And XML), asynchronous communication plays a key role in modern web page design and functionality. AJAX gives you the ability to dynamically load information to your web page without having to refresh the whole page. One benefit of this is that less data is being sent from the server when only a section of your page needs to change. This also enhances the user experience with faster load times and the page not blinking out every time something changes.

B) Dom creation and modification
Having the ability to create or modify elements on a web page allows you to create dynamic web pages that can change based on user interaction.

C) Loops, Loops, Loops, Loops
Loops are a key component of any programming language. Loops allow you to repeat blocks of code any number of required times saving you from having to write repetitive code. Loops also allow you to iterate through data structures with minimal effort. Understanding how, when, and why to use loops is an essential skill for any programmer.

D) Dev Tool Debugging
All web browsers have some form of Dev Tools for debugging, even the one you are using right now. If you are using Chrome, right-click then select Inspect. This should have brought up a “panel” either at the bottom or the right side of your browser. These are the Dev Tools, and as said before, all browsers have some form of them to help developers debug their code. All the information about the page/site can be found there including information about the HTML, CSS, and of course Javascript. Being able to utilize the Dev Tools to debug your code should be a skill you build from the very beginning.

                             [ Variables in Js]
 Like many other programming languages, JavaScript has variables. Variables can be thought of as named containers. You can place data into these containers and then refer to the data simply by naming the container.

Before you use a variable in a JavaScript program, you must declare it. Variables are declared with the var keyword as follows.

<script type = "text/javascript">
   <!--
      var money;
      var name;
   //-->
</script>
You can also declare multiple variables with the same var keyword as follows −

<script type = "text/javascript">
   <!--
      var money, name;
   //-->
</script>
Storing a value in a variable is called variable initialization. You can do variable initialization at the time of variable creation or at a later point in time when you need that variable.

For instance, you might create a variable named money and assign the value 2000.50 to it later. For another variable, you can assign a value at the time of initialization as follows.

<script type = "text/javascript">
   <!--
      var name = "Ali";
      var money;
      money = 2000.50;
   //-->
</script> 

                [JavaScript Datatypes]
One of the most fundamental characteristics of a programming language is the set of data types it supports. These are the type of values that can be represented and manipulated in a programming language.

JavaScript allows you to work with three primitive data types −

Numbers, eg. 123, 120.50 etc.

Strings of text e.g. "This text string" etc.

Boolean e.g. true or false.

JavaScript also defines two trivial data types, null and undefined, each of which defines only a single value. In addition to these primitive data types, JavaScript supports a composite data type known as object. We will cover objects in detail in a separate chapter.

Note − JavaScript does not make a distinction between integer values and floating-point values. All numbers in JavaScript are represented as floating-point values. JavaScript represents numbers using the 64-bit floating-point format defined by the IEEE 754 standard.
