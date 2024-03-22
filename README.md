# [JSL03] Project Submission: Which one is which? Declarative or Imperative?!

Loom Recording Link: [https://www.loom.com/share/b7ea539b11e5425e81d09ee27a07d9ae?sid=0e363608-07cc-4074-8a43-9159059626bd]

# Imperative Programming

Example one provides an imperative style of of programming. It focuses on explicitly detsiling the steps or actions to be taken to achieve a desired outcome. In this example, in the function "cookSteak" each step of the cooking process is outlines sequentially. Including preheating the grill, seasoning the steak, cooking the steak until it reaches its desired doness and serving the steak based on its temperature.
Mutable variables, like grillTemperature and steakTemperature, are commonly employed to keep track of how the cooking process is advancing and its current state.

# Declarative programming

Example two is a declarative style of programming. In this function, cookSteak is define as an array of steps represented as an object, containing the action to be perfomed and any associated data, like rtemperature: instead of explicitely detailing each step like in imperative programming.

The for looop goes through each step in the cooking process array and does what it says. A switch statements then handles each step, deciding what to do based on the action. This way we don`t worry about how each step works, just about the cooking process as a whole.
Even though the declarative method might hide certain mutable variables or states, there could still be data structures indicating the current condition of the cooking process.

# In Summary

The imperative programming emphasizes detailing explicit steps to achieve a goal.
