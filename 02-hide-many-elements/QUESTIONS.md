# DOM Atomic 02: Hide Many Elements

## Questions

---

> How did you go about selecting the DOM elements to hide? Describe the "contract" for that function.

Your reply here... I used querySelectorAll() to get all elements with the '.hide_me' class. This function goes through every child object of the element that it was assigned to and returns every element which contains a the specified selector as a list.

---

> Describe how you were able to hide each element. Were you able to do it as one operation, or did you use a loop of some kind? Describe the "contracts" that were utilized to accomplish your goal.

Your reply here... To hide each element I used ForEach() which allowed me to preform a function on each of the elements in the list which was returned by querySelectorAll()