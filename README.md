# Tutorial

* [official-tutorial](https://facebook.github.io/react/docs/tutorial.html)
* [thiking-in-react](https://facebook.github.io/react/docs/thinking-in-react.html)
* [ReactjsProgram - Fundamentals](http://courses.reactjsprogram.com/courses/reactjsfundamentals/lectures/760073)    

# React Important Notes

* React's one-way data flow (also called one-way binding) keeps everything modular and fast
    * may not be immediately clear which component should own what state
* Components are just like functions
    * You can think of components as simple functions that take in `props` and `state` and render HTML
* props vs state
    * `props` : props are a way of passing data from parent to child (immutable)
    * `state` : state triggers changes to your underlying data model (mutable)
* Auto-binding
    * With React, every method is automatically bound to its component instance
* Event delegation
    * When React starts up, it starts listening for all events at the top level using a single event listener. When a component is mounted or unmounted, the event handlers are simply added or removed from an internal mapping
* Try to keep as may of your components as possible stateless
    * By doing this you'll isolate the state to its most logical place and minimize redundancy, making it easier to reason about your application
    * State should contain data that a component's event handlers may change to trigger a UI update
    
