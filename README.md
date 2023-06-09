<h1>Gradebook</h1>


You are a student and you are trying to organize your subjects and grades using Python. Let’s explore what we’ve learned about lists to organize your subjects and scores.

![image](https://user-images.githubusercontent.com/100479971/228377406-4925afe1-88b8-461b-894f-ce7489cddf6f.png)

<h3>Create Some Lists:</h3>

**1 -** Create a list called ```subjects``` and fill it with the classes you are taking:

- ```"physics"```
- ```"calculus"```
- ```"poetry"```
- ```"history"```

**2 -** Create a list called ```grades``` and fill it with your scores:

- ```98```
- ```97```
- ```85```
- ```88```

**3 -** Manually (without any methods) create a two-dimensional list to combine ```subjects``` and ```grades```. Use the table below as a reference to associated values.

<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Test Score</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>"physics"</td>
    <td>98</td>
  </tr>
  <tr>
    <td>"calculus"</td>
    <td>97</td>
  </tr>
  <tr>
    <td>"poetry"</td>
    <td>85</td>
  </tr>
  <tr>
    <td>"history"</td>
    <td>88</td>
  </tr>
</tbody>
</table>

Assign the value into a variable called ```gradebook```.

**4 -** Print ```gradebook```.

Does it look how you expected it would?

<h3>Add More Subjects:</h3>

**5 -** Your grade for your computer science class just came in! You got a perfect score, ```100```!

Use the ```.append()``` method to add a list with the values of ```"computer science"``` and an associated grade value of ```100``` to our two-dimensional list of ```gradebook```.

**6 -** Your grade for ```"visual arts"``` just came in! You got a 93!

Use ```append``` to add ```["visual arts", 93]``` to ```gradebook```.

<h3>Modify The Gradebook:</h3>

**7 -** Our instructor just told us they made a mistake grading and are rewarding an extra 5 points for our visual arts class.

Access the index of the grade for your visual arts class and modify it to be 5 points greater.

**8 -** You decided to switch from a numerical grade value to a Pass/Fail option for your poetry class.

Find the grade value in your ```gradebook``` for your poetry class and use the ```.remove()``` method to delete it.

**9 -** Use the ```.append()``` method to then add a new ```"Pass"``` value to the sublist where your poetry class is located.

<h3>One Big Gradebook!</h3>

**10 -** You also have your grades from last semester, stored in ```last_semester_gradebook```.

Create a new variable ```full_gradebook``` that combines both ```last_semester_gradebook``` and ```gradebook``` using ```+``` to have one complete grade book.

Print ```full_gradebook``` to see our completed list.
