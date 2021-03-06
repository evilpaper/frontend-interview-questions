# Frontend Interview Questions

### ...and answers :boom:

A bunch of common Frontend Developer Interview Questions. Utilizing Minimum Information Principle and Cloze Deletion for effective learning.

---

#### 1. Explain the difference between (CSS) Flexbox and (CSS) Grid?

Flexbox is designed for laying out items in *. . . . .1st. . . . .* dimension, either a row *. . . . .2nd. . . . .* a column. 

Grid is designed for laying out items in *. . . . .3rd. . . . .* dimensions, rows *. . . . .4th. . . . .* columns at the same time.

| ?             | *1st*         | *2nd*         | *3rd*         | *4th*         |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **A:**        | one           | or            | two           | and           |
| **B:**        | multiple      | or            | single        | and           |
| **C:**        | two           | or            | three         | and           |
| **D:**        | block         | or            | inline        | and           |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: A

Read more: <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Relationship_of_Grid_Layout">Relationship of grid layout to other layout methods</a> at MDN.

</p>
</details>

---

#### 2. What is REST?

REST stands for *. . . . .1st. . . . .* .

REST is a set of *. . . . .2nd. . . . .* for creating API's.

REST suggests to create an *. . . . .3rd. . . . .* of the data requested by the client and send the *. . . . .4th. . . . .* of the object in response to the user.

| ?             | *1st*                          | *2nd*        | *3rd*         | *4th*         |
| ------------- | ------------------------------ | ------------ | ------------- | ------------- |
| **A:**        | Rapid State Transfer           | objects      | question      | answer        |
| **B:**        | Reactive State Transfer        | rules        | function      | callbacks     |
| **C:**        | Representational State Transfer| rules        | object        | values        |
| **D:**        | Regular State Transfer         | rules        | JSON          | object        |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: C

Read more: <a href="https://www.smashingmagazine.com/2018/01/understanding-using-rest-api/">Understanding and Using REST API's</a> at Smashing Magazine.

</p>
</details>

---

#### 3. What is Big O notation, and why is it useful?

Big O notation tells you how *. . . . .1st. . . . .* an algorithm is by comparing the number of *. . . . .2nd. . . . .* . 

It is useful in order to *. . . . .3rd. . . . .* different algorithms.

| ?             | *1st*         | *2nd*         | *3rd*        |
| ------------- | ------------- | ------------- | ------------ |
| **A:**        | strong        | loops         | merge        | 
| **B:**        | fast          | operations    | compare      |
| **C:**        | smart         | seconds       | code         |
| **D:**        | complex       | statements    | setup        |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: B

For example, suppose you have a list of size n. Simple search needs to check each element, so it will take n operations. This means it grows linear e.g. at constant speed. 10 items takes 10 operations, 20 items take 20 operations and so on. In Big O notation we write this O(n).

You use this to compare to other algorithms like this:

* O(log n), also known as log time. Grows slow, is fast. Example: Binary search.
* O(n), also known as linear time. Our example above, called: Simple search.
* O(2^N), also known as quadratic time. Grows fast, is slowest. 

Judging from the above, Binary search would be the more perfomant option in our case.

</p>
</details>

___

#### 4. What is the DOM?

DOM stand for the *. . . . .1st. . . . .* . It’s the *. . . . .2nd. . . . .* of a document on the web. As such the DOM is a programming *. . . . .3rd. . . . .* . 

The DOM allows programmatic *. . . . .4th. . . . .* to the web document. 

| ?             | *1st*                         | *2nd*               | *3rd*         | *4th*         |
| ------------- | ----------------------------- | ------------------- | ------------- | ------------- |
| **A:**        | Document Object Model         | data representation | interface     | access        |
| **B:**        | Document Observer Model       | inner workings      | environment   | view          |
| **C:**        | Digital Object Model          | rules               | host          | transfer      |
| **D:**        | Data Object Management        | bits and bytes      | set           | hack          |


<details><summary><b>Show answer</b></summary>
<p>

#### Answer: A

With DOM methods, you can change the document's structure, style, or content.

Read more: <a href="https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction">Introduction to the DOM</a> on MDN.

</p>
</details>

---

#### 5. What is the event loop?

The event loop is a programming construct or design pattern that *. . . . .1st. . . . .* for and *. . . . .2nd. . . . .* events or messages. 

JavaScript is single *. . . . .3rd. . . . .* and can only run *. . . . .4th. . . . .* task at the time. To be able to jump between tasks instead of waiting JavaScript use an event loop. 

| ?             | *1st*        | *2nd*      | *3rd*         | *4th*         |
| ------------- | ------------ | ---------- | ------------- | ------------- |
| **A:**        | care         | organize   | minded        | one           |
| **B:**        | search       | find       | throttled     | two           |
| **C:**        | looks        | forward    | wired         | three         |
| **D:**        | waits        | dispatches | threaded      | one           |


<details><summary><b>Show answer</b></summary>
<p>

#### Answer: D

The event loop use a call stack and a queue to jump between tasks when the tasks wait for other stuff to finish like a http request etc.

Read more: <a href="https://flaviocopes.com/javascript-event-loop/">The JavaScript Event Loop</a> by Flavio Copes.

</p>
</details>

---

#### 6. Explain event delegation?

Event delegation is the process of *. . . . .1st. . . . .* *. . . . .2nd. . . . .* events. 

| ?             | *1st*        | *2nd*      | 
| ------------- | ------------ | ---------- |
| **A:**        | catching     | bubbled    |
| **B:**        | pushing      | emitted    |
| **C:**        | hoisting     | new        |
| **D:**        | dispatching  | actions    |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: A

Imagine a calculator. Instead of attaching event listeners to each and every button element, which would be a lot, we attach one to the keypad element which contains the button elements. When a button is clicked the event will bubble up to the keyboard where we catch it and identify the button. 

</p>
</details>

---

#### 7. Explain how `this` works in JavaScript??

The `this` keyword is an implicit *. . . . .1st. . . . .* passed to a function on invocation. `this` refers to the *. . . . .2nd. . . . .* that's associated with the *. . . . .3rd. . . . .* invocation, it's often called function *. . . . .4th. . . . .* . If not set `this` refer to the window object.

| ?             | *1st*        | *2nd*      | *3rd*         | *4th*       |
| ------------- | ------------ | ---------- | ------------- | ----------- |
| **A:**        | argument     | function   | function      | scope       |
| **B:**        | props        | primitive  | caller        | value       |
| **C:**        | parameter    | object     | function      | context     |
| **D:**        | variable     | function   | receiver      | source      |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: C

Read more: <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this"> this</a> at MDN.

</p>
</details>

---

#### 8. What is a closure, and how/why would you use one?

A closure is when a function has *. . . . . 1st . . . . .* to variables defined outside of itself. A closures are created every time a *. . . . . 2nd . . . . .* is created. Closures can be used to mimic *. . . . . 3rd . . . . .* object variables and dealing with *. . . . . 4th . . . . .*

| ?             | *1st*        | *2nd*      | *3rd*         | *4th*       |
| ------------- | ------------ | ---------- | ------------- | ----------- |
| **A:**        | influence    | primitive  | multiple      | context     |
| **B:**        | a relation   | object     | counters      | modules     |
| **C:**        | a iterator   | recursion  | flexible      | delegation  |
| **D:**        | access       | function   | private       | callbacks   |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: D

Read more: <a href="https://whatthefuck.is/closure">What the fuck is a closure?</a> by Dan Abramov.

</p>
</details>

---

#### 9. What language constructions do you use for iterating over array items and object properties?

For array items: *. . . . .1st. . . . .*  , *. . . . .2nd. . . . .* , *. . . . .3rd. . . . .* or *. . . . .4th. . . . .*

For object properties: *. . . . .5th. . . . .*

| ?             | *1st*        | *2nd*      | *3rd*         | *4th*       | *4th*       |
| ------------- | ------------ | ---------- | ------------- | ----------- | ----------- |
| **A:**        | for          | while      | switch        | forEach     | every       |
| **B:**        | for...of     | for        | every         | for...of    | map         |
| **C:**        | map          | for...of   | while         | every       | set.        |
| **D:**        | for...of     | forEach    | every         | map         | for...in    |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: D

for..of iterates over the values of an iterable object. Examples of iterable objects are arrays, strings, and NodeLists.

for..in iterates over all enumerable property keys of an object.

</p>
</details>

---

#### 10. Explain Function.prototype.bind?

The bind() method creates a new *. . . . .1st. . . . .* that, when called, has it's *. . . . .2nd. . . . .* keyword set to the provided value.

| ?             | *1st*        | *2nd*      | 
| ------------- | ------------ | ---------- |
| **A:**        | loop         | iterator   |
| **B:**        | function     | this       |
| **C:**        | context      | prototype  |
| **D:**        | state        | observer   |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: B

Read more: <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/bind">bind</a> at MDN.

</p>
</details>

---
