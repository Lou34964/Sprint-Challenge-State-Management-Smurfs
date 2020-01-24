1. What problem does the context API help solve?
allows us to use vars of state anywhere with in the app
1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
actions - payloads of info pssing data to the store
reducer - define the change in state based on the actions
store - the storage of state(s)
1. What is the difference between Application state and Component state? When would be a good time to use one over the other?
app state - the state of the entire app and stored within the store, this can be used to determin what context to display to the user
conp state - the state of that specific component. used when changes are made that only relate to that component.
1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?
this is the middleware of actions to store. this allows us to do thing and control the data sent to store
1. What is your favorite state management system you've learned and this sprint? Please explain why!
thunk. this is great because it allows me to make evaluations of user input before deciding what to do.
