# Redux 101

### What is Redux?

> *"Redux is a predictable state container for JavaScript apps."* \- [Redux Documentation](http://redux.js.org/)

Before we can figure out what the above definition tells us, we first need to understand another important concept—state. When we talk about state in an application, we are talking about all of the variables (or more specifically locations in memory) that can change in value over *time*. A stateful application is designed to remember preceding events or user interactions and behave respectively. While this may seem like a simple concept, you may know that managing state is a source of frustration for many developers. This is because changing state is inherently an asynchronous process, which as you know is a difficult concept to represent in code. On top of having to visualize how your application changes over time, many different parts of your code may depend upon or even manipulate the same piece of state. Separating or even repeating this logic across your code provides an abundance of opportunity for bugs to appear as the project develops. 
