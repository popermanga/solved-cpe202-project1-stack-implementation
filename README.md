Download Link: https://assignmentchef.com/product/solved-cpe202-project1-stack-implementation
<br>
<strong>Goal</strong>: The goal of this project is to implement the Stack Abstract Data Type using the built in List construct in Python and the Stack ADT using the simple linked list data structure that will cover in class.

As discussed in class you allocate a list of size stack_capacity and use this to store the items in the stack.  Since Lists in python expand when more storage is needed you will have to provide a mechanism to prevent the list <em>inside</em> your stack from growing.  This really prevents the stack from growing if the user only accesses it through the given interface but that is fine for the purposes of this exercise.  (This prevents the stack from using more space that a user might want. Think of this as a requirement for an application on a small device that has very limited storage.)  In this case, when a user attempts to push an item to a full stack, your push function (method) should raise an IndexError exception.  Similarly, if a user tries to pop from an empty stack, your pop function (method) should raise an IndexError exception.

In the PolyLearn there are <strong>starter files: 1) stack_array.py and 2)stack_linked.py stack_array.py </strong> provides the following as a starting point<strong>s</strong>:

<h2>stack_array.py</h2>

<strong>class </strong>StackArray:

<em>“””Implements an efficient last-in-first-out Abstract Data Type using a Python    </em>

<em>List””” </em>

<em>             </em><strong>def </strong>__init__(self, capacity):

“””Creates and empty stack with a capacity”””

self.capacity = capacity           # Capacity of your stack         self.items = [None]*capacity        # initializing the stack          self.num_items = 0               # number of elements in the stack

<strong>def </strong>is_empty(self):

<em>“””Returns true if the stack is empty and false otherwise””” </em>

<strong>def </strong>is_full(self):

<em>“””Returns true if the stack is full and false otherwise””” </em>

<strong>def </strong>push(self, item):    <strong> </strong>

<strong>def </strong>pop(self):

<em>“””Returns item that is popped from stack””” </em>

<strong>def </strong>peek(self):

<strong>def </strong>size(self):

<em>       “””Returns the number of elements currently in the stack(not capacity)””” </em>




<strong>Due Date: 10/11 @11:55PM for 100% </strong>

<strong>                  10/12 @11:55PM for 80% </strong>

<strong>Submit to PolyLearn three files: </strong>

<ul>

 <li><strong>py</strong> Contains an array based implementation of the stack class. The class must be called: <strong>StackArray</strong> .</li>

 <li><strong>py</strong>: Contains a linked list based implementation of the <strong>stack</strong> class. The class name must be <strong>StackLinked.</strong></li>

 <li>Both implementations must follow the above specification and be thoroughly tested.</li>

 <li><strong>py</strong> contains your set of test cases for both implementations to ensure your classes work correctly. You need to have at least two test cases for each function (or method).</li>

</ul>

You are NOT allowed to use the following Python List operations:

<ul>

 <li>append()</li>

 <li>insert()</li>

 <li>extend()</li>

 <li>remove()</li>

 <li>pop()</li>

 <li>del()</li>

 <li>+ (concatenations)</li>

 <li>List slicing</li>

</ul>

<strong>Make sure that you follow the design recipe. (No need for template, no need for boilerplates)  </strong>

<strong>Note: Your class names, function (or method) names, and file names must follow the spec of the project. </strong>


