## The Golden Rule:

🦸 🦸‍♂️ `Stop starting and start finishing.` 🏁

If you work on more than one feature at a time, you are guaranteed to multiply your bugs and your anxiety.

## Making a plan

1. **Make a drawing of your app. Simple "wireframes"**

1. **Once you have a drawing, name the HTML elements you'll need to realize your vision**
    - <h1> with name text 
    - <p> with pronouns and location
    - <button> to enable and display a button
    - <section> to enclose the button 
    <div> and <class> for hiding the animal picture

1. **For each HTML element ask: Why do I need this?**
    - <h1> and <p> To display text
    - <button> To enable button functionality
    - <section> <div> and <class> to assign properties to each individually, or by class

1. **Once we know _why_ we need each element, think about how to implement the "Why" as a "How"**
    - Enter text between the header and paragraph tags
    - create the button in the html file, and use getElementById in the app.js file to pull the button into that file.
    - 
1. **Find all the 'events' (user clicks, form submit, on load etc) in your app. Ask one by one, "What happens when" for each of these events. Does any state change?**
- One event, which is the user clicking the button. It should toggle the class 'hidden' for the image of the animal.
1. **Think about how to validate each of your features according to a Definition of Done**
- Checking the functionality in the browser is essential, but using console.log commands throughout can help validate good coding in the "inspect" tool.
1. **Consider what features _depend_ on what other features. Use this dependency logic to figure out what order to complete tasks.**

Additional considerations:

-   Ask: which of your HTML elements need to be hard coded, and which need to be dynamically generated?
-   Consider your data model.
    -   What kinds of objects (i.e., Dogs, Friends, Todos, etc) will you need?
    -   What are the key/value pairs?
    -   What arrays might you need?
    -   What needs to live in a persistence layer?
-   Is there some state we need to initialize?
-   Ask: should any of this work be abstracted into functions? (i.e., is the work complicated? can it be reused?)
