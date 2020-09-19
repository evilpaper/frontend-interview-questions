# Frontend Interview Questions

...and answers :boom:

A bunch of common Frontend Developer Interview Questions. Utilizing Minimum Information Principle and Cloze Deletion for effective learning. 

---

#### 1. Explain the difference between (CSS) Flexbox and (CSS) Grid?

Flexbox is designed for laying out items in .......... dimension, either a row .......... a column. 

Grid is designed for laying out items in .......... dimensions, rows .......... columns at the same time.

| ?             |               |               |               |               |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **A:**        | one           | or            | two           | and           |
| **B:**        | multiple      | or            | single        | and           |
| **C:**        | two           | or            | three         | and           |
| **D:**        | block         | or            | inline        | and           |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: A

</p>
</details>

---

#### 2. What is REST?

REST, stands for .......... and is a set of .......... for creating API's.

REST suggests to create an .......... of the data requested by the client and send the .......... of the object in response to the user.

| ?             |                                |              |               |               |
| ------------- | ------------------------------ | ------------ | ------------- | ------------- |
| **A:**        | Rapid State Transfer           | objects      | question      | answer        |
| **B:**        | Reactive State Transfer        | rules        | function      | callbacks     |
| **C:**        | Representational State Transfer| rules        | object        | values        |
| **D:**        | Regular State Transfer         | rules        | JSON          | object        |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: C

</p>
</details>

---

#### 3. What is Big O notation, and why is it useful?

Big O notation tells you how .......... an algorithm is by comparing the number of .......... . 

It is useful in order to .......... different algorithms.

| ?             |               |               |              |
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

DOM stand for the .......... . It’s the .......... of a document on the web. As such the DOM is a programming .......... . 

The DOM allows programmatic .......... to the web document. 

| ?             |                               |                     |               |               |
| ------------- | ----------------------------- | ------------------- | ------------- | ------------- |
| **A:**        | Document Object Model         | data representation | interface     | access        |
| **B:**        | Document Observer Model       | inner workings      | environment   | view          |
| **C:**        | Digital Object Model          | rules               | host          | transfer      |
| **D:**        | Data Object Management        | bits and bytes      | set           | hack          |


<details><summary><b>Show answer</b></summary>
<p>

#### Answer: A

With DOM methods, you can change the document's structure, style, or content.

</p>
</details>

---

#### 5. What is the event loop?

The event loop is a programming construct or design pattern that ........ for and ........ events or messages. 

JavaScript is single ........ and can only run ........ task at the time. To be able to jump between tasks instead of waiting JavaScript use an event loop. 

| ?             |              |            |               |               |
| ------------- | ------------ | ---------- | ------------- | ------------- |
| **A:**        | care         | organize   | minded        | one           |
| **B:**        | search       | find       | throttled     | two           |
| **C:**        | looks        | forward    | wired         | three         |
| **D:**        | waits        | dispatches | threaded      | one           |


<details><summary><b>Show answer</b></summary>
<p>

#### Answer: D

The event loop use a call stack and a queue to jump between tasks when the tasks wait for other stuff to finish like a http request etc.

</p>
</details>

---

#### 6. Explain event delegation?

Event delegation is the process of ........ ........ events. 

| ?             |              |            | 
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

The `this` keyword is an implicit ........ passed to a function on invocation. `this` refers to the ........ that's associated with the ........ invocation, it's often called function ........ . If not set `this` refer to the window object.

| ?             |              |            |               |             |
| ------------- | ------------ | ---------- | ------------- | ----------- |
| **A:**        | argument     | function   | function      | scope       |
| **B:**        | props        | primitive  | caller        | value       |
| **C:**        | parameter    | object     | function      | context     |
| **D:**        | variable     | function   | receiver      | source      |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: C

</p>
</details>

---

#### 8. What is a closure, and how/why would you use one?

A closure is when a function has *.....1st.....* to variables defined outside of itself. A closures are created every time a *. . . . .2nd. . . . .* is created. Closures can be used to mimic *. . . . .3rd. . . . .* object variables and dealing with *. . . . .4th. . . . .*

| ?             | *1st*        | *2nd*      | *3rd*         | *4th*       |
| ------------- | ------------ | ---------- | ------------- | ----------- |
| **A:**        | control      | primitive  | multiple      | context     |
| **B:**        | effect       | object     | counters      | modules     |
| **C:**        | dedendency   | recursion  | flexible      | delegation  |
| **D:**        | access.      | function   | private       | callbacks   |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: D

</p>
</details>

---

#### 9. What language constructions do you use for iterating over array items and object properties?

For array items: for...of , *. . . . .1st. . . . .* , *. . . . .2nd. . . . .* or *. . . . .3rd. . . . .*

For object properties: *. . . . .4th. . . . .*

| ?             | *1st*        | *2nd*      | *3rd*         | *4th*       |
| ------------- | ------------ | ---------- | ------------- | ----------- |
| **A:**        | for          | while      | switch        | forEach     |
| **B:**        | for...of     | for        | every         | for...of    |
| **C:**        | map          | for...of   | while         | every       |
| **D:**        | forEach      | every      | map           | for...in    |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: D

</p>
</details>

---
