# What is React ?
- It is a front-end JavaScript library
- A tool for building UI components

# How does React work ?
- React creates a VIRTUAL DOM in memory
- When we build an application with React, it will create a Virtual DOM in the memory of our computer instead manipulating directly with DOM in browser
- Virtual DOM is actually a copy of the real DOM but this copy is placed in the memory
- React does not update directly on the DOM of browser, it wil update in Virtual DOM first then it compares the difference between the two DOMs and only update the needed elements. This helps to enhance efficiency
- React only changes what needs to be changed !