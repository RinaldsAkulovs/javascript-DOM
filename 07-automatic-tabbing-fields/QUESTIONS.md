# DOM Atomic 07: Automatic Tabbing Fields

## Questions

---

> What are some refactoring techniques you might apply to the provided solution?

Your reply here... If I wanted to rewrite the code differently, I'd probably iterate over all objects in the document using querySellectorAll() and find all the input fields, and add an event to each one of the found input fields. This would improve readability if there are hundreds of input fields, and make it way easier to make adjustments to the code.