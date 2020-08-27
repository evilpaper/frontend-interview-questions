# Frontend Interview Questions

...and answers :boom:

A bunch of common Frontend Developer Interview Questions. Utilizing Minimum Information Principle and Cloze Deletion for effective learning. 

---

#### 1. Explain the difference between (CSS) Flexbox and (CSS) Grid?

Flexbox is designed for laying out items in ________ dimension, either a row ________ a column. 

Grid is designed for laying out items in ________ dimensions, rows ________ columns at the same time.

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

#### 2. What is REST, and why do people use it?

REST, stands for ________ and is a set of ________ for creating API's.

REST suggests to create an ________ of the data requested by the client and send the ________ of the object in response to the user.

People use it to get ________ since data is not tied to resources or methods.

| ?             |                                |              |               |               |                     |
| ------------- | ------------------------------ | ------------ | ------------- | ------------- | ------------------- |
| **A:**        | Rapid State Transfer           | objects      | question      | answer        | structure           |
| **B:**        | Reactive State Transfer        | rules        | object        | values        | performance         |
| **C:**        | Representational State Transfer| rules        | object        | values        | flexibility         |
| **D:**        | Regular State Transfer         | rules        | object        | values        | transparency        |

<details><summary><b>Show answer</b></summary>
<p>

#### Answer: C

</p>
</details>

---

#### 3. What is Big O notation, and why is it useful?

Big O notation tells you how ________ an algorithm is by comparing the number of ________ . 

It is useful in order to ________ different algorithms.

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

DOM stand for the ________ . It’s the ________ of a document on the web. As such the DOM is a programming ________ . The DOM allows programmatic _______ to the web document. With DOM methods, you can change the document's structure, style, or content.

| ?             |                               |                     |               |               |
| ------------- | ----------------------------- | ------------------- | ------------- | ------------- |
| **A:**        | Document Object Model         | data representation | interface     | access        |
| **B:**        | Document Observer Model       | inner workings      | environment   | view          |
| **C:**        | Digital Object Model          | rules               | host          | transfer      |
| **D:**        | Data Object Management        | bits and bytes      | set           | hack          |


<details><summary><b>Show answer</b></summary>
<p>

#### Answer: A

</p>
</details>

---

